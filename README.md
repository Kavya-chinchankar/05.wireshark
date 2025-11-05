# 05.wireshark

# 🧩 Task 5 – Wireshark Packet Capture and Protocol Analysis

## 📘 Title
**Wireshark Packet Capture and Protocol Analysis**

---

## 🎯 Objective
To capture live network packets on my laptop using **Wireshark** and identify different network protocols such as **DNS**, **TCP**, **HTTP**, and **ICMP**.  
The goal is to understand how data travels over the network and gain hands-on experience in analyzing packet-level communication.

---

## 🪜 Steps Performed
1. Installed Wireshark from the official website.  
2. Opened Wireshark and selected the active **Wi-Fi network interface**.  
3. Started live capture by clicking the **blue shark-fin icon**.  
4. Generated network traffic by browsing websites and pinging servers (e.g., `ping google.com`).  
5. Stopped the capture after approximately **1 minute**.  
6. Applied display filters such as `http`, `dns`, `tcp`, and `icmp` to analyze specific protocols.  
7. Saved the capture file as **network_capture.pcap**.  
8. Examined packet details to identify source/destination IP addresses and protocols.  
9. Summarized the findings and exported results for documentation.

---

## 🌐 Protocols Identified

### 1. DNS (Domain Name System)
- Used to resolve domain names (e.g., *google.com*) into IP addresses.

### 2. TCP (Transmission Control Protocol)
- Provides reliable data transfer between client and server.

### 3. HTTP (HyperText Transfer Protocol)
- Handles web communication between browser (client) and web server.

### 4. ICMP (Internet Control Message Protocol)
- Used for network diagnostics such as ping requests and replies.

---

## 🔍 Sample Packet Details

| # | Protocol | Source IP | Destination IP | Description |
|---|-----------|------------|----------------|--------------|
| 1 | **DNS** | 192.168.1.4 | 8.8.8.8 | Standard query 0x7bfc A www.google.com |
| 2 | **TCP** | 192.168.1.4 | 142.250.183.78 | 443 → 51532 [SYN, ACK] Seq=1 Ack=1 Win=65535 |
| 3 | **HTTP** | 192.168.1.4 | 142.250.183.78 | GET /index.html HTTP/1.1 |
| 4 | **ICMP** | 192.168.1.4 | 8.8.8.8 | Echo (ping) request |

---

## 🧾 Files Included

| File | Description |
|------|--------------|
| `network_capture.pcap` | Raw network packet capture file |
| `Wireshark_Report.txt` | Detailed analysis of captured traffic |
| `screenshots/` | (Optional) Screenshots showing filters and captured packets |

---

## ⚙️ Tools Used
- **Wireshark** – Network packet capture and analysis tool  
- **Wi-Fi Adapter** – For live traffic capture  
- **Windows 10 Laptop** (Environment used)

---

## 🧠 Conclusion
Wireshark successfully captured and displayed live network traffic.  
Different protocols such as **DNS**, **TCP**, **HTTP**, and **ICMP** were identified and analyzed.  
This task provided a deeper understanding of how data flows between devices and how each protocol contributes to reliable network communication.

---

## 🏁 Outcome
**Skills Gained:**
- Capturing and filtering real-time network packets  
- Identifying and analyzing multiple protocols  
- Understanding packet-level data flow  
- Strengthened troubleshooting and cybersecurity awareness

---

## 🔗 Submission
This repository contains my submission for **Task 5 – Wireshark Packet Capture and Protocol Analysis**  
as part of the **Cyber Security Internship Program**.

---
