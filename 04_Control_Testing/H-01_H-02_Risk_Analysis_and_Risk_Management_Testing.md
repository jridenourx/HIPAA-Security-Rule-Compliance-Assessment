# Control Testing Workpaper: H-01 and H-02

## Document Information

| Field | Details |
|---|---|
| Organization | Northstar Health Plan (Fictional) |
| Assessment Period | January 1 – October 31, 2026 |
| Assessment Snapshot | October 31, 2026 |
| Assessment Area | Administrative Safeguards |
| Assessor | Portfolio Assessment |
| Testing Method | Documentation Review |
| Evidence Reviewed | E-01: Security Risk Analysis |
| Classification | Internal – Synthetic Portfolio Assessment |

> **Important:** This workpaper documents a simulated control assessment using fictional organizational information and synthetic evidence. No production systems, actual ePHI, or real organizational records were reviewed.

---

# H-01: Risk Analysis

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-01 |
| Control Name | Risk Analysis |
| Regulatory Reference | 45 CFR §164.308(a)(1)(ii)(A) |
| Safeguard Category | Administrative |
| Implementation Specification | Required |
| Evidence Reference | E-01: Security Risk Analysis |
| Assessment Rating | Partially Effective |

### Control Requirement

Conduct an accurate and thorough assessment of the potential risks and vulnerabilities to the confidentiality, integrity, and availability of electronic protected health information held by the organization.

## 2. Testing Objective

Determine whether Northstar has documented a risk analysis that identifies potential threats and vulnerabilities affecting ePHI and evaluates the likelihood and potential impact of those risks.

The assessment also evaluates whether the documented analysis reflects the organization's technology environment as of October 31, 2026.

## 3. Testing Procedures

The following procedures were performed against the synthetic evidence provided:

| Test ID | Testing Procedure |
|---|---|
| H-01.1 | Review the risk analysis document to determine whether it identifies systems and locations where ePHI is created, received, maintained, or transmitted. |
| H-01.2 | Determine whether the analysis considers relevant human, natural, environmental, and technology-related threats. |
| H-01.3 | Review whether vulnerabilities and existing safeguards are identified. |
| H-01.4 | Determine whether the organization evaluates likelihood and potential impact when identifying risks. |
| H-01.5 | Review whether identified risks are documented and assigned an overall risk rating. |
| H-01.6 | Determine whether the risk analysis reflects material changes to the organization's environment during the assessment period. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-01 | Security Risk Analysis | Documents the organization's identified systems, threats, vulnerabilities, safeguards, and risk ratings. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-01.1 | Pass | E-01 identifies the claims management platform, Microsoft 365, managed workstations, remote access, cloud hosting, and third-party claims analytics integration as relevant environments. |
| H-01.2 | Pass | E-01 identifies external attacks, insider threats, human error, technology failures, third-party risks, and natural or environmental events. |
| H-01.3 | Pass | E-01 documents existing safeguards and identifies weaknesses associated with access management, audit review, encryption, workstation security, and other areas. |
| H-01.4 | Pass | E-01 uses qualitative likelihood and impact ratings to evaluate identified risks. |
| H-01.5 | Pass | E-01 documents eight risks with unique identifiers, descriptions, likelihood ratings, impact ratings, and overall risk classifications. |
| H-01.6 | Fail | E-01 was last updated January 15, 2026, and does not adequately assess the third-party claims analytics integration introduced in July 2026. |

## 6. Assessment Observations

### Finding H-01-01: Risk Analysis Not Updated Following Material System Change

**Condition**

The documented risk analysis was last updated on January 15, 2026.

Northstar introduced a third-party claims analytics integration in July 2026 that receives access to limited claims data. The existing risk analysis does not adequately evaluate the integration, associated data flows, vendor access, or related security risks.

**Criteria**

45 CFR §164.308(a)(1)(ii)(A) requires an accurate and thorough assessment of potential risks and vulnerabilities to the confidentiality, integrity, and availability of ePHI.

**Cause**

The available evidence does not demonstrate an established process for updating the risk analysis following significant changes to systems, services, or data flows.

**Effect / Risk**

Risks introduced by the analytics integration may not be identified or appropriately addressed. This could expose ePHI to unauthorized access, disclosure, or other security events.

**Recommendation**

Northstar should:

1. Update the risk analysis to include the claims analytics integration.
2. Document the ePHI accessed, transmitted, or maintained by the third party.
3. Evaluate vendor access, security controls, and applicable data protection measures.
4. Identify any additional threats and vulnerabilities introduced by the integration.
5. Establish a process requiring risk analysis updates following material changes to the technology environment.

**Priority:** High

## 7. Overall Assessment

<badge color="warning">Partially Effective</badge>

The organization maintains a documented risk analysis that identifies relevant systems, threats, vulnerabilities, existing safeguards, and qualitative risk ratings.

However, the analysis was not updated following a material change to the organization's technology environment in July 2026.

The existence of a documented analysis demonstrates that some risk analysis activities have occurred, but the outdated analysis limits confidence that the organization has accurately evaluated its current ePHI environment.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Additional evidence and an updated risk analysis are necessary to demonstrate that the requirement is being met.

---

# H-02: Risk Management

## 1. Control Information

