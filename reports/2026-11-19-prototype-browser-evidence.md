# Prototype Browser Evidence — 19 November 2026

**Source:** Four screenshots supplied by the student from Chrome running the browser-only `prototype/index.html` file locally. This is an **evidence log**, not an automated testing claim. The actual images are included in the downloadable report shared in ChatGPT; images have not yet been pushed to GitHub.

## Screenshot-supported results
| Test | Observed evidence | Assessment |
|---|---|---|
| TC01 — Required fields | Student-supplied screenshot shows empty-form rejection with error: 'Student ID must be 3-30 characters.' | **Pass — screenshot-supported** |
| TC02 — Category | Tracking and admin screen show category **IT Support** for the submitted request | **Pass — screenshot-supported** |
| TC03 — Priority | Tracking and admin screen show **High** priority | **Pass — screenshot-supported** |
| TC04 — Confirmation | Submission confirmation with unique-looking ID `CH-20261119-28571BC4` appears | **Pass — screenshot-supported** |
| TC05 — Tracking lookup | Same ID found in Track Request, status **Open** | **Pass — screenshot-supported** |
| TC06 — Admin dashboard | One row for request; summary shows **1 Open / 0 In Progress / 0 Completed** | **Pass — screenshot-supported** |
| TC07 — Assignment and status update | New screenshot shows **IT Support Team**, **In Progress**, and summary **0 Open / 1 In Progress / 0 Completed**. Updated Track Request screen was not supplied. | **Partial pass — admin-side confirmed; tracking visibility pending** |

The screenshot confirms **one generated identifier**, not statistical uniqueness across multiple submissions. Administrator-side assignment and status changes have been demonstrated. Student-facing tracking *after* the change remains to be demonstrated. There is no live authentication, backend, synchronization, or real email service.

## Next required tests
1. **TC01:** Screenshot received: empty-form validation error displayed. This verifies the visible rejection message, not that browser storage was independently inspected.
2. **TC07:** Admin screenshot received: assigned to **IT Support Team** and changed to **In Progress**, with counts updated. **Remaining:** Look up the same request under Track Request, capture the new **In Progress** status, and verify the assignment there.

## Privacy / report treatment
The original dashboard screenshot displays a numeric Student ID which may be personal. In the report copy only, this number was replaced by **REDACTED**; no request status/ID/category/priority was altered.

## Tracking
- [T09 — Test cases](https://github.com/Muhammadzayniddinov/CampusHelp/issues/9)
- [Prototype source](https://github.com/Muhammadzayniddinov/CampusHelp/blob/main/prototype/index.html)
- [Project roadmap](https://github.com/users/Muhammadzayniddinov/projects/1/views/3)

This log is a current-day snapshot and is not a backdated Day 5 / Day 8 progress checkpoint.

## Cover-page details for the report
- Student name: **Muhammad Zayniddinov**
- Course/section: **COSC 3500 1T**
- Student number deliberately omitted from the report as requested.
- The most recent report screenshot redacts the visible numeric student ID in the admin table. The original GitHub project source is unchanged.
