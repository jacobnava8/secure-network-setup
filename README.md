# 🔒 Secure Network Setup

## 📌 Overview
This project was conducted as part of a cybersecurity lab where I acted as an **IT Subject Matter Expert** to design and implement a secure IT network.  
The setup involved deploying multiple Virtual Machines, configuring firewall rules, creating baseline security, and validating protections with penetration testing tools.  

The goal was to **upgrade IT systems** by ensuring proper configuration of firewalls, servers, and user accounts, while documenting security posture through scanning and monitoring.

---

## 📂 Project Structure
📂 secure-network-setup  
├── configs/   # VM configs, firewall rules, OS settings  
├── docs/      # Network diagrams, Wireshark captures, screenshots  
└── README.md  

---

## 🛠️ Tasks Performed
- Installed **VirtualBox** and extensions to host lab VMs.  
- Deployed:  
  - **Router-Firewall**  
  - **Internal DNS Server**  
  - **Internal Web Server**  
  - **CEO PC**  
  - **3 Kali Linux Machines** (attack/analysis hosts)  
- Configured **IP addresses (DHCP)** and verified connectivity (CEO PC browsing `www.seclab.net`).  
- Collected baseline system information (OS, IP, Subnet Mask, Gateway, DNS).  
- Used **FTP** to transfer the *Social-Media-Security-Policy* file from Web Server → CEO PC.  
- Created a **new user account** on the Web Server.  
- Conducted **Nmap scans** from Kali Linux against DNS & Web Servers to identify open ports.  
- Verified **Trusted network protections** from the Untrusted network.  
- Captured **FTP credentials** in transit using **Wireshark** to demonstrate risks of plaintext protocols.  

---

## 🚀 How to Recreate
1. Install **VirtualBox** from [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads).  
2. Deploy VMs using the provided baseline configurations in `configs/`.  
3. Configure network interfaces for:
   - Trusted Network  
   - Untrusted Network  
   - DMZ (for DNS & Web Servers)  
4. Apply firewall rules to restrict traffic between zones.  
5. Use **Nmap** to perform security scans and document results.  
6. Use **Wireshark** to capture FTP traffic and analyze vulnerabilities.  

---

## 🛠️ Tech Stack
- **Virtualization**: VirtualBox  
- **Operating Systems**: Windows Server, Linux (Kali, Ubuntu)  
- **Tools**:  
  - Nmap (port scanning)  
  - Wireshark (traffic capture)  
  - FTP (file transfer test)  

---

## 📊 Results
- Successfully built a **multi-VM secure network** with firewall, DNS, and web server.  
- Verified **baseline system configurations** and connectivity.  
- Identified **plaintext FTP vulnerability** by capturing username/password via Wireshark.  
- Created recommendations for hardening:  
  - Replace FTP with **SFTP/FTPS**  
  - Enforce stricter firewall rules  
  - Apply password policies and user access controls  

---

⚠️ **Disclaimer**: This project was performed in a lab environment only. Tools and exploits should be used exclusively for authorized security testing.
