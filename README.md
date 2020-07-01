> Copyright 2020

### CREATE A NODE IN VM using Platform9 SaaS
```
bash <(curl -sL http://pf9.io/get_cli)
```
### CREATE A CLUSTER
```
pf9ctl cluster bootstrap MyFirstCluster
```
### INSTALL LIBRARIES
```
sudo apt-get install curl
```
```
sudo apt-get install git 
```
**Get all the files in one folder and use "open in terminal"
### CREATE CONTAINER USING DOCKER
```
sudo docker build -t astzko:v1 .
```
```
sudo docker images	//show all images of your cluster
```
```
sudo docker run -d -p 80:80 astzko:v1
```
### USE THE YAML FILES TO CREATE DEPLOYMENT AND SERVICE
```
kubectl apply -f depl.yaml
```
```
kubectl apply -f serv.yaml
```
## Architecture Kubernetes Single Node Cluster
![Settings Window](https://github.com/ioatzi/KubernetesAPP/blob/master/images/Architecture%20Kubernetes%20Single%20Node%20Cluster.jpg)


## Created by:
Asimakopoulos Alexandros (https://github.com/Alex-Asim)

Kouloglou Ioannis Omiros (https://github.com/GiannisKouloglou)

Tzitzios Ioannis (https://github.com/ioatzi)
