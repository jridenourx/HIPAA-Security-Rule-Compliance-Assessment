# H-09 and H-10 Control Testing Workpaper
**Project:** Northstar Health Plan – HIPAA Security Rule Compliance Assessment  
**Assessment Period:** January 1–October 31, 2026  
**Assessment Snapshot:** October 31, 2026  
**Assessment Type:** Simulated Compliance Assessment  
**Prepared By:** Security Compliance Assessment Team  
**Workpaper Status:** Final – Portfolio Simulation

---

## 1. Workpaper Purpose

This workpaper documents the assessment of two HIPAA Security Rule requirements:

- **H-09 – Access Control:** 45 CFR §164.312(a)
- **H-10 – Information System Activity Review:** 45 CFR §164.308(a)(1)(ii)(D)

The objective is to evaluate whether Northstar has documented safeguards and supporting evidence demonstrating that access to electronic protected health information (ePHI) is appropriately controlled and that information system activity is reviewed.

This assessment distinguishes between documented control design and evidence demonstrating that controls are configured and operating effectively.

## 2. Evidence Reviewed

| Evidence ID | Document | Purpose |
|---|---|---|
| E-02 | Access Control Policy | Documents user access requirements, emergency access, session management, and encryption expectations. |
| E-07 | Audit Logging Procedure | Documents logging expectations and procedures for reviewing information system activity. |

No production system configurations, access exports, audit logs, completed review records, or system-generated reports were provided for this assessment.

## 3. H-09 – Access Control

**Regulatory Reference:** 45 CFR §164.312(a)

**Control Objective:** Implement technical policies and procedures for electronic information systems that maintain ePHI to allow access only to authorized persons or software programs.

### 3.1 Control Requirements

| Implementation Specification | Classification | Assessment Focus |
|---|---|---|
| §164.312(a)(2)(i) – Unique User Identification | Required | Each user is assigned a unique identifier for tracking access to ePHI. |
| §164.312(a)(2)(ii) – Emergency Access Procedure | Required | Procedures exist to obtain necessary ePHI during an emergency. |
| §164.312(a)(2)(iii) – Automatic Logoff | Addressable | Electronic sessions terminate after a predetermined period of inactivity when reasonable and appropriate. |
| §164.312(a)(2)(iv) – Encryption and Decryption | Addressable | Mechanisms are implemented to encrypt and decrypt ePHI when reasonable and appropriate. |

*Addressable implementation specifications require an assessment of reasonableness and appropriateness. They are not automatically optional.*

### 3.2 Testing Procedures and Results

| Test ID | Testing Procedure | Evidence Reviewed | Result |
|---|---|---|---|
| H-09.1 | Determine whether the access control policy requires unique user identification for individuals accessing systems containing ePHI. | E-02 | Pass |
| H-09.2 | Determine whether emergency access procedures are documented and address access to necessary ePHI during emergencies. | E-02 | Partial |
| H-09.3 | Determine whether automatic logoff expectations are documented and whether supporting configuration evidence is available. | E-02 | Partial |
| H-09.4 | Determine whether encryption and decryption expectations are documented and whether supporting configuration and key-management evidence is available. | E-02 | Not Evidenced |
| H-09.5 | Review documented access control expectations, including role-based access and restrictions on routine shared-account use. | E-02 | Pass |

### 3.3 Testing Results and Observations

**Unique User Identification**

E-02 documents the requirement for unique user accounts and prohibits routine use of shared accounts. This provides evidence that Northstar has established a policy expectation for individual accountability.

However, no user account listing, system access export, or configuration evidence was provided to verify that unique identifiers are consistently implemented across systems containing ePHI.

**Emergency Access Procedure**

E-02 establishes an emergency access expectation. However, the supporting procedure does not provide sufficient detail to demonstrate how emergency access is requested, approved, granted, monitored, and subsequently reviewed.

The documentation supports partial control design but does not fully establish the emergency access process.

**Automatic Logoff**

E-02 documents automatic session termination expectations. However, no system configuration reports or screenshots were provided to verify inactivity timeout settings across systems containing ePHI.

The existence of a policy requirement does not independently demonstrate that the setting is configured or operating.

**Encryption and Decryption**

E-02 documents encryption expectations for ePHI. However, no technical evidence was provided to demonstrate encryption configuration, coverage across relevant systems, or supporting key-management practices.

Because encryption and decryption are addressable implementation specifications, Northstar should document its assessment of reasonableness and appropriateness and the rationale for its selected implementation approach.

**Role-Based Access**

E-02 documents role-based access expectations and restrictions on routine shared-account use. This supports the design of access restrictions. However, no role assignments, access review results, or system-generated access listings were provided to validate implementation.

### 3.4 Findings

**H-09-01 – Emergency Access Procedure Not Fully Documented**

- **Severity:** Moderate
- **Condition:** The access control policy establishes an emergency access expectation, but the supporting procedure does not fully document the request, approval, provisioning, monitoring, and review process.
- **Risk:** Incomplete emergency access procedures may delay appropriate access to ePHI during an emergency or result in access that is not adequately controlled.
- **Recommendation:** Develop a formal emergency access procedure defining authorization, responsible personnel, access provisioning, documentation, monitoring, and post-emergency access removal or review.
- **Management Response:** Pending

**H-09-02 – Technical Access Control Configuration Not Independently Demonstrated**

- **Severity:** High
- **Condition:** Policy documentation establishes unique user identification, automatic logoff, and encryption expectations. However, supporting system configuration evidence was not provided to demonstrate that these safeguards are implemented consistently.
- **Risk:** Without configuration validation, Northstar cannot demonstrate that access restrictions, session termination, and encryption safeguards are operating as intended across systems containing ePHI.
- **Recommendation:** Obtain system-generated evidence demonstrating unique user account implementation, inactivity timeout configurations, encryption settings, and applicable key-management practices. Document the rationale for addressable implementation specifications.
- **Management Response:** Pending

