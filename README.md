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

<img width="1920" height="1080" alt="Screenshot 2026-08-04 093457" src="https://github.com/user-attachments/assets/ce6c4e2b-2db1-4eac-b9e5-dfdf14f5b7de" />
<img width="1920" height="1080" alt="Screenshot 2026-08-04 093529" src="https://github.com/user-attachments/assets/f55dbfe3-57c7-49ed-9335-52f6f2b1ac8e" />

---

### EC2 System Log
<img width="1920" height="1080" alt="Screenshot 2026-08-04 093634" src="https://github.com/user-attachments/assets/7a6a424a-534a-4f34-afc9-13aed5758ece" />

---

### EC2 Monitoring Diagnosis

<img width="1920" height="1080" alt="Screenshot 2026-08-06 105514" src="https://github.com/user-attachments/assets/4cb2d65a-a43a-4dc3-a9ae-1dfb877fe18d" />

---

### Apache Web Server Output

<img width="1920" height="1080" alt="Screenshot 2026-08-17 194617" src="https://github.com/user-attachments/assets/8d8a49cd-cf97-4810-8284-441c8591cef0" />

---

### EBS Volume Modification

<img width="1920" height="1080" alt="Screenshot 2026-08-06 110812" src="https://github.com/user-attachments/assets/6debd070-b653-4443-a46e-30fcd658f673" />

---

### EC2 Instance Successfully Stopped
<img width="1920" height="1080" alt="Screenshot 2026-08-06 111211" src="https://github.com/user-attachments/assets/7bae6dea-3a5f-434e-8a9c-2273744558ab" />

---
## Result

Successfully launched and managed an Amazon EC2 instance, configured security settings, deployed an Apache web server using User Data, monitored the instance, resized the instance and storage volume, tested instance protection features, and explored Amazon EC2 service quotas.
