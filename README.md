
Network Traffic Analysis and DNS Investigation

Overview

A hands-on cybersecurity learning project using Wireshark on Kali Linux to explore DNS resolution, TCP connection establishment, and TLS traffic.

Objectives

* Inspect DNS queries and responses.
* Understand the TCP three-way handshake.
* Identify TLS handshake messages and encrypted application data.
* Practise packet capture and filtering with Wireshark.

Tools Used

* Kali Linux
* Wireshark
* DNS
* TCP/IP
* TLS

Methodology

1. Selected the wlan0 network interface in Wireshark.
2. Generated test network traffic using ping and curl.
3. Used the dns display filter to inspect DNS traffic for example.com.
4. Used the tcp display filter to examine TCP connection flags.
5. Identified TLS messages, including Client Hello, Server Hello, and Application Data.
6. Saved the packet capture in PCAPNG format and captured screenshots of the analysis.

Observations

* DNS query and response packets for example.com were observed.
* TCP connection establishment included SYN, SYN-ACK, and ACK packets.
* TLS handshake messages and application-data packets were visible.
* TCP connection-closing packets were also observed.

Key Learning

This project provided practical experience with packet capture, DNS investigation, TCP handshake analysis, and identifying TLS traffic in Wireshark.

Evidence

Screenshots documenting the DNS analysis, TCP handshake, and TLS traffic will be included in this repository.

Disclaimer

This project was performed for educational purposes using traffic generated from my own system.

Author

Cybersecurity learner | CEH v13 Certified
