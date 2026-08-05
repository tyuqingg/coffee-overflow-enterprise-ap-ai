# ☕ Coffee Overflow
# Enterprise Accounts Payable AI Employee

![Hackathon](https://img.shields.io/badge/Supervity-AI%20Hackathon%202026-blue)
![Round](https://img.shields.io/badge/Round-2-success)
![Platform](https://img.shields.io/badge/Built%20With-Supervity-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 🚧 Project Status

This project was developed for the **Supervity AI Hackathon 2026 – Round 2**.

It demonstrates an **Enterprise Accounts Payable AI Employee** that automates the invoice processing lifecycle using a multi-agent architecture. The solution integrates Microsoft Outlook, Supabase, Slack, and AI-powered decision-making to reduce manual effort while maintaining human oversight for high-risk financial transactions.

---

# 📌 Project Overview

Traditional Accounts Payable (AP) processes are often manual, repetitive, and time-consuming. Finance teams must extract invoice information, validate purchase orders, verify vendors, assess financial risks, obtain approvals, and notify stakeholders before payment can be processed.

Our solution transforms this workflow into an **Enterprise AI Employee** capable of autonomously processing invoices while enforcing business policies, enterprise governance, and human-in-the-loop approval for exceptional cases.

---

# 🎯 Objectives

Our Enterprise AP AI Employee aims to:

- Automate invoice processing from Outlook
- Reduce manual validation effort
- Improve invoice processing accuracy
- Detect duplicate and suspicious invoices
- Enforce enterprise approval policies
- Reduce financial and operational risks
- Improve auditability and compliance
- Enable intelligent decision-making using AI

---

# 🏗 Enterprise AI Architecture

```
                    Enterprise AP AI Employee
                              │
                              ▼
                  Invoice Intake Agent
                              │
                              ▼
                 PO Verification Agent
                              │
                              ▼
           Enterprise Risk Assessment Agent
                              │
                              ▼
                 AP Decision Agent
                              │
                              ▼
                   Human Workbench
                              │
                              ▼
                 Notification Agent
```

The AP AI Employee acts as an orchestrator, coordinating specialized AI agents throughout the entire invoice processing workflow.

---

# 🤖 Enterprise AI Agents

## 📥 Invoice Intake Agent

Responsible for intelligent invoice ingestion.

### Capabilities

- Monitor Outlook inbox
- Download invoice attachments
- AI-powered invoice extraction
- Extract SAP-aligned invoice fields
- Normalize enterprise data
- Mandatory field validation
- Duplicate invoice detection
- Extraction confidence scoring
- Audit metadata generation

---

## 📑 PO Verification Agent

Performs ERP validation against Supabase.

### Validation Checks

- Vendor verification
- Purchase Order verification
- Goods Receipt verification
- Currency validation
- Company Code validation
- Payment Terms validation
- Invoice tolerance checks
- Duplicate invoice detection
- Blocked vendor detection

Returns an Enterprise ERP Validation Score with detailed PASS/WARNING/FAIL results.

---

## 🛡 Enterprise Risk Assessment Agent

Evaluates invoices across multiple enterprise risk dimensions.

### Risk Categories

- Financial Risk
- Fraud Risk
- Vendor Risk
- Compliance Risk
- Payment Risk
- Operational Risk

Outputs:

- Enterprise Risk Score (0–100)
- Risk Level
- AI Explanation
- Business Impact
- Recommended Action

---

## ⚖ AP Decision Agent

Acts as the Enterprise AI Policy Engine.

Uses:

- ERP Validation
- Enterprise Risk Assessment
- Delegation of Authority (DOA)
- Enterprise Business Policies

Supports:

- ✅ Auto Approve
- 👨‍💼 Manual Review
- ❌ Auto Reject
- ⬆ Escalate to Manager
- 🏢 Escalate to Finance Director
- 📄 Request Supporting Documents

Every decision includes explainable AI reasoning and confidence scoring.

---

## 👨‍💼 Human Workbench

Supports enterprise human-in-the-loop decision making.

Finance reviewers can:

- Review AI recommendations
- View enterprise risk analysis
- Inspect ERP validation results
- Review supporting documents
- Add reviewer comments
- Approve invoices
- Reject invoices
- Escalate cases
- Override AI recommendations

All reviewer actions are recorded in the audit trail.

---

## 📢 Notification Agent

Automatically performs post-processing actions.

### Features

- Outlook notifications
- Slack notifications
- Case management
- Audit logging
- Database updates
- Execution summaries

Notifications are dynamically generated based on the final enterprise decision.

---

# 🔗 Enterprise Integrations

Our AI Employee integrates with:

- 📧 Microsoft Outlook
- 🗄 Supabase
- 💬 Slack
- 🤖 Gemini AI
- ⚙ Supervity AI Platform

---

# 📂 Enterprise Data Sources

The solution utilizes SAP-inspired enterprise datasets including:

- Vendor Master
- Purchase Orders
- Purchase Order Items
- Goods Receipts
- Invoice Records
- Bank Master
- FX Rates
- Pricing Conditions
- Approval Matrix (DOA)
- General Ledger Master

---

# 🧠 Enterprise AI Capabilities

- AI-powered Invoice Extraction
- ERP Validation
- Fraud Detection
- Enterprise Risk Assessment
- Policy-based Decision Making
- Explainable AI
- Human-in-the-loop Approval
- Intelligent Notifications
- Audit Trail Generation

---

# 📊 Business Benefits

Our Enterprise AP AI Employee helps organizations:

- Reduce manual invoice processing
- Improve processing accuracy
- Detect duplicate invoices
- Reduce fraud risks
- Improve financial governance
- Increase compliance
- Accelerate approval workflows
- Improve auditability
- Enhance operational efficiency

---

# 📸 Demonstration

The project demonstration showcases:

- Outlook invoice monitoring
- AI-powered invoice extraction
- ERP validation using Supabase
- Enterprise risk assessment
- AI-driven approval decisions
- Human Workbench
- Automated Slack notifications
- Automated Outlook notifications
- Audit trail generation

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| AI Platform | Supervity |
| AI Model | Gemini |
| Database | Supabase |
| Communication | Outlook, Slack |
| Language | Python |
| Workflow | Multi-Agent AI Architecture |

---

# 👥 Team Coffee Overflow ☕

| Member | Responsibilities |
|--------|------------------|
| **Tee Yu Qing** | Enterprise AI Workflow, AI Agent Design, Workflow Orchestration, Prompt Engineering, Human Workbench, AI Decision Logic |
| **Ding Yee Qing** | Supabase Database Design, Data Integration, ERP Validation, Backend Data Management |

---

# 📄 Repository Structure

```
coffee-overflow-enterprise-ap-ai
│
├── README.md
├── docs/
├── screenshots/
├── architecture/
├── prompts/
└── sample-data/
```

---

# 🚀 Future Enhancements

Potential future improvements include:

- SAP ERP Integration
- OCR Optimization
- Multi-language Invoice Support
- Predictive Cash Flow Analytics
- Vendor Performance Dashboard
- Payment Recommendation Engine
- AI Finance Copilot
- Real-time Fraud Intelligence

---

# 📜 License

This project was developed for the **Supervity AI Hackathon 2026** for educational and demonstration purposes.

---

## ⭐ Acknowledgements

Developed using the Supervity AI Platform as part of the Supervity AI Hackathon 2026.

Special thanks to the Supervity team for providing the platform, enterprise datasets, and hackathon environment.