| Field | Details |
|---|---|
| Control ID | H-02 |
| Control Name | Risk Management |
| Regulatory Reference | 45 CFR §164.308(a)(1)(ii)(B) |
| Safeguard Category | Administrative |
| Implementation Specification | Required |
| Evidence Reference | E-01: Security Risk Analysis |
| Assessment Rating | Partially Effective |

### Control Requirement

Implement security measures sufficient to reduce risks and vulnerabilities to electronic protected health information to a reasonable and appropriate level.

## 2. Testing Objective

Determine whether Northstar has documented and implemented a process for addressing identified security risks and vulnerabilities through appropriate safeguards and corrective actions.

The assessment considers whether identified risks are translated into actionable remediation activities and whether progress can be monitored.

## 3. Testing Procedures

| Test ID | Testing Procedure |
|---|---|
| H-02.1 | Review E-01 to determine whether identified risks are accompanied by recommended mitigation activities. |
| H-02.2 | Determine whether risk mitigation activities are assigned to responsible individuals or departments. |
| H-02.3 | Review whether remediation activities include target completion dates or established timelines. |
| H-02.4 | Determine whether remediation status is documented and monitored. |
| H-02.5 | Review whether residual risks or risk acceptance decisions are documented. |
| H-02.6 | Determine whether the organization demonstrates an ongoing process for prioritizing and addressing identified risks. |

## 4. Evidence Reviewed

| Evidence ID | Evidence Description | Relevance |
|---|---|---|
| E-01 | Security Risk Analysis | Identifies risks, existing safeguards, weaknesses, and recommended follow-up activities. |

## 5. Testing Results

| Test ID | Result | Observation |
|---|---|---|
| H-02.1 | Pass | E-01 identifies eight risks and includes recommended follow-up activities for each. |
| H-02.2 | Fail | The evidence does not identify accountable owners for individual remediation activities. |
| H-02.3 | Fail | The evidence does not establish target completion dates or remediation deadlines. |
| H-02.4 | Fail | No remediation tracking records or implementation status updates were provided. |
| H-02.5 | Fail | Residual risk determinations and documented risk acceptance decisions were not provided. |
| H-02.6 | Partial | Risks are assigned qualitative ratings, but a formal process for prioritizing, tracking, and monitoring remediation is not demonstrated. |

## 6. Assessment Observations

### Finding H-02-01: Formal Risk Remediation Tracking Not Evidenced

**Condition**

E-01 identifies eight security risks and provides recommended follow-up activities.

However, the available evidence does not demonstrate a formal risk treatment or remediation tracking process that includes:

- Assigned risk owners.
- Target remediation dates.
- Corrective action status.
- Evidence of completed remediation.
- Residual risk assessments.
- Documented risk acceptance decisions, where applicable.

**Criteria**

45 CFR §164.308(a)(1)(ii)(B) requires the implementation of security measures sufficient to reduce risks and vulnerabilities to ePHI to a reasonable and appropriate level.

**Cause**

The available documentation identifies risks and recommends corrective actions but does not demonstrate how remediation activities are assigned, tracked, implemented, and monitored.

**Effect / Risk**

Identified security weaknesses may remain unresolved or may not receive appropriate management attention. Without documented ownership and tracking, the organization may have difficulty demonstrating that identified risks are being reduced to a reasonable and appropriate level.

**Recommendation**

Northstar should establish a formal risk remediation process that includes:

1. Assigning an accountable owner to each identified risk.
2. Establishing remediation priorities based on risk severity.
3. Defining target completion dates.
4. Documenting planned safeguards and corrective actions.
5. Tracking implementation status.
6. Retaining evidence of completed remediation.
7. Evaluating residual risk after corrective actions are implemented.
8. Documenting management approval of any accepted residual risks.

**Priority:** High

## 7. Overall Assessment

<badge color="warning">Partially Effective</badge>

The organization demonstrates some risk management activity through documented risk identification, qualitative prioritization, and recommended follow-up actions.

However, the available evidence does not demonstrate a formal process for assigning, implementing, and monitoring remediation activities.

The absence of documented ownership, timelines, status tracking, and residual risk decisions limits the ability to establish that identified risks are consistently reduced to a reasonable and appropriate level.

**Assessment Conclusion:** The control is partially effective based on the available synthetic evidence. Additional documentation and evidence of implemented risk management activities are necessary to support a stronger conclusion.

---

# 8. Summary of Testing Results

| Control ID | Control Name | Testing Results | Assessment Rating | Finding |
|---|---|---|---|---|
| H-01 | Risk Analysis | 5 Pass / 1 Fail | Partially Effective | H-01-01 |
| H-02 | Risk Management | 1 Pass / 4 Fail / 1 Partial | Partially Effective | H-02-01 |

## 9. Evidence Limitations

The assessment was limited to a documentation review of E-01.

The following procedures were not performed:

- Interviews with IT or compliance personnel.
- Technical vulnerability scanning.
- Review of production system configurations.
- Independent validation of system inventories or data flows.
- Inspection of vendor security assessments.
- Review of actual remediation tickets or project tracking records.

The ratings reflect the evidence available for this simulated assessment and should not be interpreted as a conclusion about a real organization's compliance status.

## 10. References

- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – Guidance on Risk Analysis Requirements](https://www.hhs.gov/hipaa/for-professionals/security/guidance/guidance-risk-analysis/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

---

**Workpaper Status:** Completed – Synthetic Documentation Review

**Next Review:** Following receipt of additional evidence or remediation documentation.
