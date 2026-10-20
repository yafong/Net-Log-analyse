# Network Traffic Analysis

## 📌 Overview

This project was completed as part of the Google Cybersecurity Certificate.

The objective was to analyze network traffic using `tcpdump` to investigate a connectivity issue affecting the website `www.yummyrecipesforme.com`.

The investigation focused on identifying the network protocols involved, interpreting ICMP error messages, and determining why DNS queries were failing.

## 🎯 Objectives

- Analyze network traffic captured using `tcpdump`.
- Identify the protocols involved in the incident.
- Understand the role of DNS, UDP, and ICMP in network communication.
- Interpret packet information, including IP addresses, ports, and error messages.
- Identify the affected network service and the suspected root cause.
- Document the incident and recommend troubleshooting steps.

## 🧪 Methodology

First, I reviewed the incident scenario and the symptoms reported by users, who were unable to access the website and received a "destination port unreachable" error.

Then, I analyzed the provided `tcpdump` log to identify the source and destination IP addresses, timestamps, network protocols, and destination port.

I observed that DNS queries were sent over UDP to port 53, but the responses contained ICMP error messages indicating that the destination UDP port was unreachable.

Based on these findings, I identified DNS resolution as the affected service and documented the suspected cause, the impact on website accessibility, and the recommended next steps for troubleshooting.

## 📚 What I Learned

Through this project, I developed practical experience with:

- Analyzing network traffic using `tcpdump`.
- Identifying and interpreting DNS, UDP, and ICMP packets.
- Understanding the role of port 53 in DNS resolution.
- Reading packet captures to identify communication failures.
- Interpreting ICMP error messages and their implications.
- Identifying network services affected by connectivity issues.
- Documenting cybersecurity incidents and their potential root causes.
- Recommending troubleshooting steps based on network traffic evidence.

## ⚠️ Disclaimer

This project was completed in a controlled educational environment as part of the Google Cybersecurity Certificate.

The analysis was based on a simulated incident scenario and the provided network traffic logs.