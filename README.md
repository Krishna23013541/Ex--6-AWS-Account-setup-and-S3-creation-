# CLOUD STORAGE CREATION (S3) AND LAUNCHING AN (EC2) INSTANCE IN AWS (AWS EC2 Web Server Lab)

### Register Number : 212223230107
### Name : KRISHNA KUMAR R
## Aim

To understand the basic operations of Amazon Elastic Compute Cloud (EC2) by launching, configuring, monitoring, resizing, and managing an EC2 instance that hosts a simple Apache web server.

---

## Problem Statement

Cloud applications require scalable and reliable computing resources. The objective of this experiment is to learn how to deploy a virtual server on Amazon EC2, configure networking and security settings, host a web application using Apache HTTP Server, monitor the instance, modify its resources, and explore EC2 protection mechanisms and service limits.

---

## Algorithm / Procedure

1. Log in to the AWS Management Console.
2. Navigate to the EC2 Dashboard.
3. Launch a new EC2 instance using the Amazon Linux 2023 AMI.
4. Select the `t2.micro` instance type.
5. Configure the required VPC and subnet.
6. Create a Security Group.
7. Enable termination protection.
8. Add the User Data script to automatically install and start the Apache web server.
9. Launch the EC2 instance.
10. Wait until the instance status changes to **Running**.
11. Monitor the instance using the **Status Checks** and **CloudWatch Monitoring** tabs.
12. Edit the Security Group to allow inbound HTTP (Port 80) traffic.
13. Access the web server using the public IPv4 address.
14. Stop the instance and change the instance type to **t2.small**.
15. Increase the EBS volume size from **8 GB** to **10 GB**.
16. Enable and test Stop Protection.
17. Explore EC2 Service Quotas.
18. Disable Stop Protection and stop the instance successfully.

---

## Outputs


### EC2 Instance Launch

<img width="1920" height="1080" alt="Screenshot 2026-08-17 193056" src="https://github.com/user-attachments/assets/5774005d-9e75-4092-a0bf-a9ff745c512c" />

---

### Web Server Instance Details

<img width="1920" height="1080" alt="Screenshot 2026-08-17 193421" src="https://github.com/user-attachments/assets/99c71606-d069-40b4-8b5a-82f447c7c755" />

---

### Security Group Configuration

<img width="1920" height="1080" alt="Screenshot 2026-08-04 094210" src="https://github.com/user-attachments/assets/109707ef-992f-4885-9434-ba7f56cc086a" />


---

### EC2 Monitoring

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a998b6b4-e242-4ed2-ae61-51161230258b" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8a41039e-a706-4137-9f84-0c9fe70f0ab0" />

---

### EC2 System Log
<img width="1920" height="1080" alt="Screenshot 2026-08-17 195339" src="https://github.com/user-attachments/assets/06a78acf-5a43-4f8a-b5b2-fc0d2fd2b0e6" />

---

### EC2 Monitoring Diagnosis

<img width="1920" height="1080" alt="Screenshot 2026-08-17 195829" src="https://github.com/user-attachments/assets/0a71b830-9d3f-4613-bb20-6e0f4972e8d5" />

---

### Apache Web Server Output

<img width="1920" height="1080" alt="Screenshot 2026-08-17 194617" src="https://github.com/user-attachments/assets/8d8a49cd-cf97-4810-8284-441c8591cef0" />

---

### EBS Volume Modification

<img width="1920" height="1080" alt="Screenshot 2026-08-17 200310" src="https://github.com/user-attachments/assets/9ea4412b-79cf-4b14-b083-98ded0e4c679" />


---

### EC2 Instance Successfully Stopped
<img width="1920" height="1080" alt="Screenshot 2026-08-17 200051" src="https://github.com/user-attachments/assets/e36d4af2-8296-4098-b10f-558e88c112f1" />

---

### Grades:
<img width="1700" height="866" alt="image" src="https://github.com/user-attachments/assets/92d3718b-5cce-4844-a02c-7f4b68261589" />

## Result

Successfully launched and managed an Amazon EC2 instance, configured security settings, deployed an Apache web server using User Data, monitored the instance, resized the instance and storage volume, tested instance protection features, and explored Amazon EC2 service quotas.
