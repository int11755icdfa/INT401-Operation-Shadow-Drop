# INT401 – Network Security Operations

# Operation Shadow Drop

## ICDFA Phase 2 – Ethical Hacking Specialization

This repository contains my submission for the INT401 Network Security Operations assignment titled Operation Shadow Drop, completed as part of the International Cybersecurity & Digital Forensics Academy (ICDFA) Phase 2 Ethical Hacking Specialization.

The project simulates a real-world Security Operations Center (SOC) investigation involving the forensic analysis of a network packet capture (PCAP) file. The objective was to identify the attacker's activities, determine how a malicious PHP web shell was uploaded, reconstruct the attack timeline, and document the incident using professional SOC reporting standards.


## Investigation Objectives

The investigation aimed to:

- Identify the geographical origin of the attack.
- Determine the attacker's User-Agent.
- Identify the malicious web shell uploaded to the server.
- Determine the upload directory used by the attacker.
- Identify the outbound communication port used by the web shell.
- Determine the sensitive file targeted for exfiltration.
- Reconstruct the attack timeline.
- Produce a professional SOC Incident Report.


## Tools Used

- Wireshark
- Kali Linux
- IPInfo (GeoIP Lookup)
- GitHub
- Microsoft Word


## Repository Structure

"
INT401-Operation-Shadow-Drop/
│
├── README.md
├── Incident_Report.docx
├── c116-WebStrike.pcap
│
├── screenshots/
│   ├── protocol-hierarchy.png
│   ├── conversations.png
│   ├── endpoints.png
│   ├── attacker-location.png
│   ├── user-agent.png
│   ├── uploaded-webshell.png
│   ├── upload-directory.png
│   ├── outbound-port1.png
│   ├── outbound-port2.png
│   ├── exfiltration-file.png
│   └── timeline.png
│
├── evidence/
│   ├── findings.txt
│   └── wireshark-filters.txt
│
└── report/
    └── OperationShadowDrop.pdf
"


## Summary of Findings

| Investigation Item | Finding |
|--------------------|---------|
| Attacker IP        | 117.11.88.124 |
| Origin             | Tianjin, China |
| User-Agent         | Mozilla Firefox 115 on Linux |
| Upload Endpoint    | /reviews/upload.php |
| Upload Directory   | /reviews/uploads/ |
| Web Shell          | image.php / image.jpg.php |
| Reverse Shell Port | TCP 8080 |
| Targeted File      | /etc/passwd |



## Skills Demonstrated

- Network Traffic Analysis
- Packet Inspection
- HTTP Traffic Analysis
- Web Shell Identification
- Reverse Shell Investigation
- Digital Forensics
- Incident Response
- SOC Reporting
- Attack Timeline Reconstruction


## Author

Ms. Selline Nafula Mang'eni

ICDFA Phase 2 – Ethical Hacking Specialization

INT401 – Network Security Operations