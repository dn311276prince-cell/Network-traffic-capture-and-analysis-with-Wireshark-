# Network-traffic-capture-and-analysis-with-Wireshark
## NAME: DILIP KUMAR R
## REG NO:212225230059
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/159fc1d9-5d66-4699-9992-9477532cf4d9" />

Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.
<img width="1919" height="961" alt="image" src="https://github.com/user-attachments/assets/8aeb6021-0b75-460b-a055-e5cc69daec9a" />

Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.
<img width="1919" height="893" alt="image" src="https://github.com/user-attachments/assets/7f0bced8-ad93-448b-b9ac-f8d3e43b5ad3" />

Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.
<img width="1902" height="897" alt="image" src="https://github.com/user-attachments/assets/1c92d3a0-dbb1-4eec-9d4f-2525207dec81" />



## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
