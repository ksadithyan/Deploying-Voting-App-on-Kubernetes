
# Voting app on Kubernetes

### The Project Visualization
![alt text](image.png)


# How to run

Make sure kubectl is installed (minikube)
If you're on wsl2 install docker on windows and enable the wsl integration too

1) clone the repo
2) cd to deployments
3) kubectl apply -f .
4) wait for the deployment to start running all the pods
5) forward the port or see it on wsl using a browser using the nodePort:30001 for the voting application and the result on nodePort:30002
