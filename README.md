# multus
kubectl create -f ./crdnetwork.yaml
customresourcedefinition "network.kubernetes.com" created
kubectl create -f flannel-network.yaml
network "flannel-networkobj" created
kubectl create -f pod-multi-network.yaml
pod "multus-multi-net-poc" created
