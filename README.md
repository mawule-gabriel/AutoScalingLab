# Apache Web Server Auto-Scaling with AWS CloudFormation

This project demonstrates the use of AWS CloudFormation to deploy an Apache web server with auto-scaling based on CPU utilization. The setup includes an Auto Scaling Group (ASG), an Application Load Balancer (ALB), and a web page that displays the instance’s IP address and ID.

## Features
- **Auto-Scaling:** Automatically adds new instances when CPU usage exceeds 50%.
- 
- **Web Server:** Apache web server running on EC2 instances.
- 
- **Load Balancer:** ALB distributes traffic across instances.
- 
- **Instance Info:** Displays instance's IP address and ID on the web page.

## Architecture
- **Private Subnet:** Hosts the EC2 instances for the web server.
- 
- **Public Subnet:** Hosts the ALB for load balancing.
- 
- **Scaling:** The ASG dynamically adjusts the number of instances based on CPU load.


