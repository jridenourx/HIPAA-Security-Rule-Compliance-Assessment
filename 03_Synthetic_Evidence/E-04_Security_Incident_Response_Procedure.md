# E-04: Security Incident Response Procedure

**Organization:** Northstar Health Plan (Fictional)  
**Document Owner:** IT Security Manager  
**Document Type:** Security Policy and Procedures  
**Effective Date:** January 1, 2026  
**Last Review Date:** January 1, 2026  
**Classification:** Internal – Confidential  
**Assessment Reference:** HIPAA Security Rule §164.308(a)(6)

---

## 1. Purpose

This procedure establishes requirements for identifying, reporting, responding to, mitigating, and documenting security incidents affecting Northstar Health Plan's information systems.

The objective is to minimize the impact of security incidents and protect the confidentiality, integrity, and availability of electronic protected health information (ePHI).

## 2. Scope

This procedure applies to:

- All Northstar employees and workforce members.
- Contractors and authorized third-party personnel.
- Information systems that create, receive, maintain, or transmit ePHI.
- The cloud-hosted claims management platform.
- Employee workstations and organizational email systems.
- Organizational identity management and authentication services.

All workforce members are responsible for reporting suspected or confirmed security incidents.

## 3. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| IT Security Manager | Coordinates incident response activities and oversees incident documentation. |
| IT Department | Investigates technical incidents, contains threats, and supports recovery activities. |
| Human Resources | Coordinates workforce-related incident matters when applicable. |
| Department Managers | Report incidents and assist with operational response activities. |
| Workforce Members | Promptly report suspected security incidents. |
| Cloud Service Provider | Provides technical support and incident notifications according to applicable contractual arrangements. |

## 4. Security Incident Identification

A security incident is an attempted or successful unauthorized access, use, disclosure, modification, or destruction of information, or interference with system operations.

Examples include:

- Unauthorized access to systems containing ePHI.
- Suspected compromise of workforce credentials.
- Malware or ransomware infections.
- Phishing attempts resulting in credential disclosure.
- Unauthorized disclosure of member information.
- Loss or theft of devices containing sensitive information.
- Suspicious system activity or unexpected changes to records.
- Unauthorized modification or destruction of electronic information.

## 5. Incident Reporting

Workforce members must report suspected security incidents to the IT department through the organization's designated reporting channel.

Reports should include, when available:

- Date and time of the incident.
- Name or department of the reporting employee.
- Description of the suspected incident.
- Systems or information potentially affected.
- Known operational impact.
- Actions already taken.

The IT department is responsible for recording reported incidents in the organization's IT service management system.

## 6. Incident Response Procedures

Northstar follows a general incident response process consisting of the following activities.

### 6.1 Identification

The IT department evaluates reported incidents to determine whether a security incident has occurred.

Initial activities may include:

- Reviewing available system logs.
- Interviewing the reporting workforce member.
- Identifying potentially affected systems.
- Determining whether ePHI may have been involved.
- Notifying the IT Security Manager.

### 6.2 Containment

When necessary, the IT department takes steps to limit further exposure or operational impact.

Containment activities may include:

- Disabling compromised user accounts.
- Resetting affected credentials.
- Isolating affected workstations.
- Restricting access to impacted applications.
- Coordinating containment activities with the cloud service provider.

### 6.3 Investigation

The IT Security Manager coordinates with the IT department to investigate the incident.

Investigation activities may include:

- Reviewing authentication and audit logs.
- Identifying affected user accounts.
- Determining the systems and information involved.
- Establishing the approximate incident timeline.
- Evaluating whether unauthorized access or disclosure occurred.

### 6.4 Mitigation and Recovery

The IT department coordinates remediation activities to reduce the impact of the incident and restore normal operations.

Activities may include:

- Removing malicious software.
- Resetting compromised credentials.
- Applying security updates.
- Restoring affected systems.
- Validating system functionality.
- Monitoring for recurring suspicious activity.

### 6.5 Documentation and Closure

The IT Security Manager is responsible for ensuring that security incidents are documented.

Incident records should include:

- Incident identification number.
- Date reported and date identified.
- Incident description.
- Systems and information potentially affected.
- Investigation activities.
- Containment and mitigation actions.
- Recovery activities.
- Final incident disposition.
- Corrective actions and lessons learned.

Incidents should not be considered fully closed until required response activities have been completed or formally tracked.

## 7. Incident Documentation Register

The following register represents a sample of fictional security incidents recorded during 2026.

| Incident ID | Date Reported | Description | Systems Affected | Response Status |
|---|---|---|---|---|
| INC-2026-001 | 02/12/2026 | Workforce member reported a suspicious phishing email. No confirmed credential compromise. | Microsoft 365 | Closed |
| INC-2026-002 | 04/08/2026 | Former employee account identified as active following termination. | Identity Management System | Closed |
| INC-2026-003 | 06/19/2026 | Malware detected on an employee workstation. Device isolated and investigated. | Employee Workstation | Closed |
| INC-2026-004 | 09/14/2026 | Unusual authentication activity identified involving a claims platform user account. Investigation completed, but supporting documentation is incomplete. | Claims Management Platform | Closed |

## 8. Incident Response Documentation Limitations

The organization maintains incident records through its IT service management system.

However, the following process weaknesses have been identified:

1. Incident records do not consistently contain complete investigation timelines.
2. Documentation of containment and recovery activities varies between incidents.
3. Evidence demonstrating formal post-incident reviews is limited.
4. Corrective actions resulting from security incidents are not consistently tracked through a centralized register.
5. The organization does not consistently document whether incidents involving potential ePHI exposure require additional privacy or breach assessment.

The IT Security Manager is responsible for coordinating improvements to incident documentation and response procedures.

## 9. Third-Party Incident Coordination

Northstar relies on a third-party cloud service provider to host its claims management platform.

The organization expects the provider to notify Northstar of security incidents affecting hosted systems in accordance with applicable contractual requirements.

The IT Security Manager coordinates with the provider when incidents potentially affect systems containing ePHI.

**Identified Process Limitation:** Documentation demonstrating that third-party incident notification procedures have been periodically reviewed and validated is limited.

## 10. Workforce Awareness

Workforce members receive security awareness training covering incident identification and reporting responsibilities.

Employees are instructed to report suspected security incidents promptly rather than attempting to independently investigate or resolve potentially significant security events.

## 11. Policy Review

This procedure should be reviewed periodically and updated following significant organizational, technological, or regulatory changes.

The IT Security Manager is responsible for coordinating policy reviews and ensuring that identified improvements are incorporated into incident response procedures.

## 12. Assessment Considerations

The assessment should evaluate whether:

- Security incident response procedures are documented.
- Workforce members understand incident reporting responsibilities.
- Incidents are identified and investigated.
- Appropriate containment and mitigation activities are performed.
- Incident records contain sufficient supporting documentation.
- Corrective actions are identified and tracked.
- Incidents involving potential ePHI exposure receive appropriate additional evaluation.

The existence of an incident response procedure does not independently demonstrate that the process operates effectively.

## 13. Regulatory References

**HIPAA Security Rule:**

- 45 CFR §164.308(a)(6)(i) – Security Incident Procedures.
- 45 CFR §164.308(a)(6)(ii) – Response and Reporting.

**Supporting Guidance:** NIST SP 800-66 Rev. 2, Implementing the HIPAA Security Rule: A Cybersecurity Resource Guide.
