# Adactin Hotel Booking Web Application - End-to-End QA Testing Portfolio

## Project Context & Objectives
This repository houses the complete documentation matrix for the **Adactin Hotel Application** manual regression cycle. This framework tracks requirements verification from base-level test configurations directly down to integrated tracking metrics, logging functional glitches, calculations defects, boundary constraint failures, and system vulnerabilities.

---

## 🛠️ Integrated Tooling Stack
* **Test Case Layout Framework:** Configured uniformly using Single-Row structural text parameter groupings across 4 core business application folders.
* **Bug Tracking & Triage Platform:** Managed via Atlassian **Jira Cloud** under the tracking project key sequence: **`AHA-XXX`**.
* **Defect Priority Classification:** Set via clear business logic dependencies separating low-priority visual bugs from blocker-status accounting calculations failure anomalies.

---

## 📊 End-to-End Project Traceability Matrix

| Test ID | Module Target Area | Execution Status | Priority | Linked Jira Key | Official Jira Bug Summary & Defect Tracking Title |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **TC_006** | Login & Authentication | ❌ **Failed** | 🟢 Low | `AHA-1` | Login system accepts lowercase username inputs instead of enforcing strict case-sensitivity |
| **TC_009** | Login & Authentication | ❌ **Failed** | 🟢 Low | `AHA-2` | Missing password visibility toggle (eye icon) on the change password management screen |
| **TC_010** | Login & Authentication | ❌ **Failed** | 🟡 Medium | `AHA-3` | Browser back-button navigation from search hotel page triggers ERR_CACHE_MISS form resubmission crash |
| **TC_011** | Login & Authentication | ❌ **Failed** | 🟡 Medium | `AHA-4` | System forces idle redirect to login layout without displaying a 'session expired' notification message |
| **TC_003** | Search Hotel Form Grid | ❌ **Failed** | 🟡 Medium | `AHA-5` | Search Hotel reset button fails to clear room counts, attendee counters, and selected booking dates |
| **TC_005** | Search Hotel Form Grid | ❌ **Failed** | 🟡 Medium | `AHA-6` | Unexplained \$10 premium added to the subtotal pricing calculation matrix on the search results screen |
| **TC_001** | Book Hotel Checkout | ❌ **Failed** | 🟡 Medium | `AHA-7` | Checkout processing completely drops the user's input string from the Last Name confirmation text fields |
| **TC_002** | Book Hotel Checkout | ❌ **Failed** | 🟡 Medium | `AHA-8` | System overrides user configuration and automatically forces 'Standard' room tier layout to 'Deluxe' |
| **TC_004** | Book Hotel Checkout | ❌ **Failed** | 🔴 Highest | `AHA-9` | Security Bypass: Checkout gateway permits payment execution utilizing invalid 1-digit CVV entries |
| **TC_005** | Book Hotel Checkout | ❌ **Failed** | 🔴 Highest | `AHA-10` | Payment gateway allows reservation bookings using credit cards with expired historical dates (2023) |
| **TC_006** | Book Hotel Checkout | ❌ **Failed** | 🔴 Highest | `AHA-11` | Security Vulnerability: Injecting special character strings into name fields leaks raw database SQL query syntax errors to the UI |
| **TC_007** | Book Hotel Checkout | ❌ **Failed** | 🔴 Highest | `AHA-12` | Business Logic Failure: System accepts identical check-in/checkout dates, creating 0-day stays with an illegal \$11 pricing fee |
| **TC_008** | Book Hotel Checkout | ❌ **Failed** | 🟠 High | `AHA-13` | Calendar constraints violation allows users to confirm room bookings for historical past timelines |
| **TC_010** | Book Hotel Checkout | ❌ **Failed** | 🟡 Medium | `AHA-14` | Functional Data Discrepancy: Confirmation screen indicates a 'Standard' room tier while the itinerary ledger reflects 'Super Deluxe' |
| **TC_001** | Booked Itinerary Logs | ❌ **Failed** | 🟠 High | `AHA-15` | Itinerary ledger ignores room count variations and bills a 5-room booking at a single-room subtotal cost |
| **TC_002** | Booked Itinerary Logs | ❌ **Failed** | 🔴 Highest | `AHA-16` | Financial Loss: Itinerary renders 0-day stays at a broken flat subtotal rate of \$11 instead of enforcing the 1-night base room rate minimum |
| **TC_004** | Booked Itinerary Logs | ❌ **Failed** | 🟢 Low | `AHA-17` | The 'Room Type' descriptive data column is completely missing from the horizontal itinerary overview grid |
| **TC_006** | Booked Itinerary Logs | ❌ **Failed** | 🟠 High | `AHA-18` | Billing Engine Arithmetic Error: Multi-room itinerary total registers an invalid \$314 charge instead of the true \$1,815 calculation summary |

---
📁 Adactin-Hotel-QA-Documentation-Stack
 ├── 📄 Adactin_TestRail_Cases_Export.xlsx             <-- NEW NATIVE TESTRAIL SUITE EXPORT
 ├── 📄 Adactin_Functional_Regression_Run_Report.pdf   <-- NEW EXECUTION RESULTS CHART (PDF)
 ├── 📄 Adactin_Suite_Backup.xml                       <-- NEW XML METADATA DATA BACKUP
 ├── 📄 Adactin_Hotel_Master_Test_Suite.xlsx           
 ├── 📄 Jira_AHA_Defect_Export.csv                     
 └── 📄 README.md                                      

## 📂 Structural Directory & Repository Assets
* `Adactin_Hotel_Master_Test_Suite.xlsx`: Main user validation verification workbook containing full precondition metadata, manual step directives, and traceability linkage IDs.
* `Jira_AHA_Defect_Export.csv`: Direct structural issue fields data snapshot export downloaded from Atlassian Jira software, holding environmental settings parameters, step logs, and development notes.

---
**Portfolio By:** Pavithra Ramesh  
**Role:** Quality Assurance Engineer  
