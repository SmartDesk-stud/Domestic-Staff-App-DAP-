# Risk Register

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Risk Register (with outcomes) |
| **Version** | 2.0 (v1.0 issued July 7, 2025) |
| **Date** | October 31, 2025 (final update) |
| **Status** | Final – Project Closed |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Purpose and Method

The register was opened in Phase 1 and reviewed during the project. Each risk is scored for **probability (P)** and **impact (I)** from 1 (low) to 3 (high). **Score = P × I**; 6–9 is High, 3–4 Medium, 1–2 Low. The first table records the plan at the time. The second table records what the testing log and the project plan show happened.

## 2. Risk Summary

| Metric | Count |
| --- | --- |
| Risks identified | 8 |
| Risks with evidence in the testing log | 4 |
| Other risks closed without recorded impact | 4 |
| Open risks at closure | 0 |

## 3. Risk Register

### 3.1 Planned (as at July 7, 2025)

| ID | Risk | Category | P | I | Score | Rating | Owner | Planned Mitigation |
| --- | --- | --- | :-: | :-: | :-: | --- | --- | --- |
| R-01 | **Role and permission leakage.** Four roles share components, so one role may see another role's menus, data or profile. | Technical | 3 | 3 | 9 | High | Sadiq, AbdulSalam | Role-by-role QA and a general integration test across roles |
| R-02 | **Payment and subscription dependency.** Customer billing depends on the Paystack and subscription flows being connected. | Integration | 3 | 3 | 9 | High | Morenikeji Bankole | Track as its own item; test in general testing; confirm requirements early |
| R-03 | **Overlapping delivery streams.** Developers work on two roles at once, which could cause rework or quality drops. | Resource | 2 | 3 | 6 | High | Morenikeji Bankole | A fixed pipeline per role (design, build, QA, client presentation) with gates |
| R-04 | **Requirement and wording changes during testing.** Reviewers ask for label, flow or field changes late. | Scope | 3 | 2 | 6 | High | Morenikeji Bankole | Change control log; batch wording changes into the bug-fixing window |
| R-05 | **App store review delay.** Apple or Google review slows the mobile release. | Schedule | 2 | 3 | 6 | High | Salisu | Prepare store listings and builds before the release date |
| R-06 | **Client feedback delay.** Presentations slip, which holds up the next stream. | Schedule | 2 | 2 | 4 | Medium | Maryam Abubakar | Fixed presentation dates in the plan |
| R-07 | **Registration and email handling.** Email validation, duplicate detection or password reset behave inconsistently. | Quality | 2 | 3 | 6 | High | Sadiq, AbdulSalam | Targeted authentication test cases |
| R-08 | **Compressed final testing.** General testing, bug fixing and UAT run close together before release. | Schedule | 2 | 3 | 6 | High | Morenikeji Bankole | Two-week bug-fixing window; UAT scripts prepared in advance |

### 3.2 Outcomes (as at October 31, 2025)

| ID | Evidence | What the Record Shows | How It Was Resolved | Status |
| --- | --- | --- | --- | --- |
| R-01 | **Yes** | Several service personnel findings showed customer menus or profile context (S-01, S-02, S-03, S-04, S-08) and one 403 error after navigation (S-07). | Treated as a priority cluster, fixed in the General Bug Fixing window and retested in general testing. | Closed |
| R-02 | **Yes** | Customer subscription, Pay Now and billing history findings (C-04, C-07, C-08) showed the flows were not yet linked. | Logged as integration findings, linked and retested before UAT. | Closed |
| R-03 | No recorded impact | Each role went through design, build, QA and client presentation in sequence as planned. | n/a | Closed |
| R-04 | **Yes** | Nine change requests (wording, labels, fields, role rules and the payment flow) came out of testing. See the [Change Control Log](06-change-control-log.md). | Decided through change control and handled in the bug-fixing window. | Closed |
| R-05 | No recorded impact | Store releases went out on the planned date, October 16. | n/a | Closed |
| R-06 | No recorded impact | All eight presentations took place on the scheduled dates. | n/a | Closed |
| R-07 | **Yes** | Registration, reset link, session timeout and "email already taken" findings (L-01 to L-05, A-07, A-08). | Fixed in the bug-fixing window; authentication retested in general testing. | Closed |
| R-08 | No recorded impact | General testing and bug fixing ran in parallel from September 29; UAT ran October 17 – 20 as planned. | n/a | Closed |

## 4. Lessons From Risk Management

- The two top-scoring risks (role leakage and payments) matched the clusters in the testing log, so naming them in Phase 1 pointed testing at the right places.
- Running role streams in a staggered pipeline made problems visible one role at a time, rather than all at once at the end.
- Wording and layout changes are predictable during client reviews. A change log and a single bug-fixing window kept them from interrupting development.

## 5. Related Documents

- [Defect Log Summary](07-defect-log-summary.md)
- [Change Control Log](06-change-control-log.md)
- [Project Closure Report](12-project-closure-report.md)
