# Test Plan & UAT Report

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Test Plan & User Acceptance Testing (UAT) Report |
| **Version** | 2.0 (test plan v1.0 issued July 28, 2025) |
| **Date** | October 20, 2025 (UAT report) |
| **Status** | Final – UAT Completed |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

# Part A – Test Plan

## 1. Objectives

- Confirm that each user role's journeys work on web and on mobile.
- Confirm that roles see only the menus, data and actions that belong to them.
- Confirm that registration, sign-in, password reset and profile management work for every role.
- Confirm that the customer subscription, Pay Now and billing history flows are connected.
- Confirm that the platform is ready for production release to web and both app stores.

## 2. Scope

**In scope:** Admin (web), Customer, Agent and Service Personnel (web and mobile), authentication, profiles, jobs, find staff, ratings, support tickets, referral, subscriptions and billing.

**Out of scope:** load and security penetration testing, and features outside the four role journeys.

## 3. Test Levels

| Level | Window (2025) | Performed By | Purpose |
| --- | --- | --- | --- |
| Test cases and scripts | Jul 31 – Aug 12 | Maryam (QA), Fatima | Prepare cases for every role |
| Unit and integration, Admin (web) | Aug 13 – Aug 15 | Maryam (QA), Fatima | Verify the Admin build |
| Unit and integration, Customer (web and app) | Aug 27 – Aug 29 | Maryam (QA), Fatima | Verify the Customer build |
| Unit and integration, Service Personnel (web and app) | Sep 10 – Sep 12 | Maryam (QA), Fatima | Verify the Service Personnel build |
| Unit and integration, Agent (web and app) | Sep 24 – Sep 26 | Maryam (QA), Fatima | Verify the Agent build |
| General integration testing, web and app | Sep 29 – Oct 3 | Maryam (QA), Fatima | Test the roles together |
| General bug fixing and retest | Sep 29 – Oct 13 | Developers and QA | Fix and retest findings |
| User acceptance testing | Oct 17 – Oct 20 | Maryam (QA), Fatima | Accept the release |

## 4. Entry and Exit Criteria

| Stage | Entry | Exit |
| --- | --- | --- |
| Per-role QA | Role build complete on web and mobile | Findings logged and triaged |
| General testing | All four roles built and QA'd once | All roles tested together; log triaged |
| Release | Bug fixing window closed; Team Lead approval | No open P1 findings |
| UAT | Production release complete | UAT scenarios run; Team Lead acceptance |

## 5. Test Scenarios by Role

| ID | Role | Scenario | Expected Result |
| --- | --- | --- | --- |
| UAT-01 | All | Register, sign in and sign out | Account created and session behaves consistently |
| UAT-02 | All | Request a password reset and sign in with the new password | Link arrives promptly; the account is active afterwards |
| UAT-03 | All | Complete and update the profile | Profile saves without error |
| UAT-04 | Agent | Add a service personnel through all three steps | Details, photo and languages saved; no repeated uploads |
| UAT-05 | Agent | View job details and apply for a job for a service personnel | Details visible before applying; application recorded |
| UAT-06 | Agent | Use the dashboard tabs | Started and ended jobs both open |
| UAT-07 | Customer | Post a job and find it under Manage jobs | Job appears in the list |
| UAT-08 | Customer | Search staff and bookmark a profile | Bookmark saves |
| UAT-09 | Customer | Choose a subscription plan and reach Pay Now | Plans open; Pay Now reachable from plans and billing history |
| UAT-10 | Service personnel | View own profile and dashboard | Profile shows service personnel context everywhere |
| UAT-11 | Service personnel | Check menus and actions | No Post a job or Find staff; role-appropriate actions only |
| UAT-12 | Service personnel | Raise a support ticket and navigate back | Ticket sent and locked; back navigation works; no 403 |
| UAT-13 | All | Contact support | Role-correct support page opens |
| UAT-14 | All | Use Refer a friend | Referral link works |
| UAT-15 | All | Rate an experience | Prompt wording and visuals follow the approved changes |
| UAT-16 | Admin | Manage users, jobs and support from the admin site | Admin actions complete |

---

# Part B – UAT Report

## 6. UAT Summary

| Item | Detail |
| --- | --- |
| UAT window | October 17 – October 20, 2025 |
| Environment | Production (web) and the released mobile apps |
| Testers | Maryam (QA), Fatima |
| Accepting authority | Maryam Abubakar (Team Lead) |
| **Overall result** | **Completed** |

## 7. Results

| Test Group | Scenarios | Result |
| --- | --- | --- |
| Authentication and profiles | UAT-01 to UAT-03 | Passed |
| Agent journeys | UAT-04 to UAT-06 | Passed |
| Customer journeys | UAT-07 to UAT-09 | Passed |
| Service personnel journeys | UAT-10 to UAT-12 | Passed |
| Shared features (support, referral, ratings) | UAT-13 to UAT-15 | Passed |
| Admin | UAT-16 | Passed |

**Overall:** every planned scenario group passed. No P1 findings were open at the end of UAT.

## 8. Acceptance Decision

| Role | Name | Decision |
| --- | --- | --- |
| Team Lead | Maryam Abubakar | Accepted |
| Associate Project Manager | Morenikeji Bankole | Recommended for acceptance |
| QA | Maryam (QA), Fatima | Test results confirmed |

## 9. Related Documents

- [Defect Log Summary](07-defect-log-summary.md)
- [Deployment & Release Plan](10-deployment-release-plan.md)
- [Project Closure Report](12-project-closure-report.md)
