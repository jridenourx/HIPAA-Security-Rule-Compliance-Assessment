# HIPAA Security Rule Compliance Assessment – Findings Register

**Organization:** Northstar Health Plan (Fictional)  
**Assessment Period:** January 1–October 31, 2026  
**Assessment Snapshot:** October 31, 2026  
**Register Date:** November 3, 2026  
**Status:** Final Assessment Findings – Remediation Planning Documented

---

## 1. Purpose

This register consolidates findings and observations identified during the simulated HIPAA Security Rule compliance assessment of Northstar Health Plan.

The register provides a centralized record of identified control deficiencies, documentation gaps, evidence limitations, risk implications, and recommended corrective actions.

Each item is mapped to its applicable control and supporting assessment workpaper.

The register serves as the basis for the Corrective Action Plan (CAP).

## 2. Severity Definitions

| Severity | Definition |
|---|---|
| High | A significant control deficiency or evidence gap that may expose ePHI to unauthorized access, disclosure, alteration, or loss. Requires prioritized remediation. |
| Moderate | A control weakness or documentation gap that could reduce the effectiveness of security safeguards or limit the organization's ability to demonstrate compliance. Requires planned remediation. |
| Low | A limited deficiency with relatively low potential impact that should be addressed through routine improvement activities. |

Severity ratings represent the simulated assessment team's judgment based on the available evidence. They are not official HIPAA severity classifications.

## 3. Findings Summary

| Severity | Count |
|---|---:|
| High | 10 |
| Moderate | 5 |
| Low | 0 |
| **Total Findings** | **15** |

**Additional observation:** H-06-01 is retained as an observation rather than a formal control deficiency because the absence of incident execution records does not establish that Northstar failed to respond to actual incidents.

### 3.1 Findings by Control

| Finding ID | Control | Finding Title | Severity |
|---|---|---|---|
| H-01-01 | H-01 | Security Risk Analysis Not Updated for Material Environmental Changes | High |
| H-02-01 | H-02 | Formal Risk Treatment Plan Not Established | High |
| H-03-01 | H-03 | Formal Workforce Clearance Procedures Not Established | Moderate |
| H-03-02 | H-03 | Workforce Access Changes and Terminations Not Consistently Demonstrated | High |
| H-04-01 | H-04 | Periodic Access Reviews Not Consistently Documented | High |
| H-05-01 | H-05 | Training Completion and Follow-Up Not Fully Demonstrated | Moderate |
| H-05-02 | H-05 | Organization-Wide Training Coverage Not Demonstrated | High |
| H-07-01 | H-07 | Backup Restoration Testing Not Sufficiently Evidenced | High |
| H-08-01 | H-08 | Workstation Safeguard Implementation Not Independently Demonstrated | Moderate |
| H-09-01 | H-09 | Emergency Access Procedure Not Fully Documented | Moderate |
| H-09-02 | H-09 | Technical Access Control Configuration Not Independently Demonstrated | High |
| H-10-01 | H-10 | Information System Activity Review Documentation and Follow-Up Incomplete | Moderate |
| H-11-01 | H-11 | Audit Logging Implementation and Coverage Not Independently Demonstrated | High |
| H-12-01 | H-12 | Authentication Configuration and Enforcement Not Independently Demonstrated | High |
| H-13-01 | H-13 | Transmission Security Implementation Not Independently Demonstrated | High |

**Observation Register**

| Observation ID | Control | Observation Title | Classification |
|---|---|---|---|
| H-06-01 | H-06 | Incident Response Execution Not Demonstrated | Moderate – Evidence Limitation |

*H-06-01 is not included in the formal finding count. It is tracked separately for evidence improvement and management follow-up.*

---

## 4. Detailed Findings

### H-01-01 – Security Risk Analysis Not Updated for Material Environmental Changes

- **Control:** H-01 – Risk Analysis
- **Regulatory Reference:** 45 CFR §164.308(a)(1)(ii)(A)
- **Severity:** High
- **Evidence:** E-01 – Security Risk Analysis
- **Workpaper:** H-01 / H-02 Risk Analysis and Risk Management Testing

**Condition**

