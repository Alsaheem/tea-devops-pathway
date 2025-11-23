# tea-devops-pathway

# DevOps Beginner Pathway — Topics → Practical Projects

* * *

## 1\. Linux / Shell Scripting

### Projects

  

1.  User & Permission Automation Script  
      
    

*   Shell script to bring up the smallest vm on aws for demo usage ([up.sh](http://up.sh) and [down.sh](http://down.sh) ) . your shell script should export username and password to a file o your laptop
    
*   Script to create users, groups, assign permissions, and generate audit logs.  
      
    

3.  Log File Analyzer  
      
    

*   Parse /var/log/\* files, extract errors, send summary to email/slack.  
      
    

5.  Backup & Restore Script  
      
    

*   Automated file/folder backup using tar + cron, with restore capability.  
      
    

7.  Process Monitoring Tool  
      
    

*   Script that monitors CPU/memory and kills/restarts services when required.  
      
    

9.  Simple CLI Tool  
      
    

*   Create a menu-driven Bash tool (start service, stop service, check health).  
      
    

  

* * *

## 2\. Python (Scripting, Flask, FastAPI)

### Projects

1.  Simple REST API with Flask  
      
    

*   CRUD API with basic auth + Dockerization.  
      
    

3.  URL Shortener with FastAPI  
      
    

*   Includes SQLite + API tests + Swagger docs. Also includes html frontend  
      
    

5.  Automation Script — AWS Resource Cleaner  
      
    

*   Python script that deletes unused EC2, EBS, S3 (mock AWS with moto or real AWS).  
      
    

7.  Monitoring API  
      
    

*   FastAPI app that exposes system metrics in /metrics (CPU, RAM) and logs them.  
      
    

9.  Python CLI Tool  
      
    

*   Build your own CLI using argparse to manage files, logs, and servers.  
      
    

* * *

## 3\. Docker & Docker Compose

### Projects

1.  Containerize a Flask/FastAPI App  
      
    

*   Multi-stage Dockerfile + health checks.  
      
    

3.  Docker Compose: Multi-Service Application  
      
    

*   Web app + Redis + Postgres + Nginx reverse proxy.  
      
    

5.  Build a Custom Nginx Image  
      
    

*   Serve static HTML, add custom configs, use volume mounts.  
      
    

7.  “Local Dev Environment in a Box”  
      
    

*   Compose file to spin up Jenkins, Grafana, Prometheus locally.  
      
    

9.  Image Security Scanning  
      
    

*   Use Trivy to scan your images + fix vulnerabilities.  
      
    

* * *

## 4\. CI Pipelines (GitHub Actions, GitLab CI, Jenkins)

### Projects

1.  CI/CD for a Python App  
      
    

*   GitHub Actions workflow for test → build → Docker push.  
      
    

3.  GitLab CI Pipeline for a Node App  
      
    

*   Lint, unit test, build image, deploy to staging environment.  
      
    

5.  Jenkins Pipeline Using Jenkinsfile  
      
    

*   Declarative pipeline: checkout → build → test → deploy.  
      
    

7.  Automated Security Checks  
      
    

*   Integrate Trivy, Bandit, Codespell, and pytest into pipelines.  
      
    

9.  Blue-Green Deployment Pipeline  
      
    

*   CI pipeline that deploys app to two environments then switches traffic.  
      
    

* * *

## 5\. Infrastructure as Code (Terraform)

### Projects

1.  Deploy an EC2 Instance + Security Group  
      
    

*   Your first Terraform module.  
      
    

3.  VPC with Public/Private Subnets  
      
    

*   Route tables, internet/NAT gateway.  
      
    

5.  Terraform + S3 + DynamoDB Backend  
      
    

*   Remote state management with locking.  
      
    

7.  EKS Cluster Provisioning  
      
    

*   Create cluster + node group + outputs.  
      
    

9.  Reusable Terraform Modules  
      
    

*   Module for EC2, S3, IAM, and RDS.  
      
    

* * *

## 6\. Configuration Management (Ansible)

### Projects

1.  LAMP or LEMP Server Setup  
      
    

*   Install Nginx, Python using Ansible Playbooks.  
      
    

3.  Ansible Role for Docker Installation  
      
    

*   Role that installs and configures Docker on Ubuntu.  
      
    

5.  Automated User & SSH Key Management  
      
    

*   Provision multiple servers with correct users/keys.  
      
    

7.  Server Hardening Playbook  
      
    

*   Disable root login, enforce password policy, configure firewall.  
      
    

9.  Zero-Downtime Deployment with Ansible  
      
    

*   Rolling updates of a web service.  
      
    

* * *

## 7\. AWS (10 Beginner → Intermediate Projects)

### Projects

1.  S3 Static Website Hosting  
      
    
2.  EC2 Web Server Deployment (Nginx/Flask)  
      
    
3.  VPC Creation with 2 Subnets  
      
    
4.  RDS + Flask App Deployment  
      
    
5.  Load Balancer + Auto Scaling Group  
      
    
6.  Serverless API using API Gateway + Lambda  
      
    
7.  CI/CD with CodePipeline + CodeBuild  
      
    
8.  S3 → Lambda → DynamoDB ETL Pipeline  
      
    
9.  CloudWatch Alarms + SNS Notifications  
      
    
10.  Deploy EKS Cluster with App  
      
    

* * *

## 8\. Kubernetes

### Projects

1.  Deploy a Flask API to Kubernetes  
      
    

*   Deployment, Service, ConfigMap, Secret.  
      
    

3.  Ingress + Nginx Controller Setup OR Gateway API  
      
    

*   Route multiple apps through the same ingress.  
      
    

5.  Helm Chart Creation  
      
    

*   Package your app as a Helm chart.  
      
    

7.  Kubernetes Monitoring  
      
    

*   Deploy Prometheus + Grafana.  
      
    

9.  CI/CD → Kubernetes Deployment  
      
    

*   GitHub Actions deploying to a K8s cluster.