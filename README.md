# Multi-Service Network Lab – Cisco Packet Tracer Project

This lab demonstrates a complete small-office enterprise configuration using Cisco routers and switches. It includes **static routing**, **ACL**, **NAT**, **DHCP**, **AAA (TACACS+ server)**, and **SSH access** — ideal for CCNA-level practice and real-world simulation.

---

## 📘 Objectives:
- Configure static routing between R1 and R2
- Set up NAT (PAT) on R1 for internet-like access
- Implement DHCP for automatic IP distribution
- Apply ACL to control traffic between subnets
- Configure SSH remote access for router security
- Enable AAA authentication using a TACACS+ server

---

## 🧱 Topology:
- **2 x Routers (2901)**  
- **2 x Layer 2 Switches (2960-24TT)**  
- **4 x PCs + 1 Server (AAA/TACACS+)**

---

## 💻 IP Addressing Summary:
- LAN 1: `192.168.10.0/24`  
- LAN 2: `192.168.20.0/24`  
- WAN Link: `10.1.1.0/24`  
- AAA Server: `192.168.10.50`  
- NAT Outside: `10.1.1.1` (R1)

---

## 🔐 Services Implemented:
- ✅ Static Routing
- ✅ ACL to block `192.168.20.1 → 192.168.10.1`
- ✅ PAT (NAT Overload)
- ✅ DHCP Server on R1
- ✅ AAA with TACACS+ Server
- ✅ SSH login with encrypted credentials

---

## 📂 Files Included:
- `Multi-Service-Network-Lab.pkt` – Packet Tracer file
- `Multi-Service-Network-Lab.png` – Network topology diagram
- `config.txt` – Step-by-step CLI configuration

---

## 📷 Network Diagram:
![Multi-Service Network Topology](Multi-Service-Network-Lab.png)

---

## 🔗 Author
**Noor Anik**  
[LinkedIn Profile](https://www.linkedin.com/in/noor-hossain-anik)  
📧 noorhanik@outlook.com

---

> 🌐 This lab combines multiple CCNA-level topics into one real-world simulation — ideal for technical interviews and home lab practice.

