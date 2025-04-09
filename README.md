# Kubernetes with Examples

Welcome to **Kubernetes with Examples** – a repository dedicated to Kubernetes for DevOps, featuring practical scripts from real-world projects and open-source resources. This serves as a hands-on reference for automating, deploying, and managing Kubernetes workloads efficiently.

## 📂 Repository Structure

Currently, the repository includes the following directories:

```
📦 kubernetes-with-examples
 ┣ 📂 action-apiGroups      # Scripts related to API groups & RBAC
 ┣ 📂 action-deployments   # Deployment automation scripts
 ┣ 📂 action-storage      # Storage and persistence examples
 ┗ 📜 README.md            # You are here! 📖
```

More scripts and examples will be added as I progress through my learning and projects.

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- [Kubernetes CLI (kubectl)](https://kubernetes.io/docs/tasks/tools/)
- [Minikube](https://minikube.sigs.k8s.io/docs/) or access to a Kubernetes cluster
- Basic knowledge of Kubernetes concepts

### Clone the Repository
```sh
$ git clone https://github.com/codehunter-py/kubernetes-with-examples.git
$ cd kubernetes-with-examples
```

### Usage
Each folder contains specific Kubernetes YAML configurations and scripts.
For example, to apply a deployment from `action-deployments`:
```sh
$ kubectl apply -f action-deployments/httpd-deployment.yaml
```

## 📌 Topics Covered
✅ API Groups & RBAC  
✅ Deployments & Workloads  
✅ Storage & Persistence
  - Persistent Volumes (PV) and Claims (PVC)
  - Dynamic Volume Provisioning
  - Volume Types (hostPath, emptyDir, projected)
  - Backup and Restore Scenarios
✅ CI/CD with Jenkins
  - Jenkins Deployment with Persistent Storage
  - RBAC Configuration
  - Service Account Setup
✅ More topics coming soon...

## 🔍 Storage Examples
The `action-storage` directory contains various examples:
- Basic volume mounts
- Persistent volume configurations
- Dynamic volume provisioning
- Web application with persistent storage
- Backup and restore scenarios
- Jenkins deployment with persistent storage

### Example: Deploying Jenkins
```sh
# Deploy Jenkins with persistent storage
$ kubectl apply -f action-storage/jenkins-deployment.yaml

# Access Jenkins UI (using Minikube)
$ minikube service jenkins-service -n jenkins
```

## 📢 Contributing
Contributions are welcome! If you find something interesting to add, feel free to submit a pull request.

## 📜 License
This repository is licensed under the [MIT License](LICENSE).

---
