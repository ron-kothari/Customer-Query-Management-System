# Sapphire CQMS, Customer Query Management System

A simulated Business Analyst project covering the full lifecycle, from business problem to requirements, design, and Agile delivery, for a customer query management system.

## Table of Contents

- [About This Project](#about-this-project)
- [Business Problem](#business-problem)
- [Solution](#solution)
- [Key Features](#key-features)
- [System Architecture](#system-architecture)
- [User Roles](#user-roles)
- [Technology Stack](#technology-stack)
- [Project Documentation](#project-documentation)
- [Project Timeline](#project-timeline)
- [Project Scope](#project-scope)
- [Success Metrics](#success-metrics)
- [Tools Used](#tools-used)
- [Skills and Things I Learned](#skills-and-things-i-learned)

## About This Project

A full BA engagement for Sapphire CQMS, a customer query system built for a fictional company, Zenith.

**BA Skills Demonstrated**
- Business Requirements Document (BRD)
- Functional Requirements Document (FRD)
- Requirements Traceability Matrix (RTM)
- Software Lifecycle Process Flow (SLPF)
- Wireframes
- Epics, user stories, and acceptance criteria
- JIRA sprint management and Agile artifacts

## Business Problem

Zenith managed customer queries manually through Excel, causing:

- No centralized system for query management
- Difficult tracking of agent efficiency
- High risk of unresolved queries
- Slow response times with no SLA tracking
- Poor visibility into customer experience

## Solution

Sapphire fixes this with:

- Centralized ticket management
- IVR integration for automatic call routing
- Real time SLA tracking
- Smart service centre assignment by proximity
- SMS and WhatsApp notifications
- Reporting to track trends and recurring issues
- A 70 percent cut in response time

## Key Features

**Customer Service Agents**
- Secure role based login
- IVR integrated call reception
- Ticket creation and management
- Troubleshooting guide access

**Service Centres**
- Accept or decline assignments
- Update and close tickets
- Track SLA performance

**Team Leads**
- Monitor team performance
- Approve resolutions
- View SLA dashboards

**Administrators**
- Manage users and credentials
- Configure system settings
- Generate system wide reports

## System Architecture

1. Web application layer for all user roles
2. Application server for business logic
3. Database layer for customer, ticket, and user data
4. IVR integration layer for call routing
5. Notification gateway for SMS and WhatsApp
6. Authentication and authorization for secure access

## User Roles

| Role | Responsibilities | Access Level |
|---|---|---|
| Admin | User management, system configuration | Full access |
| Customer Service Agent | Handle calls, create tickets, troubleshoot | Operational access |
| Service Centre | Accept assignments, resolve issues | Service specific access |
| Team Lead | Approve resolutions, monitor performance | Team oversight access |

## Technology Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, React.js, JavaScript |
| Backend | RESTful API architecture |
| Database | Relational DBMS |
| Integration | IVR API, SMS gateway, WhatsApp Business API |
| Security | RBAC, password encryption, session management |

## Project Documentation

**Waterfall Documentation**
- BRD, FRD, RTM, SLPF
- UI wireframes

**Agile Documents and Artifacts**
- Agile artifacts in Excel, epics, user stories, acceptance criteria
- JIRA screenshots, sprint boards, backlog, burndown charts

## Project Timeline (Simulated)

| Phase | Duration | Status |
|---|---|---|
| Requirements Gathering | 4 weeks | Completed |
| Design and Architecture | 3 weeks | Completed |
| Development | 12 weeks | Simulated |
| Testing | 4 weeks | Simulated |
| UAT | 2 weeks | Simulated |
| Deployment | 1 week | Simulated |

## Project Scope

- Web based app with 4 user roles
- IVR call routing
- Ticket creation and SLA tracking
- SMS and WhatsApp notifications
- Support for 200 concurrent users

## Success Metrics

- 70 percent reduction in response time
- 100 percent query tracking
- 95 percent SLA compliance
- Improved agent efficiency through centralization

## Tools Used

- Excel for BRD, FRD, RTM, and Agile artifacts
- JIRA for sprint management
- Wireframing tools for UI design

## Skills and Things I Learned

- Writing a BRD that captures the real problem, not just the symptoms
- Translating business requirements into functional specs a dev team can build from
- Building a traceability matrix connecting requirements from source to delivery
- Mapping a full software lifecycle process flow
- Breaking a project into epics, user stories, and acceptance criteria
- Running sprint management in JIRA, including backlog and burndown tracking
- Defining clear project scope, including what is out of scope
