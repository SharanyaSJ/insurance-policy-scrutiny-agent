# 🚀 Insurance Policy Scrutiny AI Agent

🔥 Production-style AI system that analyzes insurance RFPs, quotes, and policy documents to detect deviations, hidden risks, and compliance gaps.

---

## 📌 Overview

This project simulates an end-to-end intelligent system that evaluates insurance policies against RFP requirements and identifies potential risks before final approval.

It transforms complex policy documents into structured, explainable decisions.

---

## 💡 Problem Statement

Organizations face major challenges while evaluating insurance policies:

* Manual comparison is time-consuming
* Hidden deviations go unnoticed
* Policy documents contain ambiguous clauses
* Risk exposure is often identified too late

---

## ✅ Solution

This project implements an AI-driven policy scrutiny system that:

* Extracts clauses from RFP documents
* Compares insurer quotes against requirements
* Performs three-way validation (RFP → Quote → Policy)
* Detects hidden deviations and policy “slip-ins”
* Classifies risks based on severity
* Generates decision-ready compliance reports

---

## ⚙️ System Pipeline

1. 📄 RFP Ingestion
   → Extracts structured clauses and requirements

2. 📊 Quote Analysis
   → Clause-by-clause comparison against RFP

3. 🔍 Policy Analysis
   → Three-way validation to detect drift and hidden changes

4. 🚨 Risk Detection
   → Identifies:

   * Missing clauses
   * Hidden conditions
   * Eligibility restrictions
   * Ambiguities

5. 🧾 Final Reporting
   → Generates verdict:

   * ACCEPT
   * REJECT
   * CONDITIONAL

---

## 📊 Sample Output

### 🏆 Dual-Insurer Compliance Report

* Reliance General → **ACCEPT (Low Risk)**
* Star Health → **REJECT (Critical Deviations)**

Key insights:

* 91.3% compliance vs 57.7%
* Critical deviations detected automatically
* Undeclared policy slip-ins identified

---

## 📥 Inputs

* `input/rfp.pdf` → RFP document
* `input/quote.pdf` → Insurer quote
* `input/policy.pdf` → Final policy

---

## 📤 Outputs

* `outputs/rfp_extraction.md`
* `outputs/quote_flags.md`
* `outputs/final_flags.md`
* `reports/compliance_report.md`

---

## 🧠 Key Features

* Multi-stage pipeline architecture
* Rule-based compliance engine
* Severity-based risk classification
* Policy deviation detection (5 types)
* Quote-to-policy consistency validation
* Explainable decision outputs

---

## 📈 Example Capabilities

* Detects hidden policy restrictions
* Identifies undeclared deviations
* Flags financial and operational risks
* Generates audit-ready reports
* Supports large-scale policy evaluation

---

## 🏗️ Project Structure

```
insurance-policy-scrutiny-agent/
│
├── input/
├── outputs/
├── data/
├── reports/
├── screenshots/
│
├── README.md
```

---

## 🚀 Future Improvements

* Add interactive UI (Streamlit)
* Integrate LLM for document understanding
* Deploy as API service
* Add real-time policy evaluation
* Enable multi-company scalability

---

## ⚠️ Note

All data used in this project is anonymized and created for demonstration purposes only.
No real client or company data is included.

---

## 💬 Summary

This project demonstrates the ability to design intelligent systems that combine:

* Business logic
* Risk analysis
* Document intelligence
* Decision automation

It reflects strong skills in system design, reasoning, and real-world AI application.

---
