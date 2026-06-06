# 🛡️ Advanced Network Packet Sniffer & IDS

Python & Scapy-based network packet sniffer and Intrusion Detection System (IDS) for Linux. Captures live traffic, tracks IPs/protocols, and detects threats. Features a fullscreen cyberpunk/hacker-style Tkinter GUI dashboard with complete session controls (Start/Stop/Restart) and automatic log file saving for deep security analysis.

---

## 🚀 Features
* **Real-time Packet Sniffing:** Captures live network traffic instantly.
* **Intrusion Detection System (IDS):** Flags unauthorized or suspicious IP addresses.
* **Cyberpunk UI Dashboard:** Immersive hacker-style Tkinter fullscreen interface.
* **Full Session Controls:** Easily Start, Stop, Continue, and Restart monitoring.
* **Automated Logging:** Saves captured packet details and threat alerts into `sniff.logs`.

---

## 🛠️ Requirements & Installation

This application requires root privileges to access network interfaces on Linux.

1. System Dependencies
Make sure you have Python 3 and Tkinter installed on your Linux system:

```bash
sudo apt update
sudo apt install python3 python3-tk

2. Python Libraries
Install the required Scapy library for network packet manipulation:

pip install scapy

💻 How to Run
Navigate to your project directory and run the application with sudo (required for network sniffing):
                                                                      
sudo python3 yawa-sec-monitor


⚙️ How it Works
Multi-threading: The packet sniffing engine runs on a background thread to prevent the Tkinter GUI from freezing.
IP Analysis: Every captured packet is inspected for its source IP, destination IP, and protocol type.
Threat Matching: If a source IP matches the built-in blacklist (e.g., 45.33.32.156), an immediate alert is triggered on the dashboard.
                                                                      
                                                                      
                                                                      
