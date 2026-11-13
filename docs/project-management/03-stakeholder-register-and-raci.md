# Stakeholder Register & RACI Matrix

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Stakeholder Register & RACI Matrix |
| **Version** | 1.0 |
| **Date** | July 4, 2025 |
| **Status** | Approved for Execution |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Stakeholder Register

### 1.1 Core Project Team

| ID | Name | Role | Responsibilities | Influence | Interest | Engagement Approach |
| --- | --- | --- | --- | --- | --- | --- |
| S-01 | Maryam Abubakar | Team Lead | Direction, approvals, client presentations, final acceptance | High | High | Manage closely: reports and gate approvals |
| S-02 | Morenikeji Bankole | Associate Project Manager | Plan, ClickUp, reporting, risks, changes, stakeholder meetings | High | High | Owns plan, reporting and change control |
| S-03 | Amina | Business Analyst | Requirement gathering and initiation | Medium | High | Requirement sessions, sign-off on requirements |
| S-04 | AbdulAzeez Boyi | UI/UX Designer | Wireframes, prototypes, mockups for all roles | Medium | High | Design reviews before each client presentation |
| S-05 | Sadiq | Full Stack Developer | Web and mobile development, production deployment | High | High | Daily stand-up, direct task assignment |
| S-06 | AbdulSalam | Full Stack Developer | Web and mobile development, production deployment | High | High | Daily stand-up, direct task assignment |
| S-07 | Salisu | Mobile Developer | Mobile builds, store releases, bug fixing | Medium | High | Daily stand-up, release coordination |
| S-08 | Maryam (QA) | QA Engineer | Test cases, per-role QA, general testing, UAT | Medium | High | Test status in stand-up and reports |
| S-09 | Fatima | QA Engineer | Test cases, per-role QA, general testing, UAT | Medium | High | Test status in stand-up and reports |
| S-10 | Ibrahim | Team member | Role not recorded in the plan | Low | Medium | Kept informed through team updates |

### 1.2 External and Business Stakeholders

| ID | Stakeholder | Interest | Influence | Interest Level | Engagement Approach |
| --- | --- | --- | --- | --- | --- |
| S-11 | Client | Approves prototypes and builds for each role | High | High | Keep satisfied: eight scheduled presentations |
| S-12 | Customers (households) | Easy job posting, finding staff, subscriptions | Medium | High | Reflected in requirements and UAT scenarios |
| S-13 | Agents | Register service personnel and place them in jobs | Medium | High | Reflected in the agent flow and UAT scenarios |
| S-14 | Service personnel | Own profile, find and apply for jobs | Medium | High | Reflected in the service personnel flow and UAT scenarios |
| S-15 | Platform administrators | Oversight of users, jobs, subscriptions, support | Medium | High | Admin flow built first and presented first |
| S-16 | Apple and Google app stores | Store review and release | High | Low | Early submission planning (see [Release Plan](10-deployment-release-plan.md)) |

## 2. Power / Interest Grid

| | **Lower Interest** | **High Interest** |
| --- | --- | --- |
| **High Power** | Apple and Google stores (keep satisfied) | Client, Maryam Abubakar, Morenikeji Bankole, Sadiq, AbdulSalam (manage closely) |
| **Lower Power** | Ibrahim (monitor) | Amina, AbdulAzeez Boyi, Salisu, QA engineers, customers, agents, service personnel, administrators (keep informed) |

## 3. RACI Matrix

**R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed

| Activity | Maryam Abubakar | Morenikeji Bankole | Amina | AbdulAzeez Boyi | Sadiq / AbdulSalam | Salisu | Maryam (QA) / Fatima |
| --- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Scope and timeline | A | R | C | I | C | I | I |
| Requirement gathering | A | C | R | C | C | I | I |
| Design and prototypes | A | C | C | R | C | I | I |
| Web development | A | C | I | C | R | I | C |
| Mobile development | A | C | I | C | R | R | C |
| Test cases and scripts | I | A | C | I | C | I | R |
| Per-role QA | I | A | I | I | C | C | R |
| General testing and bug fixing | I | A | I | I | R | R | R |
| Client presentations | A / R | R | C | C | C | I | I |
| Risk register | I | A / R | C | I | C | C | C |
| Change control | A | R | C | C | C | C | C |
| Production deployment: web | A | C | I | I | R | I | C |
| Production deployment: mobile | A | C | I | I | C | R | C |
| User acceptance testing | A | R | C | I | C | C | R |
| Status reporting | I | A / R | I | I | C | C | C |
| Project closure | A | R | C | C | C | C | C |

## 4. Escalation Path

1. The task owner raises a blocker with the Associate Project Manager the same day.
2. The Associate Project Manager escalates to the Team Lead if a phase gate, client presentation or release date is at risk.
3. The Team Lead decides; the decision is recorded in the [Change Control Log](06-change-control-log.md) or [Risk Register](04-risk-register.md).

## 5. Related Documents

- [Communication Plan](05-communication-plan.md)
- [Work Breakdown Structure](02-work-breakdown-structure.md)
