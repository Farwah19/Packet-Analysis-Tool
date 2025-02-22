# Intelligent Conversation Monitoring and Threat Detection

## ![Project Overview](https://media.giphy.com/media/ZVik7pBtu9dNS/giphy-downsized.gif)
This tool processes **pcap files** to extract key insights from network activity and detect potential cyber threats. It reconstructs **clear-text conversations** between network entities while identifying threats such as **ARP spoofing, DDoS, SQL injection, and port scanning**.

## ⚡ Capabilities
- **📡 Packet Analysis**: Parses and analyzes network traffic with `Tshark` and `Pyshark`.
- **🖥️ User Identification**: Extracts OS, NIC, and geographical data from captured traffic.
- **📜 Readable Communication Logs**: Converts raw packet data into structured interactions.
- **🚨 Threat Detection**: Identifies cyber threats based on network behavior.
- **📊 Automated Reports**: Generates security reports with structured insights.
- **🖱️ Interactive GUI**: Built using Tkinter for visualization and user control.

## 🛠️ Tools & Frameworks
- **🐍 Python** – Core scripting language.
- **📊 Tshark** – Extracts network packet details.
- **🔍 Pyshark** – Python wrapper for `Tshark`.
- **📜 Bash Scripting** – Automates network traffic analysis.
- **🛡️ Wireshark** – Used for validation and debugging.
- **🖥️ Tkinter** – Provides a graphical user interface.

## 🔨 Approach
1. **📥 Data Collection** – Loads and processes `pcap` files.
2. **📌 Packet Examination** – Extracts IPs, protocols, and timestamps.
3. **🔗 Traffic Reconstruction** – Maps interactions between network endpoints.
4. **🚧 Threat Evaluation** – Detects anomalies such as:
   - **💥 DDoS Attacks** – Large volumes of repetitive traffic.
   - **⚠️ ARP Spoofing** – Inconsistent MAC-IP mappings.
   - **🔓 SQL Injection** – Suspicious payloads in HTTP traffic.
   - **📡 Port Scanning** – Unusual port access patterns.
5. **📑 Security Documentation** – Generates readable logs and structured reports.

## ⚠️ Obstacles and Limitations
- **📂 Efficiently handling large pcap files**.
- **🌍 Accurately mapping geolocation data from IPs**.
- **🔐 Limited threat detection for encrypted traffic**.
- **🕵️ Enhancing OS/NIC fingerprinting precision**.

---
This project offers **real-time insights** into network security, enhancing the ability to detect and mitigate cyber threats efficiently! 🔍🛡️

