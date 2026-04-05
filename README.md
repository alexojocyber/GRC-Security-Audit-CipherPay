# GRC-Security-Audit-CipherPay
A professional GRC security audit and risk assessment report  for a fictional fintech company — CipherPay Ltd. Mapped to  NIST CSF, ISO 27001, PCI-DSS and GDPR frameworks.

#  Security Audit & Risk Assessment Report

**Company:** CipherPay Ltd
**Report Type:** Internal Security Audit & Risk Assessment
**Prepared By:** Alex Ojo — Junior GRC Analyst
**Date:** April 2026
**Classification:** Confidential

---

##  Executive Summary

CipherPay Ltd is a remote-first fintech startup providing digital payment solutions to individuals and businesses. As the company scales its operations, the need for a formal cybersecurity program has become critical — particularly given its obligations under **PCI-DSS** and **GDPR** compliance frameworks.

This report presents the findings of an independent security audit conducted across CipherPay Ltd's cloud infrastructure, web application, mobile application, and internal security practices. The audit was conducted using the **NIST Cybersecurity Framework (CSF)** and **ISO/IEC 27001:2022** as guiding standards.

###  Key Findings

| Risk Level | Count |
|------------|-------|
| 🔴 Critical | 3 |
| 🟠 High | 5 |
| 🟡 Medium | 4 |
| 🟢 Low | 2 |###  Key Findings

###  Critical Issues Identified

- **No formal Information Security Policy** in place
- **Lack of Multi-Factor Authentication (MFA)** across all systems
- **Unencrypted sensitive customer payment data** in transit and at rest
- **No incident response plan** or security monitoring capability
- **Insufficient access controls** — principle of least privilege not enforced

###  Summary of Recommendations

- Implement a formal Information Security Management System (ISMS)
- Deploy MFA across all employee and customer-facing systems immediately
- Encrypt all payment data in transit (TLS 1.2+) and at rest (AES-256)
- Establish a Security Operations capability with log monitoring and alerting
- Develop and test an Incident Response Plan
- Conduct regular security awareness training for all 50 employees

###  Overall Security Posture

CipherPay Ltd's current security posture is rated as **POOR** based on the audit findings. Immediate action is required to meet PCI-DSS and GDPR obligations and to protect customer payment data from unauthorized access.

> This report provides a structured remediation roadmap to bring CipherPay Ltd to a satisfactory security baseline within **90 days**.

---

##  Company Profile

| Field | Details |
|-------|---------|
| **Company Name** | CipherPay Ltd |
| **Industry** | Fintech — Digital Payments |
| **Founded** | 2023 |
| **Employees** | 50 (Remote-first) |
| **Headquarters** | London, United Kingdom |
| **Operations** | Global — serving customers across UK, EU, and Africa |
| **Annual Revenue** | £2.5M (projected) |
| **Compliance Obligations** | PCI-DSS, GDPR |

---

###  Technology Infrastructure

| Component | Details |
|-----------|---------|
| **Cloud Provider** | Amazon Web Services (AWS) |
| **Web Application** | Customer-facing payment portal |
| **Mobile Application** | iOS and Android payment app |
| **Internal Tools** | Slack, Google Workspace, Notion |
| **Data Storage** | AWS S3, RDS (PostgreSQL) |
| **Authentication** | Username and password only — no MFA |
| **Network Security** | Basic AWS Security Groups — no WAF |

---

###  Organisational Structure

| Department | Size |
|------------|------|
| Engineering & Development | 15 |
| Finance & Operations | 10 |
| Customer Support | 12 |
| Sales & Marketing | 8 |
| Leadership & Management | 5 |

---

###  Regulatory Obligations

**PCI-DSS (Payment Card Industry Data Security Standard)**
CipherPay Ltd processes customer card payments and is therefore required to comply with PCI-DSS standards. Currently the company has **not completed PCI-DSS certification** and has no formal compliance program in place.

**GDPR (General Data Protection Regulation)**
As a UK and EU-facing business, CipherPay Ltd processes personal data of EU and UK citizens and is subject to GDPR obligations. Currently there is **no Data Protection Officer (DPO)** appointed and no formal data protection policy exists.

---

###  Current Security Posture Summary

CipherPay Ltd currently operates with **no formal security program**. There are no dedicated security personnel, no security policies, no incident response capability, and no security monitoring in place. This represents a significant risk to the company, its customers, and its regulatory standing.

---

##  Audit Scope & Methodology

---

###  Audit Scope

This security audit covers the following areas of CipherPay Ltd's
operations:

