# Network-Traffic-Analyst-Threat-Detection-Threat-
# Objective:
TO analyse captured netwrok traffic (PCAP) and identify indicatore of compromise (IoCs) reltaed to common attack techniques, including:
- Failed login attempts (brute force indeicators)
- Port scanning activity
- Suspicious DNS behaviour
- ICMP anomalies
- Suspicious or malicious HTTP traffic

THis Lab demonstrates practical skills in network security monitoring, threat detiction, and incident documentation.

# Toola used:
- OPNsense Firewall (WAN Router)
- Kali Linux (Attacker simulation)
- Ubuntu linux (Traffic capture & analysis)
- Windows 10 (Victim machine)
- Wireshark
- TCP/IP protocol analysis
- PCAP Files
- Manual threat-hunting techniques

# Virtual Lab Environment:

 This lab was conducted in an isolated virtual environment consisting of three virtual machines and OPNSense Firewall:
 
- OPNSense firewall router only,

- Kali Linux (Attacker VM): Used to simulate adversary behaviour such as scanning, brute-force attempts, and malicious traffic generation.

- Ubuntu Linux (Monitoring/SOC VM): Acted as the network sensor, capturing traffic using Wireshark for analysis.

- Windows Machine (Victim VM): Represented an enterprise endpoint targeted by simulated attacks.

This architecture mirrors a real-world SOC monitoring scenario where analyst systems observe traffic between attackers and endpoints.

# Key Skills Demonstrated

Network traffic analysis

Attack pattern recognition

Wireshark filtering

Incident reporting

Defensive security mindset
