# crm-lead-to-trial-automation
Automated lead intake, enrichment, and trial follow-up using n8n and HubSpot to reduce manual CRM work and speed up sales response times.
crm-lead-to-trial-automation/
# CRM Lead-to-Trial Automation (n8n + HubSpot)

Automated lead routing system that captures inbound form submissions, enriches lead data, routes leads into HubSpot, and triggers automated trial follow-ups.

Built to reduce manual CRM work and improve response time for sales teams.

---

## 🔧 Tech Stack
- **n8n** – Workflow automation
- **HubSpot CRM** – Lead management & lifecycle tracking
- **Webhook Forms** – Inbound lead capture
- **Data Enrichment APIs** – Company & contact enrichment
- **Automated Email / Task Triggers** – Trial follow-ups

---

## 🚀 What This Automation Does

1. Captures inbound leads from web forms via webhook  
2. Enriches lead data (company, role, domain, etc.)
3. Applies tags and lifecycle stages in HubSpot
4. Routes leads to the correct pipeline or owner
5. Triggers automated trial follow-up sequences
6. Logs activity to reduce manual CRM touchpoints

---

## 🧠 Use Case

Sales and RevOps teams that need:
- Faster lead response times
- Cleaner CRM data
- Automated trial onboarding
- Reduced manual lead handling

---

## 📈 Impact
- Reduced manual CRM work
- Improved lead response time
- Consistent lead tagging and lifecycle management
- Better visibility into trial-stage conversions

---

## 🏗 Workflow Overview
See `/docs/architecture.md` for a step-by-step breakdown of the workflow logic.

---

## 📂 Files
- `/workflows/lead-to-trial-routing.json` – n8n workflow export
- `/examples/sample-form-payload.json` – Example inbound form data
- `/docs` – Setup and logic documentation

---

## ⚠️ Notes
- API keys and secrets are not included
- See `.env.example` for required environment variables

---

## 👤 Author
Built by Jordan  
Solutions Engineering · CRM Automation · RevOps
