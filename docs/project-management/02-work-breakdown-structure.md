# Work Breakdown Structure (WBS)

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Work Breakdown Structure |
| **Version** | 1.0 |
| **Date** | July 4, 2025 |
| **Status** | Approved for Execution |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Purpose

This WBS breaks the Domestic Staffing Platform project into work packages that match the phases in the project plan. Each package has an owner, a window and a deliverable. The same structure is tracked in ClickUp.

## 2. WBS Hierarchy

```
1.0  Domestic Staffing Platform
├── 1.0  Project Scope                       (Phase 1)
├── 2.0  Requirement Gathering               (Phase 2)
├── 3.0  Design and Prototyping              (Phase 3)
├── 4.0  Web Development                     (Phase 4)
├── 5.0  Mobile Development                  (Phase 5)
├── 6.0  Testing and QA                      (Phase 6)
├── 7.0  User Acceptance and Deployment      (Phase 7)
├── 8.0  Client Presentations                (continuous)
└── 9.0  Project Management                  (continuous)
```

Each of the four user roles (Admin, Customer, Service Personnel, Agent) moves through the same pipeline: design, build, QA, then a client presentation.

## 3. WBS Dictionary

### 1.0 Project Scope (Jul 1 – Aug 1, 2025)

| WBS ID | Work Package | Owner | Deliverable |
| --- | --- | --- | --- |
| 1.1 | Define project scope and timeline | Maryam Abubakar, Morenikeji Bankole | Approved scope and project plan |

### 2.0 Requirement Gathering (Jul 26 – Aug 4, 2025)

| WBS ID | Work Package | Owner | Deliverable |
| --- | --- | --- | --- |
| 2.1 | Project initiation and requirement gathering | Amina, Maryam Abubakar | Requirements for the four user roles |

### 3.0 Design and Prototyping (Jul 29 – Aug 25, 2025)

| WBS ID | Work Package | Window | Owner |
| --- | --- | --- | --- |
| 3.1 | Wireframes, prototypes and mockups: Admin (mobile and web) | Jul 29 – Aug 4 | AbdulAzeez Boyi |
| 3.2 | Wireframes, prototypes and mockups: Customer (mobile and web) | Aug 4 – Aug 11 | AbdulAzeez Boyi |
| 3.3 | Wireframes, prototypes and mockups: Agent (mobile and web) | Aug 11 – Aug 18 | AbdulAzeez Boyi |
| 3.4 | Wireframes, prototypes and mockups: Service Personnel (mobile and web) | Aug 18 – Aug 25 | AbdulAzeez Boyi |

### 4.0 Web Development (Jul 21 – Sep 24, 2025)

| WBS ID | Work Package | Window | Owner |
| --- | --- | --- | --- |
| 4.1 | Admin user development | Jul 21 – Aug 13 | Sadiq, AbdulSalam |
| 4.2 | Customer user development | Aug 4 – Aug 27 | Sadiq, AbdulSalam |
| 4.3 | Service Personnel user development | Aug 18 – Sep 10 | Sadiq, AbdulSalam |
| 4.4 | Agent user development | Sep 1 – Sep 24 | Sadiq, AbdulSalam |

### 5.0 Mobile Development (Aug 4 – Sep 24, 2025)

| WBS ID | Work Package | Window | Owner |
| --- | --- | --- | --- |
| 5.1 | Customer mobile app | Aug 4 – Aug 27 | Sadiq, AbdulSalam |
| 5.2 | Service Personnel mobile app | Aug 18 – Sep 10 | Sadiq, AbdulSalam |
| 5.3 | Agent mobile app | Sep 1 – Sep 24 | Sadiq, AbdulSalam |

### 6.0 Testing and QA (Jul 31 – Oct 13, 2025)

| WBS ID | Work Package | Window | Owner |
| --- | --- | --- | --- |
| 6.1 | Test cases and test scripts | Jul 31 – Aug 12 | Maryam (QA), Fatima |
| 6.2 | QA web: Admin (unit and integration) | Aug 13 – Aug 15 | Maryam (QA), Fatima |
| 6.3 | QA web and app: Customer | Aug 27 – Aug 29 | Maryam (QA), Fatima |
| 6.4 | QA web and app: Service Personnel | Sep 10 – Sep 12 | Maryam (QA), Fatima |
| 6.5 | QA web and app: Agent | Sep 24 – Sep 26 | Maryam (QA), Fatima |
| 6.6 | General integration testing, web and app | Sep 29 – Oct 3 | Maryam (QA), Fatima |
| 6.7 | General bug fixing | Sep 29 – Oct 13 | Salisu, AbdulSalam, Sadiq, Maryam (QA), Fatima |

### 7.0 User Acceptance and Deployment (Oct 16 – Oct 20, 2025)

| WBS ID | Work Package | Window | Owner |
| --- | --- | --- | --- |
| 7.1 | Production deployment: web | Oct 16 | Sadiq, AbdulSalam |
| 7.2 | Production deployment: iOS and Android on the App Store and Play Store | Oct 16 | Salisu |
| 7.3 | User acceptance testing | Oct 17 – Oct 20 | Maryam (QA), Fatima |

### 8.0 Client Presentations (continuous)

| WBS ID | Work Package | Date |
| --- | --- | --- |
| 8.1 | Prototype presentations: Admin, Customer, Service Personnel, Agent | Aug 11, Aug 18, Aug 25, Sep 2 |
| 8.2 | Build presentations: Admin, Customer, Service Personnel, Agent | Aug 19, Sep 2, Sep 16, Sep 30 |

Owner for all presentations: Maryam Abubakar (Team Lead).

### 9.0 Project Management (continuous, Jul 1 – Oct 31, 2025)

| WBS ID | Work Package | Owner |
| --- | --- | --- |
| 9.1 | Plan, ClickUp tracking and reporting | Morenikeji Bankole |
| 9.2 | Risk and change control | Morenikeji Bankole |
| 9.3 | Stakeholder and client meetings | Morenikeji Bankole, Maryam Abubakar |
| 9.4 | Closure report and lessons learned | Morenikeji Bankole |

## 4. Assumptions

- The Customer, Service Personnel and Agent users have web and mobile versions; the Admin user is delivered on the web.
- Role streams overlap. A new role starts design or development while the previous role is in QA or client review.
- Findings from testing are managed through the [Defect Log](07-defect-log-summary.md) and the [Change Control Log](06-change-control-log.md).

## 5. Related Documents

- [Project Charter](01-project-charter.md)
- [Stakeholder Register & RACI](03-stakeholder-register-and-raci.md)
- [Sprint Plan & Reports](08-sprint-plan-and-reports.md)
