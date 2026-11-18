# CampusHelp Requirements and Stakeholders

## Stakeholder needs
| Stakeholder | Need |
|---|---|
| Student | Submit a service request and monitor status |
| IT / maintenance / library staff | Receive and act on assigned requests |
| Administrator | Prioritize, assign and update requests |
| University management | See aggregate workload and progress |

## Functional requirements
| ID | Requirement | Acceptance criterion |
|---|---|---|
| FR-01 | Submit student request | Required Student ID, Category, Priority and Description; valid submission confirms receipt |
| FR-02 | Categories and priorities | IT Support, Classroom Maintenance, Library Assistance, Administrative Services; Low/Medium/High |
| FR-03 | Unique tracking ID | Submission generates ID; tracking lookup finds stored request |
| FR-04 | Administrator assignment | Admin can assign a request to a designated staff/team |
| FR-05 | Request status updates | Open, In Progress, Completed visible on lookup |
| FR-06 | Dashboard | Show correct counts for Open, In Progress and Completed requests |

## Nonfunctional requirements
- Usable on desktop and mobile widths.
- No paid external service required; browser-only demonstration.
- Each input has a label and field validation.
- Protect privacy by using fictional Student IDs for demonstrations.

## Demonstration flow
Student submits request → system creates unique demo ID → student looks up ID → admin views and assigns request → admin changes status → student sees updated status.

## Exclusions
Real login, live backend and sending email are outside original scope. All browser data is local to a single profile/device.
