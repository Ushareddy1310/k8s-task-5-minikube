# 🧪 Task 5: Build a Kubernetes Cluster Locally with Minikube

## 🎯 Objective
To deploy and manage a simple web application on a Kubernetes cluster using Minikube and `kubectl`.

---

## 🛠️ Tools Used
- [Minikube](https://minikube.sigs.k8s.io/docs/)
- [kubectl](https://kubernetes.io/docs/reference/kubectl/)
- [Docker](https://www.docker.com/)

---

## 📁 Project Structure

k8-task-5/
├── deployment.yaml # Kubernetes deployment manifest
├── service.yaml # Kubernetes service manifest
├── README.md # Documentation file
└── screenshots/ # Folder containing screenshots
├── pods-list.png
├── services-list.png
├── scaled-pods.png
└── app-access.png


---

## 🚀 Steps Performed

 1. **Start Minikube**
```bash
   minikube start


```bash
kubectl apply -f deployment.yaml




