# Scalable-and-Fault-Tolerant-3-Tier-Architecture-on-AWS
 Three-Tier Architecture on AWS with Auto Scaling, Aurora MySQL RDS, Enhanced Security and CloudWatch Monitoring
![125eccbe-4b35-41e8-aa86-4a88a1efba02](https://github.com/user-attachments/assets/e6a67558-7723-46b0-9258-2abfe8ff719e)

Project Overview:
Designed and implemented a highly scalable, fault-tolerant, and secure three-tier architecture on AWS to handle dynamic traffic and ensure high availability. The system utilizes Auto Scaling, Amazon Aurora MySQL with multi-AZ configurations, CloudWatch for monitoring, & robust security features.

Architecture Components:
 • Web Layer: Deployed an Application Load Balancer (ALB) across multiple AZs for fault tolerance and seamless traffic distribution, improving scalability and availability.
 • Application Layer: Used Auto Scaling Group (ASG) to dynamically scale EC2 instances based on demand, optimising performance and cost. Nginx was deployed for later testing by SSH from Bastion.
 • Database Layer: Deployed Amazon Aurora- MySQL combination, in a multi-AZ setup for high availability and failover, with a primary instance and read replica for redundancy and scalability.
 • Security: Applied Security Groups and Network ACLs (NACLs) to enforce traffic rules, ensuring secure access and isolating subnets by function (public for web and private for application and database layers).
 • Monitoring & Insights: Integrated CloudWatch for real-time monitoring, tracking CPU, memory, disk I/O, and database performance. Configured CloudWatch Alarms for proactive management.

Key Features:
 • Scalability & High Availability: Multi-AZ ensures uptime and failover.
 • Cost Optimization: Auto Scaling adjusts EC2 instances based on traffic.
 • Security: Robust security with isolated subnets, NACLs, and Security Group Firewalls.
 • Monitoring: CloudWatch provides continuous performance tracking and alerts.

Outcome:
 • Successfully delivered a secure, scalable, and fault-tolerant AWS architecture capable of handling variable user loads and delivering a seamless user experience with minimal downtime.
 • Ensured reliable and efficient request processing, improved application security, and achieved better operational visibility through CloudWatch monitoring.

