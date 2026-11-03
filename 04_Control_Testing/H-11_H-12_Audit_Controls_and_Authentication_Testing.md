# H-11 and H-12 Control Testing Workpaper

**Project:** Northstar Health Plan – HIPAA Security Rule Compliance Assessment  
**Assessment Period:** January 1–October 31, 2026  
**Assessment Snapshot:** October 31, 2026  
**Assessment Type:** Simulated Compliance Assessment  
**Prepared By:** Security Compliance Assessment Team  
**Workpaper Status:** Final – Portfolio Simulation

---

## 1. Workpaper Purpose

This workpaper documents the assessment of two HIPAA Security Rule requirements:

- **H-11 – Audit Controls:** 45 CFR §164.312(b)
- **H-12 – Person or Entity Authentication:** 45 CFR §164.312(d)

The objective is to evaluate whether Northstar has documented and implemented mechanisms to record and examine activity in systems containing ePHI and procedures to verify the identity of individuals or entities seeking access.

The assessment distinguishes documented policies and procedures from evidence demonstrating technical implementation and operating effectiveness.

## 2. Evidence Reviewed

| Evidence ID | Document | Purpose |
|---|---|---|
| E-02 | Access Control Policy | Documents authentication expectations, password requirements, and remote access safeguards. |
| E-07 | Audit Logging Procedure | Documents expectations for recording and reviewing information system activity. |

No production system configurations, authentication logs, audit log samples, or technical testing results were provided.

---

## 3. H-11 – Audit Controls

**Regulatory Reference:** 45 CFR §164.312(b)

**Control Objective:** Implement hardware, software, and/or procedural mechanisms that record and examine activity in information systems containing or using ePHI.

### 3.1 Control Overview

Audit controls support the ability to record and examine activity within systems containing ePHI.

Examples include:

- User access and authentication activity.
- Changes to user permissions and system configurations.
- Access to sensitive information.
- Administrative activity.
- Security-related events and exceptions.

The assessment considers whether Northstar has documented audit logging expectations and whether evidence demonstrates that relevant system activity is captured, retained, protected, and available for examination.

This requirement is distinct from H-10 – Information System Activity Review (§164.308(a)(1)(ii)(D)). H-11 addresses the mechanisms that record and examine activity; H-10 addresses the organizational process for reviewing those records.

### 3.2 Testing Procedures and Results

| Test ID | Testing Procedure | Evidence Reviewed | Result |
|---|---|---|---|
| H-11.1 | Determine whether a documented procedure establishes audit logging expectations for systems containing ePHI. | E-07 | Pass |
| H-11.2 | Determine whether relevant information system activity and security events are identified for logging. | E-07 | Partial |
| H-11.3 | Determine whether audit logging expectations address access to and protection of recorded activity. | E-07 | Partial |
| H-11.4 | Obtain system-generated evidence demonstrating that audit logging is enabled on systems containing ePHI. | E-07 | Not Evidenced |
| H-11.5 | Determine whether audit records are retained and protected against unauthorized alteration or deletion. | E-07 | Not Evidenced |
| H-11.6 | Obtain representative audit log samples to verify that recorded activity can be retrieved and examined. | E-07 | Not Evidenced |

### 3.3 Testing Results and Observations

**Documented Logging Expectations**

E-07 establishes an audit logging procedure and documents expectations for recording information system activity.

This provides evidence that Northstar has recognized the need for audit logging and established a procedural foundation.

**Logging Coverage**

The available documentation provides a general basis for audit logging. However, no system inventory or configuration reports were provided to establish whether logging is enabled across all relevant systems containing ePHI.

The assessment could not verify the completeness of logging coverage or determine whether important activity is consistently captured.

**Audit Log Protection and Retention**

No technical configuration reports, retention settings, access restrictions, or other supporting records were provided to demonstrate that audit records are appropriately protected and retained.

**Availability of Audit Records**

No representative audit log samples or system-generated reports were provided. Therefore, the assessment could not verify whether recorded activity can be retrieved and examined when needed.

### 3.4 Findings

**H-11-01 – Audit Logging Implementation and Coverage Not Independently Demonstrated**

- **Severity:** High
- **Condition:** E-07 documents audit logging expectations, but system configuration evidence and representative audit log samples were not provided to demonstrate that logging mechanisms are implemented across systems containing ePHI.
- **Risk:** Incomplete or improperly configured audit logging may limit Northstar's ability to identify unauthorized activity, investigate security incidents, and establish accountability for access to ePHI.
- **Recommendation:** Maintain an inventory of systems containing ePHI and obtain system-generated evidence demonstrating audit logging coverage. Document relevant events captured, retention settings, access restrictions, and procedures for retrieving and examining audit records.
- **Management Response:** Pending

### 3.5 H-11 Overall Assessment

**Overall Rating: Partially Effective**

Northstar has documented audit logging expectations through E-07. However, the assessment could not independently verify that audit logging mechanisms are enabled across relevant systems, that audit records are protected and retained, or that representative records can be retrieved.

The available evidence supports the design of the control but is insufficient to demonstrate technical implementation and operating effectiveness.

---

## 4. H-12 – Person or Entity Authentication

**Regulatory Reference:** 45 CFR §164.312(d)

**Control Objective:** Implement procedures to verify that a person or entity seeking access to electronic protected health information is the one claimed.

### 4.1 Control Overview

Authentication helps establish that individuals and entities accessing systems containing ePHI are who they claim to be.

Examples of authentication mechanisms include:

