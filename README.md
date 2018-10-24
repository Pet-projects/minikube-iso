# minikube-iso
For of Minikube ISO


https://kubernetes.io/docs/setup/minikube/
https://kubernetes.io/docs/tasks/tools/install-minikube/


Install kubectl
```
brew install kubectl
```

Download minikube


Start VM
```
minikube start --logtostderr --iso-url file:///Users/julianghionoiu/Applications/minikube/minikube-v0.30.0.iso --vm-driver virtualbox
```

