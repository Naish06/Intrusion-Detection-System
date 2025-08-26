# Intrusion-Detection-System
A lightweight Intrusion Detection System built in Python using Scapy. This mini-project monitors live network traffic and raises alerts for suspicious activities based on simple threshold rules.

**Features** <br>

- Blacklisted IP Detection – flags traffic from known malicious IPs
- Port Scan Detection – detects if a source IP connects to many ports in a short time
- High Request Rate Detection – identifies potential DoS/brute-force attempts by tracking packet rates
- Real-time Monitoring – uses Scapy to sniff and analyze packets on the fly

**Tech Stack** <br>
- Python 3
- Scapy (packet sniffing & analysis)
- Collections / defaultdict (connection tracking)

**Usage** <br>
`pip install scapy pandas`
`python ids.py`

<br><br>
The IDS will start sniffing packets and print alerts in the terminal when suspicious activity is detected.
