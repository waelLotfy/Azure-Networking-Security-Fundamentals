# Azure Networking & Security Fundamentals — Hands-on Exploration

## Overview
This repository documents hands-on labs focused on Azure networking and security concepts completed as part of the AZ-900T00-A course.  
The work emphasizes secure communication, traffic control, and network isolation using Azure Virtual Networks and Network Security Groups.

---

## Labs Completed
- Create a Virtual Network and deploy virtual machines
- Configure VM-to-VM communication within a VNet
- Secure network traffic using Network Security Groups
- Configure inbound and outbound traffic rules

---

## Core Concepts Explored

### Azure Virtual Networks (VNet)
- Private, isolated networking in Azure
- Enables secure communication between resources
- Supports subnet segmentation and traffic control

### Network Security Groups (NSG)
- Acts as a virtual firewall at the Azure network layer
- Controls inbound and outbound traffic
- Applied at subnet or network interface level

---

### Configure Azure DDoS Protection

#### Overview
Implemented network‑level protection by deploying an Azure DDoS Protection plan and associating it with a virtual network. This lab demonstrates how Azure provides automatic mitigation against large‑scale network attacks targeting public endpoints.

#### Objectives
- Create an Azure DDoS Protection plan  
- Deploy a virtual network  
- Associate the DDoS plan with the VNet to enable enhanced protection  

#### Tasks Performed
- Created an Azure DDoS Protection plan to provide network‑layer defense against volumetric attacks.  
- Deployed a virtual network to serve as the protected network boundary.  
- Associated the DDoS Protection plan with the virtual network to activate enhanced mitigation capabilities.

**Outcome:**  
A virtual network protected by an Azure DDoS Protection plan, enabling automatic detection and mitigation of distributed denial‑of‑service attacks.

---

## Key Learnings
- Azure Virtual Networks provide isolated, private networking for cloud resources.
- Virtual machines communicate using private IP addresses within a VNet.
- Network Security Groups enforce secure-by-default traffic rules.
- Inbound rules explicitly allow access such as RDP connectivity.
- Outbound rules can restrict virtual machines from accessing external networks.
- Network security operates at both the Azure network layer and the operating system layer.

---

## Next Steps
- Explore advanced networking services such as load balancers and VPN gateways.
- Integrate networking concepts with identity and access management.
- Apply security principles to multi-tier architectures.

