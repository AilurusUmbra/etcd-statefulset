## 部署順序

### 1. Service
kubectl apply -f service.yaml -f service-client.yaml -f discovery_service.yaml

### 2. ETCD
kubectl apply -f statefulset.yaml

### 3. Discovery Server
kubectl apply -f discovery_deploy.yaml
