# Splunk Basics – TryHackMe Lab

This repository documents my hands-on practice with Splunk using the [Splunk Basics](https://tryhackme.com/room/splunk) room on TryHackMe.

I used Splunk to ingest VPN log data, query with search commands, and visualize network activity to simulate real-world Security Operations Center (SOC) investigation.

---

## ✅ Completed Lab Objectives

- Connected to Splunk Enterprise interface using TryHackMe
- Learned how Splunk components (Indexer, Search Head, Forwarder) interact
- Ingested `vpn_logs.json` via data input setup
- Used search queries to:
  - Identify users with suspicious login times
  - Filter by source country and IP
  - Extract useful fields using Splunk’s search processing language (SPL)
- Navigated key Splunk tabs:
  - **Search**
  - **Dashboards**
  - **Datasets**
- Practiced incident investigation on real-world event logs

---

## 🔧 Tools Used

- TryHackMe AttackBox
- Splunk Enterprise 8.2.6 (Web UI)
- VPN log dataset (`vpn_logs.json`)
- Kali Linux VM (connected to browser for monitoring)

---

## 📸 Screenshots

Screenshots were captured of:
- VPN Logs being parsed in the **Search** tab
- Filtered queries using `source="vpn_logs.json"` and `username="Albert"`
- Timeline spike analysis on Jan 11
- Dashboard showing total connections per user/IP

> You can find screenshots in the `screenshots/` folder (uploaded separately).

---

## 🧠 SOC Takeaways

This lab provided experience with:
- Log ingestion and parsing
- Security data exploration using SPL
- Identifying indicators of compromise
- Building habits for log-based alerting

Splunk is widely used in SOC environments for log correlation, and this lab enhanced my threat detection workflow.

---

## 💼 Relevance

- Aligns with SOC Analyst and Cybersecurity Analyst job responsibilities
- Strengthens understanding of SIEM tools
- Prepares for Splunk certifications and hands-on interviews