| Area | Included in Audit |
|------|------------------|
| Cloud Infrastructure (AWS) | ✅ Yes |
| Web Application (Payment Portal) | ✅ Yes |
| Mobile Application (iOS & Android) | ✅ Yes |
| Internal Communication Tools | ✅ Yes |
| Employee Security Awareness | ✅ Yes |
| Access Control & Identity Management | ✅ Yes |
| Data Protection & Encryption | ✅ Yes |
| Incident Response Capability | ✅ Yes |
| Physical Security | ❌ Out of Scope (Remote-first) |
| Third Party Vendor Assessment | ❌ Out of Scope (Future Audit) |

---

###  Audit Objectives

The primary objectives of this audit were to:

- Assess CipherPay Ltd's current security posture against
industry standards
- Identify vulnerabilities, gaps, and risks across all
in-scope systems
- Evaluate compliance readiness against PCI-DSS and GDPR
requirements
- Provide a prioritised remediation roadmap to address
identified findings
- Map all findings to NIST CSF and ISO 27001 controls

---

###  Methodology

This audit was conducted using a **risk-based approach** aligned
with the following frameworks:

**1. NIST Cybersecurity Framework (CSF)**
The NIST CSF was used to evaluate CipherPay Ltd's security
capabilities across its five core functions:
- Identify
- Protect
- Detect
- Respond
- Recover

**2. ISO/IEC 27001:2022**
ISO 27001 controls were used to assess the adequacy of
CipherPay Ltd's information security management practices
across 14 control domains.

**3. PCI-DSS v4.0**
PCI-DSS requirements were reviewed to assess CipherPay Ltd's
readiness for payment card data security compliance.

---

###  Audit Activities Performed

| Activity | Description |
|----------|-------------|
| Document Review | Reviewed existing security policies and procedures |
| Infrastructure Assessment | Evaluated AWS configuration and security controls |
| Access Control Review | Assessed user accounts, permissions, and MFA status |
| Application Security Review | Evaluated web and mobile application security |
| Data Protection Review | Assessed encryption and data handling practices |
| Compliance Gap Analysis | Identified gaps against PCI-DSS and GDPR requirements |
| Risk Assessment | Identified and rated risks by likelihood and impact |
| Staff Interviews | Assessed security awareness across departments |

---

###  Risk Rating Methodology

All identified risks were rated using the following matrix:

| Likelihood \ Impact | Low | Medium | High |
|--------------------|-----|--------|------|
| **High** | 🟡 Medium | 🟠 High | 🔴 Critical |
| **Medium** | 🟢 Low | 🟡 Medium | 🟠 High |
| **Low** | 🟢 Low | 🟢 Low | 🟡 Medium |

**Risk Ratings:**
- 🔴 **Critical** — Immediate action required within 24-48 hours
- 🟠 **High** — Action required within 30 days
- 🟡 **Medium** — Action required within 60 days
- 🟢 **Low** — Action required within 90 days

---

###  Audit Timeline

| Phase | Activity | Duration |
|-------|----------|----------|
| Phase 1 | Planning & Scoping | Week 1 |
| Phase 2 | Data Collection & Assessment | Week 2-3 |
| Phase 3 | Analysis & Risk Rating | Week 4 |
| Phase 4 | Report Writing & Review | Week 5 |
| Phase 5 | Findings Presentation | Week 6 |

---

##  Risk Assessment Matrix

---

### 🔴 Critical Risks

| Risk ID | Risk Description | Likelihood | Impact | Rating | Affected Area |
|---------|-----------------|------------|--------|--------|---------------|
| R-001 | No Multi-Factor Authentication (MFA) on any system — attackers can gain access with stolen credentials | High | High | 🔴 Critical | All Systems |
| R-002 | Customer payment data transmitted without encryption — data interceptable in transit | High | High | 🔴 Critical | Web & Mobile App |
| R-003 | No formal Incident Response Plan — security incidents cannot be managed effectively | High | High | 🔴 Critical | Entire Organisation |

---

### 🟠 High Risks

| Risk ID | Risk Description | Likelihood | Impact | Rating | Affected Area |
|---------|-----------------|------------|--------|--------|---------------|
| R-004 | No Information Security Policy — employees have no security guidelines to follow | High | Medium | 🟠 High | Entire Organisation |
| R-005 | Principle of Least Privilege not enforced — employees have excessive system access | High | Medium | 🟠 High | AWS Infrastructure |
| R-006 | No security monitoring or SIEM — malicious activity goes undetected | High | Medium | 🟠 High | Cloud Infrastructure |
| R-007 | No Data Protection Officer (DPO) appointed — GDPR non-compliance risk | Medium | High | 🟠 High | Legal & Compliance |
| R-008 | AWS S3 buckets not properly configured — risk of public data exposure | Medium | High | 🟠 High | Cloud Infrastructure |

---

### 🟡 Medium Risks

