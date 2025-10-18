# Cyber-Attack-Analysis-Global-Bank
Incident response case study analyzing a major cyber attack on a global bank, including threat vector reconstruction and remediation strategy.
This project analyzes a simulated large-scale ransomware attack on a global financial institution. The attack combines file encryption with data exfiltration — a double extortion ransomware event — impacting core banking operations, regulatory compliance, and public trust.

# Incident Overview
# Attack Type	           Double Extortion Ransomware
Impacted Entity	       Global Financial Institution
Primary Threats	       Data Encryption + Data Theft
Business Impact	       Operational Shutdown, Financial Loss, Reputational Damage

# Key Objectives of Analysis
Identify attack type and threat characteristics
Assess CIA triad impact (Confidentiality, Integrity, Availability)
Perform impact assessment across legal, financial, and reputation domains
Recommend early detection, containment, and prevention strategies

# Core Analysis Breakdown
# Category	                Key Findings
# Attack Type	                Double Extortion Ransomware (Encryption + Data Theft)
CIA Impact	                - Confidentiality – Data stolen
                           - Integrity – Data corruption risk
                           - Availability – Systems locked                           
Operational Impact	       Bank service outage, halted transactions, branch closure
Financial Impact	         Estimated $10M–$100M in recovery, fines, compensation
Reputational Impact	       Global media coverage, trust collapse, regulatory scrutiny
Detection Gaps             No monitoring of abnormal data transfers or lateral movement

# Containment & Remediation Recommendations
# Immediate Response Actions
   Network Segmentation – Isolate infected zones
   Forced Credential Resets – MFA enforcement
  Emergency EDR Deployment – Block persistence methods

# Post-Incident Improvements
  Incident Timeline Analysis (Root Cause & Dwell Time)
  Zero Trust Architecture – Prevent future lateral movement
  Insider Threat & DLP Integration

# Tools & Techniques Referenced
SIEM Log Analysis (Splunk / QRadar)
Threat Intelligence Correlation
MITRE ATT&CK Mapping
CVSS Risk Scoring (Post-incident patching priorities)

# Outcome
This analysis produces an executive-level incident response strategy, including root-cause evaluation, board-level communication guidance, and strategic defensive transformations to prevent future ransomware events in critical infrastructure sectors such as banking.
