kubectl apply -f route-audit.yaml
kubectl -n net-audit get pods -o wide
kubectl -n net-audit logs <pod-name>
or logs are on the node? /var/log/aks-route-audit/<node-hostname>-<timestamp>.log
