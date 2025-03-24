# Kubernetes with Examples

Welcome to **Kubernetes with Examples** – a repository dedicated to Kubernetes for DevOps, featuring practical scripts from real-world projects and open-source resources. This serves as a hands-on reference for automating, deploying, and managing Kubernetes workloads efficiently.

## 📂 Repository Structure

Currently, the repository includes the following directories:

```
📦 kubernetes-with-examples
 ┣ 📂 action-apiGroups      # Scripts related to API groups & RBAC
 ┣ 📂 action-deployments   # Deployment automation scripts
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
$ git clone https://github.com/your-username/kubernetes-with-examples.git
$ cd kubernetes-with-examples
```

### Usage
Each folder contains specific Kubernetes YAML configurations and scripts.
For example, to apply a deployment from `action-deployments`:
```sh
$ kubectl apply -f action-deployments/my-deployment.yaml
```

## 📌 Topics Covered
✅ API Groups & RBAC  
✅ Deployments & Workloads  
✅ More topics coming soon...

## 📢 Contributing
Contributions are welcome! If you find something interesting to add, feel free to submit a pull request.

## 📜 License
This repository is licensed under the [MIT License](LICENSE).

---
