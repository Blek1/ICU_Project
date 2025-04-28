[github of projects](https://github.com/techiescamp/kubernetes-projects?tab=readme-ov-file)

Project Overview:  

This project explores the setup and management of Kubernetes clusters on AWS and the deployment of containerized full-stack applications. The initial phase focuses on manual and tool-assisted cluster provisioning and deploying typical web application stacks. Later phases extend into networking, storage, observability, automation, and security within Kubernetes.

### Phase 1: Kubernetes Setup and Full-Stack Application Deployment

1. Project 01: Kubernetes the Hard Way on AWS  
   - Manually provision and configure a Kubernetes cluster on AWS.  
   - Set up networking, certificates, kubelets, control plane, and worker nodes.

2. Project 02: Setup Self-Hosted Kubeadm Cluster  
   - Use `kubeadm` to simplify Kubernetes cluster creation.  
   - Understand the difference in automation versus manual setup.

3. Project 03: Deploy Java App with MySQL on Kubernetes  
   - Containerize and deploy a Java web application with MySQL.  
   - Use Persistent Volumes and Kubernetes Services for backend access.

4. Project 04: Deploy WordPress with Nginx and MySQL  
   - Deploy a CMS using Kubernetes with an ingress controller.  
   - Understand multi-container pod deployment and external access configuration.

5. Project 05: Deploy Python Flask App with PostgreSQL  
   - Build and deploy a lightweight Python web API with PostgreSQL.  
   - Use ConfigMaps and Secrets for configuration management.

6. Project 06: Deploy Node.js App with MongoDB  
   - Deploy a full-stack Node.js app using MongoDB as a backend.  
   - Implement horizontal scaling, probes, and replica sets.

### Phase 2: Kubernetes Networking, Storage, and Monitoring

1. Cluster Networking  
   - Explore Container Network Interface (CNI) plugins (Calico, Flannel).  
   - Configure ingress controllers and service routing.

2. Persistent Storage  
   - Use dynamic volume provisioning with AWS EBS/EFS.  
   - Deploy applications using StatefulSets for stable identity.

3. Monitoring and Logging  
   - Integrate Prometheus and Grafana for metrics collection and dashboards.  
   - Set up Fluentd or Loki for log aggregation and monitoring.

### Phase 3: Advanced Kubernetes Management and Automation

1. Helm  
   - Convert Kubernetes manifests into Helm charts.  
   - Create and deploy reusable application templates.

2. GitOps Workflow  
   - Use ArgoCD or Flux to implement Git-based continuous delivery.  
   - Maintain declarative configuration and state sync from GitHub.

3. Kustomize  
   - Use overlays to manage configuration across multiple environments (dev, staging, prod).


### Phase 4: Kubernetes Security and Secrets Management

1. RBAC  
   - Define and apply fine-grained Role-Based Access Control policies.

2. Secrets Management  
   - Use Kubernetes Secrets with encryption at rest.  
   - Explore sealed-secrets or HashiCorp Vault for secure external secrets.

3. Pod and Network Security  
   - Apply PodSecurityPolicies or Pod Security Standards.  
   - Use NetworkPolicies to control traffic flow between pods and namespaces.


Deliverables

- A GitHub repository containing all deployment files, configurations, and documentation.  
- A technical report (10–15 pages) summarizing the architecture, implementation steps, key decisions, and lessons learned.  
- (Optional) A screencast or demo walkthrough showcasing deployments and monitoring dashboards.
