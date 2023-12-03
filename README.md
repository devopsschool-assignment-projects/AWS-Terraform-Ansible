# DevOps Assignment
Note: Try to implement as much functionalities as possible and provide
proper description wherever applicable
## 1. Write a Terraform script to create below AWS components
1. VPC with two public and private subnets
2. Route tables for each subnet
3. Security Group to allow port 80 and 443
4. ELB and ALB
5. Private route53 hosted zone and CNAME entry for both ALB and ELB
6. IAM Policy for assignment-3
## 2. Ansible playbook to do following task
1. Pick a Linux AMI
2. Install webserver (Apache/Nginx)
3. Download code from git
4. Configure webserver with security best practices (List them)
5. Create a self-signed certificate
6. Secure a demo site using self-signed certificate
## 3. Execute Ansible playbook
1. Run Ansible playbook in a packer job and create AMI
2. Automatically create ASG using AMI created in above step and
attach it to ELB.
3. Showcase capability of ALB, by created two different domain route
policy.
4. Instance launched behind ELB/ALB should have role attached
having access to s3 specific bucket, pull images from S3.
## 4. Create a script using any preferred programming language (python,
Node.js, java etc.) to perform following activities
1. List AWS services being used region wise
2. List each service in detail, like EC2, RDS etc.