| Risk ID | Risk Description | Likelihood | Impact | Rating | Affected Area |
|---------|-----------------|------------|--------|--------|---------------|
| R-009 | No employee security awareness training — staff vulnerable to phishing attacks | Medium | Medium | 🟡 Medium | All Departments |
| R-010 | No Web Application Firewall (WAF) — web app exposed to common attacks | Medium | Medium | 🟡 Medium | Web Application |
| R-011 | No formal patch management process — systems running outdated software | Medium | Medium | 🟡 Medium | All Systems |
| R-012 | No password policy enforced — weak passwords in use across organisation | Medium | Medium | 🟡 Medium | All Systems |

---

### 🟢 Low Risks

| Risk ID | Risk Description | Likelihood | Impact | Rating | Affected Area |
|---------|-----------------|------------|--------|--------|---------------|
| R-013 | No formal onboarding security checklist — new employees lack security guidance | Low | Medium | 🟢 Low | HR & Operations |
| R-014 | No offboarding process — former employee accounts may remain active | Low | Medium | 🟢 Low | Identity Management |

---

###  Risk Summary

| Risk Level | Count | Percentage |
|------------|-------|------------|
| 🔴 Critical | 3 | 21% |
| 🟠 High | 5 | 36% |
| 🟡 Medium | 4 | 29% |
| 🟢 Low | 2 | 14% |
| **Total** | **14** | **100%** |

---

###  Top 3 Priority Actions

Based on the risk assessment the following three actions must be
taken immediately:

**1. Deploy MFA across all systems (R-001)**
This single control eliminates the most critical attack vector
facing CipherPay Ltd. Implementation should begin within 24 hours.

**2. Encrypt all payment data in transit and at rest (R-002)**
Customer payment data must be protected using TLS 1.2+ in
transit and AES-256 at rest. This is also a direct PCI-DSS
requirement.

**3. Develop an Incident Response Plan (R-003)**
Without an IRP, CipherPay Ltd cannot effectively respond to
a security breach. This must be developed and tested
immediately.

---

##  NIST Cybersecurity Framework (CSF) Mapping

---

### Overview

The NIST Cybersecurity Framework consists of five core functions
that represent the lifecycle of cybersecurity risk management.
The table below maps CipherPay Ltd's identified risks and
current capabilities against each function.

---

###  NIST CSF Maturity Rating

| Function | Current Maturity | Target Maturity |
|----------|-----------------|-----------------|
| Identify | 🔴 Initial (Tier 1) | 🟢 Adaptive (Tier 4) |
| Protect | 🔴 Initial (Tier 1) | 🟠 Repeatable (Tier 3) |
| Detect | 🔴 Initial (Tier 1) | 🟠 Repeatable (Tier 3) |
| Respond | 🔴 Initial (Tier 1) | 🟠 Repeatable (Tier 3) |
| Recover | 🔴 Initial (Tier 1) | 🟡 Risk Informed (Tier 2) |

> CipherPay Ltd currently operates at **Tier 1 (Initial)** across
all five NIST CSF functions — indicating an ad-hoc, reactive
approach to cybersecurity with no formal program in place.

---

### 1️ IDENTIFY (ID)

*Understanding the organisation's assets, risks, and
cybersecurity capabilities.*

| Sub-Category | Control | Current Status | Risk ID | Gap |
|-------------|---------|----------------|---------|-----|
| ID.AM-1 | Physical devices and systems inventoried | ❌ Not in place | R-005 | No asset inventory exists |
| ID.AM-2 | Software platforms and applications inventoried | ❌ Not in place | R-005 | No software inventory exists |
| ID.GV-1 | Information security policy established | ❌ Not in place | R-004 | No security policy exists |
| ID.GV-3 | Legal and regulatory requirements understood | ⚠️ Partial | R-007 | No DPO appointed |
| ID.RA-1 | Asset vulnerabilities identified | ❌ Not in place | R-011 | No vulnerability management |
| ID.RM-1 | Risk management processes established | ❌ Not in place | R-004 | No risk management program |

**Finding:** CipherPay Ltd has no formal asset inventory, risk
management program, or security governance structure. The
organisation cannot effectively identify what needs to be
protected.

---

### 2️ PROTECT (PR)

*Implementing safeguards to ensure delivery of critical services.*

| Sub-Category | Control | Current Status | Risk ID | Gap |
|-------------|---------|----------------|---------|-----|
| PR.AC-1 | Identities and credentials managed | ❌ Not in place | R-001 | No MFA deployed |
| PR.AC-3 | Remote access managed | ⚠️ Partial | R-005 | No access control policy |
| PR.AC-4 | Access permissions managed | ❌ Not in place | R-005 | Least privilege not enforced |
| PR.DS-1 | Data at rest protected | ❌ Not in place | R-002 | No encryption at rest |
| PR.DS-2 | Data in transit protected | ❌ Not in place | R-002 | No TLS enforcement |
| PR.IP-1 | Baseline configuration established | ❌ Not in place | R-011 | No patch management |
| PR.AT-1 | Users informed and trained | ❌ Not in place | R-009 | No security awareness training |