E-01 documents a security risk analysis dated January 15, 2026. The analysis does not reflect the third-party claims analytics integration introduced in July 2026, which has access to limited claims data.

The assessment therefore does not demonstrate that risks associated with this material environmental change were incorporated into an updated risk analysis.

**Risk**

Changes to systems, integrations, and data access may introduce new threats and vulnerabilities. Without an updated analysis, Northstar may not identify or evaluate risks affecting ePHI introduced by the integration.

**Recommendation**

Update the security risk analysis to include the claims analytics integration, associated data flows, access arrangements, relevant threats and vulnerabilities, and potential impacts to ePHI. Establish a process for updating the analysis when material environmental changes occur.

**Status:** Open

### H-02-01 – Formal Risk Treatment Plan Not Established

- **Control:** H-02 – Risk Management
- **Regulatory Reference:** 45 CFR §164.308(a)(1)(ii)(B)
- **Severity:** High
- **Evidence:** E-01 – Security Risk Analysis
- **Workpaper:** H-01 / H-02 Risk Analysis and Risk Management Testing

**Condition**

The available evidence does not demonstrate a formal risk treatment plan that assigns risk owners, defines remediation actions, establishes target dates, and tracks implementation status.

**Risk**

Identified risks may remain unresolved or lack appropriate management oversight. Without assigned ownership and documented follow-up, Northstar may not consistently reduce risks to a reasonable and appropriate level.

**Recommendation**

Develop a formal risk treatment plan that records identified risks, risk ratings, treatment decisions, assigned owners, target completion dates, status, and residual risk acceptance where applicable.

**Status:** Open

### H-03-01 – Formal Workforce Clearance Procedures Not Established

- **Control:** H-03 – Workforce Security
- **Regulatory Reference:** 45 CFR §164.308(a)(3)
- **Severity:** Moderate
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-03 / H-04 Workforce Security and Information Access Management Testing

**Condition**

E-02 includes general workforce clearance expectations but does not establish a sufficiently formal process defining eligibility review, required approvals, and documentation before access to ePHI is granted.

**Risk**

Without a defined clearance process, workforce members may receive access before appropriate eligibility and authorization checks are completed.

**Recommendation**

Establish a documented workforce clearance procedure defining eligibility review, responsible personnel, approval requirements, timing, and retention of supporting records.

**Status:** Open

### H-03-02 – Workforce Access Changes and Terminations Not Consistently Demonstrated

- **Control:** H-03 – Workforce Security
- **Regulatory Reference:** 45 CFR §164.308(a)(3)
- **Severity:** High
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-03 / H-04 Workforce Security and Information Access Management Testing

**Condition**

E-02 documents termination and access modification expectations, but the available evidence does not demonstrate a consistent process for reconciling workforce separations and job changes against active system accounts.

**Risk**

Former workforce members or individuals whose job responsibilities have changed may retain access that is no longer appropriate.

**Recommendation**

Establish a documented HR-to-IT notification process, define expected timelines for disabling accounts, reconcile workforce separation records against active accounts, document completed access removal, and review access following internal transfers or changes in responsibilities.

**Status:** Open

### H-04-01 – Periodic Access Reviews Not Consistently Documented

- **Control:** H-04 – Information Access Management
- **Regulatory Reference:** 45 CFR §164.308(a)(4)
- **Severity:** High
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-03 / H-04 Workforce Security and Information Access Management Testing

**Condition**

E-02 establishes an expectation that managers and system owners periodically review user access to confirm that permissions remain appropriate. However, the available evidence does not demonstrate that access reviews are consistently completed and documented across all systems containing ePHI.

**Risk**

Workforce members may retain unnecessary or excessive permissions, increasing the risk of unauthorized use or disclosure of ePHI.

**Recommendation**

Establish a recurring access review schedule, identify systems containing ePHI, require managers or system owners to review assigned permissions, document review completion and approval, track and resolve excessive permissions, and retain evidence of completed reviews and corrective actions.

**Status:** Open

### H-05-01 – Training Completion and Follow-Up Not Fully Demonstrated

