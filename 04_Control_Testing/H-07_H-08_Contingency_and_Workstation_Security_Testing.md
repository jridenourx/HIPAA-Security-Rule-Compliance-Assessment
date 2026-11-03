# Control Testing Workpaper: H-07 and H-08

## Document Information

| Field | Details |
|---|---|
| Organization | Northstar Health Plan (Fictional) |
| Assessment Period | January 1 – October 31, 2026 |
| Assessment Snapshot | October 31, 2026 |
| Assessment Areas | Administrative and Physical Safeguards |
| Assessor | Portfolio Assessment |
| Testing Method | Documentation Review |
| Evidence Reviewed | E-05: Contingency Plan; E-06: Workstation Use and Security Policy |
| Classification | Internal – Synthetic Portfolio Assessment |

> **Important:** This workpaper documents a simulated control assessment using fictional organizational information and synthetic evidence. No production systems, actual ePHI, or real organizational records were reviewed.

---

# H-07: Contingency Planning

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-07 |
| Control Name | Contingency Planning |
| Regulatory Reference | 45 CFR §164.308(a)(7) |
| Safeguard Category | Administrative |
| Implementation Specifications | Required and Addressable |
| Evidence Reference | E-05: Contingency Plan |
| Assessment Rating | Partially Effective |

### Control Requirement

Establish and implement policies and procedures for responding to an emergency or other occurrence that damages systems containing electronic protected health information.

The contingency plan should address data backup, disaster recovery, emergency mode operations, testing and revision, and applications and data criticality analysis.

## 2. Testing Objective

Determine whether Northstar has documented contingency planning procedures intended to protect ePHI and support the recovery of critical systems following an emergency or disruptive event.

The assessment considers whether the plan addresses required implementation specifications and whether available evidence demonstrates that recovery procedures have been tested and maintained.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-07.1 | Review E-05 to determine whether data backup procedures are documented. |
| H-07.2 | Determine whether disaster recovery procedures address restoration of systems and ePHI following a disruptive event. |
| H-07.3 | Review whether emergency mode operations procedures address continued access to necessary information during an emergency. |
| H-07.4 | Determine whether the plan establishes expectations for testing and revision of contingency procedures. |
| H-07.5 | Review whether critical applications and data are identified to support recovery prioritization. |
| H-07.6 | Determine whether available evidence demonstrates that backup restoration and recovery procedures have been tested. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-05 | Contingency Plan | Documents backup, disaster recovery, emergency operations, and contingency planning expectations. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-07.1 | Pass | E-05 documents data backup expectations intended to support recovery of ePHI and critical business information. |
| H-07.2 | Pass | E-05 addresses disaster recovery and restoration of critical systems following a disruptive event. |
| H-07.3 | Pass | E-05 addresses emergency mode operations and continued access to necessary information during an emergency. |
| H-07.4 | Partial | The plan addresses testing and revision expectations, but supporting evidence demonstrating completed tests and documented follow-up was not available. |
| H-07.5 | Pass | E-05 addresses identification and prioritization of critical applications and data for recovery planning. |
| H-07.6 | Fail | The available evidence does not sufficiently demonstrate completed backup restoration testing or documented results. |

## 6. Assessment Observations

### Finding H-07-01: Backup Restoration Testing Not Sufficiently Evidenced

**Condition**

E-05 documents contingency planning expectations, including backup and recovery activities.

However, the available evidence does not sufficiently demonstrate that backup restoration procedures have been periodically tested or that test results have been documented and reviewed.

The assessment did not receive completed restoration test records showing:

- The systems or data selected for testing.
- The date and scope of each test.
- Whether restoration was successful.
- Any issues identified during testing.
- Corrective actions resulting from unsuccessful or incomplete tests.
- Management review or approval of test results.

**Criteria**

45 CFR §164.308(a)(7) addresses contingency planning.

Relevant implementation specifications include:

- §164.308(a)(7)(ii)(A) — Data Backup Plan.
- §164.308(a)(7)(ii)(B) — Disaster Recovery Plan.
- §164.308(a)(7)(ii)(C) — Emergency Mode Operation Plan.
- §164.308(a)(7)(ii)(D) — Testing and Revision Procedures.
- §164.308(a)(7)(ii)(E) — Applications and Data Criticality Analysis.

