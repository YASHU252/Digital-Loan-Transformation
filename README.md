Digital Loan Transformation — Business Analyst Portfolio Project
Date: January 2026
Tools Used: JIRA | Confluence | MS Word | Process Flow Design

Project Overview
This project simulates a real-world Business Analyst engagement for a retail bank's digital loan transformation initiative. The objective was to analyse the current manual loan application process, identify inefficiencies, and design a fully automated digital solution.
The project covers the complete BA delivery lifecycle — from requirements elicitation and stakeholder analysis to process mapping, Agile sprint planning, and full documentation.

Problem Statement
The bank's existing retail loan process was heavily manual, resulting in:

Average processing time of 8.4 days per application
47% SLA breach rate (against an 8-day SLA target)
15% data entry error rate from manual document handling
Redundant multi-level approval hierarchy causing bottlenecks
No real-time visibility for customers on application status


Business Objectives
ObjectiveTargetReduce avg processing time8.4 days → ≤ 5 days (BRD) / 4 hours (TO-BE)Reduce SLA breach rate47% → < 10%Reduce error rate15% → 2% (87% reduction)Reduce cost per application₹1,200 → ₹450 (60% reduction)Annual cost savings₹50 lakh projected

Key Metrics & Impact
MetricAS-IS (Current)TO-BE (Future)ImprovementProcessing Time5–7 days (120–168 hrs)4 hours94% reductionSLA Breach Rate47%< 10%37%+ improvementError Rate15%2%87% reductionCost per Application₹1,200₹45060% reductionAuto-Approval Rate0%60%New capability

Project Deliverables
1.  Business Requirements Document (BRD)
A 20-page BRD covering:

Executive summary and business problem statement
Current state (AS-IS) analysis with identified inefficiencies
Gap analysis and proposed future state
Stakeholder mapping across 6 groups (Operations, Risk, IT, Compliance, Branch, Business Leadership)
Assumptions, constraints, risks, and success criteria
Implementation roadmap

📁 View BRD

2. Functional Requirements Document (FRD)
Defines 15 functional requirements across 6 system modules:
ModuleRequirementsKYC AutomationFR-1 to FR-3Credit Bureau IntegrationFR-4 to FR-5Risk Segmentation EngineFR-6 to FR-8Approval WorkflowFR-9 to FR-11SLA MonitoringFR-12 to FR-13Reporting & DashboardFR-14 to FR-15
4 Non-Functional Requirements covering system response time (<3 seconds), 99% uptime, data privacy compliance, and role-based access control.
📁 View FRD

3. AS-IS Process Flow (Current State)
7-step manual process | Total time: 120–168 hours
Customer Branch Visit (30–60 min)
→ Manual Data Entry (2–3 hrs, 15% error rate)
→ Manual Document Verification (24–48 hrs)
→ Manual CIBIL Request (12–24 hrs)
→ Officer Credit Assessment (24–48 hrs)
→ Email/Phone Approval Workflow (24–48 hrs)
→ Manual Customer Communication (12–24 hrs)
Key bottlenecks identified:

Manual KYC verification: 2 days
Batch credit bureau checks: 1 day
Risk assessment backlog: 2–4 days
Redundant Branch + Regional Manager approval layers: 2 days

📁 View AS-IS Process Flow

4. TO-BE Process Flow (Future State)
6-step automated process | Total time: 4 hours average
Online Application + DigiLocker Auto-Validation (10 min)
→ Automated KYC via DigiLocker + Aadhaar API (2 min)
→ Real-time CIBIL Fetch + Business Rules Engine (5 min)
→ Auto-Approval (60%) OR Officer Queue (2 hrs)
→ Smart Workflow Routing by Risk/Amount (Real-time)
→ Instant SMS + Email Notification (<1 min)
📁 View TO-BE Process Flow

5. JIRA — Agile Sprint Planning
20 user stories | 3 sprints | 105 total story points
SprintStory PointsStoriesFocus AreaSprint 1377Customer-facing features, DigiLocker & CIBIL integrationSprint 2397Aadhaar auth, Core banking sync, Compliance audit trailSprint 3296Analytics, reporting, notifications
Sample User Stories from JIRA:

SCRUM-1: As a customer, I want to apply for a loan online so that I don't have to visit the branch
SCRUM-2: As a system, I want to integrate with DigiLocker API so that document verification is automated
SCRUM-3: As a credit officer, I want to view CIBIL score automatically so that I can make faster decisions
SCRUM-8: As a system, I want to integrate with Aadhaar authentication so that identity is verified instantly
SCRUM-10: As a compliance officer, I want audit trails of all actions so that we maintain regulatory compliance

📁 View JIRA Screenshots

6. Confluence — Project Knowledge Base
5 documents maintained in Confluence:
DocumentPurposeProject CharterProject scope, objectives, and authorizationRequirements Traceability Matrix (RTM)Maps requirements to user stories and test casesTechnical SpecificationsSystem integration specs for DigiLocker, CIBIL, Aadhaar APIsDecision LogRecords all key project decisions and rationaleMeeting Notes TemplateStandardised template for stakeholder meeting documentation
📁 View Confluence Screenshot

Stakeholder Map
StakeholderRole in ProjectOperations TeamProcess owner, primary requirements sourceRisk Management TeamRisk assessment workflow requirementsBranch ManagerApproval workflow requirementsRegional ManagerEscalation and oversight requirementsIT Development TeamTechnical feasibility and integrationCompliance & Audit TeamRegulatory and audit trail requirementsBusiness LeadershipProject sponsor, success criteria approval

Tools & Techniques Used
CategoryTool / TechniqueRequirementsBRD, FRD, User Stories, Acceptance CriteriaProcess MappingAS-IS / TO-BE, Gap Analysis, FlowchartsAgile DeliveryJIRA, Scrum, Sprint Planning, Backlog GroomingDocumentationConfluence, RTM, Decision LogAPI Integrations DocumentedDigiLocker, CIBIL, Aadhaar, Core Banking System

Repository Structure
Digital-Loan-Transformation/
│
├── README.md
├── documents/
│   ├── BRD_Digital_Loan_Transformation.pdf
│   ├── FRD_Digital_Loan_Transformation.pdf
│   ├── AS-IS_Process_Flow.pdf
│   └── TO-BE_Process_Flow.pdf
│
├── process-flows/
│   └── flowchart.png
│
└── screenshots/
    ├── JIRA_Backlog.png
    ├── JIRA_Sprint1.png
    ├── JIRA_Sprint2.png
    └── Confluence_Documentation.p

About
G Yasaswini | Aspiring Business Analyst 
yashaswini2519@gmail.com
🔗 LinkedIn-https://www.linkedin.com/in/g-yasaswini/

This is a portfolio project created to demonstrate Business Analyst skills including requirements gathering, process mapping, Agile delivery, and stakeholder documentation in a BFSI context.
