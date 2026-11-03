# E-02: Access Control Policy and Procedures

**Organization:** Northstar Health Plan (Fictional)  
**Document Owner:** IT Security Manager  
**Document Type:** Security Policy and Procedures  
**Effective Date:** January 1, 2026  
**Last Review Date:** January 1, 2026  
**Classification:** Internal – Confidential  
**Assessment References:** HIPAA Security Rule §164.308(a)(3), §164.312(a)

---

## 1. Purpose

This policy establishes requirements for granting, modifying, reviewing, and terminating workforce access to organizational systems containing electronic protected health information (ePHI).

The purpose is to ensure that access to sensitive information is limited to authorized personnel based on their job responsibilities and operational requirements.

## 2. Scope

This policy applies to:

- All Northstar employees and workforce members.
- Contractors and temporary personnel authorized to access organizational systems.
- IT administrators responsible for user account management.
- Systems and applications that create, receive, maintain, or transmit ePHI.

Covered systems include the cloud-hosted claims management platform, identity management system, Microsoft 365, and employee workstations.

## 3. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| IT Security Manager | Oversees access control requirements and policy compliance. |
| IT Department | Creates, modifies, disables, and manages workforce accounts. |
| Department Managers | Approve access requests and notify IT of workforce changes. |
| Human Resources | Notifies IT of employee onboarding, transfers, and terminations. |
| Workforce Members | Protect credentials and access only information necessary for assigned responsibilities. |

## 4. User Account Management

### 4.1 Account Provisioning

Access to organizational systems must be approved before an account is created.

Department managers are responsible for submitting access requests identifying:

- Employee name.
- Department and job title.
- Requested system access.
- Required access permissions.
- Business justification.
- Manager approval.

The IT department provisions accounts based on approved requests and assigns permissions according to the employee's job responsibilities.

### 4.2 Unique User Identification

Each workforce member is assigned a unique user account for accessing organizational systems.

Shared accounts are generally prohibited for routine workforce activities.

Administrative and technical personnel may use designated privileged accounts for approved system administration activities.

### 4.3 Role-Based Access

Access permissions within the claims management platform are assigned using predefined job roles.

Common roles include:

| Role | General Access |
|---|---|
| Claims Processor | Access to claims information required for claims processing. |
| Customer Service Representative | Limited member information necessary for customer support. |
| Department Manager | Access to departmental reporting and approved operational records. |
| IT Administrator | Technical administration and system configuration privileges. |

Access permissions should reflect the minimum level of access necessary to perform assigned job responsibilities.

## 5. Access Modification

When employees transfer departments, change job responsibilities, or require additional system access:

1. The department manager submits an access modification request.
2. The request identifies the required changes and business justification.
3. The IT department reviews and implements approved modifications.
4. Updated permissions are recorded in the access management system.

Managers are responsible for notifying IT when workforce changes require adjustments to existing access permissions.

## 6. Workforce Termination

Human Resources is responsible for notifying IT of employee terminations.

Upon notification, the IT department is responsible for disabling applicable user accounts and removing access to organizational systems.

Access removal should occur promptly following termination notification.

Documentation of account deactivation is maintained through IT service tickets or account administration records.

**Identified Process Limitation:** The organization does not currently maintain a centralized report demonstrating that all terminated workforce members have had their access removed within a defined timeframe.

The IT department relies primarily on notifications from Human Resources and department managers to initiate account termination activities.

## 7. Periodic Access Reviews

Department managers are expected to review workforce access permissions to verify that assigned privileges remain appropriate.

Access reviews should identify:

- Inactive user accounts.
- Employees with excessive permissions.
- Accounts belonging to former employees.
- Inappropriate privileged access.
- Permissions that no longer align with job responsibilities.

**Identified Process Limitation:** Access reviews are performed inconsistently across departments. Evidence of completed reviews is not centrally maintained, and the organization has not established a consistent documented review schedule.

## 8. Authentication Requirements

Workforce members must authenticate using their assigned organizational credentials before accessing systems containing ePHI.

The organization uses centralized identity management to support workforce authentication.

Additional authentication requirements include:

- Passwords must meet organizational complexity requirements.
- Workforce credentials must not be shared.
- Suspected credential compromise must be reported to IT.
- Multifactor authentication is enabled for remote access to the claims management platform.

## 9. Emergency Access Procedures

The IT department maintains procedures for providing emergency access to systems containing ePHI when necessary to support critical business operations.

Emergency access requests must be authorized by the IT Security Manager or an appropriate designated manager.

Emergency access activities should be documented and reviewed following the event.

**Identified Process Limitation:** Formal documentation defining emergency access authorization, monitoring, and post-event review responsibilities is incomplete.

## 10. Automatic Logoff

The claims management platform is configured to terminate inactive user sessions after a defined period of inactivity.

The IT department is responsible for coordinating with the application provider to maintain session timeout configurations.

Configuration evidence and periodic validation records are not consistently retained.

## 11. Encryption and Decryption

Encryption and decryption mechanisms are managed through the organization's approved systems and service providers.

The IT department coordinates with the cloud platform provider to maintain encryption capabilities for stored ePHI.

**Identified Process Limitation:** Documentation describing encryption configuration, key management responsibilities, and periodic validation is incomplete.

## 12. Access Monitoring and Documentation

The IT department maintains account administration records and access-related service tickets.

These records may include:

- Account provisioning requests.
- Manager approvals.
- Account modification requests.
- Account termination activities.
- Privileged account administration activities.

Documentation is retained within the organization's IT service management environment.

The IT Security Manager is responsible for overseeing adherence to this policy and coordinating corrective actions when access management deficiencies are identified.

## 13. Policy Review

This policy should be reviewed periodically and updated when significant organizational, regulatory, or technological changes occur.

The IT Security Manager is responsible for coordinating policy reviews and obtaining management approval for substantive revisions.

## 14. Regulatory References

**HIPAA Security Rule:**

- 45 CFR §164.308(a)(3) – Workforce Security.
- 45 CFR §164.312(a) – Access Control.
- 45 CFR §164.312(d) – Person or Entity Authentication.

**Supporting Guidance:** NIST SP 800-66 Rev. 2, Implementing the HIPAA Security Rule: A Cybersecurity Resource Guide.
