# Control Testing Workpaper: H-05 and H-06

## Document Information

| Field | Details |
|---|---|
| Organization | Northstar Health Plan (Fictional) |
| Assessment Period | January 1 – October 31, 2026 |
| Assessment Snapshot | October 31, 2026 |
| Assessment Area | Administrative Safeguards |
| Assessor | Portfolio Assessment |
| Testing Method | Documentation Review |
| Evidence Reviewed | E-03: Security Awareness Training Records; E-04: Security Incident Response Procedure |
| Classification | Internal – Synthetic Portfolio Assessment |

> **Important:** This workpaper documents a simulated control assessment using fictional organizational information and synthetic evidence. No production systems, actual ePHI, or real organizational records were reviewed.

---

# H-05: Security Awareness and Training

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-05 |
| Control Name | Security Awareness and Training |
| Regulatory Reference | 45 CFR §164.308(a)(5) |
| Safeguard Category | Administrative |
| Implementation Specifications | Addressable |
| Evidence Reference | E-03: Security Awareness Training Records |
| Assessment Rating | Partially Effective |

### Control Requirement

Implement a security awareness and training program for all members of the workforce, including management.

The program should address security awareness and training needs relevant to protecting ePHI.

## 2. Testing Objective

Determine whether Northstar has documented a security awareness and training program and whether available evidence supports that workforce members are assigned and complete applicable training.

The assessment considers training topics, assignment and completion tracking, late or pending assignments, and the completeness of available training records.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-05.1 | Review E-03 to determine whether the organization documents a security awareness and training program. |
| H-05.2 | Review the documented curriculum to determine whether it addresses relevant security awareness topics. |
| H-05.3 | Review the sampled training records for assignment dates, completion dates, and current status. |
| H-05.4 | Identify training assignments completed after the organization's internal deadline or still pending at the assessment snapshot. |
| H-05.5 | Determine whether available records demonstrate training coverage across the workforce. |
| H-05.6 | Review whether overdue training and incomplete assignments are supported by documented follow-up or escalation. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-03 | Security Awareness Training Records | Documents the training program, curriculum topics, and a sample of workforce training assignments and completion records. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-05.1 | Pass | E-03 documents onboarding training, annual refresher training, and additional training expectations. |
| H-05.2 | Pass | The documented curriculum includes ePHI awareness, password security, phishing, incident reporting, workstation security, remote work security, and acceptable use. |
| H-05.3 | Pass | E-03 includes 12 employee records with assignment dates, completion dates, and status information. |
| H-05.4 | Fail | EMP-005 completed onboarding training 38 days after assignment, exceeding the organization's internal 30-day deadline. |
| H-05.5 | Fail | Only 12 of approximately 120 employees are represented. The available sample does not demonstrate organization-wide training coverage. |
| H-05.6 | Fail | Documentation of management follow-up for the late completion and other incomplete assignments was not provided. |

## 6. Assessment Observations

### Finding H-05-01: Training Completion and Follow-Up Not Fully Demonstrated

**Condition**

E-03 identifies one sampled employee, EMP-005, who completed onboarding training 38 calendar days after assignment.

The organization's internal requirement is completion within 30 calendar days. The employee therefore completed training eight days after the internal deadline.

The evidence also does not include documentation demonstrating management follow-up or escalation for the late completion.

EMP-012 had a pending assignment as of October 31, 2026, but remained within the organization's internal 30-day completion period. This record is not treated as an overdue training exception.

**Criteria**

45 CFR §164.308(a)(5) requires a security awareness and training program for all members of the workforce, including management.

The 30-day onboarding deadline is an internal Northstar expectation documented in E-03, not a specific deadline established by HIPAA.

**Cause**

The available evidence does not demonstrate a consistent process for documenting and escalating late training completion.

**Effect / Risk**

Workforce members may not receive security awareness training within the organization's expected timeframe. Without documented follow-up, management may have limited visibility into overdue assignments and recurring training gaps.

