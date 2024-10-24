# kubernetes_exercise
This repository contains Kubernetes deployment configurations for the akiraazra/multistage-test Docker image. The project demonstrates how to deploy a containerized application using a multi-stage Docker build, leveraging Kubernetes for scalability, efficient resource management, and rolling updates.

Features:

    Multi-Stage Docker Build: Optimized Docker image with reduced size.
    Kubernetes Deployment: Automated management of Pods, ensuring high availability and scalability.
    Rolling Update Strategy: Seamless updates with zero downtime using maxSurge and maxUnavailable settings.
    Resource Management: Configured CPU and memory requests/limits for efficient use of cluster resources.
    Service Exposure: Internal Kubernetes Service for communication with Pods.

Files Included:

    deployment.yaml: Defines the Deployment configuration, specifying the image, resource requirements, and rolling update strategy.
    service.yaml: Creates a Service to expose the deployed application within the Kubernetes cluster.
