# Prototype Browser Evidence — 19 November 2026

**Source:** Seven screenshots supplied by the student from Chrome running the browser-only `prototype/index.html` file locally. This is an **evidence log**, not an automated testing claim. The actual images are included in the downloadable report shared in ChatGPT; screenshots are not pushed to GitHub.

## Screenshot-supported results
| Test | Observed evidence | Assessment |
|---|---|---|
| TC01 — Required fields | Student-supplied screenshot shows empty-form rejection with error: 'Student ID must be 3-30 characters.' | **Pass — screenshot-supported** |
| TC02 — Category | Tracking and admin screen show category **IT Support** for the submitted request | **Pass — screenshot-supported** |
| TC03 — Priority | Tracking and admin screen show **High** priority | **Pass — screenshot-supported** |
| TC04 — Confirmation | Submission confirmation with unique-looking ID `CH-20261119-28571BC4` appears | **Pass — screenshot-supported** |
| TC05 — Tracking lookup | Same ID found in Track Request, status **Open** | **Pass — screenshot-supported** |
| TC06 — Admin dashboard | One row for request; summary shows **1 Open / 0 In Progress / 0 Completed** | **Pass — screenshot-supported** |
| TC07 — Assignment and status update | Admin screenshot shows **IT Support Team**, **In Progress**, and **0 Open / 1 In Progress / 0 Completed**; follow-up Track Request screenshot shows the **same ID** with **In Progress** and **assigned: IT Support Team**. | **Pass — screenshot-supported** |

The screenshot confirms **one generated identifier**, not statistical uniqueness across multiple submissions. Administrator-side assignment and status changes and **student-facing tracking reflection** are demonstrated with the same request ID. This is evidence for a browser-local prototype, not a real backend. There is no live authentication, backend, synchronization, or real email service.

## Test completion summary
Seven test cases have screenshot-supported visible outcomes (TC01–TC07). The newly supplied Track Request screenshot from 19 November 2026 verifies post-update status **In Progress** and assignment **IT Support Team** for request `CH-20261119-28571BC4`. Browser storage internals, production deployment, real email and cross-device syncing were **not** tested.

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
