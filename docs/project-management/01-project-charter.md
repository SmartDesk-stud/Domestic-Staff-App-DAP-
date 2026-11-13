# Project Charter: Domestic Staffing Platform

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Project Charter |
| **Version** | 1.0 |
| **Date** | July 1, 2025 |
| **Status** | Approved for Execution |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Project Overview & Metadata

| Project Detail | Information |
| --- | --- |
| **Project Name** | Domestic Staffing Platform (Domestic Staff App) |
| **Project Type** | New product build: web platform and mobile apps (iOS and Android) |
| **Team Lead** | Maryam Abubakar |
| **Associate Project Manager** | Morenikeji Bankole |
| **Methodology** | Hybrid (Agile + Waterfall): phase-based approvals with role-by-role incremental delivery |
| **Project Window** | July 1, 2025 – October 31, 2025 |
| **Delivery Channels** | Web application; mobile apps on the Apple App Store and Google Play Store |
| **Task Tracking** | ClickUp |
| **Document Status** | Approved for Execution |

## 2. Business Case & Executive Summary

Finding, vetting and placing domestic staff in Nigeria is largely informal and depends on word of mouth. The Domestic Staffing Platform digitizes that process. Customers post jobs and find staff, agents register and manage service personnel and apply for jobs on their behalf, service personnel manage their own profiles and jobs, and an administrator oversees the platform, subscriptions and support.

The project designs, builds, tests and releases the platform on web and mobile, with a separate experience for each of the four user roles, and prepares it for release to the public stores.

## 3. Project Objectives & Success Criteria

- **Four role-based experiences:** deliver Admin, Customer, Agent and Service Personnel journeys, each designed, built, tested and shown to the client in turn.
- **Web and mobile delivery:** release the web platform and mobile apps for the Customer, Service Personnel and Agent users.
- **Core marketplace flow:** customers can post jobs and find staff; agents and service personnel can view and apply for jobs; ratings and support are available to all relevant roles.
- **Monetization readiness:** subscription plans, billing history and Paystack payment flows are available to customers.
- **Quality gate before release:** all findings from web and app testing are triaged and closed, and User Acceptance Testing is passed before production release.
- **Client confidence:** each role's prototype and finished build is presented to the client and reviewed.

## 4. Project Scope

### In Scope

- **Authentication and onboarding:** registration, sign-in, password reset and profile management for each role.
- **Admin (web):** administration of users, jobs, subscriptions and support tickets.
- **Customer (web and mobile):** profile, post a job, manage jobs, find staff with bookmarks, subscriptions, billing history, support and referral.
- **Agent (web and mobile):** profile, add and manage service personnel (multi-step), view jobs and apply for jobs on behalf of a service personnel, dashboard, ratings, support and referral.
- **Service Personnel (web and mobile):** profile, job view and application, dashboard, support tickets and ratings.
- **Design:** wireframes, prototypes and high-fidelity mockups for all four roles.
- **Testing and release:** test cases and scripts, per-role QA, general integration testing, bug fixing, UAT and production deployment to web and both app stores.

### Out of Scope

- Features beyond the four role journeys above.
- Marketing and customer acquisition activity.
- Post-release feature roadmap (handled after project closure).

## 5. High-Level Timeline & Milestones

| Phase | Focus | Window |
| --- | --- | --- |
| **1** | Project scope: define scope and timeline | Jul 1 – Aug 1, 2025 |
| **2** | Requirement gathering: initiation and requirements | Jul 26 – Aug 4, 2025 |
| **3** | Design and prototyping: Admin, Customer, Agent, Service Personnel | Jul 29 – Aug 25, 2025 |
| **4** | Web development: Admin, Customer, Service Personnel, Agent | Jul 21 – Sep 24, 2025 |
| **5** | Mobile development: Customer, Service Personnel, Agent | Aug 4 – Sep 24, 2025 |
| **6** | Testing and QA: test cases, per-role QA, general testing, bug fixing | Jul 31 – Oct 13, 2025 |
| **7** | User acceptance testing and production deployment | Oct 16 – Oct 20, 2025 |
| – | Stabilization and closure | to Oct 31, 2025 |

Client presentations run alongside development: prototype reviews on Aug 11, Aug 18, Aug 25 and Sep 2, and build reviews on Aug 19, Sep 2, Sep 16 and Sep 30, 2025.

## 6. Project Governance & Key Stakeholders

| Role | Name | Responsibilities |
| --- | --- | --- |
| **Team Lead** | Maryam Abubakar | Direction, approvals, client presentations and acceptance |
| **Associate Project Manager** | Morenikeji Bankole | Scope, plan, ClickUp tracking, reporting, risk and change control |
| **Business Analyst** | Amina | Requirement gathering and project initiation |
| **UI/UX Designer** | AbdulAzeez Boyi | Wireframes, prototypes and high-fidelity mockups for all roles |
| **Full Stack Developers** | Sadiq, AbdulSalam | Web development for all roles; mobile development with the mobile developer |
| **Mobile Developer** | Salisu | Mobile builds, bug fixing and store releases |
| **QA Engineers** | Maryam (QA), Fatima | Test cases and scripts, per-role QA, general testing and UAT |
| **Team member** | Ibrahim | Team member (role not recorded in the plan) |

## 7. Key Deliverables

- **Project scope, roadmap and plan** with owners and dates.
- **Design package:** wireframes, prototypes and high-fidelity mockups for Admin, Customer, Agent and Service Personnel (web and mobile).
- **Web application** for all four roles.
- **Mobile apps** for Customer, Service Personnel and Agent users.
- **Test assets:** test cases, test scripts, bug log and UAT results.
- **Production releases** for the web platform and both app stores.
- **Client presentations** for each role (prototype and build).

## 8. Key Assumptions, Constraints & Risks

**Key Assumptions**

- The client is available for the scheduled prototype and build presentations.
- Store accounts and hosting access are ready before the release date.
- Paystack and subscription requirements are confirmed before the customer payment flow is built.

**Constraints**

- A fixed window of July 1 – October 31, 2025.
- Four roles built in overlapping streams by a small group of developers.
- Mobile releases depend on Apple and Google store review.

**Top Risks & Mitigation**

- *Role and permission leakage:* four roles share components, so one role may see another's menus or data. *Mitigation:* test each role flow separately and run a general integration pass.
- *Payment and subscription dependency:* customer billing depends on the Paystack flow being connected. *Mitigation:* track the integration as its own item and test it in general testing.
- *Overlapping delivery streams:* developers work on two roles at once. *Mitigation:* a four-step pipeline per role (design, build, QA, client presentation) with fixed gates.

## 9. Charter Approval & Sign-Off

| Stakeholder Role | Name | Signature | Date |
| --- | --- | --- | --- |
| Team Lead | Maryam Abubakar | _________________________ | _____ / _____ / 2025 |
| Associate Project Manager | Morenikeji Bankole | _________________________ | _____ / _____ / 2025 |