- **Control:** H-05 – Security Awareness and Training
- **Regulatory Reference:** 45 CFR §164.308(a)(5)
- **Severity:** Moderate
- **Evidence:** E-03 – Security Awareness and Training Records
- **Workpaper:** H-05 / H-06 Training and Incident Procedures Testing

**Condition**

The training sample identified EMP-005 completing assigned onboarding training 38 days after assignment, exceeding Northstar's internal 30-day completion requirement. Supporting evidence of follow-up and escalation for overdue training was not provided.

**Risk**

Delayed training and insufficient follow-up may reduce workforce awareness of security responsibilities and increase the likelihood of unsafe handling of ePHI.

**Recommendation**

Establish automated or documented reminders for overdue training, define escalation responsibilities, retain completion records, and periodically review overdue training exceptions.

**Status:** Open

### H-05-02 – Organization-Wide Training Coverage Not Demonstrated

- **Control:** H-05 – Security Awareness and Training
- **Regulatory Reference:** 45 CFR §164.308(a)(5)
- **Severity:** High
- **Evidence:** E-03 – Security Awareness and Training Records
- **Workpaper:** H-05 / H-06 Training and Incident Procedures Testing

**Condition**

E-03 contains a sample of 12 employee training records from an estimated workforce of 120. The available evidence does not include a complete workforce roster reconciliation or other documentation demonstrating training coverage across the organization.

**Risk**

Northstar may be unable to identify workforce members who have not completed required security awareness training.

**Recommendation**

Maintain a complete workforce training roster, reconcile assigned and completed training against active workforce records, identify overdue or missing training, and document periodic management review.

**Status:** Open

### H-07-01 – Backup Restoration Testing Not Sufficiently Evidenced

- **Control:** H-07 – Contingency Planning
- **Regulatory Reference:** 45 CFR §164.308(a)(7)
- **Severity:** High
- **Evidence:** E-05 – Contingency Plan
- **Workpaper:** H-07 / H-08 Contingency and Workstation Security Testing

**Condition**

E-05 documents backup and recovery expectations, but the available evidence does not sufficiently demonstrate that backup restoration testing has been performed successfully.

**Risk**

Northstar may be unable to restore ePHI and supporting systems following a disruption, potentially affecting data availability and business operations.

**Recommendation**

Perform and document backup restoration testing. Retain test dates, systems and data included, restoration results, issues identified, corrective actions, and management approval.

**Status:** Open

### H-08-01 – Workstation Safeguard Implementation Not Independently Demonstrated

- **Control:** H-08 – Workstation Use and Security
- **Regulatory Reference:** 45 CFR §164.310(b) and §164.310(c)
- **Severity:** Moderate
- **Evidence:** E-06 – Workstation Security Policy
- **Workpaper:** H-07 / H-08 Contingency and Workstation Security Testing

**Condition**

E-06 documents workstation use and security expectations. However, physical inspection records, endpoint configuration reports, or workstation review documentation were not provided to demonstrate implementation.

**Risk**

Workstations used to access ePHI may not consistently enforce appropriate physical and security safeguards.

**Recommendation**

Establish periodic workstation security reviews and retain evidence of workstation configurations, physical protection, screen privacy controls, unattended workstation safeguards, and identified corrective actions.

**Status:** Open

### H-09-01 – Emergency Access Procedure Not Fully Documented

- **Control:** H-09 – Access Control
- **Regulatory Reference:** 45 CFR §164.312(a)(2)(ii)
- **Severity:** Moderate
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-09 / H-10 Access Control and Activity Review Testing

**Condition**

The access control policy establishes an emergency access expectation, but the supporting procedure does not fully document the request, approval, provisioning, monitoring, and review process.

**Risk**

Incomplete emergency access procedures may delay appropriate access to ePHI during an emergency or result in access that is not adequately controlled.

**Recommendation**

Develop a formal emergency access procedure defining authorization, responsible personnel, access provisioning, documentation, monitoring, and post-emergency access removal or review.

**Status:** Open

### H-09-02 – Technical Access Control Configuration Not Independently Demonstrated

- **Control:** H-09 – Access Control
- **Regulatory Reference:** 45 CFR §164.312(a)
- **Severity:** High
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-09 / H-10 Access Control and Activity Review Testing

