# Control Testing Workpaper: H-03 and H-04

## Document Information

| Field | Details |
|---|---|
| Organization | Northstar Health Plan (Fictional) |
| Assessment Period | January 1 – October 31, 2026 |
| Assessment Snapshot | October 31, 2026 |
| Assessment Area | Administrative Safeguards |
| Assessor | Portfolio Assessment |
| Testing Method | Documentation Review |
| Evidence Reviewed | E-02: Workforce Security and Access Control Policy |
| Classification | Internal – Synthetic Portfolio Assessment |

> **Important:** This workpaper documents a simulated control assessment using fictional organizational information and synthetic evidence. No production systems, actual ePHI, or real organizational records were reviewed.

---

# H-03: Workforce Security

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-03 |
| Control Name | Workforce Security |
| Regulatory Reference | 45 CFR §164.308(a)(3) |
| Safeguard Category | Administrative |
| Implementation Specifications | Addressable |
| Evidence Reference | E-02: Workforce Security and Access Control Policy |
| Assessment Rating | Partially Effective |

### Control Requirement

Implement policies and procedures to ensure that all members of the workforce have appropriate access to electronic protected health information and to prevent those workforce members who do not have access from obtaining access.

## 2. Testing Objective

Determine whether Northstar has documented workforce security procedures addressing authorization, supervision, workforce clearance, and termination.

The assessment evaluates whether available evidence demonstrates that access eligibility is appropriately determined and that workforce access is managed when employment status or job responsibilities change.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-03.1 | Review E-02 to determine whether workforce access authorization and supervision responsibilities are documented. |
| H-03.2 | Determine whether procedures exist to evaluate workforce eligibility and appropriateness before access to ePHI is granted. |
| H-03.3 | Review whether termination procedures address timely removal of access following workforce separation. |
| H-03.4 | Determine whether changes in workforce responsibilities trigger appropriate access reviews and modifications. |
| H-03.5 | Evaluate whether the available evidence demonstrates consistent execution and documentation of workforce security procedures. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-02 | Workforce Security and Access Control Policy | Documents workforce authorization, supervision, clearance expectations, and termination procedures. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-03.1 | Partial | E-02 assigns access approval responsibilities to managers and account administration responsibilities to IT. However, evidence demonstrating consistent supervision and review was not provided. |
| H-03.2 | Fail | E-02 identifies clearance expectations but acknowledges that a formal written clearance procedure and consistent clearance determination records are not available. |
| H-03.3 | Partial | E-02 documents a termination process involving HR notification and IT account deactivation. However, consistent reconciliation of separation records against active accounts is not demonstrated. |
| H-03.4 | Partial | E-02 requires access changes when workforce responsibilities change, but supporting records demonstrating consistent execution were not provided. |
| H-03.5 | Fail | The available evidence consists of policy documentation and does not establish consistent operation of workforce security procedures. |

## 6. Assessment Observations

### Finding H-03-01: Workforce Clearance Procedures Not Fully Established

**Condition**

E-02 establishes general expectations for determining whether workforce members should receive access to ePHI.

However, the policy acknowledges that Northstar does not have a formal written workforce clearance procedure or consistent documentation demonstrating that clearance determinations are completed before access is granted.

The policy does not establish a sufficiently documented process for recording and retaining workforce clearance decisions.

**Criteria**

45 CFR §164.308(a)(3)(ii)(B) addresses workforce clearance procedures intended to determine whether access to ePHI is appropriate.

**Cause**

The available documentation establishes general workforce authorization expectations but does not demonstrate a formalized clearance process with defined documentation and review requirements.

**Effect / Risk**

Individuals may receive access without sufficient documentation demonstrating that their access eligibility and appropriateness were evaluated. This could increase the risk of inappropriate workforce access to ePHI.

**Recommendation**

Northstar should:

1. Establish a documented workforce clearance procedure.
2. Define the information and approvals required before access eligibility is established.
3. Identify the responsibilities of HR, managers, and IT.
4. Document clearance determinations and retain supporting records.
5. Establish a process for reviewing clearance requirements when workforce circumstances change.

**Priority:** High

### Finding H-03-02: Termination and Workforce Status Changes Not Consistently Reconciled

**Condition**

E-02 documents procedures requiring HR to notify IT when an employee or contractor separates from the organization.

The policy also identifies the need to remove or modify access when workforce responsibilities change.

However, the evidence does not demonstrate a consistent reconciliation process comparing HR separation records and workforce changes against active system accounts.

**Criteria**

45 CFR §164.308(a)(3)(ii)(C) addresses procedures for terminating access to ePHI when the employment of a workforce member ends or as otherwise required.

**Cause**

The available documentation does not demonstrate a consistently documented process for reconciling workforce status changes against active system access.

**Effect / Risk**

Former workforce members or individuals whose job responsibilities have changed may retain access that is no longer appropriate.

**Recommendation**

Northstar should:

1. Establish a documented HR-to-IT termination notification process.
2. Define expected timelines for disabling accounts.
3. Reconcile workforce separation records against active accounts.
4. Document completed access removal.
5. Review access following internal transfers or changes in job responsibilities.
6. Retain evidence of completed termination and access modification activities.

**Priority:** High

## 7. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar has documented workforce security expectations, including manager authorization, IT account administration, workforce clearance considerations, and termination procedures.

However, the available evidence identifies deficiencies in formal workforce clearance procedures and does not demonstrate consistent execution of termination and workforce status change processes.

The absence of supporting records also limits the ability to establish that workforce security activities operate consistently.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Formal clearance procedures and stronger documentation of workforce access changes are needed.

---

