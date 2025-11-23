# Python-Scanner

This project is a modern reimplementation—fully compatible with Python 3, of a classic scanner based on RAW packet sniffing.
The tool sends UDP datagrams to all hosts on a given subnet and uses ICMP “Destination Unreachable” (Type 3, Code 3) responses as an indicator that the host is active.

The goal of this project is to demonstrate fundamental concepts of network hacking and offensive security, including:

- Raw sockets and packet capture;
- Manual parsing of IP and ICMP headers;
- Threading for parallel packet sending'
- Detection of active host without relying on classic ping;
- Low-Level data manipulation using struct.
