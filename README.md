# Real-Time-Network-Traffic-Analysis-Using-Wireshark
To understand and detect common network vulnerabilities through deep packet inspection and apply security recommendations for mitigation.
This project demonstrates real-time network traffic analysis using **Wireshark**. It’s a hands-on cybersecurity project designed to simulate the role of a **SOC Analyst** investigating suspicious traffic patterns.

---

##  Objective

To gain practical experience in packet analysis and identify real-world threats such as:
- Unencrypted credentials over HTTP
- Abnormal DNS behavior
- SSH brute-force attempts
- Potential data exfiltration

---

##  Tools Used

- **Wireshark** for traffic capture and filtering
- **Npcap** for packet sniffing
- OS: Windows 11 / Kali Linux (VM)

---

##  Key Wireshark Filters Used

```bash
http contains "password"
dns
tcp.port == 22
ip.dst == [external_IP]
