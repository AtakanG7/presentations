# Cloud Agnostic Design Using Kubernetes, Helm, and Jenkins

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

## Tech Stack Overview:
![Terraform](https://blogs.vmware.com/cloudprovider/files/2019/04/og-image-8b3e4f7d-blog-aspect-ratio.png)
![Kubernetes](https://img-resize-cdn.joshmartin.ch/2000x0%2C0297127326a2d62f464846509f6db87f447340fd5bbca07b7830b5c389ee83ca/https://joshmartin.ch/app/uploads/2018/01/logo.svg)
![Helm](https://static-00.iconduck.com/assets.00/helm-icon-493x512-9fdnqczp.png)
![Jenkins](https://img.icons8.com/?size=512&id=39292&format=png)