The first three specifications are required. Testing and Revision Procedures and Applications and Data Criticality Analysis are addressable.

**Cause**

The available evidence documents contingency planning expectations but does not establish that restoration testing is consistently performed and retained as documented evidence.

**Effect / Risk**

Northstar may be unable to demonstrate that backups can be successfully restored when needed. Incomplete testing could delay recovery of systems containing ePHI and disrupt critical business operations.

**Recommendation**

Northstar should:

1. Establish a documented backup restoration testing schedule.
2. Identify critical systems and data included in each test.
3. Record test dates, procedures, and results.
4. Document recovery issues and corrective actions.
5. Retain evidence of successful restoration.
6. Require appropriate management review of test results.
7. Update contingency procedures when testing identifies weaknesses.

**Priority:** High

## 7. Implementation Specification Assessment

| Regulatory Reference | Implementation Specification | Assessment Consideration |
|---|---|---|
| §164.308(a)(7)(ii)(A) | Data Backup Plan | Backup expectations are documented in E-05. Actual backup execution was not independently validated. |
| §164.308(a)(7)(ii)(B) | Disaster Recovery Plan | Recovery procedures are documented in E-05. Actual recovery performance was not independently validated. |
| §164.308(a)(7)(ii)(C) | Emergency Mode Operation Plan | Emergency operations expectations are documented in E-05. Operational execution was not tested. |
| §164.308(a)(7)(ii)(D) | Testing and Revision Procedures | Testing expectations are documented, but supporting evidence of completed restoration tests is insufficient. |
| §164.308(a)(7)(ii)(E) | Applications and Data Criticality Analysis | Critical applications and data are addressed for recovery prioritization. Independent validation was not performed. |

Addressable implementation specifications must be evaluated for reasonableness and appropriateness. They are not automatically optional.

## 8. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar maintains a documented contingency plan addressing data backup, disaster recovery, emergency mode operations, and recovery prioritization.

However, the available evidence does not sufficiently demonstrate that backup restoration and recovery procedures have been tested and documented.

The absence of supporting test results limits the ability to establish that the organization can successfully recover systems and ePHI following a disruptive event.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Northstar should conduct and document backup restoration testing and retain evidence of corrective actions and management review.

---

# H-08: Workstation Use and Security

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-08 |
| Control Name | Workstation Use and Security |
| Regulatory References | 45 CFR §164.310(b) and §164.310(c) |
| Safeguard Category | Physical |
| Implementation Specifications | Standards under §164.310(b) and §164.310(c) |
| Evidence Reference | E-06: Workstation Use and Security Policy |
| Assessment Rating | Partially Effective |

### Control Requirements

**Workstation Use — §164.310(b)**

Implement policies and procedures that specify the proper functions to be performed, the manner in which those functions are to be performed, and the physical attributes of the surroundings of a specific workstation or class of workstations that can access ePHI.

**Workstation Security — §164.310(c)**

Implement physical safeguards for all workstations that access ePHI to restrict access to authorized users.

## 2. Testing Objective

Determine whether Northstar has documented workstation use requirements and physical safeguards intended to prevent unauthorized access to workstations that may access ePHI.

The assessment considers authorized use, screen privacy, unattended workstations, remote work practices, physical protection, and the availability of supporting implementation evidence.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-08.1 | Review E-06 to determine whether appropriate workstation use requirements are documented. |
| H-08.2 | Determine whether the policy addresses screen privacy, unattended workstations, and protection against unauthorized viewing. |
| H-08.3 | Review whether remote workstation use and security expectations are documented. |
| H-08.4 | Determine whether physical safeguards are documented to restrict workstation access to authorized users. |
| H-08.5 | Review whether responsibilities for workstation maintenance and reporting security concerns are assigned. |
| H-08.6 | Determine whether available evidence demonstrates that workstation safeguards are consistently implemented. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-06 | Workstation Use and Security Policy | Documents acceptable workstation use, screen privacy, remote work security, physical protection, and reporting expectations. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-08.1 | Pass | E-06 documents authorized workstation use and restrictions on inappropriate use of systems containing ePHI. |
| H-08.2 | Pass | E-06 addresses screen privacy, workstation locking, and protection of unattended workstations. |
| H-08.3 | Pass | E-06 establishes expectations for remote workstation use and protection against unauthorized physical access. |
| H-08.4 | Pass | E-06 documents physical protection expectations, including securing devices and restricting access to authorized users. |
| H-08.5 | Pass | E-06 assigns responsibilities for workstation maintenance, reporting security concerns, and reinforcing workstation requirements. |
| H-08.6 | Not Evidenced | No physical inspection records, workstation configuration reports, or other implementation evidence were provided. |

