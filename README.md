# 🚀 Deploying a Web Server on AWS EC2  

[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)  
[![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)](https://httpd.apache.org)  

A simple web server hosted on AWS EC2 using Apache.  

## 🌟 Features  
- **EC2 Instance**: t2.micro (Free Tier).  
- **Apache Web Server**: Hosting a static HTML page.  
- **Security**: Restricted SSH access to your IP.  

## 📸 Screenshots  
### 1. EC2 Instance in AWS Console  
![EC2 Instance](./screenshots/ec2-instance.png)  

### 2. Apache Service Status  
![Apache Status](assets/Apache_Service_Status.png)  

### 3. Website Demo  
![Website](./screenshots/website-demo.png)  

## 🛠️ Technologies Used  
- **AWS EC2**: Virtual server hosting.  
- **Apache**: Web server software.  
- **SSH**: Secure remote access.  

## 🚀 How to Run  
1. **Launch an EC2 Instance**:  
   - AMI: Amazon Linux 2, Instance Type: t2.micro.  
   - Security Group: Allow SSH (Port 22) and HTTP (Port 80).  
2. **Connect via SSH**:  
   ```bash  
   ssh -i "your-key.pem" ec2-user@<public-ip>  
