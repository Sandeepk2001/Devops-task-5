# Devops-task-5
# TASK 5: Kubernetes Local Cluster Deployment

This repository contains the deliverables for building and managing a local Kubernetes cluster using Minikube.

## Steps Performed:
1.  **Prerequisites:** Installed Docker, Minikube, and kubectl.
2.  **Cluster Setup:** Started the local cluster using `minikube start`.
3.  **Deployment:** Applied `deployment.yaml` (2 replicas) and `service.yaml` (NodePort) to deploy the Nginx web application.
4.  **Scaling:** Used `kubectl scale` to increase the number of running replicas from 2 to 4.
5.  **Verification:** Verified the application state via `kubectl get pods` before and after scaling.

## Deliverables:
- `deployment.yaml`
- `service.yaml`
- `screenshot_2_pods.png` (Proof of initial deployment)
- `screenshot_4_pods.png` (Proof of successful scaling)

## Final Verification Note:
Application access via the browser was blocked due to external Windows networking/firewall issues, which is common with the Docker driver. However, the application was confirmed to be running and scaled correctly within the cluster environment.