## 6. Assessment Observations

### Finding H-08-01: Workstation Safeguard Implementation Not Independently Demonstrated

**Condition**

E-06 documents workstation use and security requirements, including authorized use, screen privacy, unattended workstation protection, remote work security, and physical protection.

However, the assessment did not receive supporting evidence demonstrating that these requirements are consistently implemented across Northstar's workstations.

The following evidence was not provided:

- Workstation inspection records.
- Endpoint configuration reports.
- Records of workstation security reviews.
- Evidence of screen-lock configuration across applicable devices.
- Physical security review documentation.
- Records demonstrating follow-up on identified workstation security issues.

**Criteria**

45 CFR §164.310(b) requires policies and procedures addressing appropriate workstation use.

45 CFR §164.310(c) requires physical safeguards for workstations that access ePHI to restrict access to authorized users.

**Cause**

The available evidence establishes documented workstation requirements but does not include supporting records demonstrating consistent implementation or periodic review.

**Effect / Risk**

Workstations may not consistently be protected against unauthorized physical access or viewing. This could expose ePHI to unauthorized individuals, particularly in shared or remote work environments.

**Recommendation**

Northstar should:

1. Establish a documented workstation security review process.
2. Maintain an inventory of workstations authorized to access ePHI.
3. Validate workstation locking and applicable endpoint security settings.
4. Perform periodic physical workstation security reviews.
5. Document identified weaknesses and corrective actions.
6. Reinforce remote workstation privacy and physical protection expectations with workforce members.

**Priority:** Moderate

## 7. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar maintains a documented workstation policy addressing appropriate workstation use and physical safeguards.

The policy includes expectations for authorized use, screen privacy, unattended workstations, remote work, physical protection, and reporting security concerns.

However, the available evidence does not independently demonstrate that these safeguards are consistently implemented across the workstation environment.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Additional implementation evidence and periodic workstation security reviews are needed to support a stronger conclusion.

---

# 8. Summary of Testing Results

| Control ID | Control Name | Testing Results | Assessment Rating | Finding |
|---|---|---|---|---|
| H-07 | Contingency Planning | 4 Pass / 1 Partial / 1 Fail | Partially Effective | H-07-01 |
| H-08 | Workstation Use and Security | 5 Pass / 1 Not Evidenced | Partially Effective | H-08-01 |

## 9. Evidence Limitations

The assessment was limited to documentation review of E-05 and E-06.

The following procedures were not performed:

- Inspection of backup systems or backup configurations.
- Independent restoration of backed-up data.
- Testing of disaster recovery procedures.
- Observation of emergency mode operations.
- Interviews with recovery personnel.
- Physical inspection of workstations.
- Review of endpoint management configurations.
- Observation of remote work environments.
- Inspection of workstation security review records.

The assessment ratings reflect the available synthetic evidence and should not be interpreted as conclusions about a real organization's compliance status.

## 10. Scope Clarification

This workpaper assesses Workstation Use under §164.310(b) and Workstation Security under §164.310(c).

The following requirements remain outside the current assessment:

- Facility Access Controls — §164.310(a).
- Device and Media Controls — §164.310(d).

No conclusion is made regarding the effectiveness of those excluded safeguards.

## 11. References

- [45 CFR §164.310 – Physical Safeguards](https://www.ecfr.gov/current/title-45/section-164.310)
- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – Summary of the HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

---

**Workpaper Status:** Completed – Synthetic Documentation Review

**Next Review:** Following receipt of additional evidence or remediation documentation.
