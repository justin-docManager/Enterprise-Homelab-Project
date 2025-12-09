# 🏢 Enterprise Homelab Portfolio: Windows & Hybrid Cloud Infrastructure

[![Project Status: In Progress](https://img.shields.io/badge/Status-In%20Progress-blue.svg)](https://github.com/justin-docManager/Enterprise-Homelab-Project)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🎯 Executive Summary

This repository documents a comprehensive, three-phase project simulating a **highly available and secure hybrid enterprise environment** based on Windows Server, Active Directory (AD), Group Policy, and Microsoft Azure cloud services.

The goal was to move from foundational setup to advanced security governance and cloud integration, demonstrating end-to-end expertise in modern systems engineering and security operations. All procedures are documented with **Standard Operating Procedures (SOPs)** and validated with **Testing & Validation Reports**.

---

## 🛠️ Core Technology Stack

| Category | Technology / Service | Core Function |
| :--- | :--- | :--- |
| **Identity & Access** | Active Directory Domain Services (AD DS) | DNS, DHCP, AD HA, Kerberos, PKI |
| **Automation** | **PowerShell** | Advanced scripting, reporting, bulk provisioning, security baseline enforcement |
| **Endpoint Security** | Group Policy (GPO), WSUS, LAPS, AppLocker, BitLocker | Centralized control, patch management, privileged access management |
| **Virtualization** | Hyper-V | Virtual Machine and Network Management |
| **Hybrid Cloud** | **Azure AD Connect, Conditional Access** | Single Sign-On (SSO), Multi-Factor Authentication (MFA), Site-to-Site VPN |
| **Storage & File** | DFS Namespaces, FSRM, Shadow Copy | Distributed, secure, and resilient file services |

---

## 🔑 Key Architectural Achievements

The project is structured into 3 Phases, totaling **120 distinct engineering tasks**.

### Phase 1: Infrastructure Mastery (Foundation)
* **High Availability:** Successfully configured **DHCP Failover** and deployed **Redundant Domain Controllers**, verified via `repadmin`.
* **Security Foundation:** Implemented a working **Internal PKI (Certificate Authority)** and hardened remote access with **RDP Policy**.
* **Core Services:** Established resilient **DNS Zones, File Services, and FSRM** (Quotas/File Screening) from scratch.

### Phase 2: Security & Endpoint Control (Governance)
* **Privilege Management:** Implemented **LAPS** (Local Administrator Password Solution) across all endpoints and secured local groups via **GPO Restricted Groups**.
* **Policy Enforcement:** Mastered **Group Policy Preferences (GPP)** for dynamic user environment control and deployed enterprise-grade security using the **MS Security Compliance Toolkit**.
* **Automation:** Developed and deployed robust **PowerShell scripts** for bulk user provisioning, security reporting, and automated baseline remediation.

### Phase 3: Senior Engineering & Architecture (Hybrid & DR)
* **Hybrid Identity:** Implemented and validated **Azure AD Connect**, enabling **PHS, Seamless SSO, and MFA** via **Conditional Access** policies.
* **Cloud Connectivity:** Established a **Site-to-Site VPN** between the on-premises homelab network and the cloud VNet/VPC.
* **Business Continuity:** Created a formal **Disaster Recovery Plan (DRP)** with defined **RTO/RPO** goals and validated cloud-based backup and recovery procedures.

---

## 📂 Repository Navigation

This repository is organized to allow fast navigation to specific technical artifacts.

| Path | Description | Access Link (Example) |
| :--- | :--- | :--- |
| **`Phase-2-Security-Control/01-Scripts/`** | Repository for all PowerShell automation scripts (User Provisioning, Reporting, WSUS Cleanup). | [View Scripts](Phase-2-Security-Control/01-Scripts) |
| **`Phase-1-Infrastructure/02-Diagrams/`** | Network Topology, AD OU Structure, and Hyper-V Virtual Switch configurations. | [View Diagrams](Phase-1-Infrastructure/02-Diagrams) |
| **`Phase-3-Architecture/02-DRP/`** | Formal documentation for Disaster Recovery and Business Continuity Planning. | [View DR Documents](Phase-3-Architecture/02-DRP) |
| **`Final-Portfolio/`** | The compiled **Systems Design Document** (P3.40) summarizing the entire project. | [Download Final SDD](Final-Portfolio) |

---

## ➡️ Next Steps

This project is currently in the **In Progress** stage. The focus is now on finalizing the **Phase 3** implementation and compiling all documentation into the final **Systems Design Document (SDD)**.

**Contact:** [www.linkedin.com/in/justin-stern-2b671a1a0]