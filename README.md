# Task 1 — AWS Cloud Setup

## Objective
Gain hands-on experience with AWS EC2 by launching and configuring a virtual machine instance, configuring security groups, connecting via SSH, and deploying a basic web service on the cloud.

## Configuration
- **AWS Service:** Amazon EC2
- **Instance Name:** Week2-Task1-EC2
- **Operating System:** Amazon Linux 2023
- **Instance Type:** t3.micro
- **Key Pair:** week2-task1-key
- **Security Group:** week2-task1-sg
- **SSH:** TCP 22 from My IP
- **HTTP:** TCP 80 from Anywhere (0.0.0.0/0)
- **Web Server:** Nginx
- **AMI:** week2-task1-ami

## Work Completed
1. Launched an EC2 instance.
2. Created and selected a dedicated key pair.
3. Configured the security group for SSH and HTTP.
4. Connected to the EC2 instance using SSH.
5. Installed Nginx.
6. Started and enabled the Nginx service.
7. Verified the Nginx page through the EC2 public IP.
8. Created an AMI from the configured instance.

## Evidence
The `Screenshots` folder contains the supporting screenshots in the correct sequence.

The main documentation is:
`Task_1_AWS_Cloud_Setup.pdf`

## Important
Do not upload or share the `.pem` private key file.
