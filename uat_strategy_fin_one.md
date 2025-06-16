#  UAT Strategy Document

## Core Banking Application Migration – FinOne Bank

---

### 1. Introduction

This UAT Strategy outlines the approach and methodology for conducting **User Acceptance Testing** (UAT) on the upgraded core banking system at FinOne. The strategy ensures alignment between business requirements and the developed solution prior to production rollout.

---

### 2. Objective

To validate that the system:

- Satisfies business and functional requirements
- Supports day-to-day operations without defects
- Delivers a user-friendly and consistent experience across modules

---

### 3. Scope of UAT

**Modules to be Tested:**

- Customer Onboarding (KYC + CIF Creation)
- Loan Origination and Disbursement
- Account Maintenance (Update/Closure)
- Transaction History Retrieval

**Interfaces:** Internal dashboards only. Third-party APIs will be tested separately.

---

### 4. Testing Approach

- Risk-based testing focusing on high-volume, high-impact processes
- Business scenarios derived from real-world branch operations
- Tests to be executed by trained branch representatives under coordination

---

### 5. UAT Entry Criteria

- All system modules deployed to UAT environment
- Test data prepared and validated
- All major bugs from SIT (System Integration Testing) closed
- UAT test plan and test cases approved by QA

---

### 6. UAT Exit Criteria

- All critical test cases executed and passed
- All High/Medium priority defects closed or mitigated
- Final sign-off from business SMEs and sponsor
- UAT completion report submitted

---

### 7. Defect Management

- All issues to be logged in Excel/Defect Tracker Sheet
- Defects classified by severity: Critical, High, Medium, Low
- Daily triage meetings held to assess defect status
- JIRA to be used optionally for tracking resolution workflow

---

### 8. Environment & Tools

| Tool / Resource | Purpose                                  |
| --------------- | ---------------------------------------- |
| UAT Environment | Testing ground with production-like data |
| Excel           | Test case matrix and defect logs         |
| JIRA (optional) | Defect assignment and audit trail        |
| MS Teams        | Daily status syncs and issue escalation  |

---

### 9. Roles & Responsibilities

| Role            | Responsibility                                  |
| --------------- | ----------------------------------------------- |
| UAT Coordinator | Plan tests, guide testers, consolidate findings |
| Branch Testers  | Execute test cases and log defects              |
| QA Analyst      | Review test coverage and validate outcomes      |
| Business SME    | Confirm business logic and issue sign-off       |

---

### 10. Risks & Mitigation

| Risk                                   | Mitigation Plan                                           |
| -------------------------------------- | --------------------------------------------------------- |
| Unstable UAT environment               | Pre-test check with IT before execution starts            |
| Low tester availability at branches    | Allocate buffer days and communicate early                |
| High number of defects in early cycles | Prioritize critical cases; shift lesser cases to post-UAT |

---

### 11. Communication Plan

- Daily sync calls during execution (15 mins)
- End-of-week summary report
- Defect log updated daily
- Final report and sign-off documentation on last UAT day

---

**Document Owner:** Joseph Olowe\
**Version:** 1.0\
**Date:** June 2025