**Finding:** CipherPay Ltd has critical gaps in its protective
controls. The absence of MFA, encryption, and access controls
leaves customer payment data highly vulnerable to unauthorised
access.

---

### 3️ DETECT (DE)

*Identifying cybersecurity events in a timely manner.*

| Sub-Category | Control | Current Status | Risk ID | Gap |
|-------------|---------|----------------|---------|-----|
| DE.AE-1 | Baseline network operations established | ❌ Not in place | R-006 | No network monitoring |
| DE.AE-2 | Detected events analysed | ❌ Not in place | R-006 | No SIEM in place |
| DE.CM-1 | Network monitored for events | ❌ Not in place | R-006 | No monitoring capability |
| DE.CM-7 | Monitoring for unauthorised activity | ❌ Not in place | R-006 | No log analysis |
| DE.DP-1 | Detection processes maintained | ❌ Not in place | R-006 | No detection program |

**Finding:** CipherPay Ltd has zero detection capability.
Malicious activity including brute force attacks, data
exfiltration, and unauthorised access would go completely
undetected. Immediate implementation of a SIEM solution
is recommended.

---

### 4️ RESPOND (RS)

*Taking action regarding a detected cybersecurity incident.*

| Sub-Category | Control | Current Status | Risk ID | Gap |
|-------------|---------|----------------|---------|-----|
| RS.RP-1 | Response plan in place | ❌ Not in place | R-003 | No IRP exists |
| RS.CO-1 | Personnel know their roles | ❌ Not in place | R-003 | No defined roles |
| RS.CO-2 | Incidents reported | ❌ Not in place | R-003 | No reporting process |
| RS.AN-1 | Notifications from detection systems | ❌ Not in place | R-006 | No alerting capability |
| RS.MI-1 | Incidents contained | ❌ Not in place | R-003 | No containment plan |

**Finding:** CipherPay Ltd has no Incident Response Plan,
no defined roles, and no containment procedures. In the
event of a security breach the organisation would be
completely unprepared to respond effectively — risking
significant regulatory penalties under GDPR and PCI-DSS.

---

### 5️ RECOVER (RC)

*Maintaining plans for resilience and restoring capabilities.*

| Sub-Category | Control | Current Status | Risk ID | Gap |
|-------------|---------|----------------|---------|-----|
| RC.RP-1 | Recovery plan in place | ❌ Not in place | R-003 | No recovery plan |
| RC.IM-1 | Recovery plans incorporate lessons learned | ❌ Not in place | R-003 | No lessons learned process |
| RC.CO-1 | Public relations managed during recovery | ❌ Not in place | R-003 | No communications plan |

**Finding:** CipherPay Ltd has no business continuity or
disaster recovery plan. A significant security incident
could result in extended downtime, reputational damage,
and loss of customer trust.

---

###  NIST CSF Gap Summary

| Function | Controls Assessed | In Place | Partial | Not In Place |
|----------|------------------|----------|---------|--------------|
| Identify | 6 | 0 | 1 | 5 |
| Protect | 7 | 0 | 1 | 6 |
| Detect | 5 | 0 | 0 | 5 |
| Respond | 5 | 0 | 0 | 5 |
| Recover | 3 | 0 | 0 | 3 |
| **Total** | **26** | **0** | **2** | **24** |

> CipherPay Ltd has **0 fully implemented controls** out of
26 assessed against the NIST CSF. This represents a
critical gap requiring immediate and sustained investment
in cybersecurity.

---

##  ISO/IEC 27001:2022 Control Mapping

---

### Overview

ISO/IEC 27001:2022 is the international standard for Information
Security Management Systems (ISMS). The following table maps
CipherPay Ltd's identified risks and gaps against the key
ISO 27001 control domains relevant to a fintech organisation
of its size and complexity.

---

###  ISO 27001 Compliance Summary

| Control Domain | Controls Assessed | Compliant | Partial | Non-Compliant |
|----------------|------------------|-----------|---------|---------------|
| Organisational Controls | 5 | 0 | 1 | 4 |
| People Controls | 3 | 0 | 0 | 3 |
| Physical Controls | 2 | 0 | 1 | 1 |
| Technological Controls | 8 | 0 | 1 | 7 |
| **Total** | **18** | **0** | **3** | **15** |

> CipherPay Ltd is currently **non-compliant** with ISO 27001
across all assessed control domains. Achieving certification
would require a minimum of **12 months** of sustained effort
and investment.

