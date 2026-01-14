# Path to Incident Response Engineering: From Analysis to Automation

This repository serves as a technical portfolio and roadmap documenting my transition from a reactive **Cybersecurity Analyst** to a proactive **Incident Response Engineer**. 

My goal is to demonstrate a "Growth Mindset" by mastering cloud-native detection engineering, infrastructure hardening, and security automation within the Microsoft ecosystem.

## 📈 Technical Roadmap & Progress
I have organized my learning and projects into four distinct engineering pillars.

### Pillar 1: Detection Engineering (SIEM/EDR)
*Goal: Moving beyond built-in alerts to architecting custom detection logic.*
- [x] **Cross-Platform Logic:** Mapping Splunk (SPL) logic to Microsoft Sentinel (KQL).
- [x] **Behavioral Analytics:** Developing queries to detect lateral movement and credential dumping.
- [ ] **False Positive Reduction:** Engineering noise-reduction filters for high-volume telemetry.

### Pillar 2: Security Automation & Scripting
*Goal: Eliminating manual toil through Python and Bash.*
- [x] **Automated Triage:** Building scripts to collect host-level forensics (Processes, Network, Persistence).
- [x] **API Integration:** Interacting with security APIs (Qualys, CrowdStrike) to enrich alerts.
- [ ] **SOAR Orchestration:** Mapping Python logic into Azure Logic Apps for automated containment.

### Pillar 3: Identity & Cloud Hardening
*Goal: Implementing Zero Trust and Securing the Perimeter.*
- [x] **Entra ID (Azure AD):** Engineering Conditional Access policies for MFA enforcement.
- [x] **Lab Architecture:** Simulating On-Prem AD vs. Azure AD attack surfaces.
- [ ] **Governance:** Automating RBAC audits and privileged identity management (PIM) reviews.

### Pillar 4: Vulnerability Management
*Goal: Data-driven risk prioritization.*
- [x] **Scanning Operations:** Managing enterprise-scale vulnerability lifecycles in Qualys.
- [x] **Risk Scoring:** Developing logic to prioritize patches based on active exploit intelligence.

---

## 🛠 Featured Projects

### [01] Automated Forensics Collector (Python/Bash)
A suite of scripts designed to be executed during the "Identification" phase of Incident Response. It automates the collection of volatile memory data and system configurations to reduce Mean Time to Repair (MTTR).
* **Key Tech:** Python, `os`, `subprocess`, `platform` libraries.

### [02] Sentinel KQL Library
A collection of custom Kusto Query Language (KQL) hunting queries. 
* **Highlight:** "MFA Fatigue" detection logic designed to identify suspicious patterns in Entra ID Sign-in logs.

### [03] The Enterprise Lab
A documentation-heavy project where I built a mock enterprise environment to test attack/defend scenarios.
* **Focus:** GPO security, Service Account hardening, and Sentinel log ingestion.

---

## 📚 Certifications & Education
* **B.S. Information Science** | University of Illinois Urbana–Champaign
* **CompTIA Security+** | Validating foundational security principles.
* **Microsoft SC-200** | *In Progress* - Focusing on Security Operations.

## 📬 Contact & Links
- **LinkedIn:** [Your Link Here]
- **Email:** officialanthonykwok@gmail.com
