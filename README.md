# AWS DevOps Engineer Intern Assignment

## Objective
Deploy a simple website on AWS EC2 using Nginx.

## AWS Services Used
- Amazon EC2
- Security Groups

## Linux Commands Used
```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps -ef
```

## Website Deployment Steps
1. Launch Ubuntu EC2 instance.
2. Allow ports 22 and 80.
3. Connect using SSH.
4. Install Nginx.
5. Create index.html.
6. Copy file to /var/www/html/.
7. Restart Nginx.
8. Access website via Public IP.

## Learnings
- AWS EC2 basics
- Linux commands
- Nginx installation
- Website hosting on EC2
- Git and GitHub

## Problems Faced
- SSH permission issue (if any)
- Nginx installation issue (if any)

## Author
Firdose Shaikh