# H-04: Information Access Management

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-04 |
| Control Name | Information Access Management |
| Regulatory Reference | 45 CFR §164.308(a)(4) |
| Safeguard Category | Administrative |
| Implementation Specifications | Required and Addressable, as applicable |
| Evidence Reference | E-02: Workforce Security and Access Control Policy |
| Assessment Rating | Partially Effective |

### Control Requirement

Implement policies and procedures for authorizing access to electronic protected health information that are consistent with the applicable requirements of the HIPAA Security Rule.

## 2. Testing Objective

Determine whether Northstar has documented procedures for authorizing, establishing, and modifying workforce access to systems containing ePHI.

The assessment also considers whether the organization performs appropriate access reviews and whether the clearinghouse-related implementation specification applies to the defined environment.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-04.1 | Review E-02 to determine whether access authorization responsibilities and approval requirements are documented. |
| H-04.2 | Determine whether procedures address the establishment of new user access and modification of existing permissions. |
| H-04.3 | Review whether periodic access reviews are expected and whether evidence demonstrates that they are performed. |
| H-04.4 | Determine whether the clearinghouse isolation specification applies to Northstar's defined organizational environment. |
| H-04.5 | Evaluate whether available documentation supports consistent access authorization and management. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-02 | Workforce Security and Access Control Policy | Documents access authorization, account provisioning, access modification, and periodic review expectations. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-04.1 | Partial | E-02 requires manager approval and role-based access. However, actual access request and approval records were not provided. |
| H-04.2 | Partial | E-02 documents account provisioning and modification procedures, but supporting records demonstrating consistent execution were not provided. |
| H-04.3 | Fail | E-02 acknowledges that access reviews are not consistently documented across all systems containing ePHI. |
| H-04.4 | Not Applicable | Northstar is not identified as a clearinghouse operating as part of a larger organization. The clearinghouse isolation specification is not applicable to the defined environment. |
| H-04.5 | Partial | The policy establishes appropriate access management expectations, but evidence of consistent implementation and review is incomplete. |

## 6. Assessment Observations

### Finding H-04-01: Periodic Access Reviews Not Consistently Documented

**Condition**

E-02 establishes an expectation that managers and system owners periodically review user access to confirm that permissions remain appropriate.

However, the available evidence does not demonstrate that access reviews are consistently completed and documented across all systems containing ePHI.

The assessment did not receive supporting access review records showing:

- The population of active users reviewed.
- The systems included in each review.
- Manager or system owner approval.
- Identified excessive or inappropriate permissions.
- Corrective actions resulting from the review.

**Criteria**

45 CFR §164.308(a)(4)(ii)(B) addresses access authorization, while §164.308(a)(4)(ii)(C) addresses establishing and modifying access to ePHI.

Access management processes should support appropriate authorization and continued access based on workforce responsibilities.

**Cause**

The policy establishes periodic access review expectations but does not demonstrate a consistently implemented review schedule and supporting documentation process.

**Effect / Risk**

Workforce members may retain unnecessary or excessive permissions. Inappropriate access could increase the risk of unauthorized use or disclosure of ePHI.

**Recommendation**

Northstar should:

1. Establish a recurring access review schedule.
2. Identify systems containing or providing access to ePHI.
3. Require managers or system owners to review assigned permissions.
4. Document review completion and approval.
5. Track and resolve excessive or inappropriate permissions.
6. Retain evidence of completed reviews and resulting corrective actions.

**Priority:** High

### Additional Observation: Access Authorization and Provisioning Evidence

E-02 documents manager approval and IT provisioning responsibilities.

However, the assessment did not receive individual access request records, approval documentation, or account provisioning records to validate that these procedures are consistently followed.

This represents an evidence limitation rather than proof that the access authorization process is absent.

Additional evidence should be obtained during a more comprehensive assessment.

## 7. Applicability Assessment

### Clearinghouse Functions

45 CFR §164.308(a)(4)(ii)(A) addresses procedures for isolating healthcare clearinghouse functions from other functions when a clearinghouse is part of a larger organization.

Northstar's defined environment does not identify the organization as a healthcare clearinghouse operating as part of a larger organization.

The specification is therefore considered not applicable to the current assessment.

This determination is based on the fictional organization's documented operating model and should be revisited if its business activities change.

## 8. Overall Assessment

<badge color="warning">Partially Effective</badge>

Northstar has documented access authorization and account management expectations, including manager approval, role-based permissions, IT provisioning, and access modification procedures.

However, the available evidence does not demonstrate consistent periodic access reviews or provide sufficient records to validate the operation of authorization and provisioning procedures.

The lack of documented access reviews creates a risk that users may retain permissions that are no longer appropriate.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Northstar should establish a documented access review process and retain supporting evidence of access authorization and modification activities.

---

# 9. Summary of Testing Results

| Control ID | Control Name | Testing Results | Assessment Rating | Findings |
|---|---|---|---|---|
| H-03 | Workforce Security | 2 Partial / 2 Fail / 1 Partial | Partially Effective | H-03-01, H-03-02 |
| H-04 | Information Access Management | 3 Partial / 1 Fail / 1 Not Applicable | Partially Effective | H-04-01 |

## 10. Evidence Limitations

The assessment was limited to a documentation review of E-02.

The following procedures were not performed:

- Interviews with HR, IT, or department managers.
- Inspection of actual workforce clearance records.
- Review of employee termination records.
- Sampling of access provisioning requests.
- Inspection of active user account listings.
- Independent testing of role-based access permissions.
- Review of completed periodic access certifications.

The assessment ratings reflect the available synthetic evidence and should not be interpreted as conclusions about a real organization's compliance status.

## 11. References

- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – Summary of the HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

---

**Workpaper Status:** Completed – Synthetic Documentation Review

**Next Review:** Following receipt of additional evidence or remediation documentation.