---

### 1️ Organisational Controls

*Policies, roles, responsibilities, and governance.*

| Control | Reference | Requirement | Current Status | Risk ID | Finding |
|---------|-----------|-------------|----------------|---------|---------|
| Information Security Policy | ISO 27001 A.5.1 | A formal security policy must be documented and communicated | ❌ Non-Compliant | R-004 | No security policy exists |
| Information Security Roles | ISO 27001 A.5.2 | Security roles and responsibilities must be defined | ❌ Non-Compliant | R-003 | No security roles defined |
| Threat Intelligence | ISO 27001 A.5.7 | Organisation must gather and analyse threat intelligence | ❌ Non-Compliant | R-006 | No threat intelligence program |
| Information Security in Projects | ISO 27001 A.5.8 | Security must be integrated into project management | ⚠️ Partial | R-004 | Ad-hoc security considerations only |
| Incident Management | ISO 27001 A.5.24 | Incident response procedures must be documented | ❌ Non-Compliant | R-003 | No incident response plan exists |

---

### 2️ People Controls

*Human resource security and awareness.*

| Control | Reference | Requirement | Current Status | Risk ID | Finding |
|---------|-----------|-------------|----------------|---------|---------|
| Security Awareness Training | ISO 27001 A.6.3 | All staff must receive regular security awareness training | ❌ Non-Compliant | R-009 | No training program exists |
| Screening | ISO 27001 A.6.1 | Background checks must be performed on new employees | ❌ Non-Compliant | R-013 | No screening process in place |
| Termination Procedures | ISO 27001 A.6.5 | Access must be revoked upon employee termination | ❌ Non-Compliant | R-014 | No offboarding process exists |

---

### 3️ Physical Controls

*Physical security of facilities and equipment.*

| Control | Reference | Requirement | Current Status | Risk ID | Finding |
|---------|-----------|-------------|----------------|---------|---------|
| Physical Security Perimeter | ISO 27001 A.7.1 | Physical boundaries must protect information assets | ⚠️ Partial | N/A | Remote-first — limited physical risk |
| Clear Desk Policy | ISO 27001 A.7.7 | Sensitive information must be secured when unattended | ❌ Non-Compliant | R-004 | No clear desk policy exists |

---

### 4️ Technological Controls

*Technical security controls for systems and data.*

| Control | Reference | Requirement | Current Status | Risk ID | Finding |
|---------|-----------|-------------|----------------|---------|---------|
| User Authentication | ISO 27001 A.8.5 | Strong authentication must be enforced for all users | ❌ Non-Compliant | R-001 | No MFA deployed |
| Access Control | ISO 27001 A.8.3 | Access rights must follow least privilege principle | ❌ Non-Compliant | R-005 | Excessive access rights granted |
| Encryption | ISO 27001 A.8.24 | Sensitive data must be encrypted in transit and at rest | ❌ Non-Compliant | R-002 | No encryption policy enforced |
| Logging & Monitoring | ISO 27001 A.8.15 | Security events must be logged and monitored | ❌ Non-Compliant | R-006 | No logging or SIEM in place |
| Vulnerability Management | ISO 27001 A.8.8 | Vulnerabilities must be identified and remediated | ❌ Non-Compliant | R-011 | No patch management process |
| Web Filtering | ISO 27001 A.8.23 | Web access must be controlled and monitored | ❌ Non-Compliant | R-010 | No WAF deployed |
| Secure Development | ISO 27001 A.8.25 | Security must be built into the development lifecycle | ⚠️ Partial | R-010 | No formal secure coding standards |
| Data Leakage Prevention | ISO 27001 A.8.12 | Controls must prevent unauthorised data disclosure | ❌ Non-Compliant | R-002 | No DLP controls in place |

---

###  Overall ISO 27001 Compliance Rating

| Rating | Score | Description |
|--------|-------|-------------|
| 🔴 Non-Compliant | 0-30% | Significant gaps — immediate action required |
| 🟠 Partially Compliant | 31-60% | Some controls in place — improvement needed |
| 🟡 Mostly Compliant | 61-85% | Most controls in place — minor gaps remaining |
| 🟢 Fully Compliant | 86-100% | All controls implemented — certification ready |

**CipherPay Ltd Current Score: 8% — 🔴 Non-Compliant**

> CipherPay Ltd meets fewer than 1 in 10 ISO 27001 controls
assessed. Achieving ISO 27001 certification will require
a structured 12-month ISMS implementation program with
dedicated security resources.

---

###  ISO 27001 Implementation Roadmap

