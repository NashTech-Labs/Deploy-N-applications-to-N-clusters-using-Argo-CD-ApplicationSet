# Deploy-N-applications-to-N-clusters-using-Argo-CD-ApplicationSet
ArgoCD is a declarative, GitOps based Continous Delivery (CD) tool for Kubernetes. It focuses on the management of application deployments, 
with an outstanding feature set covering several synchronization options, user-access controls, status checks, and many more. 

# Prerequisite
1. Installed kubectl command-line tool
2. Have kubeconfig file
3. Git repo
4. Installed ArgoCD here
5. Setup the clusters on GKE or EKS (where ever you want)

# Applicationset controller
1. You can deploy the argoCD application to multiple Kubernetes clusters.
2. You can deploy multiple argoCD applications from one single repo
3. Allows unprivileged cluster users (those without access to the Argo CD namespace) to deploy Argo CD Applications, 
   without the need to involve cluster administrators in manually enabling the clusters/namespaces
   
# Steps 
* Just clone this repo and add your cluster name with URL in generator list. 
* For more information follow the official documentation https://argocd-applicationset.readthedocs.io/en/stable/ .
