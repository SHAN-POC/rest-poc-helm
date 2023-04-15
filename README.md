# Helm Chart for rest-poc applciation  

## Lint and see if there are any errors  

helm lint ./hello-world

## View final deployment scripts that would be run after applying values  

helm template .\rest-poc-helm\

## Install Helm chart into Kubernetes

helm install release-0-0-1-snapshot .\rest-poc-helm\  

## Uninstall Helm chart  

helm uninstall release-0-0-1-snapshot  
