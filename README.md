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
