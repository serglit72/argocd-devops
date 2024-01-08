# argocd-devops

This repository is used for update ArgoCD (ADMIN) and ArgoCD (worker nodes) instance in terms of Application for Applications deployment pattern.

Once any files in dev, prod or Helm folders is updated then ArgoCD ADMIN app pulls the newest file and deploys it to EKS corresponded cluster (dev or prod)

Trigger is any update in a APP-REPO where the applications located. 

 # TODO 
To provide update for the application version tags the GitHub Actions is used 