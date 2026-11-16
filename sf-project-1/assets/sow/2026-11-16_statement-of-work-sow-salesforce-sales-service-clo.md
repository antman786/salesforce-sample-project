# Statement of Work (SOW): Salesforce Sales & Service Cloud Implementation

**Project Name:** Project Horizon – CRM Transformation

**Client:** Vanguard Logistics & Supply Co. ("Client")

**Vendor:** Apex Cloud Partners LLC ("Consultant")

**Effective Date:** November 16, 2026

**SOW Version:** 1.0

---

## 1. Executive Summary & Objectives

Vanguard Logistics & Supply Co. ("Client") has engaged Apex Cloud Partners LLC ("Consultant") to implement Salesforce Sales Cloud and Service Cloud. The objective is to replace fragmented legacy spreadsheets and an outdated ticketing system with a unified Customer Relationship Management (CRM) platform.

**Primary Business Objectives:**

* Centralize account, contact, and opportunity data for 45 sales representatives.
* Automate lead routing and quote-to-close approval workflows.
* Deploy Service Cloud (Email-to-Case and Web-to-Case) for a 20-agent customer support team.
* Provide executive leadership with real-time pipeline visibility and SLA compliance dashboards.

---

## 2. Scope of Work

### 2.1 In-Scope Deliverables

| Workstream | Key Deliverables |
| --- | --- |
| **Core Platform & Security** | Org setup, Role Hierarchy, Profiles, Permission Sets, Organization-Wide Defaults (OWD), and Sharing Rules for 65 total users. |
| **Sales Cloud** | Configuration of Leads, Accounts, Contacts, Opportunities, and Products/Pricebooks (1 standard pricebook). Automated lead assignment rules and 1 multi-step discount approval flow. |
| **Service Cloud** | Configuration of Cases, Entitlements/Milestones (2 SLA tiers), Email-to-Case (up to 3 support addresses), and 1 Web-to-Case form. |
| **Automation** | Up to 8 Record-Triggered Flows covering lead conversion, opportunity stage alerts, and case escalation. |
| **Data Migration** | Cleansing, mapping, and loading of active Accounts, Contacts, Open Opportunities, and past 12 months of closed Cases from legacy CSV exports. |
| **Reporting & Analytics** | Up to 12 custom reports and 2 executive dashboards (Sales Pipeline & Support Operations). |
| **Enablement & Go-Live** | Train-the-Trainer documentation, 2 live virtual training sessions (Sales & Service), UAT support, and 2 weeks of post-go-live Hypercare. |

### 2.2 Out-of-Scope

* Custom Apex triggers, Lightning Web Components (LWCs), or Visualforce pages.
* Bidirectional ERP or WMS (Warehouse Management System) API integrations.
* Salesforce CPQ, Marketing Cloud, or Experience Cloud portals.
* Historical data migration older than 12 months for Cases or Closed/Lost Opportunities.

---

## 3. Project Timeline & Milestones

The estimated duration of this engagement is **10 Weeks** from the Project Kick-off date.

| Phase | Timeline | Key Milestone / Exit Criteria |
| --- | --- | --- |
| **1. Discover & Design** | Weeks 1–2 | Kick-off completed; Discovery workshops held; Solution Design Document (SDD) signed off. |
| **2. Build & Configure** | Weeks 3–6 | Iterative sprint demos (Weeks 4 & 6); Core Sales/Service configuration and Flows complete in Sandbox. |
| **3. Data & UAT** | Weeks 7–8 | Test data loaded into Full/Partial Sandbox; UAT test scripts executed; UAT sign-off obtained. |
| **4. Train & Deploy** | Week 9 | End-user training delivered; Production deployment completed; Cutover data migration verified. |
| **5. Hypercare** | Weeks 10–11 | Post-go-live support, minor bug fixes, and formal project handover to Client System Admin. |

---

## 4. Roles & Responsibilities

### Consultant Team

* **Engagement Manager (Sarah Jenkins):** Overall project governance, budget, timeline, and escalations.
* **Lead Solution Architect (Marcus Vance):** Technical architecture, data model, security, and discovery lead.
* **Senior Salesforce Consultant (Priya Nair):** Hands-on configuration, Flows, data migration, and training.

### Client Team

* **Executive Sponsor (David Thorne, VP of Operations):** Final sign-off authority on scope, budget, and SDD.
* **Product Owner / Project Lead (Elena Rostova, Director of Revenue Operations):** Day-to-day decision-maker, UAT coordinator, and SME facilitator.
* **Salesforce System Administrator (Liam O'Connor):** Technical counterpart, data extraction owner, and post-go-live admin.

---

## 5. Commercials & Payment Schedule

**Fee Structure:** Fixed Fee of **$68,000 USD** (excludes Salesforce licensing fees).

* **Milestone 1 (30% - $20,400):** Due upon SOW execution.
* **Milestone 2 (30% - $20,400):** Due upon Solution Design Document (SDD) sign-off (End of Week 2).
* **Milestone 3 (25% - $17,000):** Due upon UAT sign-off (End of Week 8).
* **Milestone 4 (15% - $10,200):** Due upon Production Go-Live (End of Week 9).

---

## 6. Assumptions & Change Control

1. Client will provide clean, deduplicated CSV exports for data migration no later than Week 5.
2. Client stakeholders will commit 4–6 hours per week during Discovery and UAT phases.
3. Any requests falling outside Section 2.1 will be evaluated via a formal Change Request (CR) detailing schedule and cost impacts.

---