**Recommendation**

Northstar should:

1. Establish a process for monitoring training assignments and completion deadlines.
2. Generate periodic reports identifying overdue assignments.
3. Require managers to follow up on late training.
4. Document escalation and resolution of overdue assignments.
5. Retain evidence of management review and corrective action.

**Priority:** Moderate

### Finding H-05-02: Organization-Wide Training Coverage Not Demonstrated

**Condition**

E-03 contains training records for 12 employees from an estimated workforce of approximately 120.

The available records do not establish the training status of the remaining workforce.

The assessment also did not receive a complete workforce roster reconciled against the training population or a complete learning management system report.

**Criteria**

45 CFR §164.308(a)(5) requires a security awareness and training program for all members of the workforce, including management.

**Cause**

The available synthetic evidence is a limited sample and does not include a complete workforce training population or reconciliation.

**Effect / Risk**

Management may be unable to demonstrate that all applicable workforce members are assigned and complete security awareness training.

**Recommendation**

Northstar should:

1. Maintain a complete workforce training population.
2. Reconcile training assignments against the active workforce roster.
3. Identify employees who have not been assigned applicable training.
4. Track completion status across the organization.
5. Retain reports demonstrating workforce training coverage.
6. Document management review of incomplete or overdue training.

**Priority:** High

## 7. Implementation Specification Considerations

The following addressable implementation specifications are included in the assessment:

| Regulatory Reference | Implementation Specification | Assessment Consideration |
|---|---|---|
| §164.308(a)(5)(ii)(A) | Security Reminders | E-03 identifies ongoing security awareness and training expectations. |
| §164.308(a)(5)(ii)(B) | Protection from Malicious Software | The curriculum includes phishing and malicious software awareness topics. |
| §164.308(a)(5)(ii)(C) | Log-in Monitoring | The curriculum addresses appropriate system access and security monitoring awareness. |
| §164.308(a)(5)(ii)(D) | Password Management | The curriculum includes password and credential security. |

The presence of these topics in the documented curriculum does not independently establish that each implementation specification has been fully addressed or that training is consistently delivered.

Northstar should document its evaluation and implementation decisions for each addressable specification.

## 8. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar has documented a security awareness and training program with relevant curriculum topics and a process for assigning onboarding and annual refresher training.

However, the available evidence identifies a late training completion, does not demonstrate organization-wide training coverage, and lacks supporting documentation of management follow-up.

The sample provides limited evidence of training program activity but is insufficient to establish consistent implementation across the workforce.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Northstar should improve training population reconciliation, completion monitoring, and management follow-up.

---

# H-06: Security Incident Procedures

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-06 |
| Control Name | Security Incident Procedures |
| Regulatory Reference | 45 CFR §164.308(a)(6) |
| Safeguard Category | Administrative |
| Implementation Specifications | Required |
| Evidence Reference | E-04: Security Incident Response Procedure |
| Assessment Rating | Partially Effective |

### Control Requirement

Implement policies and procedures to address security incidents.

The implementation specifications require the organization to identify and respond to suspected or known security incidents, mitigate harmful effects, and document incidents and their outcomes.

## 2. Testing Objective

Determine whether Northstar has documented procedures for identifying, reporting, responding to, mitigating, and documenting security incidents involving its information systems and ePHI.