### 3.5 H-09 Overall Assessment

<text>**Overall Rating: Partially Effective**</text>

Northstar has documented access control requirements covering unique user identification, emergency access, automatic logoff, encryption, and role-based access. However, emergency access documentation requires additional detail, and technical configuration evidence was not provided to demonstrate that safeguards are implemented consistently.

The assessment does not conclude that these safeguards are absent. It concludes that the available evidence is insufficient to independently demonstrate full implementation and operating effectiveness.

---

## 4. H-10 – Information System Activity Review

**Regulatory Reference:** 45 CFR §164.308(a)(1)(ii)(D)

**Control Objective:** Implement procedures to regularly review records of information system activity, such as audit logs, access reports, and security incident tracking reports.

### 4.1 Control Overview

Information System Activity Review is an administrative safeguard focused on the organization's process for reviewing system activity records.

This requirement is distinct from H-11 – Audit Controls (§164.312(b)), which addresses the technical mechanisms used to record and examine activity in systems containing ePHI.

For H-10, the assessment focuses on whether Northstar has established a review process and whether evidence demonstrates that reviews are performed and exceptions are addressed.

### 4.2 Testing Procedures and Results

| Test ID | Testing Procedure | Evidence Reviewed | Result |
|---|---|---|---|
| H-10.1 | Determine whether a documented procedure exists for reviewing information system activity records. | E-07 | Pass |
| H-10.2 | Determine whether the procedure identifies relevant activity records, such as audit logs, access reports, and security-related records. | E-07 | Pass |
| H-10.3 | Determine whether responsibilities and review expectations are documented. | E-07 | Pass |
| H-10.4 | Obtain completed activity review records or reviewer signoffs to verify that reviews are performed. | E-07 | Not Evidenced |
| H-10.5 | Determine whether exceptions identified during reviews are documented, investigated, and escalated. | E-07 | Not Evidenced |
| H-10.6 | Determine whether review records demonstrate consistent execution during the assessment period. | E-07 | Not Evidenced |

### 4.3 Testing Results and Observations

**Documented Review Procedure**

E-07 establishes an audit logging and activity review procedure. The documentation identifies expectations for reviewing information system activity and provides a foundation for Northstar's monitoring process.

This supports the design of the control.

**Review Execution Evidence**

No completed log review records, review reports, reviewer signoffs, or other evidence demonstrating actual review execution was provided.

As a result, the assessment could not verify whether the documented review process was consistently performed during the assessment period.

**Exception Identification and Follow-Up**

No evidence was provided demonstrating how exceptions identified during activity reviews are documented, investigated, assigned, and resolved.

Without supporting records, the assessment could not determine whether suspicious or unauthorized activity is consistently escalated and addressed.

### 4.4 Findings

**H-10-01 – Information System Activity Review Operating Evidence Not Provided**

- **Severity:** Moderate
- **Condition:** E-07 documents an activity review procedure, but completed review records, reviewer signoffs, and evidence of exception follow-up were not provided.
- **Risk:** Without evidence of completed reviews, Northstar may be unable to demonstrate that potentially unauthorized or suspicious activity is identified and addressed in a timely manner.
- **Recommendation:** Retain periodic activity review records identifying the reviewer, review date, systems or log sources examined, exceptions identified, investigation results, and corrective actions taken. Establish a consistent process for tracking and closing identified exceptions.
- **Management Response:** Pending

### 4.5 H-10 Overall Assessment

<text>**Overall Rating: Partially Effective**</text>

Northstar has documented an activity review procedure through E-07. However, the assessment could not verify that reviews were consistently performed or that identified exceptions were appropriately investigated and resolved.

The absence of review records is an evidence limitation and does not establish that Northstar has never performed activity reviews.

---

## 5. Consolidated Workpaper Results

| Control | Requirement | Overall Rating | Findings |
|---|---|---|---|
| H-09 | Access Control | Partially Effective | H-09-01, H-09-02 |
| H-10 | Information System Activity Review | Partially Effective | H-10-01 |

### 5.1 Key Observations

1. **Access control documentation exists:** E-02 establishes requirements for unique user identification, emergency access, session management, encryption, and role-based access.
2. **Technical validation is limited:** System configuration evidence was not provided to demonstrate consistent implementation of access safeguards.
3. **Activity review procedures exist:** E-07 documents the expected review process.
4. **Operating evidence is incomplete:** Completed activity reviews, reviewer signoffs, and exception follow-up records were not provided.

### 5.2 Evidence Limitations

The assessment relied on synthetic policy and procedure documentation. No production system access, configuration exports, audit logs, completed review records, or technical testing results were available.

Accordingly, conclusions reflect the documentation provided and the limitations of the simulated assessment. A Partially Effective rating does not necessarily mean a control is absent; it indicates that the available evidence does not demonstrate full implementation or operating effectiveness.

## 6. Conclusion

Based on the evidence reviewed, H-09 and H-10 are assessed as **Partially Effective**.

Northstar has documented policies and procedures supporting access control and information system activity review. However, additional documentation and operating evidence are needed to demonstrate that safeguards are implemented consistently and that activity reviews are performed and exceptions are addressed.

---

## 7. Regulatory and Reference Materials

- [45 CFR §164.312 – Technical Safeguards](https://www.ecfr.gov/current/title-45/section-164.312)
- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

**Portfolio Disclaimer:** This workpaper is part of a fictional compliance assessment created for educational and portfolio purposes. It does not represent an actual HIPAA audit, legal opinion, certification, or assessment of a real covered entity or business associate.
