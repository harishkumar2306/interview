Project Name:

Automated CI/CD Pipeline for Microservices Deployment using Jenkins, Docker, and Kubernetes

Description:

Designed and implemented an end-to-end CI/CD pipeline to automate the build, containerization, and deployment of a microservices-based application. The pipeline integrates Jenkins for continuous integration, Docker for containerization, and Kubernetes for orchestration, enabling automated and consistent application delivery across development and production environments. Implemented DevSecOps practices by integrating SonarQube for static code analysis and Trivy for container image vulnerability scanning to ensure secure deployments.

Role: DevOps Engineer

Responsibilities:

Designed and configured end-to-end Jenkins pipelines using Declarative Jenkinsfile with stages for code checkout, Maven build, unit testing, Docker image build, and Kubernetes deployment.
Containerized the microservices application using Docker, creating optimized multi-stage Dockerfiles to reduce image size and improve build efficiency.
Pushed Docker images to Amazon ECR with automated tagging using Jenkins build numbers and Git commit hashes for image traceability.
Deployed and managed application workloads on Kubernetes using Helm charts, configuring Deployments, Services, Ingress, ConfigMaps, and Secrets for a production-grade setup.
Integrated SonarQube into the Jenkins pipeline to enforce code quality gates, preventing code with critical vulnerabilities or low test coverage from being deployed.
Integrated Trivy into the Jenkins pipeline to scan Docker images for known CVEs before pushing to the registry, improving container security posture.
Configured Kubernetes Horizontal Pod Autoscaler to automatically scale application replicas based on CPU utilization, ensuring high availability during traffic spikes.
Implemented rolling update and blue-green deployment strategies on Kubernetes to achieve near zero-downtime production releases.
Set up Prometheus and Grafana for real-time monitoring of pod health, resource utilization, and application performance metrics.
Managed secrets securely using HashiCorp Vault and AWS Secrets Manager, ensuring no sensitive credentials were hardcoded in manifests or pipeline scripts.


Tech Stack:

Jenkins · Docker · Kubernetes · Amazon EKS · Amazon ECR · Helm · Maven · SonarQube · Trivy · Prometheus · Grafana · HashiCorp Vault · AWS Secrets Manager · Git · GitHub
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Name:

Production-Grade Application Deployment on Amazon EKS using Jenkins and Docker

Description:

Designed and implemented a complete CI/CD and container orchestration solution to deploy a microservices application on Amazon EKS using Jenkins for pipeline automation and Docker for containerization. The project covers the full delivery lifecycle — from code commit to production deployment on Kubernetes — with integrated security scanning, GitOps-based delivery using ArgoCD, auto-scaling, and real-time observability using Prometheus and Grafana.

Role: DevOps Engineer

Responsibilities:

Configured and managed Amazon EKS cluster with managed node groups, IAM roles, OIDC provider, and cluster add-ons including CoreDNS, kube-proxy, and AWS EBS CSI driver for persistent storage.
Built end-to-end Jenkins CI/CD pipelines using Declarative Jenkinsfile with stages for code checkout, Maven build, unit testing, SonarQube code quality analysis, Docker image build, Amazon ECR push, and Kubernetes deployment.
Containerized microservices using Docker with multi-stage Dockerfiles, tagging images with Jenkins build numbers and Git commit hashes to ensure full image traceability across environments.
Deployed and managed application workloads on Amazon EKS using Helm charts, configuring Deployments, Services, Ingress, ConfigMaps, Secrets, HPA, and RBAC for a production-ready Kubernetes setup.
Implemented GitOps-based continuous delivery using ArgoCD, enabling automated synchronization of Kubernetes manifests from GitHub to the EKS cluster with drift detection and one-click rollback support.
Integrated SonarQube into the Jenkins pipeline to enforce code quality gates, blocking deployments when code coverage dropped below threshold or critical vulnerabilities were detected.
Integrated Trivy into the Jenkins pipeline to scan Docker images for known CVEs before pushing to Amazon ECR, ensuring only secure images are deployed to the cluster.
Configured Nginx Ingress Controller with SSL/TLS termination to securely route external traffic to backend Kubernetes services.
Implemented Horizontal Pod Autoscaler to automatically scale application pods based on CPU and memory utilization, ensuring availability during traffic spikes.
Set up Prometheus and Grafana for real-time monitoring of pod health, node resource utilization, and application performance metrics with custom dashboards and alerting rules.
Managed application secrets using AWS Secrets Manager and HashiCorp Vault, integrated with EKS workloads to eliminate hardcoded credentials from Kubernetes manifests and pipeline scripts.
Configured AWS CloudWatch Container Insights with Fluent Bit DaemonSet for centralized log collection and analysis across all pods and nodes in the EKS cluster.


Tech Stack:

Jenkins · Docker · Amazon EKS · Helm · ArgoCD · Amazon ECR · Maven · SonarQube · Trivy · Prometheus · Grafana · Nginx Ingress · AWS Secrets Manager · HashiCorp Vault · AWS CloudWatch · Fluent Bit · Git · GitHub

