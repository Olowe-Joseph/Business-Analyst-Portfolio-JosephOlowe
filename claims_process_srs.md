# 📄 Software Requirements Specification (SRS)
## Project: Claims Process Redesign for PrimeTrust Insurance Ltd

---

### 1. Introduction
This document outlines the functional and non-functional requirements for the Claims Process Redesign project. It is intended to guide development, testing, and delivery of the updated claims processing system to support faster, more accurate, and transparent handling of customer claims.

---

### 2. Purpose
To provide a structured view of the software capabilities and features needed to implement an automated, user-friendly digital claims submission and processing platform for PrimeTrust Insurance Ltd.

---

### 3. Scope
This software will:
- Allow customers to submit and track claims via a secure web portal.
- Enable staff to manage claims with real-time dashboards.
- Automate claim assignment and status updates.
- Integrate with Zoho CRM and a document management system.
- Generate reporting based on SLAs and operational KPIs.

---

### 4. Functional Requirements
1. **Claim Submission:**
   - Users shall be able to create a claim by completing an online form and uploading documents.
   - The system shall validate mandatory fields and issue a claim ID upon submission.

2. **Claim Routing:**
   - The system shall auto-assign claims to officers based on category and workload.
   - Escalation rules shall forward unresolved claims after 48 hours of inactivity.

3. **Notifications:**
   - Email and SMS alerts shall be triggered at key stages: submission, review, resolution.

4. **Staff Dashboard:**
   - Internal users shall view claims in a queue with status filters (e.g., New, In Review, Escalated).
   - The system shall display SLAs, timestamps, and related documents.

5. **Reporting:**
   - Managers shall generate weekly and monthly reports filtered by region, product type, and officer performance.

6. **Document Management:**
   - All claim documents shall be stored securely and accessible via claim ID linkage.

---

### 5. Non-Functional Requirements
- **Performance:** Page load time for the portal shall not exceed 3 seconds.
- **Availability:** System should be operational 99.5% of the time during business hours.
- **Security:** All data must be encrypted at rest and in transit.
- **Compliance:** Must comply with NDPR and ISO 27001 guidelines.

---

### 6. Use Case Summaries
#### UC-01: Submit Claim
**Actor:** Customer  
**Trigger:** Customer visits the claims portal  
**Flow:** Fills form → uploads documents → submits → receives confirmation

#### UC-02: Review & Route Claim
**Actor:** Claims Officer  
**Trigger:** New claim submitted  
**Flow:** Officer views queue → reviews submission → updates status → flags issues if needed

#### UC-03: Generate Report
**Actor:** Manager  
**Trigger:** Weekly review  
**Flow:** Selects filters → views report → downloads or shares

---

### 7. User Interface Requirements
- Customer portal must be mobile-responsive.
- Admin dashboard should include visual indicators for SLA breaches.
- Login screens must enforce 2FA for internal users.

---

### 8. Data Requirements
- Claim ID: Auto-generated, unique identifier.
- Customer Info: Name, phone, email, policy number.
- Uploaded Files: PDFs, images up to 10MB per file.
- Status Log: Timestamps for submission, updates, approvals.

---

### 9. Dependencies
- Zoho CRM integration via API.
- Document Management System with secure file storage.
- SMS/email provider for notification delivery.

---

**Document Owner:** Joseph Olowe  
**Version:** 1.0  
**Date:** June 2025

