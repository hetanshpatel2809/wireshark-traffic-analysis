# Network Traffic Capture and Analysis Using Wireshark

## About the Project

This project focuses on capturing and analyzing live network traffic using Wireshark. It demonstrates how to identify common network protocols, examine packet details, and understand different types of network communication.

## Objectives

- Capture live network packets.
- Identify common network protocols.
- Analyze DNS requests and responses.
- Examine TCP and UDP communication.
- Identify ICMP and ARP packets.
- Understand encrypted network traffic.
- Save packet captures for further analysis.

## Tools and Technologies

- Wireshark
- Network Packet Analyzer
- PCAP / PCAPNG

## Project Structure

```text
Task-5-Wireshark-Traffic-Analysis/
│
├── README.md
│
├── network_traffic.pcap
│
└── report/
    └── network_traffic_analysis_report.txt
```

## Protocols Identified

| Protocol | Description |
|---|---|
| DNS | Translates domain names into IP addresses |
| TCP | Provides reliable, connection-oriented communication |
| UDP | Provides connectionless data transmission |
| TLS | Provides encrypted communication |
| ICMP | Used for network diagnostics and ping |
| ARP | Resolves IPv4 addresses into MAC addresses |

## Capture Summary

- Total packets analyzed: 1,822
- Capture duration: Approximately 43 seconds
- Capture interface: eth0
- Local IP observed: 10.0.2.5
- DNS resolver observed: 192.168.0.1

## Wireshark Display Filters

The following filters were used to identify network protocols:

```text
dns
tcp
udp
tls
icmp
arp
```

## Key Findings

- DNS queries and responses were identified.
- TCP and UDP traffic using port 443 was observed.
- TLS-related encrypted communication was identified.
- ICMP Echo Requests and Replies were observed.
- ARP traffic was detected.

## Results

Successfully captured and analyzed 1,822 network packets.

Multiple network protocols were identified, demonstrating how Wireshark can be used for basic network monitoring and traffic analysis.

For detailed findings, refer to:

`report/network_traffic_analysis_report.txt`

The packet capture is available in:

`network_traffic.pcap`

## Disclaimer

This project is intended for educational and cybersecurity learning purposes. Network traffic should only be captured and analyzed with proper authorization.

## Author

**Hetansh Patel**

Cyber Security Student | Cybersecurity Intern
