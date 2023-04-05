# The below steps are to access a kubernetes-dashboard using ingress on Docker Desktop

1. Install an NGINX ingress controller by running the following command:

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.7.0/deploy/static/provider/cloud/deploy.yaml

2. Install a Kubernetes Dashboard by running the following command:

kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.2.0/aio/deploy/recommended.yaml

3. Apply the dashboard-ingress.yaml manifest file

4. Type "localhost" in your browser to login