**Condition**

Policy documentation establishes unique user identification, automatic logoff, and encryption expectations. However, supporting system configuration evidence was not provided to demonstrate that these safeguards are implemented consistently.

**Risk**

Without configuration validation, Northstar cannot demonstrate that access restrictions, session termination, and encryption safeguards are operating as intended across systems containing ePHI.

**Recommendation**

Obtain system-generated evidence demonstrating unique user account implementation, inactivity timeout configurations, encryption settings, and applicable key-management practices. Document the rationale for addressable implementation specifications.

**Status:** Open

### H-10-01 – Information System Activity Review Documentation and Follow-Up Incomplete

- **Control:** H-10 – Information System Activity Review
- **Regulatory Reference:** 45 CFR §164.308(a)(1)(ii)(D)
- **Severity:** Moderate
- **Evidence:** E-07 – Audit Logging and Monitoring Procedure
- **Workpaper:** H-09 / H-10 Access Control and Activity Review Testing

**Condition**

E-07 contains four sample monitoring records, including two marked Complete and two marked Incomplete. The records demonstrate that selected monitoring activities were documented. However, the sample does not establish consistent review coverage across all systems containing ePHI. MON-002 identifies unusual claims platform activity but does not include sufficient supporting investigation or follow-up documentation.

**Risk**

Incomplete review documentation and follow-up may limit Northstar's ability to demonstrate that potentially unauthorized or suspicious activity is consistently identified, investigated, and addressed.

**Recommendation**

Establish a formally approved activity review schedule covering systems containing ePHI. Retain review records identifying the reviewer, review date, system or log source, activity examined, exceptions identified, investigation results, escalation decisions, and corrective actions. Complete and retain supporting documentation for MON-002 and other incomplete monitoring records.

**Status:** Open

### H-11-01 – Audit Logging Implementation and Coverage Not Independently Demonstrated

- **Control:** H-11 – Audit Controls
- **Regulatory Reference:** 45 CFR §164.312(b)
- **Severity:** High
- **Evidence:** E-07 – Audit Logging and Monitoring Procedure
- **Workpaper:** H-11 / H-12 Audit Controls and Authentication Testing

**Condition**

E-07 documents audit logging expectations, but system configuration evidence and representative audit log samples were not provided to demonstrate that logging mechanisms are implemented across systems containing ePHI.

**Risk**

Incomplete or improperly configured audit logging may limit Northstar's ability to identify unauthorized activity, investigate security incidents, and establish accountability for access to ePHI.

**Recommendation**

Maintain an inventory of systems containing ePHI and obtain system-generated evidence demonstrating audit logging coverage. Document relevant events captured, retention settings, access restrictions, and procedures for retrieving and examining audit records.

**Status:** Open

### H-12-01 – Authentication Configuration and Enforcement Not Independently Demonstrated

- **Control:** H-12 – Person or Entity Authentication
- **Regulatory Reference:** 45 CFR §164.312(d)
- **Severity:** High
- **Evidence:** E-02 – Access Control Policy
- **Workpaper:** H-11 / H-12 Audit Controls and Authentication Testing

**Condition**

E-02 documents password and multifactor authentication expectations, including requirements for remote access. However, supporting technical configuration evidence and authentication records were not provided to demonstrate that these requirements are enforced across relevant systems.

**Risk**

Authentication requirements that are not consistently implemented may increase the risk of unauthorized access to systems containing ePHI.

**Recommendation**

Obtain identity provider and system configuration reports demonstrating authentication settings, including multifactor authentication enforcement for applicable remote access methods. Review representative authentication records and document the systems and access methods covered by the authentication requirements.

**Status:** Open

### H-13-01 – Transmission Security Implementation Not Independently Demonstrated

- **Control:** H-13 – Transmission Security
- **Regulatory Reference:** 45 CFR §164.312(e)
- **Severity:** High
- **Evidence:** E-08 – Transmission Security Policy
- **Workpaper:** H-13 Transmission Security Testing

**Condition**

E-08 documents transmission security expectations, including encryption requirements. However, technical configuration evidence was not provided to demonstrate that encryption and integrity safeguards are implemented for relevant transmission methods.

