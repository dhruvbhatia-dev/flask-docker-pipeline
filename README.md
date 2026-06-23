# Automated CI/CD Pipeline:2-Tier-Flask-MYSQL Deployment on AWS

**Author:** Dhruv Bhatia
**Project Focus:** Automating end-to-end deployment using Jenkins and Docker.

---

### **Table of Contents**
1. [Project Overview](#1-project-overview)
2. [Infrastructure Design](#2-infrastructure-design)
3. [Prerequisites & Setup](#3-prerequisites-&-setup)
    * [AWS EC2 Instance Preparation](#aws-ec2-instance-preparation)
    * [Installing Dependencies](#installing-dependencies)
4. [Configuration & Automation](#4-configuration-and-automation)
    * [Jenkins Installation](#jenkins-installation)
    * [Github Repository Configuration](#github-repository-configuration)
       * [Dockerfile](#-dockerfile)
       * [Docker-compose.yml](#docker-composeyml)
       * [Jenkinsfile](#Jenkinsfile)
    * [Jenkins Pipeline Creation & Execution](#jenkins-pipeline-creation-&-execution)
5. [Conclusion](#5-conclusion)

---

### **1. Project Overview**
This project demonstrates the end-to-end automation of a 2-tier web application(Flask + MYSQL) deployment. The infrastructure is hosted on AWS EC2, and the deployment process is containerized using Docker and Docker Compose. A robust CI/CD pipeline,built with jenkins, ensure that code changes are automatically tested and deployed upon pusing to github.

---

### **2. Infrastructure Design**
![Devops Architecture](images/diagram-export-23-6-2026-2_59_44-PM.png)


