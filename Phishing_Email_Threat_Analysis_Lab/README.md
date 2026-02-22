# Enterprise Phishing Email Investigation & Threat Analysis Lab

## Overview

This project simulates a Tier 1 Security Operations Centre (SOC) investigation involving a reported phishing email received by an employee. The email claimed to originate from the Enterprise IT Support Team and requested an urgent password reset through an embedded hyperlink.

The purpose of this investigation was to assess the legitimacy of the reported email, identify potential Indicators of Compromise (IOCs), evaluate the associated business risk, and recommend appropriate mitigation actions based on the findings.

This project reflects common SOC analyst responsibilities including email header analysis, threat intelligence checks, IOC identification, severity assessment and incident documentation.

---

## Investigation Workflow

The following investigation steps were conducted as part of the incident response process:

- Email Header Analysis  
- Sender IP Reputation Check  
- Domain Registration Lookup (Whois)  
- URL Reputation Analysis  
- Indicator of Compromise (IOC) Identification  
- Threat Classification  
- Severity Assessment  
- Mitigation Recommendation  
- Incident Report Documentation  

---

## Tools Used

| Tool | Purpose |
|------|--------|
| MXToolbox | Email Header Analysis |
| VirusTotal | IP Reputation Check |
| Whois Lookup | Domain Registration Analysis |
| URLScan | URL Reputation Analysis |
| Microsoft Excel | IOC Documentation |

---

## Indicators of Compromise (IOCs)

The following IOCs were identified during the investigation:

- Sending IP Address: 93.184.216.34  
- Domain: example.com  
- Suspicious URL: https://example.com/reset-password  
- Sender Email Address: it-support@company-securemail.com  
- Email Subject: Urgent Password Reset Required  

---

## Threat Assessment

The reported email was determined to be a credential harvesting phishing attempt. The message contained urgency-based language and requested the recipient to reset their corporate password through an external link, which is a common tactic used in phishing campaigns.

Although no confirmed compromise was reported at the time of analysis, successful execution of this phishing attempt could result in unauthorized access to corporate systems, account takeover, data exfiltration and potential lateral movement within the enterprise network.

Based on the investigation findings, this incident was assessed as Medium severity.

---

## Recommended Mitigation Actions

1. Block the domain example.com at the enterprise web proxy or firewall level.  
2. Block the sender email address it-support@company-securemail.com.  
3. Advise affected users not to click on the provided link or disclose corporate credentials.  
4. Initiate organisation-wide phishing awareness reminders if required.  

---

## Investigation Evidence

### Email Header Analysis

![MXToolbox Header Analysis](Screenshots/Header_Analysis/MXToolbox_Header_Result.png)

---

### Sender IP Reputation Check – VirusTotal

![Sender IP Reputation](Screenshots/VirusTotal/Sender_IP_VirusTotal.png)

---

### Domain Registration Details

![Domain Whois Lookup](Screenshots/Whois/Domain_Whois.png)

---

### URL Analysis Attempt

URL analysis of the embedded hyperlink was attempted using URLScan.  
The scan was prevented by platform restrictions likely due to domain protection policies applied to reserved or high-reputation domains. This limitation has been documented as part of the investigation.

![URLScan Result](Screenshots/URLScan/URLScan_Result.png)

---

### IOC Documentation

![IOC Table](Screenshots/IOC_Table.png)

---

## SOC Incident Report

A detailed investigation report documenting the incident findings, threat assessment and recommended mitigation actions has been included in this repository.

Refer to the full report here:

SOC_Incident_Report/Phishing_Email_Investigation_Report.pdf
