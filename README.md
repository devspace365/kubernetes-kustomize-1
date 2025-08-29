# kubernetes-kustomize-basics
How to use Kubernetes Kustomize to manage deployments into stage and dev environments

Directory Structures

├── base/                  # Your original configuration
│   ├── deployment.yaml    # A basic nginx deployment
│   └── kustomization.yaml # Tells Kustomize what to include
└── overlay/              # Your customizations
    └── kustomization.yaml # Defines how to modify the base
