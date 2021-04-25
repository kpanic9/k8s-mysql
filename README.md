# Kubernetes MySQL 
 
Runs a MySQL singleton on kubernetes with persistent storage from the
host and exposes it with service name mysql-service. 

MySQL version: 5.6
 
 
## Deploy k8s-mysql
 
```bash
git clone repo
cd k8s-mysql
helm install . -n k8s-mysql
```
 
