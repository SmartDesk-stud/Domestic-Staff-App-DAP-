# Deployment & Release Plan

| Field | Detail |
| --- | --- |
| **Project** | Domestic Staffing Platform (Domestic Staff App) |
| **Document** | Deployment & Release Plan |
| **Version** | 1.0 |
| **Date** | October 9, 2025 |
| **Status** | Approved for Execution |
| **Author** | Morenikeji Bankole (Associate Project Manager) |
| **Approver** | Maryam Abubakar (Team Lead) |

---

## 1. Purpose

This plan covers the production release of the Domestic Staffing Platform on **October 16, 2025**: the web platform, and the mobile apps for iOS (Apple App Store) and Android (Google Play Store). It lists the checks before release, who does what, and how to roll back.

## 2. Release Summary

| Release | Content | Date | Owner |
| --- | --- | --- | --- |
| Web production | Web platform for Admin, Customer, Agent and Service Personnel | Oct 16, 2025 | Sadiq, AbdulSalam |
| Mobile production | Customer, Service Personnel and Agent apps on the App Store and Play Store | Oct 16, 2025 | Salisu |
| Acceptance | UAT on the released system | Oct 17 – 20, 2025 | Maryam (QA), Fatima |

## 3. Roles

| Role | Name | Responsibility |
| --- | --- | --- |
| Release approver | Maryam Abubakar | Go / No-Go decision |
| Release coordinator | Morenikeji Bankole | Checklist, communication, release record |
| Web release engineers | Sadiq, AbdulSalam | Deploy and verify the web platform |
| Mobile release engineer | Salisu | Build, submit and release the mobile apps |
| Verification | Maryam (QA), Fatima | Smoke tests after release; UAT |

## 4. Pre-Release Checklist

| # | Item | Owner | Status |
| --- | --- | --- | --- |
| 1 | General integration testing complete (Sep 29 – Oct 3) | Maryam (QA), Fatima | Complete |
| 2 | General bug fixing window closed (Oct 13) | Salisu, AbdulSalam, Sadiq | Complete |
| 3 | No open P1 findings in the [Defect Log](07-defect-log-summary.md) | Morenikeji Bankole | Complete |
| 4 | Role access checks passed for each role | Maryam (QA), Fatima | Complete |
| 5 | Payment and subscription flow connected and checked | Sadiq, AbdulSalam | Complete |
| 6 | App Store and Play Store accounts, listings and builds ready | Salisu | Complete |
| 7 | Production hosting and credentials confirmed | Sadiq, AbdulSalam | Complete |
| 8 | Rollback path confirmed for web and mobile | Sadiq, Salisu | Complete |
| 9 | Release message drafted for the team and the client | Morenikeji Bankole | Complete |

## 5. Go / No-Go Criteria

**Go** only if all are true:

- No open P1 findings.
- General testing and bug fixing are closed.
- Store builds and listings are ready.
- The rollback path is confirmed.
- The Team Lead has approved.

Any failed criterion is a **No-Go**. The date moves only with Team Lead approval through change control.

## 6. Deployment Steps

### October 16, 2025 – Web

1. Freeze changes to the release version.
2. Deploy the verified build to production.
3. Run a smoke test: sign-in, profile, jobs, subscriptions and support for each role.
4. Monitor errors after the release.

### October 16, 2025 – Mobile

1. Confirm the release builds for the Customer, Service Personnel and Agent apps.
2. Release on the Apple App Store and the Google Play Store.
3. Install from the stores and run the same smoke test on a phone.
4. Share store links with the team and the Team Lead.

### October 17 – 20, 2025 – Acceptance

1. QA run the UAT scenarios on the released system.
2. Findings are triaged the same day; P1 findings trigger a fix or rollback decision.
3. The Team Lead gives acceptance (see the [Test Plan & UAT Report](09-test-plan-and-uat-report.md)).

## 7. Rollback Plan

| Trigger | Action | Decision Maker |
| --- | --- | --- |
| Web smoke test fails | Redeploy the previous web build | Sadiq, AbdulSalam, informing the Team Lead |
| Serious defect found in a mobile app | Pause the store release or ship a fix build; use the previous version where the store allows | Team Lead with Salisu |
| P1 finding in UAT | Decide between a fix build and a rollback | Team Lead |

## 8. Release Record (Actuals)

| Release | Planned | Actual | Outcome |
| --- | --- | --- | --- |
| Web production | Oct 16 | Oct 16 | Released |
| Mobile production (iOS and Android) | Oct 16 | Oct 16 | Released |
| UAT | Oct 17 – 20 | Oct 17 – 20 | Completed |

## 9. Post-Release Support

- Stabilization runs through October 31, 2025.
- Production issues are logged in ClickUp and triaged using the P1, P2 and P3 definitions in the Defect Log.

## 10. Related Documents

- [Test Plan & UAT Report](09-test-plan-and-uat-report.md)
- [Risk Register](04-risk-register.md)
- [Status Reports](11-status-reports.md)
