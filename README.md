# 📡 Task 1 - Basic Network Sniffer

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Scapy](https://img.shields.io/badge/Library-Scapy-orange?style=for-the-badge)
![Network](https://img.shields.io/badge/Domain-Network%20Security-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**Capture. Analyze. Understand.**

*A Python-based tool to intercept and dissect live network traffic*

</div>

---

## 🎯 Objective

Build a Python program that captures live network packets, analyzes their structure, and displays meaningful information such as source/destination IPs, protocols, and payload data — all to understand how data flows across a network.

---

## 🧠 What I Learned

- How network packets are structured at different OSI layers
- The role of protocols like TCP, UDP, ICMP, HTTP, DNS
- How tools like Wireshark work under the hood
- Ethical and legal considerations of packet sniffing
- Real-world network traffic patterns

---

## ⚙️ Features

| Feature | Description |
|--------|-------------|
| 📥 Live Packet Capture | Captures real-time packets from the network interface |
| 🔍 Protocol Detection | Identifies TCP, UDP, ICMP, ARP, DNS, HTTP, and more |
| 🌐 IP Analysis | Displays source and destination IP addresses |
| 📦 Payload Inspection | Shows packet payload data where applicable |
| 🗂️ Packet Filtering | Filter packets by protocol or IP address |
| 💾 Log Export | Save captured data to a file for later analysis |

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.x
- **Libraries:** `scapy`, `socket`, `struct`
- **Platform:** Linux / Windows (run as Administrator/root)

---

## 📦 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/CodeAlpha_CyberSecurity.git
cd CodeAlpha_CyberSecurity/Task1_NetworkSniffer

# Install dependencies
pip install scapy

# Run the sniffer (requires root/admin privileges)
sudo python3 network_sniffer.py
```

---

## 📸 Sample Output

```
============================================================
        🔍 CodeAlpha Network Sniffer — Live Capture
============================================================
[*] Starting packet capture... Press Ctrl+C to stop

[+] Packet #1
    ├── Protocol  : TCP
    ├── Source IP : 192.168.1.5 : 54321
    ├── Dest IP   : 142.250.190.14 : 443
    └── Payload   : <encrypted HTTPS data>

[+] Packet #2
    ├── Protocol  : DNS
    ├── Source IP : 192.168.1.5
    ├── Dest IP   : 8.8.8.8
    └── Query     : www.google.com
============================================================
```

---

## ⚠️ Ethical Disclaimer

> This tool is built **strictly for educational purposes**. Only use it on networks you own or have explicit permission to monitor. Unauthorized packet sniffing is illegal and unethical.

---

## 📚 References

- [Scapy Documentation](https://scapy.readthedocs.io/)
- [Python Socket Library](https://docs.python.org/3/library/socket.html)
- [OSI Model — Cloudflare](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)

---

<div align="center">

📌 Part of [CodeAlpha Cybersecurity Internship](../README.md) | Task 1 of 3

</div>
