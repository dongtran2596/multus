# multus
1.  git clone https://github.com/dongtran2596/multus/
2.  cd multus
1.  Tạo một CustomResourceDefinition: 
kubectl create -f crdnetwork.yaml
3.  Tạo các Network:
kubectl create -f flannel-network.yaml sriov-network.yaml sriov-vlanid-l2enable-network.yaml 
6.  Tạo một Pod có nhiều giao diện mạng:
kubectl create -f pod-multi-network.yaml

