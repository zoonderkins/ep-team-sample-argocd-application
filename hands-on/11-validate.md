# ConfigMap
kubectl exec configmap-example -c nginx -- cat /etc/config/conf.yml
kubectl exec configmap-example -c nginx -- printenv

# Secret
kubectl exec secret-example -c nginx -- printenv
kubectl exec secret-example -c nginx -- cat /etc/config/foo