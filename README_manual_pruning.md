# Multi-Service Infrastructure Setup
---

## Project Overview
This Project is a multi-tier web application demonstrating a manual provisioning approach for setting up a distributed infrastructure. This project involves configuring multiple services and ensuring secure networking for a production-like environment.

---

## Features
- **Automated VM provisioning** using Vagrant with VirtualBox and host manager plugins.
- **Manual configuration** of services: MariaDB, Memcached, RabbitMQ, Tomcat, and Nginx.
- **Secure networking** through firewall and port management.
- **Maven-based application build** and deployment.

---

## Technologies Used
- **Infrastructure Automation**: Vagrant, VirtualBox  
- **Operating Systems**: CentOS, Ubuntu  
- **Services**: MariaDB, Memcached, RabbitMQ, Tomcat, Nginx  
- **Build Tools**: Maven  
- **Version Control**: Git  

---

## Prerequisites
- Oracle VM VirtualBox  
- Vagrant (with `vagrant-hostmanager` plugin)  
- Git Bash or equivalent terminal  
- JDK 17  
- Maven  

---

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/vprofile-project.git
   cd vprofile-project
