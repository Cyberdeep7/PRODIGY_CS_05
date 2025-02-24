# PRODIGY_CS_05

# Network Packet Analyzer

## Overview
The **Network Packet Analyzer** is a powerful tool designed to capture and analyze network packets in real-time. It extracts crucial information such as source and destination IP addresses, protocols, and payload data. This tool is intended for **educational and ethical** use only.

## Features
- Capture live network traffic
- Display source and destination IP addresses
- Identify protocols (TCP, UDP, ICMP, etc.)
- Analyze packet payload data
- Save captured packets for further analysis

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/network-packet-analyzer.git
   ```
2. Navigate to the project directory:
   ```sh
   cd network-packet-analyzer
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. **(Linux Users Only)** Run with root privileges:
   ```sh
   sudo python packet_analyzer.py
   ```

## Usage
Run the packet analyzer script:
```sh
python packet_analyzer.py
```

## Technologies Used
- Python
- Scapy (for packet capturing and analysis)
- Wireshark (optional, for additional analysis)

## Ethical Considerations
- **Do not** use this tool for malicious activities.
- **Only** capture packets on networks you own or have explicit permission to monitor.
- Ensure compliance with local cybersecurity laws and regulations.

## Future Enhancements
- Add real-time graphical visualization
- Implement filtering based on IP, protocol, or port
- Develop a GUI for user-friendly interaction
