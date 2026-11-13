# Project Closure Report & Lessons Learned

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Project Closure Report & Lessons Learned |
| **Version** | 1.0 |
| **Date** | October 31, 2025 |
| **Status** | Final – Project Closed |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Executive Summary

The Domestic Staffing Platform project ran from **July 1 to October 31, 2025** under a hybrid (Agile + Waterfall) approach. It delivered a web platform and mobile apps that connect customers, agents and service personnel, with an administrator overseeing the platform.

The team delivered four user roles (Admin, Customer, Service Personnel and Agent) in a staggered pipeline of design, build, QA and client presentation. Every planned phase in the project plan was completed. The web platform and the iOS and Android apps were released to production on October 16, 2025, and user acceptance testing was completed from October 17 to 20, 2025. The testing log recorded 40 findings, which were triaged, handled in a two-week bug-fixing window and closed at release.

## 2. Objectives and Outcomes

| Charter Objective | Outcome |
| --- | --- |
| Four role-based experiences | **Achieved.** Admin, Customer, Service Personnel and Agent journeys each designed, built, QA'd and presented to the client |
| Web and mobile delivery | **Achieved.** Web platform plus Customer, Service Personnel and Agent mobile apps released on Oct 16 |
| Core marketplace flow | **Achieved.** Job posting, find staff, applications, ratings and support covered in UAT |
| Monetization readiness | **Achieved.** Subscription plans, billing history and Pay Now flow linked and tested |
| Quality gate before release | **Achieved.** Findings triaged and closed; UAT completed |
| Client confidence | **Achieved.** All eight client presentations held on their scheduled dates |

## 3. Scope Delivery

| Scope Item | Delivered |
| --- | --- |
| Authentication, onboarding and profile management | Yes |
| Admin experience on web | Yes |
| Customer experience on web and mobile | Yes |
| Agent experience on web and mobile | Yes |
| Service Personnel experience on web and mobile | Yes |
| Design package for all four roles | Yes |
| Test assets and UAT | Yes |
| Production releases: web, App Store and Play Store | Yes |

## 4. Schedule Performance

| Phase | Planned | Actual | Variance |
| --- | --- | --- | --- |
| 1 – Project scope | Jul 1 – Aug 1 | Jul 1 – Aug 1 | On time |
| 2 – Requirement gathering | Jul 26 – Aug 4 | Jul 26 – Aug 4 | On time |
| 3 – Design and prototyping | Jul 29 – Aug 25 | Jul 29 – Aug 25 | On time |
| 4 – Web development | Jul 21 – Sep 24 | Jul 21 – Sep 24 | On time |
| 5 – Mobile development | Aug 4 – Sep 24 | Aug 4 – Sep 24 | On time |
| 6 – Testing and QA | Jul 31 – Oct 13 | Jul 31 – Oct 13 | On time |
| 7 – Release and UAT | Oct 16 – Oct 20 | Oct 16 – Oct 20 | On time |
| Stabilization and closure | to Oct 31 | to Oct 31 | On time |

## 5. Quality Performance

| Measure | Result |
| --- | --- |
| Findings logged | 40 |
| Distinct findings (excluding duplicates) | 38 |
| P1 findings | 16 |
| Open at closure | 0 |
| Change requests | 9 (8 approved, 1 approved in part) |
| UAT | All planned scenario groups passed |

Details: [Defect Log Summary](07-defect-log-summary.md), [Change Control Log](06-change-control-log.md) and [Test Plan & UAT Report](09-test-plan-and-uat-report.md).

## 6. Risks and Changes

| Item | Summary | Result |
| --- | --- | --- |
| R-01 Role and permission leakage | Evidenced by the service personnel findings | Fixed in hardening and retested |
| R-02 Payment dependency | Evidenced by customer subscription findings | Linked and retested before UAT |
| R-04 Wording and flow changes | Nine change requests from testing and client review | Decided and applied in the bug-fixing window |
| R-07 Registration and email handling | Evidenced by authentication findings | Fixed and retested |
| R-03, R-05, R-06, R-08 | No recorded impact | Closed |

Details: [Risk Register](04-risk-register.md).

## 7. Deliverables Acceptance

| Deliverable | Accepted By | Result |
| --- | --- | --- |
| Project scope, roadmap and plan | Maryam Abubakar | Accepted |
| Design package for all roles | Maryam Abubakar | Accepted |
| Web platform | Maryam Abubakar | Accepted |
| Mobile apps (iOS and Android) | Maryam Abubakar | Accepted |
| Test assets and UAT results | Maryam Abubakar | Accepted |

## 8. Lessons Learned

### 8.1 What Went Well

| # | Lesson | Evidence |
| --- | --- | --- |
| 1 | **A staggered pipeline per role** kept every stream busy and made issues visible one role at a time. | Four roles delivered in overlapping windows |
| 2 | **Fixed client presentation dates** forced a demo-ready build on a cadence. | Eight presentations on schedule |
| 3 | **One shared bug-fixing window** fixed shared components once for all roles. | Support and referral findings appeared in several flows |
| 4 | **Change control kept wording requests organised.** | Nine change requests logged and decided |
| 5 | **Top risks named early pointed testing at the right places.** | Role leakage and payments matched the largest finding clusters |

### 8.2 What Could Be Improved

| # | Lesson | Recommendation |
| --- | --- | --- |
| 1 | UAT ran after the production release date, so acceptance happened on the live system. | Schedule UAT before the release gate, and release after acceptance |
| 2 | Role rules (who can see or do what) surfaced as findings late in testing. | Write a role-and-permission matrix at design time and test it per role |
| 3 | The payment and subscription flow was a dependency on the Customer role, not just a screen. | Connect external services such as Paystack before that role's QA |
| 4 | The bug log recorded findings but had no priority, owner or status columns. | Add priority, owner, status and fix date to every finding from day one |
| 5 | Some wording decisions were agreed in chat and recorded later. | Record each decision in the change log on the day it is made |
| 6 | Per-role QA windows were short (two to three days). | Allow longer QA for roles with multi-step journeys such as Add Service Personnel |

### 8.3 Recommendations for the Next Release

- Start with the shared components (support, referral, ratings), then the role journeys.
- Use the role-and-permission matrix as the basis for test cases.
- Keep the staggered role pipeline and the fixed client presentation dates.
- Maintain a single, prioritised defect log with owners and status from the first test day.

## 9. Handover and Next Steps

| Item | Owner | Note |
| --- | --- | --- |
| Web platform and hosting | Sadiq, AbdulSalam | Handed to ongoing operations |
| Mobile apps and store accounts | Salisu | Handed to ongoing operations |
| Defect, risk and change records | Morenikeji Bankole | Archived in this repository |
| Post-release backlog | Maryam Abubakar | Input for the next release |

## 10. Closure Sign-Off

| Stakeholder Role | Name | Signature | Date |
| --- | --- | --- | --- |
| Team Lead | Maryam Abubakar | _________________________ | _____ / _____ / 2025 |
| Associate Project Manager | Morenikeji Bankole | _________________________ | _____ / _____ / 2025 |

## 11. Related Documents

All project artifacts are indexed in the [project management README](README.md).
