# Acme-Starters (Group G027) — Innovation, Sponsorship & Campaign Management Platform

Layered enterprise web application built in **Java** on top of **Acme Framework (26.3.0)** as a team project for *Design & Testing II (DP2)* at the University of Seville (ETSII).

## My Role: Project Manager & Lead Developer
- **Project Management:** Coordinated a 5-person development team (`G027`), led team chartering, milestone tracking, task allocation, and code reviews ([Chartering Report](reports/group/Chartering%20report.docx)).
- **Backend & Frontend Implementation (166 commits):** Built the **Inventor**, **Invention**, and **Part** verticals end-to-end—entities, business rules & constraints (unique ticker check, EUR-only validation, derived attributes `monthsActive` & `cost`), role-based authorization, JSP views, and i18n support.

## Architecture & Domain
- **Layered Architecture:** Presentation (Spring MVC + JSP/i18n) → Services → Persistence (JPA/Hibernate) → Domain Constraints & Security Realms.
- **User Roles & Modules:**
  - `Inventor`: Manage inventions, parts, and publication workflows.
  - `Fundraiser`: Define fundraising strategies and tactics.
  - `Spokesperson`: Run campaigns and track milestones.
  - `Sponsor`: Manage sponsorships and donations.
  - `Auditor`: Author audit reports and audit sections.

## Tech Stack
`Java` · `Spring MVC` · `JPA / Hibernate` · `Maven` · `JSP` · `Acme Framework`
