# EC2 Windows Help Desk Lab – AWS Remote Desktop Setup

## 📌 Project Overview

This project demonstrates how to deploy and access a Windows EC2 instance in AWS. It simulates a real-world help desk scenario where a technician provisions a system, enables secure remote access, and connects using Remote Desktop Protocol (RDP).

The lab focuses on hands-on cloud support skills, including instance setup, remote connectivity, and basic troubleshooting.

---

## 📸 Visual Walkthrough

This lab is documented step-by-step using real screenshots from the AWS console and Windows login process to demonstrate the full workflow.

---

## 🛠️ Tools & Technologies

- Amazon Web Services (AWS)
- EC2 (Elastic Compute Cloud)
- Windows Server
- Remote Desktop Protocol (RDP)
- AWS Security Groups

---

## 🚀 Step 1: Launch EC2 Instance

Navigate to:

EC2 → Instances → Launch an instance

![Step 1 - Launch Instance](./images/Step 1.png)

### Configuration:
- Name: HelpDesk
- AMI: Windows Server
- Instance Type: t3.micro
- Storage: 8 GiB

---

## 🔐 Step 2: Configure Access & Connect

After launching the instance:

- Select the instance
- Click **Connect**
- Navigate to the **RDP Client tab**

![Step 2 - RDP Connection](./images/Step 2.png)

Then:

- Download the Remote Desktop file
- Retrieve the Administrator password using your key pair

---

## 💻 Step 3: Login to Windows Server

Open the downloaded `.rdp` file.

Enter the credentials:

![Step 3 - Windows Login](./images/Step 3.png)

- Username: Administrator  
- Password: Retrieved from AWS  

If needed, use:

---

## ✅ Step 4: Successful Connection

Once logged in, you now have access to your Windows EC2 instance.

This system can now be used to simulate real help desk tasks such as:

- User support and troubleshooting
- Remote system access
- Software installation testing
- System configuration practice

---

## 🧪 Troubleshooting

### Unable to Connect via RDP
- Ensure instance is in **Running** state  
- Verify security group allows **port 3389 (RDP)**  
- Confirm your IP is allowed  

### Login Issues
- Use `Administrator` or `.\Administrator`  
- Recheck decrypted password  

---

## 💡 Skills Demonstrated

- AWS EC2 provisioning  
- Windows Server access and navigation  
- Remote Desktop (RDP) connectivity  
- Basic cloud networking and security awareness  
- Technical documentation and workflow explanation  

---

## 📊 Summary

This lab provides hands-on experience with deploying and accessing a Windows EC2 instance in AWS. It reflects real-world help desk responsibilities, including system setup, secure remote access, and user support workflows.
