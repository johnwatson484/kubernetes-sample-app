[![Build Status](https://dev.azure.com/johnwatson484/John%20D%20Watson/_apis/build/status/Kubernetes%20Test%20App?branchName=master)](https://dev.azure.com/johnwatson484/John%20D%20Watson/_build/latest?definitionId=36&branchName=master)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=johnwatson484_kubernetes-test-app&metric=alert_status)](https://sonarcloud.io/dashboard?id=johnwatson484_kubernetes-test-app)
[![Known Vulnerabilities](https://snyk.io/test/github/johnwatson484/kubernetes-test-app/badge.svg)](https://snyk.io/test/github/johnwatson484/kubernetes-test-app)

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
