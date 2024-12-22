# **Hosting a Web Page with Apache on a Linux Server**

## **Overview**
This project demonstrates how to provision a cloud server, install the Apache web server, deploy an HTML page, and configure networking to make the page publicly accessible.

---

## **Steps to Complete the Project**

### **Step 1: Provisioning the Server**
1. Log in to your cloud provider (e.g., AWS, ).
2. Launch a new virtual machine (VM) instance:
   - Choose an operating system (Ubuntu 20.04 LTS is recommended).
   - Select an appropriate instance type (e.g., `t2.micro` for AWS free-tier).
3. Configure key pair authentication:
   - Download the `.pem` file to your local system for SSH access.
4. Assign a public IP to the instance.
5. Launch the instance.

---

### **Step 2: Connecting to the Server**
1. Open your terminal or SSH client (e.g., vscode).
2. Connect to your server using the `.pem` file:
   ```bash
   ssh -i "exam_key.pem" ubuntu@ec2-13-48-190-58.eu-north-1.compute.amazonaws.com
