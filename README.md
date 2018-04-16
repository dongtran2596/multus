# multus
1.  kubectl create -f ./crdnetwork.yaml
2.  customresourcedefinition "network.kubernetes.com" created
3.  kubectl create -f flannel-network.yaml
4.  network "flannel-networkobj" created
5.  kubectl create -f pod-multi-network.yaml
6.  pod "multus-multi-net-poc" created
