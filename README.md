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


---

## 🚀 Steps Performed

1. **Start Minikube**
  
   ```bash
    minikube start
   ```
2. **Create Deployment**
   
   Apply the deployment manifest to create your app deployment:
 
   ```bash
     kubectl apply -f deployment.yaml 
   ```

3. **Expose the App**

   Expose your app using a Kubernetes service:
 ```bash
   kubectl apply -f service.yaml
 ```

4. **Check All Resources**

   View all the Kubernetes objects running in your cluster:

   ```bash
     kubectl get all 
   ```
5. **Clean Up Resources**

   To delete the deployment and service:
```bash
   kubectl delete -f deployment.yaml
   kubectl delete -f service.yaml  
```

6. **Project Structure**
    
├── deployment.yaml
└── service.yaml


## 🎉 Conclusion

Congratulations! You’ve successfully deployed your application on Kubernetes using Minikube.  
This foundational setup opens the door to exploring more advanced Kubernetes features like scaling, rolling updates, and monitoring.  
Keep experimenting and building your skills — the cloud-native world is yours to conquer!




















