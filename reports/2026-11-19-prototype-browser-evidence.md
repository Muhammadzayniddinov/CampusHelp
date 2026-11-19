# Prototype Browser Evidence — 19 November 2026

**Source:** Four screenshots supplied by the student from Chrome running the browser-only `prototype/index.html` file locally. This is an **evidence log**, not an automated testing claim. The actual images are included in the downloadable report shared in ChatGPT; images have not yet been pushed to GitHub.

## Screenshot-supported results
| Test | Observed evidence | Assessment |
|---|---|---|
| TC01 — Required fields | Empty-form validation outcome was not supplied | **Not verified** |
| TC02 — Category | Tracking and admin screen show category **IT Support** for the submitted request | **Pass — screenshot-supported** |
| TC03 — Priority | Tracking and admin screen show **High** priority | **Pass — screenshot-supported** |
| TC04 — Confirmation | Submission confirmation with unique-looking ID `CH-20261119-28571BC4` appears | **Pass — screenshot-supported** |
| TC05 — Tracking lookup | Same ID found in Track Request, status **Open** | **Pass — screenshot-supported** |
| TC06 — Admin dashboard | One row for request; summary shows **1 Open / 0 In Progress / 0 Completed** | **Pass — screenshot-supported** |
| TC07 — Assignment and status update | Dashboard row remains **Unassigned** and **Open** | **Not verified** |

The screenshot confirms **one generated identifier**, not statistical uniqueness across multiple submissions. Status updates have not yet been demonstrated. There is no live authentication, backend, synchronization, or real email service.

## Next required tests
1. **TC01:** Press Submit Request on an empty form. Capture validation error and confirm no new request was stored.
2. **TC07:** On Admin Dashboard assign the same test request to **IT Support Team**, change its status to **In Progress** and capture the updated dashboard; look it up under Track Request and capture its new status. Record the actual outcome as Pass/Fail.

## Privacy / report treatment
The original dashboard screenshot displays a numeric Student ID which may be personal. In the report copy only, this number was replaced by **REDACTED**; no request status/ID/category/priority was altered.

## Tracking
- [T09 — Test cases](https://github.com/Muhammadzayniddinov/CampusHelp/issues/9)
- [Prototype source](https://github.com/Muhammadzayniddinov/CampusHelp/blob/main/prototype/index.html)
- [Project roadmap](https://github.com/users/Muhammadzayniddinov/projects/1/views/3)

This log is a current-day snapshot and is not a backdated Day 5 / Day 8 progress checkpoint.
