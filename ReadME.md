# Digital Loan Transformation — Business Analyst Portfolio Project

**Domain:** BFSI | Retail Banking | Digital Transformation  
**Role Simulated:** Business Analyst  
**Date:** 2025
**Tools Used:** JIRA | Confluence | MS Word | Process Flow Design  

---

## Project Overview

This project simulates a real-world Business Analyst engagement for a retail bank's digital loan transformation initiative. The objective was to analyse the current manual loan application process, identify inefficiencies, and design a fully automated digital solution.

The project covers the complete BA delivery lifecycle — from requirements elicitation and stakeholder analysis to process mapping, Agile sprint planning, and full documentation.

---

## Problem Statement

The bank's existing retail loan process was heavily manual, resulting in:

- Average processing time of **8.4 days** per application
- **47% SLA breach rate** against an 8-day SLA target
- **15% data entry error rate** from manual document handling
- Redundant multi-level approval hierarchy causing bottlenecks
- No real-time visibility for customers on application status

---

## Business Objectives

| Objective | Target |
| --- | --- |
| Reduce avg processing time | 8.4 days to 5 days (BRD) / 4 hours (TO-BE) |
| Reduce SLA breach rate | 47% to below 10% |
| Reduce error rate | 15% to 2% (87% reduction) |
| Reduce cost per application | Rs.1,200 to Rs.450 (60% reduction) |
| Annual cost savings | Rs.50 lakh projected |

---

## Key Metrics and Impact

| Metric | AS-IS (Current) | TO-BE (Future) | Improvement |
| --- | --- | --- | --- |
| Processing Time | 5-7 days (120-168 hrs) | 4 hours | 94% reduction |
| SLA Breach Rate | 47% | Below 10% | 37%+ improvement |
| Error Rate | 15% | 2% | 87% reduction |
| Cost per Application | Rs.1,200 | Rs.450 | 60% reduction |
| Auto-Approval Rate | 0% | 60% | New capability |

---

## Project Deliverables

### 1. Business Requirements Document (BRD)

A 20-page BRD covering:

- Executive summary and business problem statement
- Current state (AS-IS) analysis with identified inefficiencies
- Gap analysis and proposed future state
- Stakeholder mapping across 6 groups: Operations, Risk, IT, Compliance, Branch, Business Leadership
- Assumptions, constraints, risks, and success criteria
- Implementation roadmap

[View BRD](documents/BRD_Digital_Loan_Transformation.pdf)

---

### 2. Functional Requirements Document (FRD)

Defines 15 functional requirements across 6 system modules:

| Module | Requirements |
| --- | --- |
| KYC Automation | FR-1 to FR-3 |
| Credit Bureau Integration | FR-4 to FR-5 |
| Risk Segmentation Engine | FR-6 to FR-8 |
| Approval Workflow | FR-9 to FR-11 |
| SLA Monitoring | FR-12 to FR-13 |
| Reporting and Dashboard | FR-14 to FR-15 |

4 Non-Functional Requirements covering system response time (under 3 seconds), 99% uptime, data privacy compliance, and role-based access control.

[View FRD](documents/FRD_Digital_Loan_Transformation.pdf)

---

### 3. AS-IS Process Flow (Current State)

7-step manual process | Total time: 120-168 hours

```
Customer Branch Visit (30-60 min)
  -> Manual Data Entry (2-3 hrs, 15% error rate)
  -> Manual Document Verification (24-48 hrs)
  -> Manual CIBIL Request (12-24 hrs)
  -> Officer Credit Assessment (24-48 hrs)
  -> Email/Phone Approval Workflow (24-48 hrs)
  -> Manual Customer Communication (12-24 hrs)
```

Key bottlenecks identified:

- Manual KYC verification: 2 days
- Batch credit bureau checks: 1 day
- Risk assessment backlog: 2-4 days
- Redundant Branch and Regional Manager approval layers: 2 days

[View AS-IS Process Flow](documents/AS-IS_Process_Flow.pdf)

---

### 4. TO-BE Process Flow (Future State)

6-step automated process | Total time: 4 hours average