- Password-based authentication.
- Multifactor authentication.
- Authentication through approved identity providers.
- Controls governing authentication for remote access.
- Procedures for managing authentication credentials.

The assessment focuses on the authentication requirements documented in E-02 and whether evidence demonstrates that those requirements are implemented.

### 4.2 Testing Procedures and Results

| Test ID | Testing Procedure | Evidence Reviewed | Result |
|---|---|---|---|
| H-12.1 | Determine whether the access control policy establishes authentication requirements for users accessing systems containing ePHI. | E-02 | Pass |
| H-12.2 | Determine whether password and credential requirements are documented. | E-02 | Pass |
| H-12.3 | Determine whether multifactor authentication expectations are documented for remote access. | E-02 | Pass |
| H-12.4 | Obtain system configuration evidence demonstrating that documented authentication requirements are enforced. | E-02 | Not Evidenced |
| H-12.5 | Determine whether authentication records or other supporting evidence demonstrate successful and unsuccessful authentication activity. | E-02 | Not Evidenced |
| H-12.6 | Determine whether authentication requirements are consistently applied to relevant systems and access methods involving ePHI. | E-02 | Not Evidenced |

### 4.3 Testing Results and Observations

**Documented Authentication Requirements**

E-02 establishes authentication expectations for users accessing systems containing ePHI. The policy includes password requirements and multifactor authentication expectations for remote access.

This supports the design of the authentication control.

**Multifactor Authentication**

The policy documents multifactor authentication expectations for remote access. However, no identity provider configuration reports, authentication policy exports, or other technical evidence were provided to demonstrate that multifactor authentication is enforced.

The assessment therefore could not verify whether the documented requirement is consistently applied.

**Authentication Configuration and Enforcement**

No system configuration reports or authentication policy exports were provided to demonstrate how authentication requirements are configured across relevant systems.

The assessment could not independently verify whether authentication requirements are consistently enforced for users and other entities accessing ePHI.

**Authentication Activity**

No authentication logs or reports were provided to demonstrate how successful and unsuccessful authentication attempts are recorded or monitored.

This is an evidence limitation and does not establish that authentication controls are absent.

### 4.4 Findings

**H-12-01 – Authentication Configuration and Enforcement Not Independently Demonstrated**

- **Severity:** High
- **Condition:** E-02 documents password and multifactor authentication expectations, including requirements for remote access. However, supporting technical configuration evidence and authentication records were not provided to demonstrate that these requirements are enforced across relevant systems.
- **Risk:** Authentication requirements that are not consistently implemented may increase the risk of unauthorized access to systems containing ePHI.
- **Recommendation:** Obtain identity provider and system configuration reports demonstrating authentication settings, including multifactor authentication enforcement for applicable remote access methods. Review representative authentication records and document the systems and access methods covered by the authentication requirements.
- **Management Response:** Pending

### 4.5 H-12 Overall Assessment

**Overall Rating: Partially Effective**

Northstar has documented authentication requirements through E-02, including password controls and multifactor authentication expectations for remote access.

However, the assessment could not verify that these requirements are technically enforced or consistently applied across relevant systems. Additional configuration evidence and authentication records are needed to demonstrate implementation and operating effectiveness.

---

## 5. Consolidated Workpaper Results

| Control | Requirement | Overall Rating | Findings |
|---|---|---|---|
| H-11 | Audit Controls | Partially Effective | H-11-01 |
| H-12 | Person or Entity Authentication | Partially Effective | H-12-01 |

### 5.1 Key Observations

1. **Audit logging procedures exist:** E-07 documents expectations for recording information system activity.
2. **Technical logging evidence is limited:** System configurations, representative audit logs, and supporting retention and protection evidence were not provided.
3. **Authentication requirements exist:** E-02 documents password requirements and multifactor authentication expectations for remote access.
4. **Authentication enforcement is unverified:** Configuration reports and authentication records were not available to demonstrate consistent implementation.

### 5.2 Evidence Limitations

The assessment relied on synthetic policy and procedure documentation. No production system access, technical configuration exports, audit log samples, authentication records, or system-generated reports were available.

Conclusions reflect the evidence provided and the limitations of the simulated assessment. A Partially Effective rating does not necessarily mean a control is absent; it indicates that the available evidence does not demonstrate full implementation or operating effectiveness.

---

## 6. Conclusion

Based on the evidence reviewed, H-11 and H-12 are assessed as **Partially Effective**.

Northstar has documented procedures and expectations supporting audit logging and authentication. However, additional technical evidence is needed to demonstrate that audit mechanisms are implemented across systems containing ePHI and that authentication requirements are consistently enforced.

The organization should prioritize obtaining system-generated configuration evidence, representative audit records, and authentication reports to support future control validation.

---

## 7. Regulatory and Reference Materials

- [45 CFR §164.312 – Technical Safeguards](https://www.ecfr.gov/current/title-45/section-164.312)
- [45 CFR §164.308 – Administrative Safeguards](https://www.ecfr.gov/current/title-45/section-164.308)
- [HHS – HIPAA Security Rule](https://www.hhs.gov/hipaa/for-professionals/security/index.html)
- [NIST SP 800-66 Rev. 2 – Implementing the HIPAA Security Rule](https://csrc.nist.gov/pubs/sp/800/66/r2/final)

**Portfolio Disclaimer:** This workpaper is part of a fictional compliance assessment created for educational and portfolio purposes. It does not represent an actual HIPAA audit, legal opinion, certification, or assessment of a real covered entity or business associate.
