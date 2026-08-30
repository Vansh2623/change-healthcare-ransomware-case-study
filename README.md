# Cyber-Incident-Analysis
A real-world cybersecurity case study

## Project Overview
This project is a real-world cybersecurity case study that analyzes a cyber incident and its impact on the affected organization. It examines the cause of the incident, the response taken by the organization, the effectiveness of that response, and the lessons and recommendations that emerged from the analysis.

## Objective
To analyze a real-world cybersecurity incident by identifying the root cause, analyzing the response, evaluating its timeliness and effectiveness, assessing its impact on the organization, and developing lessons learned and recommendations for future improvement.

## 📰 Case Study

### Name
The 2024 Change Healthcare Ransomware Attack 

### Introduction
In February 2024, Change Healthcare was hit by a massive ransomware attack launched by the cybercriminal group ALPHV/BlackCat. The hackers gained initial entry simply by using stolen passwords on a remote access account that lacked Multi-Factor Authentication (MFA).

Once inside, they moved freely through the network, stealing massive amounts of private patient data and freezing the company’s systems with malware. Because Change Healthcare handles roughly 15 billion medical billing transactions a year, the attack paralyzed pharmacies and doctors across the United States, leaving them unable to fill prescriptions or get paid for weeks.

This major breach shows how neglecting basic security steps like MFA can create a single point of failure that disrupts an entire industry supply chain.

### 📚 References

1. Farringer, D. R. (2026). *Cybersecurity risk shifting*. Vanderbilt Journal of Entertainment & Technology Law, 28(2), 49.  
   https://scholarship.law.vanderbilt.edu/jetlaw/vol28/iss2/2

2. Kanter, G. P., Rekowski, J. R., & Kannarkat, J. T. (2024). *Lessons from the Change Healthcare ransomware attack*. JAMA Health Forum, 5(9), e242764.

## 🔍 Case Study Analysis

### 🔎 Analysis Approach
The case study was analyzed from the initial compromise through the organization's response and recovery. The analysis focused on:

1. **Identifying the Root Cause** — Examining how compromised credentials and the absence of MFA enabled the attackers to gain initial access.

2. **Analyzing the Response** — Reviewing the containment and recovery actions taken by Change Healthcare, including network isolation and the involvement of external cybersecurity experts.

3. **Evaluating the Response** — Assessing the effectiveness and timeliness of the actions taken and identifying areas where the response could have been stronger.

4. **Assessing the Impact** — Examining the operational and wider healthcare impact caused by the disruption.

5. **Identifying Lessons & Recommendations** — Drawing key cybersecurity lessons from the incident and suggesting measures to strengthen security and improve future incident response.

### 💡 Key Findings
- **Weak authentication enabled the initial compromise:** The absence of Multi-Factor Authentication on a remote access portal allowed stolen credentials to be used as the entry point.

- **Network segmentation was a major weakness:** Once inside, the attackers were able to move through the network and reach sensitive systems, increasing the scale of the breach.

- **Containment was effective, but recovery was slow:** Isolating the network helped prevent further spread, while the involvement of external cybersecurity experts supported investigation and recovery. However, restoring normal operations took several weeks. :contentReference.
- **Business continuity was a significant gap:** The existing backup and recovery approach was not sufficient to maintain operations during a major disruption.

- **The impact extended beyond the organization:** The disruption affected healthcare providers and pharmacies, while the organization also faced major financial, legal, and reputational consequences. 

- **Resilience requires more than prevention:** The case highlighted the importance of strong identity controls, network segmentation, and independent fallback systems to reduce the impact of future incidents.

### 📚 What I Learned
This case study helped me understand how a single weakness in an organization's security controls can develop into a much larger cybersecurity incident.

- The importance of **Multi-Factor Authentication (MFA)** in protecting remote access points.
- How **network segmentation** can limit an attacker's ability to move through critical systems.
- The role of **incident response and containment** in reducing the spread and impact of ransomware.
- Why **backup, recovery, and business continuity plans** are essential when critical systems become unavailable.
- How cybersecurity incidents can create consequences beyond data loss, including **operational, financial, legal, and reputational impacts**.
- The importance of designing security controls and recovery processes with **resilience** in mind, rather than focusing only on preventing an attack.

### 🧠 Skills & Concepts Applied

- Cybersecurity Case Study Analysis
- Ransomware & Data Breach Analysis
- Threat Identification & Mitigation
- Root Cause Analysis
- Incident Response & Recovery
- Network Security & Segmentation
- Multi-Factor Authentication (MFA)
- Penetration Testing Concepts
- Point of Sale (PoS) Security
- Insider Threat Awareness
  
### 🔚 Conclusion

The Change Healthcare ransomware attack demonstrates how a weakness in a basic security control can lead to widespread consequences when it exists within a highly interconnected environment. The incident highlighted the importance of strong authentication, network segmentation, effective recovery planning, and resilient cybersecurity practices. An effective security strategy must not only focus on preventing attacks but also on limiting their spread and maintaining critical operations when an incident occurs.
