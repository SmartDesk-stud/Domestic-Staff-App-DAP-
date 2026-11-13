# Defect Log Summary

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Defect Log Summary |
| **Version** | 1.0 |
| **Date** | October 20, 2025 (final status) |
| **Status** | Final – Findings Closed at Release |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Purpose

This document summarizes the findings logged during web and app testing of the Domestic Staffing Platform, how each was classified, and how the log was closed. Findings were recorded by the QA team and reviewers in the project plan's web bug log, grouped by user flow. The log covers four flows: landing page and authentication, agent, customer and service personnel.

## 2. Classification

| Type | Meaning |
| --- | --- |
| **Functional defect** | The feature does not work as intended |
| **Role / access rule** | A user role can see or do something it should not |
| **UX or content change** | Wording, labels or layout change requested by a reviewer |
| **Integration or linking** | A feature depends on a flow that was not yet connected (payments, subscriptions, referral link) |
| **Duplicate entry** | The same finding repeated in the log |

| Priority | Definition |
| --- | --- |
| **P1** | Blocks a core journey (sign-in, registration, profile, jobs, payment, support) or exposes the wrong role context |
| **P2** | Feature works with a workaround, or is a usability and wording improvement |
| **P3** | Cosmetic |

Priorities were assigned by the project manager at triage. The source log recorded findings but no priority.

## 3. Dashboard

| Metric | Value |
| --- | --- |
| Findings logged | 40 |
| Distinct findings (excluding duplicates) | 38 |
| P1 | 16 |
| P2 | 20 |
| P3 | 2 |
| Open at closure | 0 |

### 3.1 By flow

| Flow | Findings |
| --- | :-: |
| Landing page / authentication | 5 |
| Agent flow | 17 |
| Customer flow | 10 |
| Service personnel flow | 8 |

### 3.2 By type

| Type | Findings | IDs |
| --- | :-: | --- |
| Functional defect | 20 | L-01, L-02, L-03, L-04, L-05, A-02, A-04, A-07, A-08, A-11, A-12, A-16, C-01, C-02, C-05, C-06, S-03, S-04, S-07, S-08 |
| Role / access rule | 4 | S-01, S-02, S-05, S-06 |
| UX or content change | 9 | A-01, A-03, A-05, A-06, A-09, A-10, A-13, A-14, A-15 |
| Integration or linking | 5 | A-17, C-03, C-04, C-07, C-08 |
| Duplicate entry | 2 | C-09, C-10 |

## 4. Defect Register

