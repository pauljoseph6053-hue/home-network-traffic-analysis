# Home Network Traffic Analysis

## Objective

Capture and analyze network traffic generated during normal web browsing activity using Wireshark.

## Environment

- Windows PC
- Wireshark
- Home Wi-Fi Network

## DNS Findings

Observed DNS requests for:

- outlook.office.com
- youtube.com
- google.com
- yimg.com

DNS traffic was used to resolve domain names into IP addresses.

## TCP Findings

Observed:

- SYN packets
- SYN-ACK packets
- ACK packets

HTTPS traffic primarily used destination port 443.

TCP established reliable communication between the local device and remote servers.

## TLS Findings

Observed:

- Client Hello
- Server Hello
- TLSv1.2
- TLSv1.3
- Encrypted Application Data

TLS encrypted communications after the TCP connection was established.

## Key Takeaways

- DNS resolves hostnames to IP addresses.
- TCP establishes reliable connections.
- TLS encrypts network communications.
- Modern web browsing relies heavily on encrypted HTTPS traffic.