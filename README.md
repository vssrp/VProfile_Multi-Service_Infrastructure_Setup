# VProfile Multi-Service Infrastructure Setup

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Prerequisites](#prerequisites)
5. [Setup Instructions](#setup-instructions)
   - [Manual Provisioning](#manual-provisioning)
   - [Automated Provisioning](#automated-provisioning)
6. [Services and Ports](#services-and-ports)
7. [Testing](#testing)
8. [Outcomes](#outcomes)
9. [Contributing](#contributing)
10. [License](#license)

---

## Project Overview
VProfile is a multi-tier web application that demonstrates the setup of a distributed infrastructure using both **manual** and **automated provisioning** approaches. This setup was tested on a Java-based project to deploy and manage backend services efficiently.

---

## Features
- **Manual Provisioning**: Step-by-step configuration of services for hands-on learning and granular control.
- **Automated Provisioning**: Shell scripts automate the setup of services for faster deployment and consistency.
- **Multi-Service Architecture**: Deployed MariaDB, Memcached, RabbitMQ, Tomcat, and Nginx services.
- **Scalable and Reliable Infrastructure**: Ensures secure networking and proper resource allocation.
- **Maven-based Application Build**: Deployment of a Java application as part of the test environment.

---

## Technologies Used
- **Infrastructure Automation**: Vagrant, VirtualBox  
- **Operating Systems**: CentOS, Ubuntu  
- **Services**: MariaDB, Memcached, RabbitMQ, Tomcat, Nginx  
- **Programming Language**: Java (for the test application)  
- **Build Tools**: Maven  
- **Scripting**: Shell scripting  

---

## Prerequisites
- Oracle VM VirtualBox  
- Vagrant  
- Vagrant plugins (`vagrant-hostmanager`)  
- Git  
- JDK 17 (for Java application testing)  
- Maven  

---

