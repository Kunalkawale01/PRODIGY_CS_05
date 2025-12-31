# PRODIGY_CS_05
Develop a packet sniffer tool that captures and analyzes network packets. Display relevant information such as source and destination IP addresses, protocols, and payload data. Ensure the ethical use of the tool for educational purposes.

# Network Packet Analyzer

## Project Overview
The **Network Packet Analyzer** is an educational cybersecurity tool built using Python and Scapy.  
It captures live network packets and analyzes key information such as source IP, destination IP, protocol type, and payload data.

This project is developed **strictly for educational and ethical purposes**.

---

## Ethical & Legal Disclaimer
This tool must be used **ONLY**:
- On networks you own
- On networks where you have **explicit permission**

Unauthorized packet sniffing is illegal and unethical.  
The developer is **not responsible for misuse** of this software.

---

## Features
- Live network packet capture
- Displays:
  - Source IP address
  - Destination IP address
  - Protocol (TCP / UDP)
- Logs packet details with timestamps
- Saves output to a log file
- Command-line based (transparent usage)

---

## BEFORE RUNNING COMMANDS (ONE-TIME)

✔ Install Npcap
✔ During install, check “WinPcap Compatible Mode”
✔ Restart PC
✔ Open CMD as Administrator

## Go to Project Directory
    cd C:\Users\ainsh\Downloads\network_packet_analyzer_project

## Activate Virtual Environment
    python -m venv venv
    venv\Scripts\activate

## Upgrade pip (Optional but Recommended)
     python -m pip install --upgrade pip

## Install Requirements
    pip install -r requirements.txt

## Run the Packet Analyzer
     python main.py
