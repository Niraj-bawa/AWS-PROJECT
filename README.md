# AWS-PROJECT
3-Tier E-Commerce Infrastructure on AWS – “Shop Now”
Built a secure and scalable AWS cloud infrastructure for a simulated e-commerce application.
Designed highly available architecture using Elastic Load Balancer and Auto Scaling Groups.
Configured networking components including VPC, public/private subnets, and route tables.
Managed Linux-based EC2 instances for application hosting and administration.
Implemented secure access management using IAM roles and security groups.
Utilized S3 for object storage and backup management.


Services Covered

 

VPC

EC2

Security Groups

Application Load Balancer

S3

RDS

IAM

Auto Scaling


Networking
•⁠  ⁠Create custom VPC
•⁠  ⁠2 Availability Zones
•⁠  ⁠Public subnet → Load Balancer
•⁠  ⁠Private subnet → Application servers
•⁠  ⁠Private DB subnet → RDS

Compute
•⁠  ⁠Deploy web server on EC2
•⁠  ⁠No public IP on application instances

 Storage
•⁠  ⁠Store product images in S3

 Database
•⁠  ⁠MySQL RDS instance
•⁠  ⁠Accessible only from application servers

 Traffic
•⁠  ⁠Internet → ALB → EC2 → RDS

 
<img width="714" height="936" alt="image" src="https://github.com/user-attachments/assets/4985d9d2-4081-4f42-8956-55f23f524405" />
