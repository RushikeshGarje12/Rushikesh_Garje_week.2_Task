# OrangeHRM Open Source – Manual Test Case Suite (Week 2)

**Author:** Rushikesh Garje
**Role:** QA Engineer Intern (Manual) – YuvaIntern
**Submission Date:** November 20, 2026

## 📌 Overview
This repository contains the manual test suite for **OrangeHRM Open Source (Web-Based HRMS)**. The test cases are mapped to the Functional Requirements (FR-01 to FR-14) and Non-Functional Requirements (NFR-01 to NFR-08) defined in Week 1.

Each test case includes: Test Case ID, Requirement Traceability, Purpose, Test Type, Preconditions & Test Data, Test Steps, Expected Result, Actual Result, and Status.

## 🌐 Application Under Test
- **Application:** OrangeHRM Open Source
- **URL:** https://opensource-demo.orangehrmlive.com/
- **Testing Type:** Manual Testing
- **Test Types Covered:** Positive, Negative, Boundary, Security, Performance, Usability, Compatibility

## 🧪 Test Coverage Summary

| Module | Req. IDs | Positive | Negative / Boundary | Non-Functional | Total |
|---|---|---|---|---|---|
| Authentication & Session Management | FR-01, FR-02, FR-03, FR-14 | 2 | 3 | – | 5 |
| Admin & User Management (RBAC) | FR-04, FR-05 | 1 | 3 | – | 4 |
| PIM (Personal Information Mgmt.) | FR-06, FR-07, FR-08 | 2 | 3 | – | 5 |
| Leave Management | FR-09, FR-10, FR-11 | 3 | 3 | – | 6 |
| Time & Attendance | FR-12 | 1 | 2 | – | 3 |
| Recruitment (ATS) | FR-13 | 1 | 2 | – | 3 |
| Performance, Security & Usability | NFR-01 to NFR-08 | – | – | 6 | 6 |
| **Total** | **FR-01–FR-14 & NFR-01–NFR-08** | **10** | **16** | **6** | **32** |

## 🔍 Modules & Test Case IDs

| Module | Test Case IDs |
|---|---|
| Authentication & Session | TC_AUTH_001 – TC_AUTH_005 |
| Admin & RBAC | TC_ADM_001 – TC_ADM_004 |
| PIM | TC_PIM_001 – TC_PIM_005 |
| Leave Management | TC_LVE_001 – TC_LVE_006 |
| Time & Attendance | TC_TIM_001 – TC_TIM_003 |
| Recruitment | TC_REC_001 – TC_REC_003 |
| Performance, Security & Usability | TC_NFR_001 – TC_NFR_006 |

## ✅ Key Scenarios Tested
- **Authentication:** valid/invalid login, blank fields, logout and Back-button protection
- **Admin/RBAC:** user creation, password policy, duplicate username, ESS privilege restriction
- **PIM:** add employee, mandatory fields, profile picture upload (type & 1 MB limit), search
- **Leave:** entitlement assignment, apply leave, date-range validation, insufficient balance, overlapping requests, approval and balance deduction
- **Time & Attendance:** punch in/out, chronological validation, overlapping records
- **Recruitment:** candidate with PDF resume, unsupported file type, oversized file (> 1 MB)
- **Non-Functional:** page load < 3s, search < 2s, HTTPS and password masking, unauthenticated URL access, cross-browser/responsive, data integrity

## 📊 Execution Summary
| Metric | Result |
|---|---|
| Total Test Cases | 32 |
| Passed | 32 |
| Failed | 0 |
| Pass Rate | 100% |

## 🛠️ Tools Used
- Google Chrome, Firefox, Microsoft Edge
- Chrome DevTools (Network tab, Device Toolbar)
- Microsoft Word (test case documentation)

## 🎯 Learning Outcomes
- Writing detailed manual test cases with requirement traceability
- Applying positive, negative, and boundary value testing
- Testing RBAC, file upload validation, and security basics
- Verifying performance benchmarks and cross-browser compatibility

## 📬 Contact
**Rushikesh Garje**
📧 garjerushikesh123@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/rushikesh-garje-450a9239a)
💻 [GitHub](https://github.com/RushikeshGarje12)
