# CampusHelp Prototype Test Plan

**Application:** `prototype/index.html` (single-file standalone version).  
**Testing:** Use fictional student details in one browser profile; data is stored in localStorage.  
**Execution status:** Test scenarios specified below; actual results to be recorded after execution. Do not label unexecuted tests Passed.

| Test ID | Steps | Expected result | Actual result | Status |
|---|---|---|---|---|
| TC01 Required fields | Open Submit Request; click Submit without data | Error displayed; nothing saved | Pending | Not Run |
| TC02 Category | Enter fictional Student ID, choose IT Support and valid other fields; submit | Request saved with IT Support | Pending | Not Run |
| TC03 Priority | Select High and submit a request | Saved record shows High priority | Pending | Not Run |
| TC04 Confirmation | Submit all valid required fields | Confirmation displays unique CH-... ID | Pending | Not Run |
| TC05 Status tracking | Open Track Request; enter saved ID | Matching request and Open status appear | Pending | Not Run |
| TC06 Admin dashboard | Open Admin Dashboard after creating one request | Request row and Open count appear | Pending | Not Run |
| TC07 Assignment/update | Change team and status to In Progress; track same ID | Dashboard count and tracking status reflect change | Pending | Not Run |

### Notes
This demonstration has no real email, production database, authentication or cross-browser synchronization. Test results should identify simulated behavior explicitly. Capture timestamped screenshots of actual testing, rather than using illustrative wireframes as evidence.
