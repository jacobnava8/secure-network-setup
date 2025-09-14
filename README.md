# 🔒 Secure Network Setup

## 📌 Overview  
This project was conducted as part of a cybersecurity lab where I acted as an **IT subject matter expert** to design and implement a secure network.  
The goal was to **upgrade IT systems with Virtual Machines**, configure firewall rules, establish baseline security, and verify protections using penetration testing tools.  

---

## 📂 Project Structure
📂 secure-network-setup

├── configs/ # VM configs, firewall rules, OS settings

├── docs/ # Network diagrams, screenshots, Wireshark captures

└── README.md

markdown
Copy code

---

## 🛠️ Tasks Performed
- Installed **VirtualBox** and extensions to host multiple VMs  
- Configured:  
  - Firewall Router  
  - DNS Server  
  - Web Server  
  - CEO PC  
  - Kali Linux Machines (3)  
- Verified network connectivity by accessing `www.seclab.net` from CEO PC  
- Discovered system info (OS version, IP, subnet mask, gateway, DNS) using `ifconfig` and `cat /etc/resolv.conf`  
- Used **FTP** to transfer the *Social-Media-Security-Policy* document from Web Server → CEO PC  
- Created a **new user account** on the Web Server  
- Performed **Nmap port scans** on DNS and Web Servers to establish a security baseline  
- Verified segmentation between **Trusted vs Untrusted Networks**  
- Captured FTP traffic with **Wireshark**, successfully identifying **cleartext username and password**  

---

## 🚀 How to Use
1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and required extensions.  
2. Deploy the VM setup (Firewall, DNS, Web Server, CEO PC, and Kali Linux).  
3. Follow `configs/` for firewall and OS hardening.  
4. Use **Nmap** to run scans on DNS/Web servers.  
5. Reproduce Wireshark FTP capture to analyze cleartext credentials.  

---

## 🛠️ Tech Stack
- **Virtualization**: VirtualBox  
- **Operating Systems**: Linux (Kali, DNS, Web Server), Windows (CEO PC)  
- **Security Tools**: Nmap, Wireshark, FTP, Firewall  
- **Network Services**: DNS, Web, FTP  

---

## 📊 Results
- Successfully implemented a secure, **multi-VM environment** with firewall protection  
- Established a **security baseline** by scanning open ports and documenting configurations  
- Demonstrated risks of **cleartext FTP credentials** using Wireshark  
- Validated segmentation between trusted and untrusted networks  

---

⚠️ **Disclaimer**: This project was conducted in a **lab environment only**. All tools and methods are for educational purposes and should not be used against unauthorized systems.  
