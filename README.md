# home-network-traffic-analysis
Beginner cybersecurity project analyzing DNS, TCP, and TLS traffic using Wireshark.
# Home Network Traffic Analysis

## Project Overview

This project demonstrates basic network traffic analysis using Wireshark. Traffic was captured from a home Wi-Fi network during normal web browsing activity and analyzed to identify DNS, TCP, and TLS communications.

## Objective

The objective of this project was to:

* Capture live network traffic
* Identify common network protocols
* Analyze how devices communicate across a network
* Understand how encrypted web traffic is established

## Tools Used

* Wireshark
* Windows 11
* Home Wi-Fi Network

## Methodology

1. Started a packet capture using Wireshark.
2. Generated network traffic by browsing websites.
3. Filtered captured traffic using protocol filters:

   * DNS
   * TCP
   * TLS
4. Recorded observations and documented findings.

## Findings

### DNS Analysis

Observed DNS requests for domains including:

* outlook.office.com
* youtube.com
* google.com
* yimg.com

DNS was used to resolve domain names into IP addresses before communication began.

### TCP Analysis

Observed TCP communication including:

* SYN packets
* SYN-ACK packets
* ACK packets

TCP established reliable communication between the local device and remote servers.

### TLS Analysis

Observed:

* Client Hello
* Server Hello
* TLSv1.2
* TLSv1.3
* Encrypted Application Data

TLS encrypted communications after TCP connections were established.

## Skills Demonstrated

* Packet Capture
* Network Traffic Analysis
* DNS Analysis
* TCP Analysis
* TLS Analysis
* Cybersecurity Documentation
* Wireshark Fundamentals

## Screenshots

See uploaded screenshots for examples of DNS, TCP, and TLS traffic observed during analysis.

## Key Takeaways

This project improved my understanding of how web traffic flows across a network and how DNS, TCP, and TLS work together to establish secure communications.
