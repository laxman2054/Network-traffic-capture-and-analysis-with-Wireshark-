# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1: 
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

![Screenshot 2025-04-26 170033](https://github.com/user-attachments/assets/45dfc37f-c50c-4e44-afbc-25b5558a60d3)

* Start Capturing Packets:
1. Click the blue shark fin icon or double-click the interface.
2. Now the Wireshark will start capturing all the real-time traffic.


<img width="611" alt="image" src="https://github.com/user-attachments/assets/5c32bee0-8e27-4215-8c8f-80ad65f1a42e" />



* Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

<img width="616" alt="image" src="https://github.com/user-attachments/assets/4e9f201b-790b-423d-a053-7380f66e83a9" />


* Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.

<img width="617" alt="image" src="https://github.com/user-attachments/assets/1daab503-93fd-436d-ad94-d8ef7efe4c06" />











## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
