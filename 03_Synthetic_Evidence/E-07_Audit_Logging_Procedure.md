# E-07: Audit Logging and Monitoring Procedure

**Organization:** Northstar Health Plan (Fictional)  
**Document Owner:** IT Security Manager  
**Document Type:** Security Monitoring Procedure  
**Effective Date:** January 1, 2026  
**Last Review Date:** January 1, 2026  
**Classification:** Internal – Confidential  
**Assessment References:** HIPAA Security Rule §164.308(a)(1)(ii)(D), §164.312(b)

---

## 1. Purpose

This procedure establishes requirements for generating, maintaining, reviewing, and monitoring information system activity records associated with systems containing electronic protected health information (ePHI).

The objective is to support the identification of suspicious activity, unauthorized access, and potential security incidents affecting organizational systems.

## 2. Scope

This procedure applies to information systems that create, receive, maintain, or transmit ePHI, including:

- Cloud-hosted claims management platform.
- Identity management and authentication services.
- Microsoft 365.
- Employee workstations.
- Supporting infrastructure and security services.

The procedure applies to IT personnel and other authorized individuals responsible for system monitoring and security administration.

## 3. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| IT Security Manager | Oversees security monitoring activities and coordinates review of significant findings. |
| IT Department | Maintains logging configurations and performs assigned monitoring activities. |
| Department Managers | Report suspicious activity identified within their operational areas. |
| Cloud Service Provider | Maintains applicable logging capabilities within the hosted platform according to contractual responsibilities. |

## 4. Audit Logging Requirements

Northstar relies on system-generated audit logs to record selected activities occurring within organizational systems.

Audit records may include:

- User authentication attempts.
- Successful and unsuccessful login activity.
- User account creation and modification.
- Access to sensitive application functions.
- Changes to system configurations.
- Administrative activities.
- Security-related events.

The claims management platform maintains application-level activity logs, while the identity management system maintains authentication and account administration records.

## 5. Logging Configuration and Retention

The IT department coordinates logging configuration with the applicable system administrators and cloud service provider.

Audit records are retained within the respective systems or provider-managed logging environments.

The organization expects audit records to be protected against unauthorized modification or deletion.

**Identified Process Limitation:** Northstar does not maintain a centralized inventory documenting logging coverage and retention configurations across all systems within the assessment scope.

Documentation validating audit log retention periods and access restrictions is also incomplete.

## 6. Information System Activity Review

The IT Security Manager is responsible for overseeing periodic reviews of information system activity.

Reviews are intended to identify:

- Unusual authentication activity.
- Repeated unsuccessful login attempts.
- Access from unexpected locations.
- Unauthorized account activity.
- Suspicious privileged user actions.
- Unexpected changes to sensitive records.
- Other activity that may indicate unauthorized access to ePHI.

The IT department may investigate unusual activity and escalate suspected security incidents through the established incident response process.

### 6.1 Review Frequency

The organization expects security-related system activity to be reviewed periodically.

The frequency of review may depend on the system, the sensitivity of the information, and the availability of monitoring capabilities.

**Identified Process Limitation:** A formally approved review schedule has not been established for all systems containing ePHI. Evidence demonstrating consistent completion of periodic reviews is limited.

## 7. Investigation and Escalation

When suspicious activity is identified, the IT department should:

1. Review the available audit records.
2. Identify affected user accounts and systems.
3. Determine whether unauthorized access may have occurred.
4. Escalate significant findings to the IT Security Manager.
5. Document investigation activities.
6. Initiate incident response procedures when appropriate.

Potential security incidents must be handled in accordance with E-04: Security Incident Response Procedure.

## 8. Audit Monitoring Records

The following records represent sample monitoring activities during 2026.

| Review ID | Review Date | System | Activity Reviewed | Result | Documentation Status |
|---|---|---|---|---|---|
| MON-001 | 02/15/2026 | Identity Management | Failed authentication attempts | No significant findings | Complete |
| MON-002 | 04/20/2026 | Claims Platform | User access activity | Unusual activity identified | Incomplete |
| MON-003 | 06/30/2026 | Microsoft 365 | Authentication activity | No significant findings | Complete |
| MON-004 | 09/25/2026 | Claims Platform | Administrative activity | No significant findings reported | Incomplete |

**Register Notes:**

- Monitoring records are synthetic.
- Incomplete indicates that supporting review documentation is insufficient to establish the full scope and completion of the review.
- The records do not represent a complete inventory of all monitoring activities conducted by Northstar.

## 9. Access to Audit Records

Access to audit records should be restricted to authorized personnel with appropriate business responsibilities.

The IT department is responsible for managing access to logging environments and coordinating with the cloud service provider when hosted audit records are required.

**Identified Process Limitation:** Northstar does not consistently retain evidence of periodic reviews of personnel authorized to access audit records.

## 10. Policy Review

The IT Security Manager is responsible for coordinating periodic reviews of this procedure.

Updates should be considered following significant system changes, security incidents, or changes to applicable regulatory requirements.

## 11. Assessment Considerations

The assessment should evaluate whether:

- Systems containing ePHI generate appropriate audit records.
- Audit logging capabilities are implemented.
- Audit records are protected from unauthorized access or modification.
- Information system activity is reviewed regularly.
- Suspicious activity is investigated and escalated.
- Review activities are documented.
- Logging configurations and retention practices are validated.

The presence of audit logging functionality does not independently demonstrate that system activity is regularly reviewed or that monitoring procedures are operating effectively.

## 12. Regulatory References

**HIPAA Security Rule:**

- 45 CFR §164.308(a)(1)(ii)(D) – Information System Activity Review.
- 45 CFR §164.312(b) – Audit Controls.

**Supporting Guidance:** NIST SP 800-66 Rev. 2, Implementing the HIPAA Security Rule: A Cybersecurity Resource Guide.
