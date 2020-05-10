[![Build Status](https://dev.azure.com/johnwatson484/John%20D%20Watson/_apis/build/status/Kubernetes%20Test%20App?branchName=master)](https://dev.azure.com/johnwatson484/John%20D%20Watson/_build/latest?definitionId=36&branchName=master)

# Kubernetes test app
Simple test app to test deployment to Kubernetes cluster.

## Prerequisites
- Kubernetes
- Helm

## Installing to cluster 
```
helm repo add helm repo add johnwatson https://johnwatson484.github.io/helm-charts/
helm repo update
helm install DEPLOYMENT_NAME johnwatson/kubernetes-test-app
```
