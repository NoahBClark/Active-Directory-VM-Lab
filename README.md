# 🔧 Active Directory Home Lab

## 📌 Overview
This project simulates a real-world enterprise Active Directory environment using Windows Server and virtual machines.

The purpose of this lab is to:
- Deploy a Domain Controller
- Manage users and groups
- Apply Group Policy Objects (GPOs)

---

## 🎯 Objectives
- Install and configure Active Directory Domain Services
- Join a client machine to the domain
- Create and manage users and groups
- Implement Group Policy

---

## 🛠️ Tools & Technologies
- Windows Server 2022
- Windows 10 VM
- VirtualBox
- Active Directory Domain Services
- PowerShell

---

## 🗺️ Lab Architecture
- **Domain:** homelab.local
- **Server IP:** 192.168.1.10
- **Client IP:** 192.168.1.20
- **Network Type:** Internal Network

---

## ⚙️ Implementation

### 1. Install Windows Server
- Created VM with 4GB RAM
- Installed Windows Server 2022

### 2. Configure Domain Controller
- Installed AD DS role
- Promoted server to Domain Controller
- Created domain: homelab.local

### 3. Join Client Machine
- Connected Windows 10 VM to domain
- Verified domain login functionality

---

## 📸 Screenshots

### Active Directory Users & Computers
![ADUC Screenshot](images/aduc.png)

### Group Policy Management
![GPO Screenshot](images/gpo.png)

---

## 🔐 Skills Demonstrated
- Active Directory Administration
- Group Policy Configuration
- Network Configuration
- Troubleshooting Domain Issues

---

## 🚀 Lessons Learned / Improvements
- DNS configuration is critical for domain functionality
- Troubleshooting domain join errors requires careful network setup

---

## 📚 References
- Microsoft Learn Documentation
- YouTube Lab Tutorial

---

## 👤 Author
**Noah B Clark**  
Airman First Class (A1C), U.S. Air Force National Guard 