| Phase | Timeline | Focus Area |
|-------|----------|------------|
| Phase 1 — Foundation | Month 1-2 | Security policy, roles, and governance |
| Phase 2 — Technical Controls | Month 3-5 | MFA, encryption, access control, SIEM |
| Phase 3 — People & Process | Month 6-8 | Training, incident response, patch management |
| Phase 4 — Audit & Review | Month 9-10 | Internal audit and gap remediation |
| Phase 5 — Certification | Month 11-12 | External audit and ISO 27001 certification |

---

##  Recommendations & Remediation Plan

---

### Overview

Based on the findings of this security audit, the following
recommendations are presented in priority order. Each
recommendation is mapped to the identified risk, relevant
framework controls, and a target remediation timeline.

---

### 🔴 Critical — Immediate Action Required (0-30 Days)

---

#### REC-001 — Deploy Multi-Factor Authentication (MFA)
**Risk ID:** R-001
**Framework:** NIST PR.AC-1 | ISO 27001 A.8.5 | PCI-DSS Req 8.4

**Recommendation:**
Implement MFA across all CipherPay Ltd systems immediately
including AWS Console, web application, mobile application,
Google Workspace, and Slack.

**Implementation Steps:**
1. Enable AWS IAM MFA for all administrator accounts
2. Integrate Google Authenticator or Microsoft Authenticator
3. Enforce MFA for all customer-facing payment portal logins
4. Set MFA as mandatory — no exceptions for any user role
5. Document MFA policy and communicate to all 50 employees

**Expected Outcome:**
Eliminates 99.9% of credential-based attack risk according
to Microsoft Security research.

**Estimated Effort:** 3-5 days
**Estimated Cost:** Low — most tools already support MFA

---

#### REC-002 — Encrypt All Payment Data
**Risk ID:** R-002
**Framework:** NIST PR.DS-1, PR.DS-2 | ISO 27001 A.8.24 | PCI-DSS Req 3, 4

**Recommendation:**
Implement end-to-end encryption for all customer payment
data in transit and at rest.

**Implementation Steps:**
1. Enforce TLS 1.2 or higher on all web and API endpoints
2. Implement AES-256 encryption for all data stored in AWS RDS
3. Encrypt all AWS S3 buckets containing customer data
4. Implement tokenisation for payment card data
5. Conduct quarterly encryption audits

**Expected Outcome:**
Meets PCI-DSS encryption requirements and protects customer
payment data from interception and unauthorised access.

**Estimated Effort:** 2-3 weeks
**Estimated Cost:** Medium — AWS encryption services

---

#### REC-003 — Develop Incident Response Plan
**Risk ID:** R-003
**Framework:** NIST RS.RP-1 | ISO 27001 A.5.24 | PCI-DSS Req 12.10

**Recommendation:**
Develop, document, and test a formal Incident Response Plan
covering all possible security incident scenarios.

**Implementation Steps:**
1. Define incident severity levels (P1 Critical to P4 Low)
2. Assign incident response roles to key personnel
3. Document step by step response procedures for each
   incident type
4. Establish communication protocols for internal and
   external stakeholders
5. Conduct tabletop exercise to test the plan
6. Review and update the plan every 6 months

**Expected Outcome:**
CipherPay Ltd will be able to detect, contain, and recover
from security incidents effectively — reducing breach
impact and meeting GDPR 72 hour notification requirement.

**Estimated Effort:** 2-3 weeks
**Estimated Cost:** Low — primarily staff time

---

### 🟠 High — Action Required Within 30 Days

---

#### REC-004 — Establish Information Security Policy
**Risk ID:** R-004
**Framework:** NIST ID.GV-1 | ISO 27001 A.5.1

**Recommendation:**
Develop a comprehensive Information Security Policy as the
foundation of CipherPay Ltd's security program.

**Policy must cover:**
- Acceptable use of company systems
- Password requirements and management
- Data classification and handling
- Remote working security requirements
- Incident reporting procedures
- Consequences of policy violations

**Estimated Effort:** 1-2 weeks
**Estimated Cost:** Low

---

#### REC-005 — Implement Least Privilege Access Control
**Risk ID:** R-005
**Framework:** NIST PR.AC-4 | ISO 27001 A.8.3

**Recommendation:**
Conduct a full access rights review and enforce the
principle of least privilege across all systems.

**Implementation Steps:**
1. Audit all existing user accounts and permissions
2. Remove excessive access rights immediately
3. Implement role-based access control (RBAC)
4. Review access rights quarterly
5. Automate access provisioning and deprovisioning

**Estimated Effort:** 2-3 weeks
**Estimated Cost:** Low

---

#### REC-006 — Deploy SIEM Solution
**Risk ID:** R-006
**Framework:** NIST DE.CM-1 | ISO 27001 A.8.15

**Recommendation:**
Implement a Security Information and Event Management
(SIEM) solution to provide real-time monitoring and
alerting across all CipherPay Ltd systems.