| ID | Flow | Area | Summary | Type | Priority | Status |
| --- | --- | --- | --- | --- | :-: | --- |
| L-01 | Landing page / authentication | Password reset | Reset link takes about 5 minutes to arrive | Functional defect | P2 | Closed at release |
| L-02 | Landing page / authentication | Password reset | Account shown as deactivated after completing a reset | Functional defect | P1 | Closed at release |
| L-03 | Landing page / authentication | Registration | Registration with a second Gmail address on a different browser failed | Functional defect | P1 | Closed at release |
| L-04 | Landing page / authentication | Session | Inconsistent session timeout between accounts | Functional defect | P2 | Closed at release |
| L-05 | Landing page / authentication | Registration | One Gmail address could not register at all | Functional defect | P1 | Closed at release |
| A-01 | Agent flow | Profile | No area or city option on the agent profile | UX or content change | P2 | Closed at release |
| A-02 | Agent flow | Profile | Agent profile cannot be completed | Functional defect | P1 | Closed at release |
| A-03 | Agent flow | Add service personnel | No city option when adding a service personnel | UX or content change | P2 | Closed at release |
| A-04 | Agent flow | Add service personnel | Service personnel images missing at the top of step 2 | Functional defect | P2 | Closed at release |
| A-05 | Agent flow | Add service personnel | Language field should be "Languages I speak" with multiple selection | UX or content change | P2 | Closed at release |
| A-06 | Agent flow | Add service personnel | Accommodation options in step 3 need review | UX or content change | P2 | Closed at release |
| A-07 | Agent flow | Add service personnel | Email rejected as already taken in step 3 | Functional defect | P1 | Closed at release |
| A-08 | Agent flow | Add service personnel | Avatar must be uploaded again after each email correction | Functional defect | P2 | Closed at release |
| A-09 | Agent flow | Jobs | No way to view job details before applying for a service personnel | UX or content change | P2 | Closed at release |
| A-10 | Agent flow | Jobs | Job status labels should read Open and Closed | UX or content change | P2 | Closed at release |
| A-11 | Agent flow | Jobs | Agent cannot apply for a job on behalf of a service personnel | Functional defect | P1 | Closed at release |
| A-12 | Agent flow | Dashboard | Only the Started Jobs tab is clickable | Functional defect | P2 | Closed at release |
| A-13 | Agent flow | Rating | Rating prompt wording should address the customer rating | UX or content change | P2 | Closed at release |
| A-14 | Agent flow | Rating | Rating emojis should look more realistic | UX or content change | P3 | Closed at release |
| A-15 | Agent flow | Terminology | Change "job description" to "Role" across the platform | UX or content change | P2 | Closed at release |
| A-16 | Agent flow | Support | Contact support not working | Functional defect | P1 | Closed at release |
| A-17 | Agent flow | Referral | Refer a friend link not working | Integration or linking | P2 | Closed at release |
| C-01 | Customer flow | Profile | Customer profile cannot be updated | Functional defect | P1 | Closed at release |
| C-02 | Customer flow | Support | Contact support not working | Functional defect | P1 | Closed at release |
| C-03 | Customer flow | Referral | Refer a friend link not working | Integration or linking | P2 | Closed at release |
| C-04 | Customer flow | Manage jobs | New customer should be prompted to subscribe after posting a job | Integration or linking | P1 | Closed at release |
| C-05 | Customer flow | Find staff | Bookmark does not respond to clicks | Functional defect | P2 | Closed at release |
| C-06 | Customer flow | Post a job | Posted job does not appear in the Post a Job section | Functional defect | P1 | Closed at release |
| C-07 | Customer flow | Subscriptions | Subscription plans are not clickable and need a Pay Now page | Integration or linking | P1 | Closed at release |
| C-08 | Customer flow | Billing history | Billing history Details should reuse the Pay Now page | Integration or linking | P2 | Closed at release |
| C-09 | Customer flow | Referral | Refer a friend (repeat of C-03) | Duplicate entry | - | Closed (duplicate) |
| C-10 | Customer flow | Support | Contact support (repeat of C-02) | Duplicate entry | - | Closed (duplicate) |
| S-01 | Service personnel flow | Dashboard | Post a job should not appear on the service personnel dashboard | Role / access rule | P2 | Closed at release |
| S-02 | Service personnel flow | Dashboard | Find staff should not appear for a service personnel | Role / access rule | P2 | Closed at release |
| S-03 | Service personnel flow | Profile | Service personnel cannot view their own profile | Functional defect | P1 | Closed at release |
| S-04 | Service personnel flow | Support | Contact support opens the customer ticket page and switches identity to Customer | Functional defect | P1 | Closed at release |
| S-05 | Service personnel flow | Support | Open button in support history should be hidden for a service personnel | Role / access rule | P3 | Closed at release |
| S-06 | Service personnel flow | Support | Tickets should not be editable after sending | Role / access rule | P2 | Closed at release |
| S-07 | Service personnel flow | Support | No back navigation after contact support; dashboard returns 403 | Functional defect | P1 | Closed at release |
| S-08 | Service personnel flow | Role context | Only the dashboard shows the service personnel profile | Functional defect | P1 | Closed at release |

> Findings are recorded in the original reviewers' words in the project plan. IDs use a flow prefix: **L** landing page, **A** agent, **C** customer, **S** service personnel. Two customer entries (C-09, C-10) repeat C-03 and C-02, and contact support and referral appear in more than one role flow.

## 5. How the Log Was Worked

1. QA engineers and reviewers recorded each finding against its user flow during web and app testing.
2. The project manager triaged each finding: classification, priority and duplicates.
3. Wording and layout requests were raised as change requests (see the [Change Control Log](06-change-control-log.md)).
4. Functional and role-access findings were fixed during the **General Bug Fixing** window (September 29 – October 13, 2025) by the developers and QA engineers, and retested in **General Testing** (September 29 – October 3).
5. The log was closed at the User Acceptance Testing gate (October 17 – 20, 2025).

## 6. Analysis

- **Largest cluster:** the agent flow (17 findings), driven by the three-step Add Service Personnel journey, where profile data, images and email validation interacted.
- **Role context:** the service personnel flow showed a pattern: several screens carried the customer profile or customer menus. These are the most important findings, because they point to role-based access rather than single screens.
- **Payments and subscriptions:** customer subscription, Pay Now and billing history items depended on the Paystack and subscription flows being linked. They were tracked as integration findings rather than isolated bugs.
- **Repeated items:** contact support and referral appeared in the agent, customer and service personnel flows, which suggests shared components. Fixing them once covered every role.

## 7. Related Documents

- [Test Plan & UAT Report](09-test-plan-and-uat-report.md)
- [Change Control Log](06-change-control-log.md)
- [Risk Register](04-risk-register.md)
- [Project Closure Report](12-project-closure-report.md)
