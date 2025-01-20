# Automated Multi-Service Infrastructure Setup
---

## Project Overview
This Project is a multi-tier web application that demonstrates automated provisioning of a distributed infrastructure. This setup uses shell scripts to configure and deploy essential services for a production-like environment.

---

## Features
- **Automated VM provisioning** using Vagrant and VirtualBox.
- **Service Automation**: MariaDB, Memcached, RabbitMQ, Tomcat, and Nginx.
- **Pre-configured Application**: Database and backend setup via automated scripts.
- **Scalability**: Scripts are modular for easy customization.

---

## Technologies Used
- **Infrastructure Automation**: Vagrant, VirtualBox  
- **Operating Systems**: CentOS, Ubuntu  
- **Services**: MariaDB, Memcached, RabbitMQ, Tomcat, Nginx  
- **Build Tools**: Maven  
- **Scripting**: Shell scripting  

---

## Prerequisites
- Oracle VM VirtualBox  
- Vagrant  
- Vagrant plugins (`vagrant-hostmanager`)  
- Git  
- Shell (Bash) environment  

---

## Setup Instructions

### **Clone the Repository**
```bash
git clone https://github.com/your-repo/vprofile-project.git
cd vprofile-project
