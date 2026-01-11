# 3-Tier AWS Deployment 

## Overview
This project demonstrates a **3-Tier Architecture** deployed on **AWS**, designed for scalability, security, and automation.  
It includes:
- **Presentation Layer** → Web servers with nginx + External Load Balancer  
- **Application Layer** → Node.js App servers + Internal Load Balancer  
- **Data Layer** → Amazon RDS (MySQL)  

The deployment uses **VPC, Security Groups, Auto Scaling Groups, ACM (HTTPS), and Route53** for DNS.

---

##  Architecture Diagram
