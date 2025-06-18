# 🕵️‍♂️ PCAP Analysis with Wireshark

This project is a completed lab for analyzing PCAP files using Wireshark, simulating a real-world incident response scenario involving brute-force attacks and malware delivery.

## 📁 Overview

In this scenario, a virtual machine hosting a web service goes offline. As a SOC Analyst, your job is to examine captured network traffic using Wireshark and identify signs of compromise.

Key objectives:

- Identify brute-force SSH login attempts
- Detect malware downloads
- Analyze protocol behavior
- Recognize attacker tools and IPs

## 🛠️ Tools Used

- [Wireshark](https://www.wireshark.org/)
- PCAP file (`hp_challen.pcap`) [not included in repo]
- Online research & CVE analysis

## 🔍 Analysis Highlights

- **Attack Type**: Brute force via SSH
- **Tool Used**: Likely `hydra`
- **Failed Attempts**: 52
- **Malware Delivery**: Via `wget` using HTTP
- **Downloaded Files**: 9 BMP files with base64-like filenames
- **Attacker IP**: `174.129.57.253`

## 📸 Screenshots

Screenshots of analysis can be found in the `screenshots/` folder:

- `brute_force_attempts.png`
- `wget_user_agent.png`
- `http_objects.png`

## 📄 Report

The full lab submission can be found in [Lab_Report.pdf](./Lab_Report.pdf).

## 🔒 Legal & Ethical Disclaimer

All analysis was performed on educational data provided in a controlled lab environment. Unauthorized packet capture or analysis on live networks may be illegal. Always have proper authorization.

## 📜 License

This project is for educational use only.
