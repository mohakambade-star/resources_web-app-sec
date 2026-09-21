## Interactive Practice Platforms & Wargames

* **LetsDefend:** A fully simulated SOC environment. Practice triaging alerts, interacting with a simulated SIEM/EDR, analyzing emails, and containing endpoints.
* **CyberDefenders (Boss of the SOC & CCDC):** Massive repository of Blue Team challenges. Excellent for analyzing real-world incident datasets (PCAPs, memory dumps, disk images, and Splunk logs).
* **Blue Team Labs Online (BTLO):** Scenario-based investigations covering incident response, digital forensics, security operations, and reverse engineering.
* **Splunk BOTS (Boss of the SOC) Datasets:** Open-source datasets provided by Splunk. Essential for practicing threat hunting and building SPL (Splunk Processing Language) queries against real APT behaviors.
* **TryHackMe (SOC Level 1 & 2 Learning Paths):** Highly structured, gamified introductory modules covering SIEM deployment, phishing analysis, and endpoint logs.

## Structured Courses & Frameworks

* **Antisyphon Training (Pay-What-You-Can):** Foundational SOC courses like "SOC Core Skills" by John Strand. High-quality instruction for defensive operations.
* **Microsoft SC-200 (Security Operations Analyst) Labs:** Free Microsoft Learn modules covering the deployment and hunting queries within Microsoft Defender XDR and Microsoft Sentinel.
* **Cisco CyberOps Associate (CBROPS) Blueprints:** Excellent foundational theory for understanding network intrusion analysis, cryptography, and basic incident response.
* **SANS Cyber Aces Online:** Free introductory courses covering operating system security, networking, and systems administration.

## Self-Hosted Lab Environments

* **DetectionLab:** A collection of Packer and Vagrant scripts that automatically deploy an Active Directory environment pre-configured with Splunk, Sysmon, and Zeek for immediate log analysis practice.
* **Security Onion:** A free, open-source Linux distribution for threat hunting, enterprise security monitoring, and log management. Includes Suricata, Zeek, Elastic Stack, and CyberChef out of the box.
* **Splunk Attack Range:** An open-source tool by Splunk that builds a simulated local environment (or cloud), executes attacks, and forwards the data into a Splunk instance to practice detection engineering.
* **HELK (The Hunting ELK):** An advanced threat hunting platform based on Elasticsearch, Logstash, Kafka, and Kibana, enriched with data science capabilities.
* **Wazuh:** Open-source SIEM and XDR platform. Excellent for learning endpoint compliance, vulnerability detection, and active response actions on virtual machines.

## Network Security Monitoring (NSM) & Packet Analysis

* **Zeek (formerly Bro):** Powerful network analysis framework that extracts rich metadata from network traffic (e.g., DNS queries, HTTP headers) rather than just full packet captures.
* **Suricata / Snort:** Open-source Intrusion Detection/Prevention Systems (IDS/IPS). Crucial for learning how network signatures trigger on malicious traffic.
* **Arkime (formerly Moloch):** Large-scale, open-source, indexed packet capture and search tool.
* **RITA (Real Intelligence Threat Analytics):** Open-source framework by Active Countermeasures for detecting command and control (C2) communication via beaconing analysis.
* **Wireshark & Tshark:** The industry standard for deep-dive packet inspection. (Refer to *Malware-Traffic-Analysis.net* for practice PCAPs).

## SIEM, EDR, & Log Analysis

* **Splunk Enterprise (Free Tier):** The industry-standard SIEM. The free version allows up to 500MB of daily ingestion—perfect for local lab analysis.
* **Elastic Security (ELK Stack):** Open-source SIEM and endpoint security platform. Core to understanding JSON-based log ingestion and Lucene queries.
* **Microsoft Sysmon (System Monitor):** A Windows system service that logs system activity (process creations, network connections, file changes) to the Windows Event Log. *The most critical log source for Windows endpoint hunting.*
* **Velociraptor:** Advanced open-source endpoint monitoring, digital forensics, and cyber incident response (DFIR) platform. 

## Incident Response & Digital Forensics (DFIR)

* **KAPE (Kroll Artifact Parser and Extractor):** High-speed tool used to parse and extract specific triage artifacts (evidence) from Windows systems in minutes.
* **Volatility 3:** The premier memory forensics framework. Used for extracting running processes, network connections, and hidden malware from RAM dumps.
* **Autopsy:** The premier end-to-end open-source digital forensics platform for hard drive investigation.
* **CyberChef:** The "Cyber Swiss Army Knife" by GCHQ. A web app for decoding, decrypting, unzipping, and analyzing obfuscated scripts and payloads.
* **Zimmerman's Tools (Eric Zimmerman):** A suite of command-line tools for deep-dive Windows forensic analysis (parsing MFT, Prefetch, Jump Lists, LNK files).

## Malware Analysis, Phishing & OSINT

* **ANY.RUN & Triage (tria.ge):** Interactive online malware sandboxes. Watch malware detonate in real-time and review the generated network and host indicators.
* **urlscan.io:** A sandbox for websites. Use it to safely examine suspicious URLs and phishing domains without risking your own environment.
* **PhishTool / MXToolbox:** Essential for extracting and analyzing email headers, SPF/DKIM/DMARC records, and tracing malicious email origins.
* **VirusTotal & AlienVault OTX (Open Threat Exchange):** Threat intelligence platforms for researching IP addresses, file hashes (SHA256), and domains.
* **YARA:** The "pattern matching swiss army knife" for malware researchers. Learn to write YARA rules to classify and identify malware samples.

## Essential Reading Resources & Frameworks

* **MITRE ATT&CK Framework:** The global knowledge base of adversary tactics and techniques based on real-world observations. The SOC Analyst's bible.
* **NIST SP 800-61 Rev. 2:** The "Computer Security Incident Handling Guide." The foundational government standard for the Incident Response lifecycle (Preparation -> Detection/Analysis -> Containment/Eradication/Recovery -> Post-Incident Activity).
* **The Cyber Kill Chain (Lockheed Martin):** Foundational model for understanding the stages of a cyberattack.
* **Red Canary Threat Detection Report:** Annual report detailing the most prevalent MITRE ATT&CK techniques observed in the wild and how to detect them.
* **SANS DFIR Posters:** "Hunt Evil," "Windows Forensic Analysis," and "Network Forensics" cheat sheets. Excellent quick-reference guides for identifying anomalies.

## High-Yield Video Resources

* **13Cubed:** The absolute best channel for deep-dive Digital Forensics and Incident Response (DFIR) tutorials, covering memory forensics and Windows artifacts.
* **Simply Cyber (Gerald Auger):** Excellent for understanding the day-to-day life, workflows, and mindset of a SOC analyst.
* **Active Countermeasures:** High-quality webinars on cyber threat hunting, specifically focused on detecting C2 beaconing and anomalous network behavior.
* **John Hammond / IppSec:** Great for reverse-engineering the attacker's mindset (Red Team) so you can better understand what logs are generated during an intrusion (Blue Team).
* **Black Hills Information Security (BHIS):** "Pay What You Can" webcasts covering advanced defensive tactics, Purple Teaming, and SOC methodologies.
