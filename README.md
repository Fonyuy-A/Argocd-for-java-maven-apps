# Argocd-for-java-maven-apps
# Java Maven App - Argo CD Deployment

This repository contains Kubernetes manifests for deploying a Java Maven application using Argo CD.

## Application Details
- *Image*: fonyuya/java-maven-app
- *Port*: 3000
- *Replicas*: 2
- *Namespace*: webapp

## Files
- k8s/deployment.yaml - Kubernetes Deployment
- k8s/service.yaml - Kubernetes Service  
- k8s/kustomization.yaml - Kustomize configuration
- argocd-app.yaml - Argo CD Application definition

## Deployment
1. Make sure the webapp namespace exists:
   ```bash
   kubectl create namespace webapp