```
Online Application + DigiLocker Auto-Validation (10 min)
  -> Automated KYC via DigiLocker + Aadhaar API (2 min)
  -> Real-time CIBIL Fetch + Business Rules Engine (5 min)
  -> Auto-Approval (60%) OR Officer Queue (2 hrs)
  -> Smart Workflow Routing by Risk/Amount (Real-time)
  -> Instant SMS + Email Notification (under 1 min)
```

[View TO-BE Process Flow](documents/TO-BE_Process_Flow.pdf)

---

### 5. JIRA — Agile Sprint Planning

20 user stories | 3 sprints | 105 total story points

| Sprint | Story Points | Stories | Focus Area |
| --- | --- | --- | --- |
| Sprint 1 | 37 | 7 | Customer-facing features, DigiLocker and CIBIL integration |
| Sprint 2 | 39 | 7 | Aadhaar auth, Core banking sync, Compliance audit trail |
| Sprint 3 | 29 | 6 | Analytics, reporting, notifications |

Sample User Stories from JIRA:

- SCRUM-1: As a customer, I want to apply for a loan online so that I don't have to visit the branch
- SCRUM-2: As a system, I want to integrate with DigiLocker API so that document verification is automated
- SCRUM-3: As a credit officer, I want to view CIBIL score automatically so that I can make faster decisions
- SCRUM-8: As a system, I want to integrate with Aadhaar authentication so that identity is verified instantly
- SCRUM-10: As a compliance officer, I want audit trails of all actions so that we maintain regulatory compliance

[View JIRA Screenshots](screenshots/)

---

### 6. Confluence — Project Knowledge Base

5 documents maintained in Confluence:

| Document | Purpose |
| --- | --- |
| Project Charter | Project scope, objectives, and authorization |
| Requirements Traceability Matrix (RTM) | Maps requirements to user stories and test cases |
| Technical Specifications | System integration specs for DigiLocker, CIBIL, Aadhaar APIs |
| Decision Log | Records all key project decisions and rationale |
| Meeting Notes Template | Standardised template for stakeholder meeting documentation |

[View Confluence Screenshot](screenshots/Confluence_Documentation.png)

---

## Stakeholder Map

| Stakeholder | Role in Project |
| --- | --- |
| Operations Team | Process owner, primary requirements source |
| Risk Management Team | Risk assessment workflow requirements |
| Branch Manager | Approval workflow requirements |
| Regional Manager | Escalation and oversight requirements |
| IT Development Team | Technical feasibility and integration |
| Compliance and Audit Team | Regulatory and audit trail requirements |
| Business Leadership | Project sponsor, success criteria approval |

---

## Tools and Techniques Used

| Category | Tool / Technique |
| --- | --- |
| Requirements | BRD, FRD, User Stories, Acceptance Criteria |
| Process Mapping | AS-IS / TO-BE, Gap Analysis, Flowcharts |
| Agile Delivery | JIRA, Scrum, Sprint Planning, Backlog Grooming |
| Documentation | Confluence, RTM, Decision Log |
| API Integrations Documented | DigiLocker, CIBIL, Aadhaar, Core Banking System |

---

## Repository Structure

```
Digital-Loan-Transformation/
|
|-- README.md
|-- documents/
|   |-- BRD_Digital_Loan_Transformation.pdf
|   |-- FRD_Digital_Loan_Transformation.pdf
|   |-- AS-IS_Process_Flow.pdf
|   |-- TO-BE_Process_Flow.pdf
|
|-- process-flows/
|   |-- flowchart.png
|
|-- screenshots/
    |-- JIRA_Backlog.png
    |-- JIRA_Sprint1.png
    |-- JIRA_Sprint2.png
    |-- Confluence_Documentation.png
```

---

## About

**G Yasaswini** |
yashaswini2519@gmail.com  
[LinkedIn](https://www.linkedin.com/in/g-yasaswini/)

This is a portfolio project created to demonstrate Business Analyst skills including requirements gathering, process mapping, Agile delivery, and stakeholder documentation in a BFSI context.