The assessment also considers whether available evidence demonstrates that the incident response process has been exercised or used in practice.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-06.1 | Review E-04 to determine whether a documented security incident response procedure exists. |
| H-06.2 | Determine whether the procedure addresses identification and reporting of suspected or known security incidents. |
| H-06.3 | Review whether the procedure establishes response and escalation activities for security incidents. |
| H-06.4 | Determine whether the procedure addresses mitigation of harmful effects resulting from security incidents. |
| H-06.5 | Review whether the procedure requires documentation of incidents and their outcomes. |
| H-06.6 | Determine whether evidence demonstrates that incident response procedures have been exercised or followed in practice. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-04 | Security Incident Response Procedure | Documents the organization's incident response process and expected handling of security incidents. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-06.1 | Pass | E-04 provides documented security incident response procedures. |
| H-06.2 | Pass | The procedure addresses identification and reporting of suspected or known security incidents. |
| H-06.3 | Pass | The procedure documents response and escalation expectations. |
| H-06.4 | Pass | The procedure addresses actions intended to contain incidents and mitigate harmful effects. |
| H-06.5 | Pass | The procedure establishes expectations for documenting incidents and their outcomes. |
| H-06.6 | Not Evidenced | No incident tickets, completed incident records, tabletop exercise results, or other execution evidence were provided. |

## 6. Assessment Observations

### Observation H-06-01: Incident Response Execution Not Demonstrated

**Condition**

E-04 provides documented incident response procedures addressing the identification, reporting, response, mitigation, and documentation of security incidents.

However, the assessment did not receive evidence demonstrating that the procedures have been exercised or followed in practice.

The following supporting records were not provided:

- Completed incident records.
- Incident response tickets.
- Incident investigation documentation.
- Evidence of escalation and management notification.
- Tabletop exercise results.
- Corrective action records resulting from incident response activities.

**Criteria**

45 CFR §164.308(a)(6)(i) requires policies and procedures to address security incidents.

The required implementation specifications under §164.308(a)(6)(ii) include:

- **Response and Reporting:** Identify and respond to suspected or known security incidents; mitigate, to the extent practicable, harmful effects of security incidents; and document incidents and their outcomes.

**Cause**

The available evidence consists of a documented procedure without supporting execution records or exercise results.

**Effect / Risk**

Although response expectations are documented, Northstar cannot demonstrate through the available evidence that personnel can consistently execute the procedure or that incident response activities are appropriately documented.

**Recommendation**

Northstar should:

1. Conduct periodic incident response tabletop exercises.
2. Document exercise scenarios, participants, decisions, and results.
3. Maintain incident records containing identification, investigation, response, and resolution details.
4. Document escalation and management notification activities.
5. Track corrective actions resulting from actual incidents and exercises.
6. Periodically review and update the incident response procedure.

**Priority:** Moderate

## 7. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar maintains a documented security incident response procedure that addresses the primary response and reporting expectations under the HIPAA Security Rule.

The documentation provides a basis for responding to suspected or known security incidents and describes expected mitigation and documentation activities.

However, the available evidence does not demonstrate that the procedure has been exercised or consistently followed in practice.

The absence of execution evidence limits the ability to conclude that the incident response process is operating effectively.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Northstar should retain incident records and conduct documented exercises to demonstrate implementation of the response process.

---

# 8. Summary of Testing Results

| Control ID | Control Name | Testing Results | Assessment Rating | Finding / Observation |
|---|---|---|---|---|
| H-05 | Security Awareness and Training | 3 Pass / 3 Fail | Partially Effective | H-05-01, H-05-02 |
| H-06 | Security Incident Procedures | 5 Pass / 1 Not Evidenced | Partially Effective | H-06-01 |

## 9. Evidence Limitations

The assessment was limited to documentation review of E-03 and E-04.

The following procedures were not performed:

- Interviews with HR, IT, or security personnel.
- Review of a complete workforce roster.
- Inspection of a live learning management system.
- Independent validation of training completion records.
- Review of actual security incident tickets.
- Interviews with incident response personnel.
- Observation of an incident response exercise.
- Testing of incident escalation or notification workflows.

The assessment ratings reflect the available synthetic evidence and should not be interpreted as conclusions about a real organization's compliance status.

## 10. References

- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – Summary of the HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

---

**Workpaper Status:** Completed – Synthetic Documentation Review

**Next Review:** Following receipt of additional evidence or remediation documentation.
