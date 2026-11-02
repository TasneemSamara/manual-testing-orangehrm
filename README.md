# OrangeHRM - My Info Module (PIM) Testing Portfolio

**Author:** Tasneem Samara  
**Role:** Junior Manual QA Engineer  
**Project:** OrangeHRM 3.0 – My Info Module (PIM)  
**Application Under Test:** [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/)  
**Version:** 1.0

---

## 🎯 Project Overview

A comprehensive manual testing project on the **OrangeHRM** Human Resources system, focusing on the **My Info (PIM)** module. The testing covered employee self-service (ESS) features, including Personal Details, Contact Details, Emergency Contacts, Dependants, Immigration, Qualifications, and Session Management.

The project followed the full Software Testing Life Cycle (STLC) and includes execution results, bug reports, a Requirement Traceability Matrix (RTM), and a final Test Summary.

---

## 📊 Test Results Summary

| Metric | Value |
|---|---|
| Total Test Scenarios | 45 |
| Total Test Cases | 117 |
| Executed | 107 (91.4%) |
| **Pass** | **98 (91.5%)** |
| **Fail** | **9** |
| **Blocked** | **10** |
| **Bugs Found** | **9** |

### Bugs by Severity
* **Major:** 4
* **Minor:** 5

### Bugs by Priority
* **P1:** 1
* **P2:** 6
* **P3:** 2

---

## 🐛 Notable Bugs Found (Out of 9)

| Bug ID | Summary | Severity | Priority |
|---|---|---|---|
| ORANGEHRM-BUG-9 | License form allows saving a future Issued Date | Major | P1 |
| ORANGEHRM-BUG-6 | Immigration form allows saving a Review Date earlier than the Issued Date | Major | P2 |
| ORANGEHRM-BUG-8 | Education form accepts alphabetic characters in the GPA/Score field | Major | P2 |
| ORANGEHRM-BUG-3 | Missing "Delete" button for profile picture (can only replace, not remove) | Major | P2 |
| ORANGEHRM-BUG-1 | Cached login form is non-functional via browser Back button | Minor | P2 |

*Full details for all 9 bugs are available in the Bug Report spreadsheet.*

---

## 🛑 Blocked Test Cases (Environment Constraints)
Because the demo environment provided **Admin** access rather than **ESS-User** access, 10 test cases were **Blocked**. 
*(e.g., Admin has edit privileges on Employee ID, SSN, and DOB by design. To test the "ESS-User read-only restriction", a true ESS-User account is required).* 
All Blocked tests were documented with specific reasons rather than skipped.

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| **`Tasneem_OrangeHRM_TestScenarios.xlsx`** | 45 Test Scenarios mapped to FRS sections |
| **`Tasneem_OrangeHRM_TestCases.xlsx`** | 117 Detailed Test Cases with steps and test data |
| **`Tasneem_OrangeHRM_TestExecution.xlsx`** | Execution results (Pass/Fail/Blocked) |
| **`Tasneem_OrangeHRM_BugReport.xlsx`** | 9 Bugs documented with severity and priority |
| **`Tasneem_OrangeHRM_RTM.xlsx`** | Requirement Traceability Matrix (22 Requirements) |
| **`Tasneem_OrangeHRM_TestSummary.xlsx`** | Final Test Summary Report |

---

## 🛠️ Skills Demonstrated
* **Edge Case Testing:** Tested unrealistic dates, file masquerading (.exe to .jpg), and text in numeric fields.
* **Session Management Testing:** Tested browser back/forward caching, session timeouts, and logout behavior.
* **Defect Management:** Severity vs. Priority classification, clear reproduction steps.
* **Handling Constraints:** Identified environment limitations (lack of ESS-User credentials) and documented them professionally as "Blocked."

---



