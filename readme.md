

This repo deploys a simple nginx server to a local machine with Docker, kubectl, k3s, ArgoCD installed and running as prerequisites.

Once deployed and synced to this repo via ArgoCD web ui, run nginx locally using kubectl port-forward svc/nginx-service -n default 8081:80
