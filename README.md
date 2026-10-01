# AWS Kubernetes GitOps

This repository contains the desired Kubernetes deployment state for the
`aws-k8s-devops-project`.

## Repository Structure

```text
apps/
└── ksh-devops-demo/
    ├── base/
    │   ├── deployment.yaml
    │   ├── service.yaml
    │   └── kustomization.yaml
    └── overlays/
        └── production/
            ├── namespace.yaml
            ├── deployment-patch.yaml
            └── kustomization.yaml