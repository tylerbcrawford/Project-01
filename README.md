# **Secure Cloud Infrastructure Deployment on Microsoft Azure**

## **Introduction**

In this project, I designed and implemented a secure, cloud-based web application infrastructure using Microsoft Azure. The primary objective was to create a resilient and secure environment that demonstrates best practices in cloud security, load balancing, and redundancy. This project showcases my practical knowledge in cloud computing, network security, automation using Ansible, and containerization with Docker.

## **Table of Contents**

- [Project Overview](#project-overview)
  - [Objectives](#objectives)
  - [Tools and Technologies](#tools-and-technologies)
- [Architecture Diagram](#architecture-diagram)
- [Quick Start Guide](#quick-start-guide)
- [Results and Highlights](#results-and-highlights)
- [Conclusion and Reflections](#conclusion-and-reflections)
- [Contact Information](#contact-information)
- [License](#license)

## **Project Overview**

### **Objectives**

The core objectives of this project were:

- **Design a Secure Virtual Network**: Establish a virtual network within Azure, segmented into subnets and secured with Network Security Groups (NSGs).
- **Implement a Jump Box for Secure Access**: Deploy a Jump Box to manage access to the virtual machines securely.
- **Deploy Web Servers with Docker Containers**: Use Docker to deploy web servers running the Damn Vulnerable Web Application (DVWA).
- **Automate Deployment with Ansible**: Leverage Ansible for automating the configuration and deployment of VMs and Docker containers.
- **Set Up Load Balancing for High Availability**: Configure an Azure Load Balancer to distribute traffic and ensure availability.
- **Configure Network Security**: Implement NSGs and firewalls to protect the infrastructure.
- **Test Redundancy and Failover Capabilities**: Validate the system's ability to handle failures gracefully.
- **Conduct Security Assessments**: Perform penetration testing and vulnerability assessments.

### **Tools and Technologies**

- **Microsoft Azure**
- **Ansible**
- **Docker**
- **LEMP Stack (Linux, Nginx, MariaDB, PHP)**
- **Jump Box**
- **Network Security Groups (NSGs)**
- **Azure Load Balancer**
- **Damn Vulnerable Web Application (DVWA)**

For a detailed project report, please refer to the [Project Report](docs/Project_Report.md).

## **Architecture Diagram**

![Network Architecture Diagram](images/Network_Diagram.png)

*The diagram illustrates the Azure Virtual Network, subnets, Jump Box, web servers, load balancer, and their interconnections.*
