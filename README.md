# AWS EC2 Public Web Server Deployment

## Overview
This project demonstrates deployment of a publicly accessible Linux web server using Amazon EC2 within a Virtual Private Cloud (VPC).

## Architecture
- Region: us-east-2
- Instance Type: t3.micro
- Operating System: Amazon Linux 2023
- Web Server: Apache HTTP Server
- Networking: Default VPC + Public Subnet
- Security: Custom Security Group

## Configuration Steps
1. Launched EC2 instance with Amazon Linux 2023 AMI
2. Assigned key pair for secure SSH access
3. Configured Security Group:
   - Port 80 (HTTP) open to 0.0.0.0/0
   - Port 22 (SSH) open to 0.0.0.0/0
4. Installed and started Apache web server
5. Verified connectivity using Public IPv4 address

## Result
Successfully deployed a web server accessible from the public internet.

## Screenshots

![Web Server Running](Screenshots/04-webpage.png)
