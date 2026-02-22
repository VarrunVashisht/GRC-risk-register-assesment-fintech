# 🛡️ Risk Register (assesment) – Financial Services Environment

This project demonstrates a structured risk assessment using a qualitative methodology aligned with industry best practices (ISO 27005, NIST RMF concepts).

It simulates a financial services cloud environment hosted on AWS and walks through:

- Risk methodology design
- Risk identification
- Inherent risk scoring
- Risk heat map visualization

---

## 📁 Project Structure

04-risk-assessment/
│
├── risk-methodology.md
├── cloud-risk-register.xlsx
├── inherent-risk-analysis.md
├── risk-heat-map.png

---

## 🎯 Objectives

- Apply qualitative risk scoring (Likelihood × Impact)
- Identify realistic cloud security risks
- Evaluate existing controls
- Calculate residual risk
- Present executive-level analysis

---

## 🧠 Risk Scoring Model

Risk Score = Likelihood × Impact  
Scoring scale: 1 (Low) to 5 (High)

Risk Levels:
- 1–5 → Low
- 6–10 → Medium
- 11–15 → High
- 16–25 → Critical

---

## 🔥 Key Risks Identified

- Public S3 data exposure
- IAM privilege escalation
- Ransomware on EC2
- No MFA on admin accounts
- Misconfigured security groups
- CloudTrail disabled
- Backup failure
- DDoS attack
- Insider data export
- Third-party API compromise

---

## 📊 Executive Insight

The highest inherent risks were related to:

- Data exposure
- Identity compromise
- Logging failures
- Network misconfiguration

Given the financial services context, regulatory and reputational impacts significantly increase overall risk severity.

---

## 📈 Deliverables

- Structured risk methodology
- Professional risk register
- Inherent risk analysis
- Risk heat map visualization

---

## 👤 Author

Varrun  
Cyber Risk & GRC Portfolio Project  
