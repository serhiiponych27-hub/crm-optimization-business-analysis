CRM Sales Process Optimization
## Case Study Overview

This repository presents a **Business Analysis case study** focused on optimizing the sales process in a CRM system for a design and renovation company.

The project demonstrates a complete BA workflow:

- problem discovery  
- process redesign  
- requirements definition  
- CRM data model design  
- KPI framework  
- backlog management in Jira  
- implementation planning

The goal of the project was to transform a loosely used CRM into a **controlled and measurable sales management system**.

Business Analysis Case Study

CRM optimization project for a Design & Renovation company aimed at improving sales pipeline management, data quality, and revenue forecasting.

Project Overview

This project demonstrates how business analysis can improve sales operations by introducing structured pipelines, validation rules, automation, and analytics.

The case study covers the full BA lifecycle:
	•	business problem analysis
	•	AS-IS / TO-BE process design
	•	business rules definition
	•	functional requirements
	•	data model design
	•	KPI framework
	•	backlog management in Jira
	•	implementation roadmap

## Tools Used

The project uses typical tools from a modern Business Analysis workflow.

**Documentation**

- Confluence

**Backlog Management**

- Jira

**Process Modeling**

- BPMN diagrams (draw.io)

**Data Modeling**

- ER Diagram

**Reporting Design**

- KPI framework
- dashboard specification

**Version Control**

- GitHub

Business Context

The company provides turnkey interior design and renovation services.

Key characteristics:
	•	50–70 employees
	•	mixed sales model: inside + field sales
	•	client segments: B2B and B2C
	•	sales cycle:

Consultation → Estimation → Proposal → Contract

The CRM system is used by sales managers to track leads and opportunities.

Problem Statement

The CRM system is used formally and does not provide operational control.

Major issues:
	•	lack of pipeline discipline
	•	poor data quality
	•	unclear lead ownership
	•	inconsistent follow-up
	•	no structured loss analysis

Business consequences
	•	unreliable revenue forecast
	•	limited visibility into sales performance
	•	high risk of losing potential clients
	•	difficult scaling of the sales team

Project Goal

Improve sales process governance by introducing:
	•	standardized sales pipeline
	•	stage transition rules
	•	SLA monitoring
	•	KPI framework
	•	role-based access control
	•	structured reporting layer

Scope
In Scope
	•	Lead & Opportunity pipeline redesign
	•	automatic lead distribution
	•	stage transition validation rules
	•	required fields enforcement
	•	lost reason tracking
	•	deferred follow-up logic
	•	SLA monitoring
	•	KPI dashboards
	•	role-based access control

Out of Scope
	•	CRM platform replacement
	•	accounting processes
	•	production workflow
	•	design project management

Stakeholders

Primary stakeholders:
	•	Head of Sales
	•	Sales Managers

Secondary stakeholders:
	•	Accountant
	•	Designer
	•	Foreman

System owner:
	•	Director

Project sponsor:
	•	Business Owner

AS-IS Process

Before optimization, the sales workflow had several issues:
	•	manual lead creation
	•	duplicate records
	•	unclear ownership
	•	inconsistent stage usage
	•	no follow-up discipline
	•	no SLA monitoring
	•	no structured loss analysis

This resulted in poor visibility into the sales pipeline.

TO-BE Process

The optimized CRM process introduces automation and governance.
Main improvements:
	•	automatic lead creation from web channels
	•	duplicate detection
	•	automatic lead assignment
	•	stage validation rules
	•	SLA monitoring
	•	required lost reasons
	•	deferred follow-up logic
	•	KPI reporting

TO-BE Process Diagram

Sales Pipeline Structure

Lead Stages
	•	New
	•	Contacted
	•	Budget Not Confirmed
	•	Qualified
	•	Lost

Opportunity Stages
	•	Estimation in Progress
	•	Proposal Sent
	•	Deferred
	•	Won
	•	Lost

Business Rules

Key governance rules implemented in CRM:
	•	BR-01 Stage transition allowed only when required fields are filled
	•	BR-02 Lost stage requires selecting a reason
	•	BR-03 Lost reason “Other” requires comment
	•	BR-04 Deferred requires follow-up date
	•	BR-05 Ownership can be changed only by Head of Sales
	•	BR-06 SLA violation marks deal as Overdue


Functional Requirements

Examples of implemented system requirements:
	•	automatic lead creation from web channels
	•	duplicate detection by phone/email
	•	automatic ownership assignment
	•	lead → opportunity conversion
	•	required fields enforcement
	•	lost reason validation
	•	deferred follow-up scheduling
	•	SLA monitoring
	•	revenue tracking
	•	audit logging of key changes

User stories and backlog items were managed in Jira.


Jira Backlog
Backlog / Issue List
Workflow Board
Example User Story

Data Model

The CRM data model supports lead qualification, opportunity management, task tracking, and loss analysis.

Main entities:
	•	User
	•	Lead
	•	Opportunity
	•	Activity
	•	Task
	•	LostReason
	•	AuditLog

ER Diagram

KPI Framework

Key performance indicators used to monitor sales performance:
	•	Win Rate
	•	Conversion Rate by Stage
	•	Average Sales Cycle
	•	Overdue Deals
	•	Top Lost Reasons
	•	Performance per Manager
	•	Revenue Forecast

KPI Definition Table

Reporting Layer

Sales monitoring dashboards provide operational insights.

Dashboards include:
	•	Sales Pipeline Dashboard
	•	Sales Performance Dashboard
	•	Loss Analysis Dashboard

Reporting Layer Design

Role-Based Access Control

Access control model ensures secure data governance.

Sales Manager
	•	sees only own deals
	•	cannot change ownership

Head of Sales
	•	sees all deals
	•	can reassign ownership
	•	monitors KPIs and SLA

Director
	•	read-only access to analytics

Accountant
	•	read-only access to pipeline and final amounts

Implementation Roadmap

The solution is implemented in multiple phases.

1️⃣ Process Definition
2️⃣ CRM Configuration
3️⃣ Reporting Setup
4️⃣ Training & Rollout
5️⃣ Monitoring & Optimization

Implementation Plan

Expected Outcomes

The CRM optimization enables:
	•	improved conversion rates
	•	shorter sales cycle
	•	reduced lead loss
	•	transparent manager performance
	•	reliable revenue forecasting
	•	scalable sales operations
Key Business Analysis Deliverables

This project demonstrates the following BA artifacts:
	•	Business context analysis
	•	Problem definition
	•	AS-IS / TO-BE process modeling
	•	Business rules definition
	•	Functional requirements
	•	Role-based access design
	•	Data model design
	•	KPI framework
	•	Jira backlog management
	•	Implementation roadmap
  
