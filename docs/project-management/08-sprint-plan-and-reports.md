# Sprint (Iteration) Plan & Reports

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Sprint (Iteration) Plan & Reports |
| **Version** | 2.0 (plan v1.0 issued July 7, 2025) |
| **Date** | October 20, 2025 (final report) |
| **Status** | Final – All Iterations Closed |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Delivery Approach

The project follows a hybrid model: phase-based approvals with agile, incremental delivery. The increments are the four **user roles**. Each role moves through the same four steps: design, build (web, and mobile where applicable), QA, then a client presentation. The roles are staggered so that the team is designing one role while building another and testing a third.

## 2. Iteration Calendar

| Iteration | Role | Scope | Window (2025) |
| --- | --- | --- | --- |
| 0 | Project set-up | Scope, timeline and requirements | Jul 1 – Aug 4 |
| 1 | Admin | Design, web build, QA, client review | Jul 21 – Aug 19 |
| 2 | Customer | Design, web and mobile build, QA, client review | Aug 4 – Sep 2 |
| 3 | Service Personnel | Design, web and mobile build, QA, client review | Aug 18 – Sep 16 |
| 4 | Agent | Design, web and mobile build, QA, client review | Aug 11 – Sep 30 |
| 5 | Hardening | General integration testing and general bug fixing | Sep 29 – Oct 13 |
| 6 | Release and acceptance | Production release and UAT | Oct 16 – Oct 20 |
| – | Stabilization | Monitoring and closure | to Oct 31 |

## 3. Iteration Plan (Planned Scope)

### Iteration 1 – Admin (Jul 21 – Aug 19)

| Step | Window | Owner |
| --- | --- | --- |
| Wireframes, prototype and mockups (mobile and web) | Jul 29 – Aug 4 | AbdulAzeez Boyi |
| Web build | Jul 21 – Aug 13 | Sadiq, AbdulSalam |
| Prototype presentation | Aug 11 | Maryam Abubakar |
| QA: unit and integration | Aug 13 – Aug 15 | Maryam (QA), Fatima |
| Build presentation | Aug 19 | Maryam Abubakar |

### Iteration 2 – Customer (Aug 4 – Sep 2)

| Step | Window | Owner |
| --- | --- | --- |
| Wireframes, prototype and mockups | Aug 4 – Aug 11 | AbdulAzeez Boyi |
| Web and mobile build | Aug 4 – Aug 27 | Sadiq, AbdulSalam |
| Prototype presentation | Aug 18 | Maryam Abubakar |
| QA: web and app | Aug 27 – Aug 29 | Maryam (QA), Fatima |
| Build presentation | Sep 2 | Maryam Abubakar |

### Iteration 3 – Service Personnel (Aug 18 – Sep 16)

| Step | Window | Owner |
| --- | --- | --- |
| Wireframes, prototype and mockups | Aug 18 – Aug 25 | AbdulAzeez Boyi |
| Web and mobile build | Aug 18 – Sep 10 | Sadiq, AbdulSalam |
| Prototype presentation | Aug 25 | Maryam Abubakar |
| QA: web and app | Sep 10 – Sep 12 | Maryam (QA), Fatima |
| Build presentation | Sep 16 | Maryam Abubakar |

### Iteration 4 – Agent (Aug 11 – Sep 30)

| Step | Window | Owner |
| --- | --- | --- |
| Wireframes, prototype and mockups | Aug 11 – Aug 18 | AbdulAzeez Boyi |
| Web and mobile build | Sep 1 – Sep 24 | Sadiq, AbdulSalam |
| Prototype presentation | Sep 2 | Maryam Abubakar |
| QA: web and app | Sep 24 – Sep 26 | Maryam (QA), Fatima |
| Build presentation | Sep 30 | Maryam Abubakar |

### Iteration 5 – Hardening (Sep 29 – Oct 13)

| Item | Window | Owner |
| --- | --- | --- |
| General integration testing, web and app | Sep 29 – Oct 3 | Maryam (QA), Fatima |
| General bug fixing | Sep 29 – Oct 13 | Salisu, AbdulSalam, Sadiq, Maryam (QA), Fatima |

### Iteration 6 – Release and Acceptance (Oct 16 – Oct 20)

| Item | Window | Owner |
| --- | --- | --- |
| Production release: web | Oct 16 | Sadiq, AbdulSalam |
| Production release: iOS and Android | Oct 16 | Salisu |
| User acceptance testing | Oct 17 – Oct 20 | Maryam (QA), Fatima |

## 4. Iteration Reports

### Iteration 0 Report – Project set-up (closed Aug 4)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Scope and timeline defined (Aug 1); requirements gathered (Aug 4); test cases and scripts under way |
| Carried over | None |

### Iteration 1 Report – Admin (closed Aug 19)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Design, web build, QA and both client presentations for the Admin role |
| Carried over | None |
| Retrospective | Starting the Admin build while its design was being finished let development begin early; the pattern was repeated for later roles |

### Iteration 2 Report – Customer (closed Sep 2)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Design, web and mobile build, QA and both client presentations for the Customer role |
| Carried over | Subscription, payment and billing history linking carried into general testing (see risk R-02 and CR-008) |
| Retrospective | The payment flow is a dependency, not a screen; it needs to be connected before QA, not after |

### Iteration 3 Report – Service Personnel (closed Sep 16)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Design, web and mobile build, QA and both client presentations for the Service Personnel role |
| Carried over | Role-rule findings (menus and profile context) handled in hardening (see CR-007) |
| Retrospective | Role rules should be listed per role at design time |

### Iteration 4 Report – Agent (closed Sep 30)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Design, web and mobile build, QA and both client presentations for the Agent role |
| Carried over | Wording and field changes in the Add Service Personnel journey, handled in hardening (see CR-003, CR-005, CR-009) |
| Retrospective | The three-step Add Service Personnel journey attracted the most review feedback of any single journey |

### Iteration 5 Report – Hardening (closed Oct 13)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | General integration testing and general bug fixing; the defect log was worked down |
| Carried over | None |
| Retrospective | A single, shared fix window for all roles removed duplicated effort on common components such as support and referral |

### Iteration 6 Report – Release and Acceptance (closed Oct 20)

| Measure | Result |
| --- | --- |
| Goal met | Yes |
| Completed | Web and mobile releases on Oct 16; UAT completed Oct 17 – 20 |
| Carried over | None |
| Retrospective | UAT ran after the release date; see the lessons in the [Project Closure Report](12-project-closure-report.md) |

## 5. Delivery Summary

All planned iterations were completed in the plan's windows and every client presentation took place on its scheduled date.

## 6. Related Documents

- [Defect Log Summary](07-defect-log-summary.md)
- [Status Reports](11-status-reports.md)
- [Work Breakdown Structure](02-work-breakdown-structure.md)
