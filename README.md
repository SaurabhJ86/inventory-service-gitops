# Inventory Service GitOps

This repository contains Kubernetes deployment configurations for the inventory-service.

## Structure
- `applications/` - ArgoCD Application definitions
- `base/` - Base Kubernetes manifests
- `environments/` - Environment-specific configurations

## Environments
- `local` - Kind cluster for local development
- `dev` - EKS development environment