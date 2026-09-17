# RESOURCES
---

## Interactive Practice Platforms & Disclosures
* **PortSwigger Web Security Academy:** Core web security curriculum and hosted labs covering modern vectors like HTTP Request Smuggling, JWT flaws, Web Cache Poisoning, and OAuth bugs.
* **OverTheWire (Bandit & Natas):** Command-line Linux fundamentals (*Bandit*) and web application wargames (*Natas*).
* **PwnCollege:** Open-source platform covering low-level Linux internals, privilege escalation, memory safety, and binary exploitation fundamentals.
* **SQLBolt:** Interactive SQL query syntax, joins, and database logic drills.
* **root-me:** Spaced-repetition challenge platform for web, networking, and cryptography PCAP analyses.
* **HackerOne Hacktivity & Bugcrowd:** Disclosed real-world vulnerability reports for daily review of actual production exploit chains and bypass logic.
* **PentesterLab (Free Tier):** Targeted, bite-sized labs covering specific web vulnerabilities and public CVEs.

---

## Structured Courses
* **CS50P (Harvard's Intro to Programming with Python):** Free, problem-set-driven course focusing on clean script architecture, regex parsing, file I/O, error handling, and building custom CLI tools.
* **CS50x (Harvard's Intro to Computer Science):** Foundational coverage of C, memory management, pointers, and underlying data structures.
* **CS50's Introduction to Cybersecurity:** Fundamentals of cryptography, network defense, threat modeling, and defensive engineering.
* **Professor Messer's CompTIA Network+ (N10-009):** Free training covering enterprise network infrastructure, OSI model breakdowns, and protocol operations.

---

## Self-Hosted Vulnerable Targets
* **OWASP Juice Shop:** Node.js/Angular OWASP Top 10 web app. Easily deployed via `docker-compose`.
* **GOAD (Game of Active Directory):** Containerized multi-node AD lab for testing Kerberos flows (dissecting `KRB_AS_REQ`/`KRB_AS_REP`), ticket roasting, and LDAP privilege escalation.
* **OWASP WebGoat & DVWA:** Java/Spring and PHP/MySQL targets with configurable security levels for manual proxy manipulation.
* **bWAPP (Buggy Web Application):** Comprehensive PHP target containing over 100 web vulnerabilities across multiple categories.
* **OWASP crAPI & VAmPI:** Microservice, REST, and OpenAPI vulnerable target environments.
* **OWASP Security Shepherd & NodeGoat:** Specialized training targets for web/mobile applications and Node.js/MongoDB environments.
* **DVGA (Damn Vulnerable GraphQL Application):** Specialized target for testing GraphQL introspection leaks and authorization bypasses.
* **hackxor & XVWA:** Realistic multi-step web application simulators and PHP target corpora.

---

## Networking, Virtualization & Packet Analysis
* **GNS3 & Containerlab:** Native Linux network emulators for building complex switch topologies, routing networks, and containerized lab nodes.
* **Docker & Docker Engine:** Container runtime for running target stacks and network nodes.
* **FRRouting (FRR) / SR Linux:** Free container images for virtual network routers and dynamic routing protocols.
* **Wireshark, Tshark & tcpdump:** Interactive and headless packet capture, display filtering, and programmatic dissection.
* **Scapy:** Python packet manipulation framework for writing custom protocol injectors and dissecting raw network frames programmatically.
* **Malware-Traffic-Analysis.net:** Real-world PCAPs with technical writeups for threat hunting and traffic decryption.
* **Subnetting.net & DavidC Subnetting Generator:** Interactive drills for CIDR notation, binary math, wildcard masks, and IPv4/IPv6 allocation practice.
* **The TCP/IP Guide & HPBN:** Free online references for protocol mechanics ([tcpipguide.com](http://www.tcpipguide.com/)) and browser network performance ([hpbn.co](https://hpbn.co/)).

---

## Web, API & Network Pentesting Tools
* **Burp Suite Community & OWASP ZAP:** Primary intercepting proxies for manual request manipulation, repeater analysis, and automated scanning.
* **Caido:** Lightweight, Rust-powered proxy with low system resource consumption and a clean UI.
* **Impacket:** Python library for low-level network protocol manipulation, essential for custom SMB, RPC, and Kerberos operations.
* **ffuf & Feroxbuster:** Blazing-fast web fuzzing and directory discovery engines (paired with Assetnote wordlists).
* **Kiterunner & Arjun:** Route discovery engines for hidden API endpoints and HTTP parameter brute-forcing.
* **bettercap:** Network attack, interception, and ARP-spoofing framework.
* **nmap, nc (netcat) & curl:** Port scanning, service enumeration, network listeners, and HTTP testing.

---

## Essential Reading Resources & Documentation
* **OWASP Web Security Testing Guide (WSTG) & Cheat Sheet Series:** Technical testing methodologies, API security patterns, and remediation standards.
* **The Web Application Hacker's Handbook (WAHH):** Core text covering multi-tier web application architecture, state management, and flaw patterns.
* **HackTricks (`book.hacktricks.xyz`) & PayloadsAllTheThings:** Community wikis for technical pentesting vectors, service enumeration cheatsheets, and bypass payloads.
* **Official RFC Specifications:** Deep protocol specs including RFC 9110 (HTTP Semantics), RFC 6749 (OAuth 2.0), RFC 7519 (JWT), and RFC 4120 (Kerberos V5).
* **MDN Web Docs & Python Official Documentation:** Essential reference material for standard HTTP protocols, DOM mechanics, and Python standard libraries (`requests`, `httpx`, `asyncio`, `sqlite3`).
* **Khan Academy Statistics & scikit-learn Documentation:** References for evaluating metrics like precision, recall, F1-scores, and confidence intervals.

---

## High-Yield Video Resources
* **Rana Khalil:** Step-by-step code breakdowns and exploitation walkthroughs focused on PortSwigger Academy web labs.
* **LiveOverflow:** Conceptual breakdowns of binary exploitation, browser internals, and vulnerability research mindsets.
* **InsiderPhD & NahamSec:** Web API reconnaissance methodologies, bug hunting workflows, live target enumeration, and reporting.
* **PwnFunction:** Animated visual explanations of core web vulnerabilities (XSS, CSRF, SSRF, JWT, SQLi).

---

## Modern Python Security Tooling Stack
* **uv:** Blazing-fast, Rust-based Python package and virtual environment manager (`uv pip install`).
* **httpx + asyncio:** High-concurrency Python stack for writing custom async web scanners and multi-threaded recon tooling.
* **Typer & Rich:** Libraries for rapidly building polished CLI interfaces, progress bars, and formatted terminal output.

---

## AI Engine, Local RAG & Data Processing
* **Ollama + Open-WebUI:** Local LLM execution engine paired with a self-hosted management UI.
* **ChromaDB + LangChain / LlamaIndex:** Vector database setup to ingest offline documentation (HackTricks, OWASP WSTG, RFCs) for local RAG lookups.
* **Local Models (VRAM Dependent):**
  * *8GB VRAM Tier:* `Llama-3:8b`, `Mistral:7b`, `Qwen2.5:7b` for fast local scripting assistance.
  * *12GB–16GB+ VRAM Tier:* `Qwen2.5:14b`, `Command-R` for parsing large logs and long codebase contexts.
* **SQLite & Pandas:** Built-in structured logging of scan outputs, proxy logs, and quantitative data manipulation.
