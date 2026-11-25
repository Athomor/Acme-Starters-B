# Acme-Starters (Group G027) — Innovation, Campaign & Sponsorship Platform

**Acme-Starters** is a multi-role enterprise web application for managing **inventions, components, fundraising strategies, campaigns, sponsorships, and audits**. Built on top of **Acme Framework (26.3.0)** by **Group G027** for *Design and Testing II (DP2 — 2025/2026)* at the University of Seville (ETSII).

> 📄 Team chartering and project organization documents are available in [`reports/group/Chartering report.docx`](reports/group/Chartering%20report.docx) and [`reports/00 - Identification Form.docx`](reports/00%20-%20Identification%20Form.docx).

---

## Key Features

- **Inventions & Parts (`inventor`):** Create, edit, delete, and publish inventions and modular parts with domain constraints (unique ticker verification, EUR currency validation) and derived metrics (`monthsActive`, `cost`).
- **Fundraising Strategies & Tactics (`fundraiser`):** Design and manage structured fundraising strategies and actionable tactics.
- **Campaigns & Milestones (`spokesperson`):** Manage promotional campaigns and track execution milestones.
- **Sponsorships & Donations (`sponsor`):** Handle financial sponsorships and donations linked to initiatives.
- **Audits (`auditor`):** Author structured audit reports and sections across platform entities.
- **Public & Authenticated Views (`any`, `authenticated`):** Public browsing of published items alongside role-based access control, user profile management, and internationalization (i18n).

---

## Architecture & Tech Stack

The project follows a strict **layered architecture** (`constraints`, `datatypes`, `entities`, `features`, `realms`) powered by **Acme Framework**:

- **Backend:** Java · Spring MVC · Spring Security / Realms · JPA / Hibernate · Maven (`war`)
- **Frontend:** JSP · Apache Tiles · JSTL · Internationalization (`i18n`)
- **Database:** MariaDB (`development`, `testing`, and `production` profiles)
- **Framework:** Acme Framework `26.3.0` (with built-in populator and task runners)

---

## My Role & Contributions

- **Project Manager (`Manager`):** Coordinated the 5-member team (`G027`), led team chartering, milestone planning, task distribution, and pull request reviews.
- **Lead Developer (`166` commits):** Implemented the **`Inventor`**, **`Invention`**, and **`Part`** verticals end-to-end—entities, business validations, derived attributes, role authorization checks, JSP views, i18n keys, and administrator configuration fixes.

---

## Quick Start

> ⚠️ Requires access to the `Acme-Framework` (`26.3.0`) parent Maven setup from the course environment.

1. Configure your MariaDB instances for development/testing as specified in `src/main/resources/platform-development.properties`.
2. Run the framework populator task (`task-populator.properties`) to initialize the schema and sample dataset.
3. Build and launch the web application with Maven / your IDE (`task-application.properties`).

---

## Team (Group G027 — DP2 2025/2026)

- Rares Nicolae Petre *(Project Manager, Analyst, Developer, Tester, Operator)*
- Jaime Díaz Villalba *(Analyst, Developer, Tester)*
- José Egido Carnerero *(Analyst, Developer, Tester)*
- Jesús Ramírez Martínez *(Analyst, Developer, Tester)*
- Francisco Manuel Sabido González *(Analyst, Developer, Tester)*
