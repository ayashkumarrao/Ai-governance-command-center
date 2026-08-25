# 🤖 AI Governance Command Centre

An enterprise-style **AI Governance, Risk & Compliance dashboard** built using Microsoft Power BI.

The project provides a centralized view of an organization's AI portfolio, risk exposure, governance controls, compliance status, assessments, incidents, remediation activities, and ongoing monitoring.

---

## 📊 Project Overview

As organizations rapidly adopt Artificial Intelligence, traditional reporting approaches are not sufficient to understand the overall AI governance landscape.

The **AI Governance Command Centre** was designed to answer key governance questions:

- How many AI systems are currently in use?
- Which AI systems have high or critical risk?
- Are governance controls effective?
- Which AI systems have compliance gaps?
- How well does each AI system align with AI governance frameworks?
- Which assessments are overdue?
- Which remediation issues require immediate attention?
- Are deployed AI systems being continuously monitored?
- Which AI systems require management attention?

The solution brings these areas together into a single Power BI command centre.

---

# 🎯 Objectives

The primary objectives of this project are to:

1. Create a centralized AI inventory.
2. Assess AI risk across the enterprise.
3. Monitor inherent and residual risk.
4. Measure AI governance effectiveness.
5. Track AI control effectiveness.
6. Monitor compliance against multiple frameworks.
7. Track AI assessments and reviews.
8. Monitor incidents and remediation.
9. Track AI lifecycle stages.
10. Provide an AI 360° governance profile for individual AI systems.
11. Identify areas requiring management attention.

---

# 🏗️ Solution Architecture

```text
                    AI GOVERNANCE ECOSYSTEM
                             │
              ┌──────────────┴──────────────┐
              │                             │
        AI INVENTORY                   GOVERNANCE
              │                             │
              │                    ┌────────┼─────────┐
              │                    │        │         │
              │                  Risk    Controls  Compliance
              │                    │        │         │
              └──────────────┬─────┴────────┴─────────┘
                             │
                       DATA MODEL
                             │
                       POWER QUERY
                             │
                            DAX
                             │
                       POWER BI
                             │
              ┌──────────────┼──────────────┐
              │              │              │
           Executive        Risk        Compliance
          Command Centre   Analytics      Monitoring
              │              │              │
              └──────────────┼──────────────┘
                             │
                       AI 360° PROFILE
