# 🔐 Security Investigation and Enrichment Tools
2
 
3
A curated collection of cybersecurity, threat intelligence, Microsoft Security, Azure, and OSINT resources used for SecOps investigations, threat hunting, incident response, and enrichment.
4
 
5
## Threat Intelligence & Reputation
6
 
7
| Tool | Purpose |
8
|--------|--------|
9
| [FortiGuard](https://www.fortiguard.com/) | Threat intelligence and reputation data for domains, URLs, IPs, and signatures. Good for quick plausibility checks. |
10
| [Cisco Talos Intelligence](https://talosintelligence.com/) | Threat intelligence for IPs, domains, malware, and campaigns. Useful for IOC context and enrichment. |
11
| [AlienVault OTX](https://otx.alienvault.com/) | Community-driven threat intelligence with pulses and IOC context. Good for quick IP, domain, and hash lookups. |
12
| [ThreatBook](https://threatbook.io/) | CTI platform with IOC reputation and campaign information. |
13
| [AbuseIPDB](https://www.abuseipdb.com/) | Crowdsourced abuse reports for IP addresses. Always validate with additional sources. |
14
| [Spamhaus Reputation Checker](https://check.spamhaus.org/results/) | Checks whether an IP is listed on Spamhaus blocklists. |
15
| [Microsoft Defender Threat Intelligence](https://ti.defender.microsoft.com/) | Microsoft threat intelligence portal for IOC enrichment and hunting. |
16
 
17
## URL & Domain Analysis
18
 
19
| Tool | Purpose |
20
|--------|--------|
21
| [URLScan](https://urlscan.io/) | Browser-based URL scanning with screenshots, requests, certificates, and redirect chains. |
22
| [URLVoid](https://www.urlvoid.com/) | Domain and URL reputation across multiple engines. |
23
| [Host.io](https://host.io/) | Domain metadata, DNS data, and hosting information. |
24
| [DNSlytics](https://dnslytics.com/) | Reverse IP, DNS, WHOIS, MX, NS, and subdomain analysis. |
25
| [Whois.com](https://www.whois.com/whois/) | Domain and IP ownership information. |
26
 
27
## IP Intelligence & Geolocation
28
 
29
| Tool | Purpose |
30
|--------|--------|
31
| [IPVoid](https://www.ipvoid.com/) | IP reputation, blacklist checks, and DNS analysis. |
32
| [IPInfo](https://ipinfo.io/) | ASN, organization, geolocation, carrier, and privacy insights. |
33
| [DB-IP](https://db-ip.com/) | IP geolocation and ASN data. |
34
| [IPLocation](https://www.iplocation.net/) | Geolocation lookup using multiple providers. |
35
| [Scamalytics](https://scamalytics.com/) | Fraud and scam signals with risk scoring. |
36
| [IPQualityScore](https://www.ipqualityscore.com/vpn-ip-address-check) | Detects VPNs, proxies, Tor usage, and fraud indicators. |
37
| [Netify](https://www.netify.ai/resources/ips/) | IP categorization and network intelligence. |
38
| [AzureSpeed IP Lookup](https://www.azurespeed.com/Azure/IPLookup) | Identifies Azure-owned IPs and associated regions. |
39
 
40
## DNS & Email Analysis
41
 
42
| Tool | Purpose |
43
|--------|--------|
44
| [MXToolbox](https://mxtoolbox.com/) | DNS, MX, SPF, DKIM, DMARC, and blacklist checks. Useful for email investigations. |
45
 
46
## Microsoft Security & Azure
47
 
48
| Tool | Purpose |
49
|--------|--------|
50
| [Microsoft 365 Security Portal](https://security.microsoft.com/) | Central portal for Defender XDR, incidents, alerts, and hunting. |
51
| [Microsoft Entra Admin Center](https://entra.microsoft.com/) | Identity, application, and conditional access administration. |
52
| [Microsoft Online Error Lookup](https://login.microsoftonline.com/error) | Explains AADSTS and authentication-related errors. |
53
| [Azure Built-in Roles](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles) | Reference for Azure RBAC roles and permissions. |
54
| [MSPortals](https://msportals.io/) | Quick access to Microsoft portals and admin centers. |
55
 
56
## Vulnerability & Supply Chain Security
57
 
58
| Tool | Purpose |
59
|--------|--------|
60
| [Tenable CVE](https://www.tenable.com/cve) | CVE database with CVSS scores and references. |
61
| [Open Source Insights](https://deps.dev/) | Supply-chain and dependency risk analysis for open-source packages. |
62
 
63
## Investigation Utilities
64
 
65
| Tool | Purpose |
66
|--------|--------|
67
| [WhatIsMyBrowser User-Agent Parser](https://developers.whatismybrowser.com/useragents/parse/) | Converts user agents into readable browser and device information. |
68
| [UnixTimestamp](https://www.unixtimestamp.com/) | Epoch, UTC, and timezone conversions. |
69
| [Luftlinie](https://www.luftlinie.org/) | Distance calculator useful for travel and geo-plausibility checks. |
70
| [Apple Maps](https://maps.apple.com/) | Geographic lookups and location validation. |
71
 
72
## OSINT
73
 
74
| Tool | Purpose |
75
|--------|--------|
76
| [LinkedIn Feed](https://www.linkedin.com/feed/) | Research organizations, personnel, and professional context during investigations. |
77
 
78
---
79
 
80
### 💡 About
81
 
82
This repository serves as a personal knowledge base and quick-access toolbox for daily Security Operations (SecOps), cloud security investigations, threat hunting, and incident response activities.
