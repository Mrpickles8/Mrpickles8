# Hello, I'm David
<a href="https://linkedin.com/in/david-artaud"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I am a young professional with a profound interest in technology and a dedication to solving complex problems.

## Objective

Junior SOC Analyst with hands-on experience in log analysis, SIEM triage (Splunk, Chronicle and Elastic) and incident 
response through 90+ lab rooms on TryHackMe. Business engineering background with proven analytical skills and 
strong bilingual communication skills (EN/FR). Seeking a Tier 1/2 SOC role where I can contribute to threat detection 
and response operations. 

## Skills

| Skill                                         | Associated Project         |
|-----------------------------------------------|----------------------------|
| SIEM Implementation and Log Analysis          | link in creation|
| Network Traffic Monitoring and Attack Detection | link in creation|
| Perform memory forensics         | link in creation|
| Incident Response Planning and Execution      |link in creation|
| Phishing Unfolding                  | link in creation|
| Scripting and Automation for Threat Mitigation | link in creation|

## Tools

### Network
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-Suricata-EF3B2D?&style=for-the-badge&logo=Suricata&logoColor=white" />
    <img src="https://img.shields.io/badge/-Zeek-777BB4?&style=for-the-badge&logo=Zeek&logoColor=white" />
    <img src="https://img.shields.io/badge/-BRIM-4A90D9?&style=for-the-badge&logoColor=white" />
</div>

### Endpoint
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Defender_for_Endpoint-00A4EF?&style=for-the-badge&logo=Microsoft&logoColor=white" />
</div>

### SIEM
<div>
    <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
    <img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" />
    <img src="https://img.shields.io/badge/-Elastic-005571?&style=for-the-badge&logo=Elastic&logoColor=white" />
</div>

### IPS/IDS
<div>
    <img src="https://img.shields.io/badge/-Snort-F90101?&style=for-the-badge&logo=Snort&logoColor=white" />
</div>

### Forensics
<div>
    <img src="https://img.shields.io/badge/-Volatility-4B275F?&style=for-the-badge&logoColor=white" />
</div>

### Operatin system
<div>
    <img src="https://img.shields.io/badge/-Kali_Linux-557C94?&style=for-the-badge&logo=Kali-Linux&logoColor=white" />
    <img src="https://img.shields.io/badge/-Ubuntu-E95420?&style=for-the-badge&logo=Ubuntu&logoColor=white" />
    <img src="https://img.shields.io/badge/-Windows-0078D6?&style=for-the-badge&logo=Windows&logoColor=white" />
</div>

## Certifications
<div>
<img src="https://img.shields.io/badge/-Google_Cybersecurity_Certificate-4285F4?&style=for-the-badge&logo=Google&logoColor=white" />
<img src="https://img.shields.io/badge/-SOC_Level_1_Completion-212C42?&style=for-the-badge&logo=TryHackMe&logoColor=white" />
</div>

## Projects

- Splunk SOC Lab implementation
- Elastic SOC Lab implementation
- Wireshark traffic analysis
- Volatility3 memory forensics
- Snort threat detection

## Challenges

- Investigating with Splunk - Identified a backdoor user by investing with Splunk, resulting in remote WMIC cmd, malicious 
  powershell events and C2 beacon communicqtion. 
- Benign - Detected a LOLBIN abuse (certutil.exe) to downloads malicious payload from a C2 server on a HR workstation 
  using Splunk on Windows envent.
- Tempest - Reconstructed a full attack chain using Sysmon, Wireshark, and TimelineExplorer; traced initial access via Folina 
  exploit; identified base64 encoded C2 beacons and uncovered privilege escalation with persistence via rogue admin.
- Snort Challenge - Live Attacks -Detected and blocked an SSH Brute-force attack (port 22) and a reverse shell C2 channel 
  (port 4444) using Snort IPS mode. Wrote custom drop rules to server both connections in real time.
- Secret Recipe - Conducted windows registry forensics investigating across 6 hives using Registry Explorer; recovering a 
  accessed filenames, identified a backdoor account and tracing suspect activity via UserAssit artifacts.
-  <a href="https://github.com/Mrpickles8/Snapped-Phish-ing-Line/tree/main">Snapped Phishing Line</a> - Investigated a large-scale phishing campaign by analyzing multiple artifacts including emails, URLs, and credential harvesting pages. The goal was to identify the threat actor's infrastructure and reconstruct the attack chain from initial delivery to credential exfiltration.
- <a href="https://github.com/Mrpickles8/Invite-Only/tree/main">Invite Only</a> Analyzed a suspicious email invitation to identify embedded malicious content, trace the delivery mechanism, and document the indicators of compromise associated with the phishing attempt.
