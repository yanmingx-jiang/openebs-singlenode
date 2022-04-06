# openebs-singlenode
```text
pvcreate /dev/sdX
vgcreate lvmvg /dev/sdX

yum install lvm2 -y
kubectl apply -f openebs-operator.yaml
kubectl apply -f lvm-operator.yaml
kubectl apply -f sc.yaml
kubectl apply -f pvc.yaml
kubectl apply -f fio.yaml
```
