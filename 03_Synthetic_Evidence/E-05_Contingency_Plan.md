# E-05: Contingency Plan

**Organization:** Northstar Health Plan (Fictional)  
**Document Owner:** IT Security Manager  
**Document Type:** Business Continuity and Contingency Plan  
**Effective Date:** January 1, 2026  
**Last Review Date:** January 1, 2026  
**Classification:** Internal – Confidential  
**Assessment Reference:** HIPAA Security Rule §164.308(a)(7)

---

## 1. Purpose

This contingency plan establishes procedures for maintaining or restoring access to information systems containing electronic protected health information (ePHI) following emergencies, system failures, or other operational disruptions.

The objective is to protect the availability and integrity of ePHI and support the continued operation of critical business functions.

## 2. Scope

This plan applies to organizational systems and services necessary to support Northstar's healthcare administration and claims processing operations.

Covered systems include:

- Cloud-hosted claims management platform.
- Identity management and authentication services.
- Microsoft 365 and organizational communications.
- Employee workstations used to access ePHI.
- Third-party cloud infrastructure supporting claims processing.

The plan applies to disruptions resulting from:

- Cloud service outages.
- Hardware or software failures.
- Cybersecurity incidents.
- Ransomware or malware events.
- Natural disasters.
- Power or network interruptions.
- Other events affecting access to critical organizational systems.

## 3. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| IT Security Manager | Oversees security-related contingency planning and coordinates recovery priorities. |
| IT Department | Coordinates technical recovery activities and validates system availability. |
| Department Managers | Identify critical business functions and coordinate workforce activities during disruptions. |
| Executive Management | Provides direction and approves significant operational decisions. |
| Cloud Service Provider | Supports infrastructure recovery and restoration activities according to contractual responsibilities. |

## 4. Data Backup Procedures

Northstar relies on its cloud service provider to maintain backups of the claims management platform and associated organizational data.

The provider performs routine backups to support data recovery following system failures or data loss events.

The IT department coordinates with the provider regarding backup availability and restoration requests.

### 4.1 Backup Expectations

The organization expects the following:

- Routine backups of critical claims management data.
- Protection of backup information against unauthorized access.
- Availability of backup data following system disruptions.
- Coordination between Northstar and the cloud provider during restoration activities.

**Identified Process Limitation:** Northstar does not consistently retain independent documentation demonstrating backup completion, backup integrity, and successful restoration testing.

## 5. Disaster Recovery Procedures

The IT department coordinates disaster recovery activities when critical organizational systems become unavailable.

Recovery activities may include:

1. Identifying the affected systems and services.
2. Notifying the IT Security Manager and relevant management personnel.
3. Contacting the cloud service provider when hosted infrastructure is affected.
4. Evaluating available backup and restoration options.
5. Coordinating system recovery activities.
6. Validating system functionality and data availability.
7. Notifying affected departments when normal operations can resume.

The cloud service provider is responsible for maintaining the underlying infrastructure supporting the hosted claims management platform, subject to contractual service commitments.

### 5.1 Recovery Priorities

| System | Business Criticality | Recovery Priority |
|---|---|---|
| Claims Management Platform | Critical | High |
| Identity Management System | Critical | High |
| Microsoft 365 | High | Medium |
| Employee Workstations | High | Medium |

The claims management platform and identity management system are considered essential to Northstar's ability to access and process member information.

**Identified Process Limitation:** Documented recovery time objectives (RTOs) and recovery point objectives (RPOs) have not been formally approved for all critical systems.

## 6. Emergency Mode Operations

When normal system operations are disrupted, Northstar may activate emergency operating procedures to maintain essential business functions.

Department managers coordinate temporary operational adjustments based on system availability and business requirements.

Emergency activities may include:

- Prioritizing critical claims processing activities.
- Communicating service disruptions to affected workforce members.
- Coordinating temporary alternative workflows.
- Contacting the cloud service provider.
- Restricting access to affected systems until recovery is validated.

Workforce members must continue following applicable security policies when handling sensitive information during emergency operations.

**Identified Process Limitation:** Formal emergency mode operating procedures have not been fully documented for all departments that handle ePHI.

## 7. Testing and Plan Maintenance

The IT Security Manager is responsible for coordinating periodic reviews of the contingency plan.

The organization expects contingency procedures to be reviewed when significant system or operational changes occur.

Testing activities may include:

- Backup restoration exercises.
- Disaster recovery simulations.
- Review of provider recovery procedures.
- Evaluation of emergency communication processes.
- Validation of critical system recovery dependencies.

**Identified Process Limitation:** The organization does not consistently retain evidence of completed contingency plan tests. The most recent documented backup restoration exercise was conducted in November 2024.

## 8. Applications and Data Criticality Analysis

Northstar identifies the claims management platform as its most critical application because it supports claims processing and maintains member ePHI.

The identity management system is also considered critical because it provides authentication and access management for organizational systems.

A formal, documented analysis of application and data criticality has not been completed across all systems within the assessment scope.

## 9. Third-Party Service Provider Dependencies

Northstar relies on a third-party cloud service provider to maintain the infrastructure supporting the claims management platform.

The provider is expected to maintain appropriate backup and recovery capabilities under its service agreements.

Northstar's IT department is responsible for coordinating with the provider during disruptions and obtaining relevant recovery information.

**Identified Process Limitation:** Northstar has not consistently retained documentation validating the provider's disaster recovery testing and restoration capabilities.

## 10. Assessment Considerations

The assessment should evaluate whether:

- Procedures exist for backing up ePHI.
- Disaster recovery procedures are documented.
- Emergency mode operations are established.
- Contingency plans are periodically tested and revised.
- Applications and data criticality are evaluated.
- Third-party recovery responsibilities are understood and documented.
- Backup restoration activities are supported by evidence.

The existence of cloud backups does not independently demonstrate that backup data can be successfully restored or that recovery procedures are effective.

## 11. Regulatory References

**HIPAA Security Rule:**

- 45 CFR §164.308(a)(7)(i) – Contingency Plan.
- §164.308(a)(7)(ii)(A) – Data Backup Plan.
- §164.308(a)(7)(ii)(B) – Disaster Recovery Plan.
- §164.308(a)(7)(ii)(C) – Emergency Mode Operation Plan.
- §164.308(a)(7)(ii)(D) – Testing and Revision Procedures.
- §164.308(a)(7)(ii)(E) – Applications and Data Criticality Analysis.

**Supporting Guidance:** NIST SP 800-66 Rev. 2, Implementing the HIPAA Security Rule: A Cybersecurity Resource Guide.