**Recommended Solution:** Splunk Cloud (Free Trial to start)

**Implementation Steps:**
1. Deploy Splunk Cloud or equivalent SIEM
2. Ingest logs from AWS CloudTrail, web application,
   and authentication systems
3. Create detection rules for common attack patterns
4. Configure real-time alerts for critical events
5. Assign SOC monitoring responsibilities

**Expected Outcome:**
Real-time visibility into security events — reducing
mean time to detect (MTTD) from unknown to under 1 hour.

**Estimated Effort:** 3-4 weeks
**Estimated Cost:** Medium — Splunk licensing

---

#### REC-007 — Appoint Data Protection Officer (DPO)
**Risk ID:** R-007
**Framework:** GDPR Article 37 | ISO 27001 A.5.2

**Recommendation:**
Appoint a qualified Data Protection Officer to oversee
GDPR compliance and data protection activities.

**Responsibilities:**
- Monitor GDPR compliance across the organisation
- Serve as point of contact for data subjects
- Liaise with regulatory authorities
- Conduct data protection impact assessments (DPIAs)

**Estimated Effort:** 2-4 weeks (recruitment)
**Estimated Cost:** High — dedicated staff member

---

#### REC-008 — Secure AWS S3 Configuration
**Risk ID:** R-008
**Framework:** NIST PR.DS-1 | ISO 27001 A.8.24

**Recommendation:**
Immediately audit and remediate all AWS S3 bucket
configurations to prevent public data exposure.

**Implementation Steps:**
1. Enable S3 Block Public Access on all buckets
2. Enable S3 server-side encryption (SSE-S3 or SSE-KMS)
3. Enable S3 access logging
4. Implement S3 bucket policies restricting access
5. Enable AWS Config to monitor bucket configuration changes

**Estimated Effort:** 1 week
**Estimated Cost:** Low

---

### 🟡 Medium — Action Required Within 60 Days

---

#### REC-009 — Security Awareness Training Program
**Risk ID:** R-009
**Framework:** NIST PR.AT-1 | ISO 27001 A.6.3

**Recommendation:**
Implement a mandatory security awareness training program
for all 50 CipherPay Ltd employees.

**Training must cover:**
- Phishing awareness and simulation
- Password security and MFA usage
- Data handling and classification
- Incident reporting procedures
- Remote working security

**Frequency:** Quarterly training + monthly phishing simulations
**Estimated Effort:** 2-3 weeks to set up
**Estimated Cost:** Low-Medium — training platform

---

#### REC-010 — Deploy Web Application Firewall (WAF)
**Risk ID:** R-010
**Framework:** NIST PR.AC-5 | ISO 27001 A.8.23

**Recommendation:**
Deploy AWS WAF in front of CipherPay Ltd's payment portal
to protect against common web attacks including SQL
injection, XSS, and DDoS.

**Estimated Effort:** 1-2 weeks
**Estimated Cost:** Medium — AWS WAF pricing

---

#### REC-011 — Implement Patch Management Process
**Risk ID:** R-011
**Framework:** NIST PR.IP-1 | ISO 27001 A.8.8

**Recommendation:**
Establish a formal patch management process to ensure
all systems are kept up to date.

**Implementation Steps:**
1. Inventory all software and systems
2. Subscribe to vendor security advisories
3. Define patching windows and schedules
4. Test patches in staging before production deployment
5. Track and report patch compliance monthly

**Estimated Effort:** 2-3 weeks
**Estimated Cost:** Low

---

#### REC-012 — Enforce Password Policy
**Risk ID:** R-012
**Framework:** NIST PR.AC-1 | ISO 27001 A.8.5

**Recommendation:**
Implement and enforce a strong password policy across
all CipherPay Ltd systems.

**Password Requirements:**
- Minimum 12 characters
- Mix of uppercase, lowercase, numbers, and symbols
- No password reuse for last 12 passwords
- Maximum 90 day password expiry
- Deploy a password manager company-wide

**Estimated Effort:** 1 week
**Estimated Cost:** Low

---

### 🟢 Low — Action Required Within 90 Days

---

#### REC-013 — Security Onboarding Checklist
**Risk ID:** R-013
**Framework:** ISO 27001 A.6.1

**Recommendation:**
Develop a security onboarding checklist for all new
employees covering account setup, MFA enrollment,
security training completion, and policy acknowledgement.

**Estimated Effort:** 3-5 days
**Estimated Cost:** Low

---

#### REC-014 — Formal Offboarding Process
**Risk ID:** R-014
**Framework:** ISO 27001 A.6.5

**Recommendation:**
Implement a formal offboarding process to ensure all
access is revoked immediately upon employee termination.

