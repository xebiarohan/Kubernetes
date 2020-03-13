Kubernetes

        Its a system of running many different containers on different machines.
        Its used to scale up our application. When we want to run different containers
        in different quantities.
  
minikube :
        
        manages kubernetes cluster on our local machine. Use to manage the virtual machine or node 
        on which containers runs in dev environment. 
        
kubectl : 
       
        Use for managing containers in the node
        
        
Local kubernetes development :
        
        install cubectl  -->  Install a VM driver virtualbox  --> install minikube
        
cubectl : CLI for interacting with master
VM driverbox : User to make virtual machine that will be our single node
minikube: Runs a single node on that virtual machine


Installing kubectl in linux :


curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl

$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)

curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.17.0/bin/linux/amd64/kubectl

chmod +x ./kubectl

sudo mv ./kubectl /usr/local/bin/kubectl


kubectl version --client

which kubectl

        

  
