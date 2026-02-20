# Basic demo for argocd application

This demo is made by following the tutorial in the video [ArgoCD Tutorial for Beginners | GitOps CD for Kubernetes](https://www.youtube.com/watch?v=MeU5_k9ssrs) by Tech world with Nana 

The application resource features:
- Namespace creation if the target namespace does not exit
- Automatic synch by overwiting any maual changes made to the cluster to match the desired state found in the source repository
- Allows deletion of resources on the cluster following their deletion from the source repository (pruning)
