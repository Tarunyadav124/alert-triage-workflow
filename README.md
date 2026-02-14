
# Alert Triage Workflow – Cloud Attack Simulation & Detection
This project demonstrates an **alert triage workflow** by simulating real-world cloud attacks and analyzing how security alerts are generated, collected, and investigated.

The setup uses **three machines**:
- **Attacker machine**
- **Cloud environment (AWS via LocalStack on Ubuntu)**
- **Wazuh SIEM for detection and alerting**

The goal is to show **attack → detection → alert triage → investigation**.

## Simulated Attacks
The following attack techniques were performed:

- IAM User Enumeration
- S3 Bucket Enumeration
- SSH Enumeration
- API Gateway Fuzzing

Each attack generates logs and alerts that are analyzed in Wazuh as part of the triage workflow.

---

## Alert Triage Workflow
1. Attack execution from attacker machine  
2. Log generation in cloud services / host  
3. Log ingestion into Wazuh  
4. Alert generation  
5. Alert analysis and triage  
6. Investigation and validation  

---


## 📊 Diagrams (Figma)
The following diagrams explain the system and workflow:
  See '/wireframes'
- Flow design Diagram  
- Dashboard overview  
- Response  

📎 **Figma Link:**  
https://www.figma.com/design/cmub4bValMuucomjewcNg1/FlowDesign?node-id=0-1&t=y9HMDJK5rOZVbObg-1
https://www.figma.com/design/miK1A8ZTIEUvrp9Xt4Qybs/DashboardOverview?t=y9HMDJK5rOZVbObg-1
https://www.figma.com/design/NNatuwRcX0ktcrS2J7TX2E/Response?t=y9HMDJK5rOZVbObg-1
---


---

## 📄 Write-up
- Attack methodology
- Tools used
- Alerts generated
- Triage and investigation steps

📂 See: `/writeup`

---

## 🧪 Proof of Concept (PoC)
Contains scripts, commands, and steps used to perform:
- Enumeration
- Fuzzing
- Attack validation

📂 See: `/poc`

---

## 📌 Proposal
- Objectives
- Scope of ideas implementation
- Expected outcomes

📂 See: `/proposal`

---

## Tools & Technologies
- AWS (LocalStack)
- Ubuntu
- Wazuh SIEM
- SSH
- API Gateway
- IAM & S3

---

## Disclaimer
This project is for **educational and defensive security research purposes only**.

