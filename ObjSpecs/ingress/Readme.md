# this is best way to install ingress-nginx
(also there is two ingress controllers in the opensource, ingress-nginx and kubernetes-ingress - use ingress-nginx)
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm repo update
helm install ingress-nginx ingress-nginx/ingress-nginx
