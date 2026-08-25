# 🛡️ CodeAlpha_Network_Intrusion_Detection

This repository contains the configuration and rules for a Network Intrusion Detection System (NIDS) set up using Snort 3 on Kali Linux. This project is part of my Cyber Security Internship at CodeAlpha.

## 📌 Task Overview (Task 4)
The objective of this task is to:
1. Set up a network-based intrusion detection system (Snort).
2. Configure rules and alerts to detect suspicious or malicious activity.
3. Monitor network traffic continuously for potential threats.

## ⚙️ Environment Setup
- Operating System: Kali Linux (Virtual Machine via VMware)
- Tool Used: Snort 3 (Intrusion Detection System)
- Target Network Interface: eth0

## 📝 The Rule (local.rules)
I created a custom rule to detect any suspicious ICMP Ping attempts directed at my network. This is often the first reconnaissance step taken by attackers.

The rule configured in /etc/snort/rules/local.rules is:
`text
alert icmp any any -> $HOME_NET any (msg:"Suspicious Ping (ICMP) Detected"; sid:1000001; rev:1;)

## 📸 Project Screenshots (Full Documentation)

<details>
  <summary><b>Click here to view all 10 project screenshots</b></summary>
  <br>

  <img src="Screenshot 2026-08-25 213349.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213349 1.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213513.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213513 2.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213548.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213548 3.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213623.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213623 4.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213644.png" width="800"><br><br>
  <img src="Screenshot 2026-08-25 213644 5.png" width="800"><br><br>

</details>
