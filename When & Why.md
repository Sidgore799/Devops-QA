# When & Why a Tool is launched in the Industry

## 1. Networking -
Why -
Networking is essential in DevOps because it enables communication between applications, servers, and services in distributed systems.
It is required for cloud infrastructure, CI/CD pipelines, and tools like Docker and Kubernetes to function properly.
It also helps in securing systems and troubleshooting issues like connectivity or performance problems.

Before:
Manual network configuration (routers, switches, firewalls)
Static IP management, hardware-based scaling
Troubleshooting was slow and mostly manual

After:
Software-defined networking (SDN), cloud networking
Auto-scaling, load balancers, VPCs
Faster troubleshooting with monitoring tools

## 2. Devops -
When & why -
DevOps is needed to improve collaboration between development and operations, enabling faster, reliable software delivery and reducing deployment failures.
It automates processes like testing, integration, and deployment, increasing efficiency and scalability.
The DevOps culture started around 2008–2009, popularized after the first DevOpsDays conference in Belgium.

Before:
Dev & Ops worked in silos
Manual deployments, slow releases
High failure rate

After:
CI/CD pipelines, collaboration culture
Automated builds, tests, deployments
Faster delivery, high reliability

## 3. Linux -
When & why -
Linux is needed in DevOps because most servers, cloud systems, and tools run on it, making it essential for automation, scripting, and deployment.
It provides stability, security, and flexibility for managing infrastructure and containers.
Linux started in 1991, created by Linus Torvalds as an open-source operating system kernel.

Before:
Manual server setup
Configuration inconsistencies
Hard to manage at scale

After:
Automated provisioning (scripts, tools)
Standardized environments
Used heavily in cloud & containers

## 4. Shell scripting -
Why -
Shell scripting is needed in DevOps to automate repetitive tasks like deployments, backups, and server configuration.
It helps in writing scripts for CI/CD pipelines, reducing manual effort and human errors.
It also allows efficient system management and integration with tools in Linux-based environments.

Before:
Tasks done manually
Human errors common

After:
Automation of repetitive tasks
Cron jobs, deployment scripts
Saves time and reduces errors
  
## 5. Disaster recovery -
When & Why -
Disaster recovery is needed in DevOps to quickly restore systems and data after failures, ensuring minimal downtime and business continuity.
It protects against data loss, cyberattacks, and infrastructure failures through backups and failover strategies.
The concept began evolving in the 1970s with mainframe backup systems and became more structured after events like the September 11, 2001 attack in US, which highlighted the need for robust recovery planning.

Before:
Manual backups (tapes, physical storage)
Slow recovery (hours/days)

After:
Automated backups, snapshots
Multi-region redundancy
Faster recovery (minutes)

# Phase - 1 -->

## 1. Git-GitHub -
When & Why -
Git and GitHub are needed in DevOps for version control, enabling teams to track changes, collaborate, and manage code efficiently.
They support CI/CD pipelines by integrating code changes with automated build and deployment processes.
Git was created in 2005 by Linus Torvalds, and GitHub was launched in 2008 for hosting and collaboration.

Before:
Centralized version control (SVN)
Code conflicts difficult to manage

After:
Distributed version control (Git)
Branching, merging, pull requests
Collaboration becomes easy

## 2. Docker -
When & Why -
Docker is needed in DevOps to package applications with all dependencies into containers, ensuring consistent environments across development, testing, and production.
It improves scalability, portability, and simplifies deployment in CI/CD pipelines.
Docker was introduced in 2013 by Docker Inc., popularizing containerization.

Before:
Applications ran directly on OS
“Works on my machine” issue
Environment mismatch

After:
Containerization
Same environment everywhere
Lightweight & portable

## 3. Jenkins -
When & Why -
Jenkins is needed in DevOps to automate CI/CD pipelines, enabling continuous integration, testing, and deployment of applications.
It reduces manual effort, speeds up delivery, and helps catch errors early in the development cycle.
Jenkins started in 2011 as a fork of Hudson, becoming a widely used open-source automation tool.

Before:
Manual build & deployment
No automation pipeline

After:
CI/CD automation
Pipelines for build, test, deploy
Faster and consistent delivery

