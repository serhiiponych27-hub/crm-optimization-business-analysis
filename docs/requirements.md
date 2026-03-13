# Requirements Specification

## Project Scope

The goal of the project is to improve CRM governance and sales pipeline management for a design and renovation company.

The project focuses on improving data quality, sales process discipline, and analytical capabilities of the CRM system.

---

# Scope

## In Scope

The following improvements are included in the project:

- redesign of Lead and Opportunity pipeline structure
- validation rules for stage transitions
- required field enforcement
- automatic lead assignment
- tracking of lost opportunity reasons
- SLA monitoring for follow-up activities
- KPI dashboard definitions
- role-based access control

## Out of Scope

The following areas are not included in the project:

- CRM platform migration
- marketing automation workflows
- financial accounting integration
- external reporting tools implementation

---

# Business Rules

BR-01  
Every Lead must have an assigned owner (sales manager).

BR-02  
A Lead cannot be converted to Opportunity without required contact information.

BR-03  
An Opportunity cannot move to the "Lost" stage without selecting a Lost Reason.

BR-04  
If the Lost Reason "Other" is selected, a comment must be provided.

BR-05  
Follow-up activities must be scheduled within the defined SLA period.

BR-06  
Each Opportunity must have at least one associated activity during active stages.

---

# Functional Requirements

## FR-01 Lead Creation

The system must allow creation of new Leads with the following required fields:

- client name
- contact phone or email
- source
- owner

Acceptance Criteria:

- Lead cannot be created without contact information
- Lead must automatically receive a creation timestamp

---

## FR-02 Lead Assignment

The system must automatically assign Leads to sales managers based on predefined rules.

Acceptance Criteria:

- Lead owner must be populated automatically
- assignment must be visible in the CRM activity log

---

## FR-03 Opportunity Creation

The system must allow conversion of a Lead into an Opportunity.

Acceptance Criteria:

- Opportunity must reference the originating Lead
- Opportunity owner must match Lead owner

---

## FR-04 Stage Transition Validation

The system must enforce validation rules when moving Opportunities between stages.

Acceptance Criteria:

- transition must be blocked if required fields are missing
- validation message must explain the reason

---

## FR-05 Lost Opportunity Tracking

The system must require selection of a Lost Reason when an Opportunity is marked as Lost.

Acceptance Criteria:

- Lost Reason must be selected from predefined list
- if "Other" is selected, comment field becomes mandatory

---

## FR-06 Activity Tracking

Sales managers must log activities related to Opportunities.

Acceptance Criteria:

- activities must be linked to an Opportunity
- activities must contain date and activity type

---

# Non-Functional Requirements

NFR-01  
CRM response time must remain under 2 seconds for standard operations.

NFR-02  
All stage changes must be logged in the audit log.

NFR-03  
Access to sensitive sales data must be restricted based on user roles.
