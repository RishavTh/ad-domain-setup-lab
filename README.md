#  Active Directory Lab

This project simulates a real-world enterprise Active Directory (AD) domain environment designed with a Blue Team focus. It showcases identity and access management, group policy enforcement, basic network communication, and event monitoring — all within a virtualized lab built using Oracle VirtualBox.

## 📌 Project Overview

This lab demonstrates the setup of:
- An **Active Directory Domain Services (AD DS)** infrastructure
- A domain-joined Windows 10 client (crop.local)
- **Group Policy Objects (GPOs)** for centralized control (e.g., wallpaper enforcement)
- Basic **Blue Team monitoring** using **Sysmon** and **Windows Event Forwarding (WEF)**

> 🔐 Goal: Build foundational skills in Blue Team operations through domain hardening, monitoring, and secure configuration.

---

## 💻 Lab Architecture

- **Virtualization Platform**: Oracle VirtualBox
- **Server OS**: Windows Server 2022 (DC01)
- **Client OS**: Windows 10 Pro
- **Domain Name**: `crop.local`
- **Network Mode**: Bridged Adapter

---

## 🧰 Tools & Technologies

| Tool/Service                | Purpose                                |
|----------------------------|----------------------------------------|
| Active Directory (AD DS)   | Centralized user & access management   |
| DNS & DHCP                 | Name resolution & IP assignment        |
| Group Policy (GPO)         | Security & configuration enforcement   |
| Sysmon                     | Deep system-level monitoring           |
| Windows Event Forwarding   | Centralized log collection             |
| ICMP, `ipconfig`, `ping`   | Network communication testing          |

---

## ✅ Key Features

- ✔️ Server assigned static IP and DNS setup
- ✔️ Client configured for DHCP & domain join
- ✔️ Creation of Organizational Unit `Client` and domain user `harirai`
- ✔️ Group Policy to enforce desktop wallpaper
- ✔️ Sysmon installed for behavior visibility
- ✔️ Event Forwarding configured (WEF setup)
- ✔️ ICMP enabled for client-server pinging

---

## 📂 Repository Contents