**Risk**

Without verified transmission safeguards, ePHI may be exposed to unauthorized access or improper modification while being transmitted over electronic communications networks.

**Recommendation**

Identify systems and communication channels that transmit ePHI. Obtain technical evidence demonstrating encryption configurations and applicable integrity protections. Document the reasonableness and appropriateness assessments supporting addressable implementation specifications.

**Status:** Open

---

## 5. Observation Register

### H-06-01 – Incident Response Execution Not Demonstrated

- **Control:** H-06 – Security Incident Procedures
- **Regulatory Reference:** 45 CFR §164.308(a)(6)
- **Classification:** Moderate – Evidence Limitation
- **Evidence:** E-04 – Security Incident Response Procedure
- **Workpaper:** H-05 / H-06 Training and Incident Procedures Testing

**Observation**

E-04 documents procedures for identifying, reporting, responding to, mitigating, and documenting security incidents. However, no incident tickets, exercise records, or other execution evidence were provided.

**Risk Consideration**

Without supporting records, the assessment cannot verify whether the documented incident response process has been exercised or consistently followed.

**Recommendation**

Retain incident response records, tabletop exercise documentation, escalation records, and post-incident reviews. If no incidents occurred during the assessment period, document that fact and retain evidence of periodic response exercises.

**Management Follow-Up:** Recommended

**Status:** Open – Evidence Improvement

*This observation does not establish that Northstar has failed to respond to actual security incidents.*

---

## 6. Findings by Priority

### High Priority – 10 Findings

1. H-01-01 – Security Risk Analysis Not Updated for Material Environmental Changes.
2. H-02-01 – Formal Risk Treatment Plan Not Established.
3. H-03-02 – Workforce Access Changes and Terminations Not Consistently Demonstrated.
4. H-04-01 – Periodic Access Reviews Not Consistently Documented.
5. H-05-02 – Organization-Wide Training Coverage Not Demonstrated.
6. H-07-01 – Backup Restoration Testing Not Sufficiently Evidenced.
7. H-09-02 – Technical Access Control Configuration Not Independently Demonstrated.
8. H-11-01 – Audit Logging Implementation and Coverage Not Independently Demonstrated.
9. H-12-01 – Authentication Configuration and Enforcement Not Independently Demonstrated.
10. H-13-01 – Transmission Security Implementation Not Independently Demonstrated.

### Moderate Priority – 5 Findings

1. H-03-01 – Formal Workforce Clearance Procedures Not Established.
2. H-05-01 – Training Completion and Follow-Up Not Fully Demonstrated.
3. H-08-01 – Workstation Safeguard Implementation Not Independently Demonstrated.
4. H-09-01 – Emergency Access Procedure Not Fully Documented.
5. H-10-01 – Information System Activity Review Documentation and Follow-Up Incomplete.

### Separate Observation

- H-06-01 – Incident Response Execution Not Demonstrated.

---

## 7. Finding Management and Tracking

All formal findings begin with an Open status.

Recommended status values:

| Status | Definition |
|---|---|
| Open | Finding has been identified and corrective action has not been completed. |
| In Progress | Remediation activities are underway. |
| Pending Validation | Management reports remediation complete; supporting evidence is awaiting assessment validation. |
| Closed | Corrective action has been validated and closure criteria have been met. |
| Accepted Risk | Management has formally accepted the residual risk with documented approval and rationale. |

A finding should not be closed solely because a policy or procedure has been updated. Closure requires evidence demonstrating that the corrective action has been implemented and validated.

## 8. Reference Materials

- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [45 CFR §164.310 – Physical Safeguards](https://www.ecfr.gov/current/title-45/section-164.310)
- [45 CFR §164.312 – Technical Safeguards](https://www.ecfr.gov/current/title-45/section-164.312)
- [HHS – HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- [NIST SP 800-66 Rev. 2](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

---

**Portfolio Disclaimer:** This register is part of a fictional compliance assessment created for educational and portfolio purposes. It does not represent an actual HIPAA audit, legal opinion, certification, or assessment of a real covered entity or business associate.
