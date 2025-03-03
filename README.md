# Helm_Charts and Kustomize
Helm Charts and Kustomize simplifies K8 Deployments, Rollbacks etc 

#Kustomization
k8s/
├── base/
│   ├── kustomization.yaml
│   ├── deployment.yaml
│   ├── service.yaml
│   └── configmap.yaml
├── overlays/
│   ├── dev/
│   │   ├── kustomization.yaml
│   │   └── configmap-dev.yaml
│   ├── staging/
│   │   ├── kustomization.yaml
│   │   └── configmap-staging.yaml
│   └── prod/
│       ├── kustomization.yaml
│       └── configmap-prod.yaml
└── common/
    ├── kustomization.yaml
    └── namespace.yaml
