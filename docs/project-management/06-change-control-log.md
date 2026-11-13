# Change Control Process & Log

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Change Control Process & Log |
| **Version** | 2.0 (process v1.0 issued July 7, 2025) |
| **Date** | October 31, 2025 (final update) |
| **Status** | Final – Project Closed |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Purpose

The project uses a hybrid model: phase approvals around role-by-role delivery. Reviewers see each role's prototype and build for the first time during presentations and testing, so wording, field and flow changes are expected. Change control makes sure each one is recorded, assessed and decided, instead of changing the plan informally.

## 2. What Counts as a Change

| Type | Example | Handling |
| --- | --- | --- |
| **Clarification** | A clearer error message | Project manager updates the task; no formal request |
| **Content or label change** | Renaming a status or field | Change request, batched into the bug-fixing window |
| **Flow or field change** | Adding a city list or a details view | Change request with impact check |
| **Role rule change** | Removing a feature from one role | Change request; Team Lead approval |
| **Schedule change** | Moving a gate, presentation or release date | Change request; Team Lead approval |

## 3. Process

1. **Raise.** A reviewer, tester or team member sends the request to the project manager.
2. **Log.** The project manager assigns a CR number and records it below.
3. **Assess.** The project manager, with the developers and QA, checks the impact on scope, schedule, testing and other roles.
4. **Decide.** The Team Lead approves, approves in part, defers or rejects.
5. **Implement.** Approved items become ClickUp tasks and are handled in the next fitting window.
6. **Close.** The project manager confirms completion and updates the log.

**Decision rules**

- Wording and label changes are batched into one window to avoid interrupting a build in progress.
- A change that touches several roles is applied once, platform-wide, so every role stays consistent.
- No change moves a client presentation date or the release date without Team Lead approval.

## 4. Change Request Template

| Field | Entry |
| --- | --- |
| CR number | |
| Date raised / Raised by | |
| Description | |
| Reason | |
| Impact on scope, schedule, quality, other roles | |
| Recommendation | |
| Decision | Approve / Approve in part / Defer / Reject |
| Resulting action | |

## 5. Change Log

All requests came out of web and app testing and client review (August – October 2025). Linked findings refer to the [Defect Log](07-defect-log-summary.md).

| CR | Description | Linked Findings | Impact Assessment | Decision | Outcome |
| --- | --- | --- | --- | --- | --- |
| CR-001 | Replace "job description" with **"Role"** across the platform (agreed with the team in chat) | A-15 | Platform-wide label; touches every role | Approved | Applied platform-wide during bug fixing |
| CR-002 | Show job status as **Open** and **Closed** instead of Active and Inactive | A-10 | Label change in job lists | Approved | Applied during bug fixing |
| CR-003 | Rename "Preferred Language" to **"Languages I speak"** and allow several selections when adding a service personnel | A-05 | Field and form change in the Add Service Personnel journey | Approved | Applied during bug fixing |
| CR-004 | Reword the rating prompt to ask for feedback on the customer and replace the rating emojis | A-13, A-14 | Content and visual change on the rating page | Approved | Applied during bug fixing |
| CR-005 | Add **city and area** selection to the agent profile and Add Service Personnel | A-01, A-03 | New field with a location list | Approved | Applied during bug fixing |
| CR-006 | Add **View job details** before applying for a job on behalf of a service personnel | A-09 | Small screen addition on the jobs list | Approved | Applied during bug fixing |
| CR-007 | Remove actions a service personnel should not have: post a job, find staff, the Open button in ticket history; lock tickets after sending | S-01, S-02, S-05, S-06 | Role rule change; needs retest of the service personnel flow | Approved | Applied and retested in general testing |
| CR-008 | Link subscription plans, billing history Details and job posting to a single **Pay Now** page | C-04, C-07, C-08 | Payment flow; depends on the Paystack connection | Approved | Linked and retested before UAT |
| CR-009 | Review the accommodation options in the Add Service Personnel journey with the team | A-06 | Content decision, not a code change | Approved in part | Reviewed with the team and adjusted |

## 6. Change Summary

| Metric | Count |
| --- | --- |
| Change requests logged | 9 |
| Approved | 8 |
| Approved in part | 1 |
| Rejected | 0 |
| Changes that moved a client presentation date | 0 |
| Changes that moved the release date | 0 |

## 7. Related Documents

- [Risk Register](04-risk-register.md)
- [Defect Log Summary](07-defect-log-summary.md)
- [Project Closure Report](12-project-closure-report.md)
