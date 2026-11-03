# HIPAA Security Rule Control Assessment Matrix

**Organization:** Northstar Health Plan (Fictional)  
**Assessment Type:** Simulated Compliance Assessment  
**Framework:** HIPAA Security Rule  
**Reference Guidance:** NIST SP 800-66 Rev. 2  
**Assessment Period:** January 1–October 31, 2026  
**Assessment Snapshot:** October 31, 2026  
**Control Testing Status:** Completed

---

## 1. Assessment Status Definitions

| Status | Definition |
|---|---|
| Effective | Available evidence supports that the control is appropriately designed and implemented for the assessed requirement. |
| Partially Effective | Some control elements are documented or implemented, but gaps or inconsistencies remain. |
| Ineffective | Available evidence demonstrates that the control is missing, materially deficient, or not implemented. |
| Not Evidenced | Available documentation is insufficient to determine whether the control is implemented. |
| Not Applicable | The requirement or implementation specification does not apply to the defined environment, with supporting rationale documented. |

**Important:** A control-level rating summarizes the assessment of the applicable standard and its relevant implementation specifications. Individual implementation specifications may have different test results. A Not Applicable determination for one specification does not automatically make the entire control Not Applicable.

## 2. Control Assessment Matrix

| ID | Safeguard Category | HIPAA Reference | Control Area | Implementation Specifications | Evidence Reference | Status |
|---|---|---|---|---|---|---|
| H-01 | Administrative | §164.308(a)(1)(ii)(A) | Risk Analysis | Risk Analysis (Required) | E-01 | Partially Effective |
| H-02 | Administrative | §164.308(a)(1)(ii)(B) | Risk Management | Risk Management (Required) | E-01 | Partially Effective |
| H-03 | Administrative | §164.308(a)(3) | Workforce Security | Authorization and/or Supervision (Addressable); Workforce Clearance Procedure (Addressable); Termination Procedures (Addressable) | E-02 | Partially Effective |
| H-04 | Administrative | §164.308(a)(4) | Information Access Management | Access Authorization (Addressable); Access Establishment and Modification (Addressable); Isolating Health Care Clearinghouse Functions (Not Applicable to Northstar's defined environment) | E-02 | Partially Effective |
| H-05 | Administrative | §164.308(a)(5) | Security Awareness and Training | Security Reminders (Addressable); Protection from Malicious Software (Addressable); Log-in Monitoring (Addressable); Password Management (Addressable) | E-03; E-02; E-07 | Partially Effective |
| H-06 | Administrative | §164.308(a)(6) | Security Incident Procedures | Response and Reporting (Required) | E-04 | Partially Effective |
| H-07 | Administrative | §164.308(a)(7) | Contingency Planning | Data Backup Plan (Required); Disaster Recovery Plan (Required); Emergency Mode Operation Plan (Required); Testing and Revision Procedures (Addressable); Applications and Data Criticality Analysis (Addressable) | E-05 | Partially Effective |
| H-08 | Physical | §164.310(b); §164.310(c) | Workstation Use and Security | No separate implementation specifications | E-06 | Partially Effective |
| H-09 | Technical | §164.312(a) | Access Control | Unique User Identification (Required); Emergency Access Procedure (Required); Automatic Logoff (Addressable); Encryption and Decryption (Addressable) | E-02 | Partially Effective |
| H-10 | Administrative | §164.308(a)(1)(ii)(D) | Information System Activity Review | Information System Activity Review (Required) | E-07 | Partially Effective |
| H-11 | Technical | §164.312(b) | Audit Controls | Audit Controls Standard (No separate implementation specifications) | E-07 | Partially Effective |
| H-12 | Technical | §164.312(d) | Person or Entity Authentication | Person or Entity Authentication Standard (No separate implementation specifications) | E-02 | Partially Effective |
| H-13 | Technical | §164.312(e) | Transmission Security | Integrity Controls (Addressable); Encryption (Addressable) | E-08 | Partially Effective |

## 3. Implementation Specification Assessment Notes

### 3.1 Required Specifications

Required implementation specifications must be implemented when applicable.

The assessment evaluates whether the organization has established appropriate safeguards and whether supporting evidence demonstrates implementation.

### 3.2 Addressable Specifications

Addressable implementation specifications must be evaluated individually.

For each specification, the assessment considers whether:

1. The specification is reasonable and appropriate for Northstar's environment.
2. The specification has been implemented when reasonable and appropriate.
3. An equivalent alternative security measure has been implemented when the original specification is not reasonable and appropriate, if an alternative measure is reasonable and appropriate.
4. The organization's determination and supporting rationale are documented.

An Addressable designation does not mean the implementation specification can simply be ignored. The organization must document its assessment and implementation decision.

### 3.3 Not Applicable Specifications

The implementation specification for isolating health care clearinghouse functions under §164.308(a)(4)(ii)(A) is not applicable to Northstar's defined environment because the fictional organization does not operate a health care clearinghouse as part of a larger organization.

This determination is limited to the fictional organizational scenario and should be revisited if the organization's operating environment changes.

The H-04 control remains Partially Effective because other applicable elements of Information Access Management were assessed and deficiencies were identified.

## 4. Evidence Mapping

The following evidence documents support the assessment.

| Evidence ID | Document | Primary Assessment Areas |
|---|---|---|
| E-01 | Security Risk Analysis | Risk Analysis and Risk Management |
| E-02 | Access Control Policy and Procedures | Workforce Security, Information Access Management, Access Control, Authentication |
| E-03 | Security Awareness and Training Records | Security Awareness and Training |
| E-04 | Security Incident Response Procedure | Security Incident Procedures |
| E-05 | Contingency Plan | Contingency Planning |
| E-06 | Workstation Security Policy | Workstation Use and Workstation Security |
| E-07 | Audit Logging and Monitoring Procedure | Information System Activity Review and Audit Controls |
| E-08 | Transmission Security Policy | Transmission Security |

## 5. Assessment Summary

All 13 selected controls have completed control-testing workpapers.

| Assessment Rating | Number of Controls |
|---|---:|
| Effective | 0 |
| Partially Effective | 13 |
| Ineffective | 0 |
| Not Evidenced | 0 |
| Not Applicable | 0 |
| **Total** | **13** |

The matrix reports overall control-level conclusions. Individual test procedures and implementation specifications may have results such as Pass, Partial, Fail, Not Evidenced, or Not Applicable.

A control rated Partially Effective may contain individual requirements that passed testing alongside deficiencies or evidence limitations.

## 6. Assessment Notes

- All 13 selected controls have completed testing workpapers.
- Evidence references identify the primary supporting documents for each assessment area.
- Individual implementation specifications were evaluated separately where applicable.
- Assessment conclusions distinguish between control deficiencies, documentation gaps, and insufficient supporting evidence.
- A documented policy does not independently demonstrate that a control is implemented or operating effectively.
- Addressable implementation specifications were considered based on the fictional organization's environment and available documentation.
- Not Applicable determinations include supporting rationale.
- Findings and recommended corrective actions will be maintained in the consolidated Findings Register and Corrective Action Plan.

## 7. Regulatory References

- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [45 CFR §164.310 – Physical Safeguards](https://www.ecfr.gov/current/title-45/section-164.310)
- [45 CFR §164.312 – Technical Safeguards](https://www.ecfr.gov/current/title-45/section-164.312)
- [45 CFR §164.306(d) – Required and Addressable Implementation Specifications](https://www.ecfr.gov/current/title-45/section-164.306)
- [HHS – Summary of the HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

**Portfolio Disclaimer:** This matrix is part of a fictional compliance assessment created for educational and portfolio purposes. It does not represent an actual HIPAA audit, legal opinion, certification, or assessment of a real covered entity or business associate.
