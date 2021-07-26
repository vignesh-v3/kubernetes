kubectl create ns cert-manager
kubectl apply -f https://github.com/jetstack/cert-manager/releases/download/v1.4.0/cert-manager.yaml
kubectl get ns
kubectl get pod -n cert-manager
kubectl get all -n cert-manager

cert manager has the following components
-cert manager
-ca injector
-webhook
