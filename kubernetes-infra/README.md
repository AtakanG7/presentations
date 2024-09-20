## Cloud Agnostic Design Using Kubernetes, Helm, and Jenkins

This project demonstrates a cloud-agnostic deployment pipeline using Terraform, Kubernetes, Helm, and Jenkins. The focus is on achieving scalable, flexible infrastructure across multiple cloud providers.

## Key Technologies:
- **Terraform**: Infrastructure provisioning
- **Kubernetes**: Container orchestration
- **Helm**: Kubernetes package management
- **Jenkins**: CI/CD automation

## Features:
1. **Cloud Agnostic Architecture**: Supports AWS, Azure, and GCP.
2. **Kubernetes Cluster**: Includes namespaces for monitoring, staging, and production with services like Prometheus, Grafana, and MongoDB.
3. **Jenkins Pipeline**:
   - Code Checkout
   - Helm Chart Setup
   - Docker Build & Push
   - Staging Deploy, Testing, Approval
   - Production Deploy

## Pipeline Workflow:
1. **Checkout Application**: Clones the latest code from GitHub.
2. **Helm Chart Repository Setup**: Prepares Helm charts for deployment.
3. **Docker Build & Push**: Builds and pushes Docker images to the registry.
4. **Staging & Production Deployment**: Automated deployments with manual approval for production.