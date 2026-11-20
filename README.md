# Threat Intelligence Report: 4-Day Honeypot Deployment & ELK Stack Analysis

A threat intelligence report analyzing ~26,000 unsolicited honeypot interactions observed over a 4-day (~96-hour) exposure window using **T-Pot** on an **AWS EC2** instance (administered via SSH from Kali Linux), visualized in **Kibana (ELK Stack)**, and enriched with **Cisco Talos Intelligence** and **CVE Details**[span_0](start_span)[span_0](end_span).

## Key Highlights
* **Scope & Setup:** T-Pot containerized sensors and Suricata IDS running on AWS EC2 (`eu-north-1`), observed across ~96 hours[span_1](start_span)[span_1](end_span).
* **Activity Observed:** Heavy automated scanning and probing across ports/protocols, credential brute-forcing (such as `root` and `123456`), and Suricata alerts including `CVE-2002-0013` / legacy SNMP references[span_2](start_span)[span_2](end_span).
* **Analyst Reasoning:** Separates observed telemetry and network origin from threat actor attribution or confirmed exploitation, outlines limitations where logs/percentages were not exported, and provides practical defensive controls[span_3](start_span)[span_3](end_span).

## Report File
* See `Threat-Intelligence-Report.pdf` in this repository for the full analysis, architecture diagram, tables, and recommendations.
