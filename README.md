# sillytavern-kubernetes
Kubernetes port of sillytavern

This implementation tries to stay as true to the original docker and local install as possible.

Features:

    Kubernetes-Native Deployment: Deploy SillyTavern with a single kubectl apply using provided manifests.

    Persistent Storage: Uses PersistentVolumeClaims (PVCs) to store user data (characters, chats, settings).

    Configurable Settings: Customize SillyTavern via a ConfigMap for easy management.

    Scalable Architecture: Supports multiple replicas for high availability.


Prerequisites:
    A running Kubernetes cluster (e.g., Minikube, K3s, or a cloud provider like AWS EKS, GKE, or AKS).

    kubectl installed and configured to interact with your cluster.

    Docker installed for local testing or building custom images (optional).

    Git installed to clone this repository.

    A storage class configured in your cluster for persistent storage (e.g., gp2 for AWS).

    (Optional) An Ingress controller (e.g., NGINX) for external access.



Acknowledgments
    SillyTavern for the core application and Docker image.

    The Kubernetes community for robust container orchestration.




