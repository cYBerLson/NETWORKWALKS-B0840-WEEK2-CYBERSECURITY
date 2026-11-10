\# Networkwalks Cybersecurity Internship — Week 2



\### Footprinting, OSINT, Reconnaissance and Network Discovery



\*\*Intern:\*\* Abdulmajid Bello  

\*\*Intern ID:\*\* NW-084-2ST  

\*\*Batch:\*\* B0840  

\*\*Assessment Period:\*\* November 8–13, 2026  

\*\*Environment:\*\* Kali Linux and Windows 11  

\*\*GitHub:\*\* \[cYBerLson](https://github.com/cYBerLson)



\---



\## Project Overview



This repository documents my Week 2 practical cybersecurity projects completed during the Networkwalks Cybersecurity Internship.



The exercises focused on domain footprinting, open-source intelligence (OSINT), DNS reconnaissance, web technology identification, local network scanning, and security assessment documentation.



My approach involved executing the required practical tasks, understanding the tools and commands, analysing their actual outputs, capturing evidence, and documenting the findings.



\## Project Modules



| Module | Project | Progress |

|---|---|---|

| W2-PM1 | Footprinting with Kali Linux Tools | Completed |

| W2-PM2 | Google Hacking Database (GHDB) | Research documented; verification limitations |

| W2-PM3 | Footprinting with Maltego | Completed |

| W2-PM4 | Footprinting with theHarvester | Practical work documented |

| W2-PM5 | Network Scanning with Zenmap | Completed |

| W2-PM-FINAL | Final Technical Assessment Report | Pending |



\## W2-PM1 — Kali Linux Footprinting



\*\*Target:\*\* `networkwalks.com`



Six tools were used:



\- WHOIS — Domain registration information

\- WhatWeb — Web technology identification

\- NSLookup — DNS resolution

\- cURL — HTTP header inspection

\- WAFW00F — Web Application Firewall identification

\- DNSRecon — DNS infrastructure enumeration



The tools provided information about the domain's registration, server technologies, IP resolution, HTTP configuration, WAF fingerprint, and DNS infrastructure.



\*\*\[View W2-PM1 Documentation](01-footprinting-kali-tools/README.md)\*\*



\## W2-PM2 — Google Hacking Database



This module explored Google search operators and GHDB techniques for identifying publicly indexed information.



The assigned research covered camera-related search queries and mathematics PDF listings.



The research documentation distinguishes search results from verified security vulnerabilities. Third-party camera feeds, authentication credentials, and unnecessary sensitive information are excluded from public-facing evidence.



\*\*\[View W2-PM2 Documentation](02-ghdb/README.md)\*\*



\## W2-PM3 — Maltego Footprinting



\*\*Tool:\*\* Maltego Graph Desktop 4.14.0



Maltego was installed and configured on Windows to investigate relationships between domain and email entities.



A public-information transform returned one email address associated with the assigned domain.



The resulting investigation graph was saved for technical review.



\*\*\[View W2-PM3 Documentation](03-maltego/README.md)\*\*



\## W2-PM4 — theHarvester



\*\*Target:\*\* `microsoft.com`



Two instructor-specified command configurations were used:



\*\*Task 1 — Baidu source\*\*



`theHarvester -d microsoft.com -l 1000 -b baidu`



\*\*Task 2 — All supported sources\*\*



`theHarvester -d microsoft.com -l 50 -b all`



The module documents the reconnaissance methodology, command configurations, screenshots, saved tool outputs, and limitations associated with external information sources.



\*\*\[View W2-PM4 Documentation](04-theharvester/README.md)\*\*



\## W2-PM5 — Network Scanning with Zenmap



\*\*Environment:\*\* Windows 11 and an authorized local Wi-Fi network.



The project covered all seven instructor tasks, including Zenmap installation, IP configuration, subnet identification, host discovery, host counting, IP and MAC address collection, and topology export.



\### Key Results



| Metric | Result |

|---|---|

| Nmap version | 7.993 |

| Scan profile | Ping scan |

| Addresses scanned | 256 |

| Live hosts detected | 2 |

| Scan duration | 7.53 seconds |

| Network topology | Generated and saved as PDF |



Local IP and MAC addresses were redacted from shareable documentation.



\*\*\[View W2-PM5 Documentation](05-zenmap/README.md)\*\*



\## Final Technical Report



The final report will consolidate the completed practical modules, methodologies, collected evidence, observations, limitations, and recommendations.



It will distinguish informational reconnaissance findings from confirmed vulnerabilities.



\*\*Status:\*\* In preparation.



\## Repository Structure



```text

NETWORKWALKS-B0840-WEEK2-CYBERSECURITY/

├── README.md

├── .gitignore

├── 01-footprinting-kali-tools/

├── 02-ghdb/

├── 03-maltego/

├── 04-theharvester/

├── 05-zenmap/

└── final-report/

```



\## Security and Ethical Considerations



All practical work was intended for authorized educational and defensive cybersecurity purposes.



The project emphasizes accurate reporting, responsible handling of potentially sensitive information, and maintaining evidence without fabricating findings.



Automated tool detections are not treated as confirmed exploitable vulnerabilities without appropriate verification.



\## Learning Outcomes



The internship strengthened my understanding of:



\- Website footprinting and DNS reconnaissance

\- HTTP technologies and security headers

\- Open-source intelligence techniques

\- Visual entity analysis using Maltego

\- Network discovery and topology visualization

\- Security evidence handling

\- Technical documentation and reporting



\## Conclusion



These Week 2 exercises provided practical experience with cybersecurity reconnaissance and network discovery across Kali Linux and Windows.



The repository documents the completed activities, observed results, technical challenges, and lessons learned in a structured, reproducible format.



\---



\*\*Prepared by Abdulmajid Bello\*\*  

\*\*Networkwalks Cybersecurity Internship — Batch B0840\*\*



\*Cybersecurity | Networking | Ethical Hacking\*