**Checklist must include:**
- Disable all system accounts within 24 hours
- Revoke AWS IAM access
- Remove from Google Workspace and Slack
- Retrieve company devices
- Transfer knowledge and handover documentation

**Estimated Effort:** 3-5 days
**Estimated Cost:** Low

---

###  Remediation Summary

| Priority | Recommendations | Timeline | Est. Cost |
|----------|----------------|----------|-----------|
| 🔴 Critical | REC-001, 002, 003 | 0-30 days | Medium |
| 🟠 High | REC-004, 005, 006, 007, 008 | 30 days | Medium-High |
| 🟡 Medium | REC-009, 010, 011, 012 | 60 days | Low-Medium |
| 🟢 Low | REC-013, 014 | 90 days | Low |

---

###  Expected Security Posture After Remediation

| Metric | Current | After 90 Days |
|--------|---------|---------------|
| NIST CSF Maturity | Tier 1 | Tier 3 |
| ISO 27001 Compliance | 8% | 65% |
| Critical Risks | 3 | 0 |
| High Risks | 5 | 1 |
| Overall Security Rating | 🔴 Poor | 🟡 Moderate |

---

## 📝 Conclusion

---

### Summary of Findings

This security audit of CipherPay Ltd has revealed significant
gaps across all areas of the organisation's cybersecurity
posture. Of the 14 risks identified, 3 were rated Critical,
5 High, 4 Medium, and 2 Low — indicating an organisation
that has prioritised growth over security.

CipherPay Ltd currently operates with:

- ❌ No formal Information Security Policy
- ❌ No Multi-Factor Authentication
- ❌ No encryption of customer payment data
- ❌ No Incident Response Plan
- ❌ No security monitoring or SIEM capability
- ❌ No Data Protection Officer
- ❌ No security awareness training program

These gaps represent a significant risk to CipherPay Ltd's
customers, operations, and regulatory standing. A serious
security breach at this stage could result in:

- **Financial penalties** — up to £17.5M or 4% of global
  turnover under GDPR
- **PCI-DSS non-compliance fines** — up to $100,000 per month
- **Reputational damage** — loss of customer trust and
  business partnerships
- **Operational disruption** — extended downtime and
  recovery costs

---

### Path Forward

The good news is that CipherPay Ltd is at an early enough
stage to build security into its foundation rather than
retrofitting it later. The 14 recommendations provided
in this report — if implemented in priority order — will
significantly improve the organisation's security posture
within 90 days and position it for ISO 27001 certification
within 12 months.

The recommended 90-day remediation roadmap is as follows:

| Month | Focus | Key Milestones |
|-------|-------|----------------|
| Month 1 | Critical Controls | MFA deployed, encryption enforced, IRP drafted |
| Month 2 | Governance & Monitoring | Security policy published, SIEM deployed, DPO appointed |
| Month 3 | People & Process | Training launched, WAF deployed, patch management active |
| Month 4-12 | Continuous Improvement | ISO 27001 implementation, quarterly audits, certification |

---

### Final Security Rating

| Category | Rating |
|----------|--------|
| Overall Security Posture | 🔴 Poor |
| NIST CSF Maturity | Tier 1 — Initial |
| ISO 27001 Compliance | 8% |
| PCI-DSS Readiness | 🔴 Not Ready |
| GDPR Compliance | 🔴 Not Ready |
| Recommended Priority | 🔴 Immediate Action Required |

---

### Auditor Statement

> This report was prepared by **Alex Ojo**, Junior GRC Analyst,
> as an independent security audit of CipherPay Ltd. All
> findings are based on information gathered during the audit
> period and are accurate to the best of the auditor's
> knowledge. This report should be reviewed by CipherPay Ltd's
> leadership team and acted upon immediately.

---

**Prepared by:**
Alex Ojo
Junior GRC Analyst
April 2026

**Report Classification:** Confidential
**Next Review Date:** October 2026

---

## 🔗 Related Projects

| Project | Description |
|---------|-------------|
| [Splunk SIEM Lab](https://github.com/alexojocyber/Splunk-SIEM-Lab) | Enterprise SIEM detection dashboard |
| [SSH Brute Force Detection Lab](https://github.com/alexojocyber/SSH-BruteForce-Detection-Lab) | Real SSH attack simulation + Fail2Ban defense |
| [Python Log Parser](https://github.com/alexojocyber/Python-Log-Parser) | Automated Python brute force detection |
| [Enterprise SIEM Lab](https://github.com/alexojocyber/SIEM-Investigation-Lab) | PAM brute force detection and MITRE mapping |

---

## 👨‍💻 Author

**Alex Ojo**
Cybersecurity Student | GRC & SOC Analyst Trainee

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/alex-o-ojo-ab9252185)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/alexojocyber)
