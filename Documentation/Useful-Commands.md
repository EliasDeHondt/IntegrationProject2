![logo](https://eliasdh.com/assets/media/images/logo-github.png)
# 💙🤍Useful Commands🤍💙

## 📘Table of Contents

1. [📘Table of Contents](#📘table-of-contents)
2. [📝Commands](#📝Commands)
3. [🔗Links](#🔗links)

---

## 📝Commands

- Gcloud
```bash
gcloud init # Initialize gcloud

sudo apt-get install google-cloud-cli-gke-gcloud-auth-plugin # Install gcloud package for kubernetes

gcloud container clusters delete $cluster_name --region=$zone -q # Delete a cluster
```

- kubernetes
```bash
kubectl top nodes # Get the usage of all nodes

kubectl top pods --all-namespaces # Get the usage of all pods

kubectl get all # Get all resources

kubectl get nodes # Get all nodes

kubectl get pods # Get all pods

kubectl get deployments # Get all deployments

kubectl get services # Get all services

kubectl get pvc # Get all persistent volume claims

kubectl get pv # Get all persistent volumes

kubectl apply -f ./apllication.yaml # Apply a yaml file

kubectl delete -f ./apllication.yaml # Delete a yaml file

kubectl delete pvc <pvc-name> # Delete a persistent volume claim

kubectl logs <pod-name> # Get the logs of a pod
```

## 🔗Links
- 👯 Web hosting company [EliasDH.com](https://eliasdh.com).
- 📫 How to reach us elias.dehondt@outlook.com