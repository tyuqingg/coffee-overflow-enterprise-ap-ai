# ☕ Coffee Overflow
# Enterprise Accounts Payable AI Employee

An Enterprise Accounts Payable (AP) AI Employee built with **Supervity** to automate invoice processing using AI-powered document extraction, ERP validation, enterprise risk assessment, intelligent decision-making, and automated notifications.

---

## 📌 Overview

Traditional Accounts Payable processes are often manual, repetitive, and prone to human error. Finance teams spend significant time validating invoices, checking purchase orders, reviewing vendor information, and obtaining approvals.

Our Enterprise AP AI Employee streamlines the entire invoice lifecycle by integrating AI with enterprise business rules to automate invoice processing while maintaining human oversight for high-risk transactions.

---

## 🚀 Key Features

### 📥 Invoice Intake Agent
- Monitors Outlook mailbox for incoming invoices
- Downloads invoice attachments automatically
- Extracts invoice information using AI
- Normalizes enterprise invoice data
- Performs mandatory field validation
- Calculates extraction confidence score

### 📑 PO Verification Agent
- Validates Vendor ID
- Verifies Purchase Order
- Checks Goods Receipt
- Detects duplicate invoices
- Validates payment terms
- Checks blocked vendors
- Performs ERP validation against Supabase

### 🛡 Enterprise Risk Assessment Agent
Evaluates multiple enterprise risks including:

- Financial Risk
- Fraud Risk
- Vendor Risk
- Compliance Risk
- Payment Risk
- Operational Risk

Generates an Enterprise Risk Score (0–100) with explainable AI reasoning.

### ⚖ AP Decision Agent
Applies enterprise business policies and DOA (Delegation of Authority) rules to determine:

- Auto Approve
- Manual Review
- Auto Reject
- Escalate to Manager
- Escalate to Finance Director
- Request Supporting Documents

### 👨‍💼 Human Workbench
Supports human-in-the-loop decision making by providing:

- AI recommendation
- Enterprise Risk Score
- Validation summary
- Supporting evidence
- Reviewer comments
- Approval history
- Audit trail

### 📢 Notification Agent
Automatically:

- Updates Supabase records
- Sends Outlook notifications
- Sends Slack notifications
- Records execution summaries
- Maintains audit logs

---

# 🏗 System Architecture

```
Outlook Inbox
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

---

# 🛠 Technology Stack

- Supervity AI
- Supabase
- Microsoft Outlook
- Slack
- Python
- Gemini AI
- SAP-inspired Enterprise Data Model

---

# 📂 Enterprise Data Sources

The solution utilizes enterprise datasets including:

- Vendor Master
- Purchase Orders
- Purchase Order Items
- Goods Receipts
- Invoice Records
- Bank Master
- FX Rates
- Approval Matrix (DOA)
- Pricing Conditions
- General Ledger Master

---

# 🤖 AI Capabilities

- Intelligent Invoice Extraction
- Enterprise Data Validation
- Fraud Detection
- Enterprise Risk Assessment
- Explainable AI Decisions
- Policy-based Approval Engine
- Human-in-the-loop Workflow
- Automated Notifications
- Audit Trail Generation

---

# 📊 Business Benefits

- Reduce manual invoice processing
- Improve invoice accuracy
- Detect duplicate invoices
- Reduce fraud risk
- Accelerate approval workflows
- Increase compliance
- Improve auditability
- Enhance financial governance

---

# 📸 Demo

The project demonstration showcases:

- Invoice ingestion from Outlook
- AI-powered invoice extraction
- ERP validation
- Enterprise risk scoring
- AI policy-based decision making
- Human review workflow
- Automated Slack & Outlook notifications

---

# 👥 Team

**Coffee Overflow ☕**

Developed as part of the Supervity AI Hackathon.

---

# 📄 License

This project was developed for educational and hackathon purposes.
