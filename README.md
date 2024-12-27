# Library Inventory System

The Library Inventory System is an advanced web-based application built to efficiently manage library books, including functionalities for adding, updating, borrowing, and returning books. The system utilizes containerization with Docker, deployment on Kubernetes, and monitoring with Prometheus and Grafana. Infrastructure is provisioned using Terraform, while a CI/CD pipeline is orchestrated with Jenkins.

---

## Table of Contents

1. [Getting Started](#getting-started)  
2. [Prerequisites](#prerequisites)  
3. [Installation](#installation)  
4. [Usage](#usage)  
   - [Running Locally](#running-locally)  
   - [Docker Deployment](#docker-deployment)  
   - [Kubernetes Deployment](#kubernetes-deployment)  
   - [Terraform Infrastructure](#terraform-infrastructure)  
   - [CI/CD with Jenkins](#ci-cd-with-jenkins)  
5. [Monitoring and Alerts](#monitoring-and-alerts)  
   - [Prometheus Setup](#prometheus-setup)  
   - [Creating Alerts](#creating-alerts)  
6. [Project Checklist](#project-checklist)  

---

## Getting Started

### Prerequisites

Ensure the following tools are installed before starting:  

- **Python 3.10+**: Required for running the Flask backend.  
- **Docker**: For containerizing the application.  
- **Kubernetes**: To manage and scale containerized applications.  
- **Terraform**: For provisioning AWS infrastructure (e.g., EKS).  
- **AWS CLI**: To interact with AWS resources via the command line.  
- **Jenkins**: For automating CI/CD processes.  
  

---

## Installation

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/Malak-emam/library-inventory.git
   cd library-inventory

# Library Inventory System Instructions

## Install Dependencies

```bash
pip install -r requirements.txt

