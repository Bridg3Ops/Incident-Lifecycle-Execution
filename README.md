# Incident Response Management Techniques

In this project, I applied practical incident response techniques aligned with the NIST framework, using real tools such as Splunk and OS Forensics. I explored detection, analysis, and forensic investigation methods by reviewing key playbooks, setting up monitoring for port scanning, and capturing forensic images for analysis.

## Tags
`Incident Response Playbooks` `Port Scanning` `Forensic Imaging` `NIST` `Splunk` `TA-winfw`

---


### Exercise 1: Reviewed Incident Response Playbooks
- Studied the **NIST SP 800-61 Rev.2** Incident Handling Guide to understand the lifecycle phases: Preparation, Detection, Containment, Eradication, Recovery, and Post-Incident Activity.
- Analyzed the **CISA Cybersecurity Incident & Vulnerability Response Playbook** to align with U.S. federal guidelines.
- Reviewed the **Microsoft Incident Response Playbooks** to understand real-world response flows and role-based coordination.

### Exercise 2: Port Scanning Detection with Splunk
- Installed and configured **Splunk Enterprise** on a Windows system.
- Set up the **Splunk Universal Forwarder** on an endpoint to collect logs.
- Installed the **TA-winfw** (Splunk add-on for Windows Firewall).
- Simulated a **port scan** using `nmap` from another system.
- Identified and visualized the scan patterns in Splunk using search queries and dashboards.

### Exercise 3: Forensic Imaging & Investigation
- Created a separate **data source partition** on a local drive for forensic analysis.
- Installed and used **OS Forensics** to:
  - Create a new investigation case
  - Acquire a full forensic image of the partition
  - Mount the image for file system and artifact analysis
- Captured hash values to ensure image integrity and explored mounted volumes for file evidence.

---

## Learning Outcomes

By the end of this module, I was able to:

- Review and compare industry-standard incident response playbooks (NIST, CISA, Microsoft)
- Detect and investigate port scanning activity using Splunk Enterprise and TA-winfw
- Prepare a data partition and perform forensic imaging with OS Forensics
- Mount and analyze forensic images while maintaining evidence integrity

---

## Tools & Technologies Used

- **Splunk Enterprise**  
- **Splunk Universal Forwarder**  
- **TA-Windows-Firewall (TA-winfw)**  
- **Nmap** (for simulating port scans)  
- **OS Forensics**  
- **Windows Event Viewer**  
- **CISA & NIST Guidelines**

---

