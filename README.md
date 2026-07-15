Network Traffic Analysis with Wireshark

Project Overview

This project demonstrates practical network traffic analysis using Wireshark.

The objective was to capture, inspect, and analyze network communications while learning how to investigate normal and potentially suspicious activity.

The project covers:

* DNS analysis
* TCP communication
* TLS encryption
* HTTP requests
* IP address investigation
* Network conversations
* Incident documentation

⸻

Objectives

* Capture live network traffic
* Identify common network protocols
* Investigate DNS requests and responses
* Analyze encrypted TLS sessions
* Compare encrypted and unencrypted web traffic
* Investigate IP addresses
* Document findings as an analyst

⸻

Tools Used

* Wireshark
* Windows 10 Virtual Machine
* VirtualBox
* IP lookup services
* NeverSSL

⸻

Skills Demonstrated

* Packet Analysis
* DNS Investigation
* HTTP Analysis
* TLS Analysis
* TCP Stream Analysis
* Network Troubleshooting
* IP Reputation Investigation
* Incident Documentation

⸻

Key Findings

DNS

Observed multiple successful DNS queries and responses for:

* Google
* Bing
* YouTube

⸻

TLS

Observed encrypted TLS traffic including:

* Client Hello
* Server Hello
* Certificate exchange

Verified that application data remained encrypted.

⸻

HTTP

Captured unencrypted HTTP traffic using NeverSSL.

Successfully identified:

* GET request
* Host header
* User-Agent
* Accept headers

Demonstrated the difference between encrypted HTTPS traffic and plaintext HTTP traffic.

⸻

IP Investigation

Investigated multiple IP addresses.

Findings included:

* Fastly CDN (United Kingdom)
* Fastly CDN (Netherlands)
* Microsoft Windows Update traffic
* Initial investigation of a Russian-hosted IP, later determined to be legitimate Windows Update infrastructure.

⸻

Lessons Learned

This project improved my understanding of:

* How DNS resolution works
* TCP session establishment
* TLS encryption
* HTTP requests
* Packet analysis methodology
* How to differentiate legitimate and suspicious traffic

⸻

Screenshots

(Add screenshots here)

⸻

Future Improvements

* Analyze malware traffic
* Investigate malicious PCAP files
* Create detection rules
* Automate packet analysis using Zeek

⸻

Author

Collen Macamo

CompTIA Security+ Certified

Aspiring SOC Analyst

⸻

Step 4: Screenshots

We’ll include screenshots such as:

* DNS query
* DNS response
* TLS handshake
* HTTP GET request
* Conversations window
* IP lookup results
* TCP Stream
* NeverSSL capture

⸻

Step 5: What this project demonstrates

This is what recruiters should immediately see from your repository:

* You can use Wireshark confidently.
* You understand how DNS, TCP, TLS, and HTTP work together.
* You can investigate IP addresses instead of making assumptions.
* You can distinguish normal network activity from suspicious activity.
* You know how to document findings professionally.
# Network-Traffic-Analysis-Wireshark
Investigated DNS, TCP, TLS and HTTP traffic using Wireshark. Analyzed network conversations, validated IP ownership, and documented findings in a professional incident report.
