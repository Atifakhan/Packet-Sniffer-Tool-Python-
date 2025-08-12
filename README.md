# Packet-Sniffer-Tool-Python-
This tool is intended only for educational use and authorized network testing. Using it on networks without permission may violate laws and regulations.
📡 Packet Sniffer Tool (Python)
This is a simple Python-based Packet Sniffer that captures and analyzes network packets.
It displays key information such as:

Source IP address

Destination IP address

Protocol type

Payload data

The tool is built using scapy, making it lightweight yet powerful for educational and testing purposes.

⚠️ Ethical Disclaimer:
This tool is intended only for educational use and authorized network testing. Using it on networks without permission may violate laws and regulations.

🚀 Features
Captures real-time network packets

Displays source & destination IPs

Identifies protocol type (TCP, UDP, ICMP, etc.)

Shows raw packet payload

Works on Windows and Linux

🛠 Installation
bash
Copy
Edit
pip install scapy
▶️ Usage
Run with administrative privileges:

bash
Copy
Edit
python packet_sniffer.py
📌 Example Output:
yaml
Copy
Edit
Source IP: 192.168.0.5
Destination IP: 142.250.183.206
Protocol: TCP
Payload: b'GET / HTTP/1.1\r\nHost: example.com\r\n\r\n'
