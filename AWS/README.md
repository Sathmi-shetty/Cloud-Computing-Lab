# Cloud Computing Lab - AWS EC2 Web Hosting

## Overview

This project demonstrates hosting a static HTML website on an Amazon EC2 instance using Apache HTTP Server.

The website contains:
- College Vision and Mission
- Department of Computer Science & Engineering Vision and Mission
- CLOUDS CSE Student Association information

## Technologies Used

- Amazon EC2 (Amazon Linux)
- Apache HTTP Server
- HTML5
- Git
- GitHub

## Steps Performed

1. Launched an Amazon EC2 instance.
2. Connected to the EC2 instance using SSH.
3. Installed Apache HTTP Server.
4. Started and enabled Apache service.
5. Created a static HTML webpage.
6. Copied the webpage to Apache web root directory.
7. Accessed the website using EC2 Public IP address.
8. Uploaded the project files to GitHub.

## Commands Used

### Install Apache Server

```bash
sudo yum install httpd -y

##Start Apache Service
sudo systemctl start httpd

##Enable Apache Service
sudo systemctl enable httpd

##Navigate to Website Directory
cd /var/www/html

##Git Commands Used
git add .
git commit -m "AWS EC2 Lab"
git push

##Output
The static website is successfully hosted on an Amazon EC2 instance using Apache HTTP Server and is accessible through the EC2 Public IP address.

##Screenshots
The repository contains:
Frontend website screenshots
EC2 terminal screenshots

## Author
Sathmi Shetty
