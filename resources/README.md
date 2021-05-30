## 部署順序


### 1. ETCD
kubectl apply -f etcd/

### 2. Discovery Server
kubectl apply -f discoveryserver/

### 3. Network Policy
kubectl apply -f networkpolicy.yaml
