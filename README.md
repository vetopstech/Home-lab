# 🧠 Home.Lab Portfolio

Welcome to my **Home Lab Documentation & Portfolio** — a self-built environment for learning, experimenting, and demonstrating practical IT, networking, and, soon, cybersecurity skills.

---

## 🏠 Lab Overview

My lab simulates a small enterprise network to practice Windows Server administration, networking, and security operations.  
It includes domain services, DHCP, DNS, AD, and multiple client systems for cross-platform management and testing.

**Current Setup**
- **Domain:** `home.lab`
- **Server:** Windows Server 2022 (Active Directory / DNS / DHCP)
        **Soon** File / Print / FTP
- **Clients:** Windows 11 (FIN1, OPS1, MGMT1)
        **Soon** Xubuntu (SIEM node), Kali Linux (IDS / forensics)
- **Network:** flat topology via AT&T router   
- **Virtualization:** Oracle VirtualBox on main system  
- **Physical Hosts:**  
  - Main PC (16 GB RAM, 512 GB SSD (All VM's, Server 2022 and one Client at a time)  
  - Kali (Ideapad 4 GB RAM – Linux test machine (Working on the practical use of this for penttesting)  
  - Xubuntu (Chromebook 32 GB SSD, 4 GB RAM - Admin Tools (Still working on this))  

---

## 🔧 Services & Configurations

| Role | Description |
|------|--------------|
| **Active Directory / DNS / DHCP** | Centralized identity management and IP addressing |
| **File & Print Server** | Shared folders, permissions, and group policy printing (Work in Progress)|
| **FTP Server** | Secure file transfer and permission testing (Work in progress)|
| **Email Simulation** | Internal mail relay for lab users (Work in Progress)|
| **Security Monitoring** | Wazuh SIEM dashboard collecting logs from all nodes (Work in Progress)|
| **IDS / Packet Analysis** | Suricata and Zeek sensors on Kali for intrusion detection Work in Progress) |

---

## 💡 Learning Goals

- Strengthen system administration skills in **Windows Server 2022**
- Gain practical experience for **CompTIA Security+**, **Microsoft AZ-900**, and **Cisco CCNA**
- Understand real-world **network segmentation**, **DHCP relay**, and **VLAN** concepts
- Practice **incident detection**, **log correlation**, and **digital forensics workflows**

---

## 🧩 Lab Projects

1. **Active Directory Build** – Created domain `home.lab` with OUs, GPOs, and PowerShell user import scripts.  
2. **DHCP & DNS Integration** – Defined scopes for Finance, Operations, and Admin networks.  
3. **SIEM Implementation** – Forwarded Windows and Linux logs to Wazuh; created custom alerts.  
4. **Kali IDS Deployment** – Configured Suricata and Zeek to monitor network traffic.  
5. **Troubleshooting Journal** – Ongoing record of DNS, DHCP, and connectivity fixes.  

---

## 🔐 Security & Forensics Focus

- Monitor event logs, failed logons, and policy changes.  
- Capture and analyze network traffic.  
- Conduct mock incident response cases using captured data.  
- Maintain chain-of-custody documentation for practice forensic scenarios.

---

## 🧭 Future Enhancements

- Add Layer 3 switch and VLAN segmentation hardware.  
- Integrate **Docker** for lightweight server testing.  
- Deploy **Azure AD Connect** for hybrid identity experimentation.  
- Expand forensic exercises with **FTK Imager**, **Autopsy**, and **Volatility**.
