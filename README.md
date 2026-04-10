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

## Challenges - CTF

-  <a href="https://github.com/Mrpickles8/Snapped-Phish-ing-Line/tree/main">Snapped Phishing Line</a> - Investigated a large-scale phishing campaign by analyzing multiple artifacts including emails, URLs, and credential harvesting pages. The goal was to identify the threat actor's infrastructure and reconstruct the attack chain from initial delivery to credential exfiltration.
- <a href="https://github.com/Mrpickles8/Invite-Only/tree/main">Invite Only</a> - Pivoted across IOCs (hash + IP) using VirusTotal to map a full AsyncRAT attack chain — from execution parents and dropped files to ClickFix phishing and Discord-based delivery.
- <a href="https://github.com/Mrpickles8/Disgruntled/tree/main">Disgruntled</a> - Performed a Linux forensic investigation on a compromised system used by a disgruntled insider. The objective was to identify malicious commands executed, files accessed or exfiltrated, and reconstruct the attacker's timeline using system artifacts.
- <a href="https://github.com/Mrpickles8/Shadow-Trace/tree/main">Shadow Trace</a> - Performed static malware analysis on `windows-update.exe` and correlate findings with two EDR alerts involving Base64 and CharCode obfuscation.
- <a href="https://github.com/Mrpickles8/Summit/tree/main">Summit</a> - Applyed the Pyramid of Pain framework iteratively — block a simulated adversary across 6 escalating levels using hash blocks, firewall rules, DNS filters, Sigma rules, beaconing detection, and file creation monitoring.
- <a href="https://github.com/Mrpickles8/-Snort-Challenge---Challenge-1/tree/main">Snort challenge 1</a> - Learnt and apply Snort IDS/IPS rule syntax to analyze network traffic and write custom detection rules for known attack patterns. The focus was on understanding rule structure, testing against PCAP files, and validating detection accuracy.
- <a href="https://github.com/Mrpickles8/Snort-Challenge---Challenge-2/tree/main">Snort challenge 2</a> - Applyed Snort in IPS mode to detect and block two live attack scenarios in real time: an SSH brute force attack on port 22 and a C2 reverse shell on port 4444. Custom rules were written and deployed to stop both attacks without prior knowledge of the exact payload.
- <a href="https://github.com/Mrpickles8/-ItsyBitsy/tree/main">Itsybitsy</a> - Investigated a potential C2 beaconing activity using Elastic SIEM. The goal was to analyze HTTP traffic logs to identify a compromised host communicating with a command and control server, extract IOCs, and determine the scope of the infection.
- <a href="https://github.com/Mrpickles8/Benign/tree/main">Benign</a> - Investigated a suspected LOLBin (Living Off the Land Binary) abuse on a corporate Windows workstation using Splunk. The goal was to detect the use of certutil.exe to download a malicious payload from a C2 server, leveraging Windows event logs.
- <a href="https://github.com/Mrpickles8/Investigating-with-Splunk/tree/main">Investigating with Splunk</a> - Investigated a compromised Windows environment using Splunk to identify a backdoor user account, malicious PowerShell execution, WMIC remote command execution, and C2 communication. The goal was to reconstruct the full attack chain from initial compromise to lateral movement.
- <a href="https://github.com/Mrpickles8/Tempest/tree/main">Tempest</a> - Reconstructed a complete attack chain on a compromised Windows host using Sysmon, Wireshark, and Timeline Explorer. The investigation covered initial access via the Follina exploit (CVE-2022-30190), base64-encoded C2 beaconing, and privilege escalation with persistence via a compromised administrator account.
- <a href="https://github.com/Mrpickles8/Boogeyman-2/tree/main">Boogeyman 2</a> - Performed digital forensics on a phishing email and a Windows memory dump to reconstruct the full malware execution chain using olevba and Volatility3.
- <a href="https://github.com/Mrpickles8/Boogeyman-3/tree/main">Boogeyman 3</a> - Investigated a full intrusion chain in Elastic SIEM — from HTA phishing delivery through C2, UAC bypass, Mimikatz credential dumping, WinRM lateral movement, DCSync, and ransomware deployment.
- <a href="https://github.com/Mrpickles8/New-Hire-Old-Artifacts/tree/main">New Hire Old Artifacts</a> - Investigated a compromised Finance workstation using Splunk and Sysmon logs
to identify credential theft tools, C2 communication, Windows Defender
tampering, and malicious binary staging.
- <a href="https://github.com/Mrpickles8/ExfilNode/tree/main">ExfilNode</a> - Conducted a Linux forensic investigation on a compromised server suspected of being used as an exfiltration node. The goal was to identify how the attacker gained access, what data was staged or exfiltrated, and what persistence mechanisms were deployed on the Linux system.