## 4. Maven -
When & Why -
Maven is needed in DevOps to automate build processes, manage project dependencies, and ensure consistent project structure.
It simplifies compiling, testing, and packaging applications, making CI/CD pipelines more efficient.
Apache Maven was introduced in 2004 by the Apache Software Foundation.

Before:
Manual dependency management
Complex build process

After:
Automated dependency management
Standard build lifecycle
Easy project structure

# Phase - 2 -->

## 1. Kubernetes -
When & Why -
Kubernetes is needed in DevOps to automate deployment, scaling, and management of containerized applications.
It ensures high availability, load balancing, and efficient resource utilization in production environments.
Kubernetes was introduced in 2014 by Google and later maintained by the Cloud Native Computing Foundation.

Before:
Manual container management
Scaling & orchestration difficult

After:
Container orchestration
Auto-scaling, self-healing
High availability

## 2. Terraform -
When & Why -
Terraform is needed in DevOps to automate infrastructure provisioning using Infrastructure as Code (IaC), making environments consistent and reusable.
It helps manage cloud resources efficiently across platforms with version-controlled configurations.
Terraform was introduced in 2014 by HashiCorp.

Before:
Manual infrastructure setup
Hard to replicate environments

After:
Infrastructure as Code (IaC)
Version-controlled infra
Easy to recreate environments

## 3. Ansible -
When & Why -
Ansible is needed in DevOps to automate configuration management, application deployment, and server provisioning without needing agents.
It simplifies infrastructure management using simple YAML-based playbooks and reduces manual errors.
Ansible was introduced in 2012 and later acquired by Red Hat in 2015.

Before:
Manual configuration of servers
Inconsistent environments

After:
Configuration management automation
Agentless (SSH-based)
Consistent server setup
 
## 4. AWS -
When & Why -
AWS is needed in DevOps to provide scalable, on-demand cloud infrastructure for building, deploying, and managing applications.
It supports automation, CI/CD pipelines, and services like compute, storage, and networking without managing physical hardware.
Amazon Web Services started in 2006, launched by Amazon.

Before:
Physical data centers
High upfront cost
Limited scalability

After:
On-demand cloud services
Pay-as-you-go
Infinite scalability
 
## 5. Monitoring -
Grafana -
When & Why -
Grafana is needed in DevOps to visualize and monitor system metrics, logs, and performance through dashboards.
It helps teams track application health, detect issues, and improve reliability in real time.
Grafana was first released in 2014 by Torkel Ödegaard.

Prometheus -
When & Why -
Prometheus is needed in DevOps to monitor systems and applications by collecting metrics and enabling alerting.
It helps in real-time performance tracking and quick issue detection for reliable operations.
Prometheus was developed in 2012 at SoundCloud and later became a CNCF project.

Before:
Reactive monitoring
Logs checked manually

After:
Real-time monitoring & alerting
Tools like Prometheus, Grafana
Proactive issue detection
 
## 6. GitHub Actions -
When & Why -
GitHub Actions is needed in DevOps to automate CI/CD workflows directly from the code repository, enabling build, test, and deployment pipelines.
It simplifies automation, improves collaboration, and speeds up software delivery.
GitHub Actions was launched in 2018 by GitHub.

Before:
External CI/CD tools required

After:
Built-in CI/CD in GitHub
Easy workflow automation
Faster integration

## 7. ArgoCD -
When & Why -
Argo CD is needed in DevOps to implement GitOps, automating deployment and synchronization of applications in Kubernetes from Git repositories.
It ensures consistent, version-controlled deployments and simplifies rollback and monitoring.
Argo CD was introduced around 2018 by Intuit and later became a CNCF project.

Before:
Manual Kubernetes deployments
Hard to track configuration drift

After:
GitOps-based deployment
Auto-sync from Git
Declarative infrastructure

## 8. GitLab -
When & Why -
GitLab is needed in DevOps to provide an all-in-one platform for version control, CI/CD, and project management in a single tool.
It helps automate the software lifecycle from code commit to deployment, improving collaboration and efficiency.
GitLab was started in 2011 by Dmitriy Zaporozhets and Valery Sizov.

Before:
Separate tools for repo, CI/CD, security

After:
All-in-one DevOps platform
Repo + CI/CD + security
Simplified workflow
