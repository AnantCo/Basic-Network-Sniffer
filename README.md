asic Network Sniffer 🚀

Overview

The Basic Network Sniffer is a Python-based tool that captures and analyzes network traffic using the Scapy library. This project helps in understanding how data flows across a network and how packets are structured.

Features

✅ Captures live network packets.
✅ Displays Source IP, Destination IP, and Protocol.
✅ Uses Scapy for packet sniffing at Layer 3 (IP level).
✅ Works on both Windows & Linux.

Installation & Setup

Prerequisites

Python 3.x: Download Here

Scapy: Install it using pip:

pip install scapy

Npcap (Windows Only): Download Here

Ensure you check the "WinPcap API-compatible mode" during installation.

How to Run

Open a terminal or command prompt.

Navigate to the project directory:

cd path/to/project

Run the script:

python sniffer.py

Usage

Run the script as an administrator.

The program captures incoming and outgoing network packets.

Output Example:

Source: 192.168.1.5 -> Destination: 8.8.8.8 | Protocol: ICMP
Source: 10.0.0.2 -> Destination: 192.168.1.1 | Protocol: TCP

Security & Privacy Warning ⚠️

Do NOT share real IP addresses publicly!

If posting a demo video, blur or mask the IP addresses for security.

License 📜

This project is MIT Licensed.

🔗 Follow me on LinkedIn for more projects! [Your LinkedIn Profile]

