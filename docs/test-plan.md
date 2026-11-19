# CampusHelp Prototype — Executed Manual Tests

**Application:** `prototype/index.html`, browser-local academic demonstration.  
**Test date:** 19 November 2026 (student-supplied Chrome screenshots).  
**Evidence:** [Browser evidence log](../reports/2026-11-19-prototype-browser-evidence.md), illustrated screenshots in the evidence-backed PDF shared with the lecturer. These are direct observed UI outcomes, not automated tests.

| ID | Steps performed | Expected result | Actual result observed | Assessment |
|---|---|---|---|---|
| TC01 | Leave form blank and press Submit Request | Required-field error, form not submitted | Red message: **Student ID must be 3-30 characters.** | **Pass (UI observation)** |
| TC02 | Select IT Support category and submit fictional request | Request retains selected category | Matching Track Request and admin row show **IT Support** | **Pass** |
| TC03 | Select High priority and submit | Priority remains High | Tracking and admin show **High** | **Pass** |
| TC04 | Complete valid form and submit | Confirmation shows a request ID | Confirmation displays `CH-20261119-28571BC4` | **Pass** |
| TC05 | Search by generated ID | Same request retrieved with status | Matching ID retrieved, initially **Open** | **Pass** |
| TC06 | Open Admin Dashboard after one request | Correct row and summary counts | One matching row; **1 Open, 0 In Progress, 0 Completed** | **Pass** |
| TC07 | Assign request to IT Support Team, set In Progress, then look up same ID | Admin counts and student tracking reflect changes | Dashboard: **0 Open, 1 In Progress, 0 Completed**; Track Request shows **In Progress** and **assigned: IT Support Team** | **Pass** |

## Boundaries and risk notes
- TC01 confirms visible rejection, but browser storage contents were not independently inspected.
- Only one request ID was shown: statistical uniqueness across many requests was not tested.
- No real authentication, server, database, email or cross-device synchronization is implemented or claimed.
- Student ID shown in the original admin screenshot was redacted in the report image for privacy; observed status and assignment were not changed.

## Result
**7 / 7 screenshot-supported checks passed** within the *manual browser demonstration*. The project is not thereby production-ready, and this does not close unrelated planning or closure tasks.
