# AWS-ec2-helpdesk-lab
AWS EC2 Windows Help Desk Lab with RDP setup and documentation
# EC2 Windows Help Desk Lab – AWS Remote Desktop Setup

## Project Overview

This lab demonstrates how to launch and connect to a Windows EC2 instance in AWS. The goal is to simulate a basic help desk environment where a technician provisions a system, connects remotely, and prepares it for troubleshooting or support tasks.

---

## Architecture Diagram

```mermaid
flowchart TD
    A[Local Computer] -->|RDP| B[EC2 Windows Instance]
    B --> C[Security Group]
    C --> D[Port 3389 Open]
    B --> E[VPC]
    B --> F[Storage - 8 GiB]
