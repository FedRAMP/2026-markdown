---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Rev5 Controls

This reference contains the NIST SP 800-53 Revision 5 controls for which the FedRAMP Consolidated Rules define additional guidance or organization-assigned parameter values.

!!! info "Official NIST OSCAL source"
    **Electronic (OSCAL) Version of NIST SP 800-53 Rev 5.2.0 Controls and SP 800-53A Rev 5.2.0 Assessment Procedures**

    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

**Control families**

- [Access Control (AC)](#access-control-ac)
- [Audit and Accountability (AU)](#audit-and-accountability-au)
- [Assessment, Authorization, and Monitoring (CA)](#assessment-authorization-and-monitoring-ca)
- [Configuration Management (CM)](#configuration-management-cm)
- [Contingency Planning (CP)](#contingency-planning-cp)
- [Identification and Authentication (IA)](#identification-and-authentication-ia)
- [Incident Response (IR)](#incident-response-ir)
- [Maintenance (MA)](#maintenance-ma)
- [Personnel Security (PS)](#personnel-security-ps)
- [Risk Assessment (RA)](#risk-assessment-ra)
- [System and Services Acquisition (SA)](#system-and-services-acquisition-sa)
- [System and Communications Protection (SC)](#system-and-communications-protection-sc)
- [System and Information Integrity (SI)](#system-and-information-integrity-si)
- [Supply Chain Risk Management (SR)](#supply-chain-risk-management-sr)

---

## Access Control (AC) { #access-control-ac }

### Authorize Access to Security Functions { #ac-06-01-authorize-access-to-security-functions }

??? abstract "AC-06(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Authorize access for [Assignment: organization-defined individuals and roles] to:
    
    - **(a)** [Assignment: organization-defined security functions (deployed in hardware, software, and firmware)]; and
    - **(b)** [Assignment: organization-defined security-relevant information].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.01_odp.02` | security functions (deployed in hardware) | all functions not publicly accessible |
        | `ac-06.01_odp.05` | security-relevant information | all security-relevant information not publicly available |

---

### Non-privileged Access for Nonsecurity Functions { #ac-06-02-non-privileged-access-for-nonsecurity-functions }

??? abstract "AC-06(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Require that users of system accounts (or roles) with access to [Assignment: organization-defined security functions or security-relevant information] use non-privileged accounts or roles, when accessing nonsecurity functions.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.02_odp` | security functions or security-relevant information | all security functions |

---

### Privilege Levels for Code Execution { #ac-06-08-privilege-levels-for-code-execution }

??? abstract "AC-06(08)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(08)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Prevent the following software from executing at higher privilege levels than users executing the software: [Assignment: organization-defined software].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.08_odp` | software | any software except software explicitly documented |

---

### Use of External Systems { #ac-20-use-of-external-systems }

??? abstract "AC-20"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-20`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** [Selection: one or more of: establish; identify], consistent with the trust relationships established with other organizations owning, operating, and/or maintaining external systems, allowing authorized individuals to:
        - **1.** Access the system from external systems; and
        - **2.** Process, store, or transmit organization-controlled information using external systems; or
    - **b.** Prohibit the use of [Assignment: organization-defined prohibited types of external systems].

    !!! note ""
        **FedRAMP Guidance**

        The interrelated controls of AC-20, CA-3, and SA-9 should be differentiated as follows:

        AC-20 describes system access to and from external systems.

        CA-3 describes documentation of an agreement between the respective system owners when data is exchanged between the CSO and an external system.

        SA-9 describes the responsibilities of external system owners. These responsibilities would typically be captured in the agreement required by CA-3.

---

## Audit and Accountability (AU) { #audit-and-accountability-au }

### Audit Record Review, Analysis, and Reporting { #au-06-audit-record-review-analysis-and-reporting }

??? abstract "AU-06"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-06`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Review and analyze system audit records [Assignment: organization-defined frequency] for indications of [Assignment: organization-defined inappropriate or unusual activity] and the potential impact of the inappropriate or unusual activity;
    - **b.** Report findings to [Assignment: organization-defined personnel or roles]; and
    - **c.** Adjust the level of audit record review, analysis, and reporting within the system when there is a change in risk based on law enforcement information, intelligence information, or other credible sources of information.

    !!! note ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

---

### Integrated Analysis of Audit Records { #au-06-05-integrated-analysis-of-audit-records }

??? abstract "AU-06(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-06(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Integrate analysis of audit records with analysis of [Selection: one or more of: vulnerability scanning information; performance data; system monitoring information] to further enhance the ability to identify inappropriate or unusual activity.

    !!! note ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

---

### Non-repudiation { #au-10-non-repudiation }

??? abstract "AU-10"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-10`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide irrefutable evidence that an individual (or process acting on behalf of an individual) has performed [Assignment: organization-defined actions].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-10_odp` | actions | at least actions including the addition, modification, deletion, approval, sending, or receiving of data |

---

### Audit Record Generation { #au-12-audit-record-generation }

??? abstract "AU-12"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-12`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Provide audit record generation capability for the event types the system is capable of auditing as defined in AU-2a on [Assignment: organization-defined system components];
    - **b.** Allow [Assignment: organization-defined personnel or roles] to select the event types that are to be logged by specific components of the system; and
    - **c.** Generate audit records for the event types defined in AU-2c that include the audit record content defined in AU-3.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-12_odp.01` | system components | at least all information system and network components where audit capability is deployed/available |

---

## Assessment, Authorization, and Monitoring (CA) { #assessment-authorization-and-monitoring-ca }

### Control Assessments { #ca-02-control-assessments }

??? abstract "CA-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CA-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Select the appropriate assessor or assessment team for the type of assessment to be conducted;
    - **b.** Develop a control assessment plan that describes the scope of the assessment including:
        - **1.** Controls and control enhancements under assessment;
        - **2.** Assessment procedures to be used to determine control effectiveness; and
        - **3.** Assessment environment, assessment team, and assessment roles and responsibilities;
    - **c.** Ensure the control assessment plan is reviewed and approved by the authorizing official or designated representative prior to conducting the assessment;
    - **d.** Assess the controls in the system and its environment of operation [Assignment: organization-defined assessment frequency] to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security and privacy requirements;
    - **e.** Produce a control assessment report that document the results of the assessment; and
    - **f.** Provide the results of the control assessment to [Assignment: organization-defined individuals or roles].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ca-02_odp.02` | individuals or roles | individuals or roles to include FedRAMP and agency customers |

---

### Leveraging Results from External Organizations { #ca-02-03-leveraging-results-from-external-organizations }

??? abstract "CA-02(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CA-02(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Leverage the results of control assessments performed by [Assignment: organization-defined external organization(s)] on [Assignment: organization-defined system] when the assessment meets [Assignment: organization-defined requirements].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ca-02.03_odp.01` | external organization(s) | any FedRAMP Recognized independent assessor |

---

### Continuous Monitoring { #ca-07-continuous-monitoring }

??? abstract "CA-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CA-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:
    
    - **a.** Establishing the following system-level metrics to be monitored: [Assignment: organization-defined system-level metrics];
    - **b.** Establishing [Assignment: organization-defined frequencies] for monitoring and [Assignment: organization-defined frequencies] for assessment of control effectiveness;
    - **c.** Ongoing control assessments in accordance with the continuous monitoring strategy;
    - **d.** Ongoing monitoring of system and organization-defined metrics in accordance with the continuous monitoring strategy;
    - **e.** Correlation and analysis of information generated by control assessments and monitoring;
    - **f.** Response actions to address results of the analysis of control assessment and monitoring information; and
    - **g.** Reporting the security and privacy status of the system to [Assignment: organization-defined personnel or roles] [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Guidance**

        Follow the Continuous Collaborative Monitoring, Significant Change Notification, and Vulnerability Detection and Response rules.

---

### Penetration Testing { #ca-08-penetration-testing }

??? abstract "CA-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CA-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Conduct penetration testing [Assignment: organization-defined frequency] on [Assignment: organization-defined system(s) or system components].

    !!! note ""
        **FedRAMP Guidance**

        Penetration testing is part of vulnerability detection and is subject to the Vulnerability Detection and Response rules.

---

## Configuration Management (CM) { #configuration-management-cm }

### Policy and Procedures { #cm-01-policy-and-procedures }

??? abstract "CM-01"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-01`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] configuration management policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the configuration management policy and the associated configuration management controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the configuration management policy and procedures; and
    - **c.** Review and update the current configuration management:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    !!! note ""
        **FedRAMP Guidance**

        Follow the Significant Change Notification rules.

---

### System Component Inventory { #cm-08-system-component-inventory }

??? abstract "CM-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop and document an inventory of system components that:
        - **1.** Accurately reflects the system;
        - **2.** Includes all components within the system;
        - **3.** Does not include duplicate accounting of components or components assigned to any other system;
        - **4.** Is at the level of granularity deemed necessary for tracking and reporting; and
        - **5.** Includes the following information to achieve system component accountability: [Assignment: organization-defined information]; and
    - **b.** Review and update the system component inventory [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Guidance**

        Follow the Continuous Collaborative Monitoring, Significant Change Notification, and Vulnerability Detection and Response rules.

---

### Automated Unauthorized Component Detection { #cm-08-03-automated-unauthorized-component-detection }

??? abstract "CM-08(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-08(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **(a)** Detect the presence of unauthorized hardware, software, and firmware components within the system using [Assignment: organization-defined automated mechanisms] [Assignment: organization-defined frequency]; and
    - **(b)** Take the following actions when unauthorized components are detected: [Selection: one or more of: disable network access by unauthorized components; isolate unauthorized components; notify].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cm-08.03_odp.01` | automated mechanisms | automated mechanisms with a maximum five-minute delay in detection. |
        | `cm-08.03_odp.04` | frequency | continuously |

---

### User-installed Software { #cm-11-user-installed-software }

??? abstract "CM-11"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-11`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish [Assignment: organization-defined policies] governing the installation of software by users;
    - **b.** Enforce software installation policies through the following methods: [Assignment: organization-defined methods]; and
    - **c.** Monitor policy compliance [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cm-11_odp.03` | frequency | Continuously (via CM-7 (5)) |

---

### Information Location { #cm-12-information-location }

??? abstract "CM-12"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-12`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Identify and document the location of [Assignment: organization-defined information] and the specific system components on which the information is processed and stored;
    - **b.** Identify and document the users who have access to the system and system components where the information is processed and stored; and
    - **c.** Document changes to the location (i.e., system or system components) where the information is processed and stored.

    !!! note ""
        **FedRAMP Guidance**

        Follow Minimum Assessment Scope (MAS) rules.

---

### Automated Tools to Support Information Location { #cm-12-01-automated-tools-to-support-information-location }

??? abstract "CM-12(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-12(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Use automated tools to identify [Assignment: organization-defined information by information type] on [Assignment: organization-defined system components] to ensure controls are in place to protect organizational information and individual privacy.

    !!! note ""
        **FedRAMP Guidance**

        Follow Minimum Assessment Scope (MAS) rules.

---

### Signed Components { #cm-14-signed-components }

??? abstract "CM-14"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-14`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Prevent the installation of [Assignment: organization-defined software and firmware components] without verification that the component has been digitally signed using a certificate that is recognized and approved by the organization.

    !!! note ""
        **FedRAMP Guidance**

        If digital signatures/certificates are unavailable, alternative cryptographic integrity checks (hashes, self-signed certs, etc.) can be utilized.

---

## Contingency Planning (CP) { #contingency-planning-cp }

### Resume Mission and Business Functions { #cp-02-03-resume-mission-and-business-functions }

??? abstract "CP-02(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CP-02(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Plan for the resumption of [Selection: one of: all; essential] mission and business functions within [Assignment: organization-defined time period] of contingency plan activation.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cp-02.03_odp.02` | time period | time period defined in service provider and organization SLA |

---

### Separation from Primary Site { #cp-07-01-separation-from-primary-site }

??? abstract "CP-07(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CP-07(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Identify an alternate processing site that is sufficiently separated from the primary processing site to reduce susceptibility to the same threats.

    !!! note ""
        **FedRAMP Guidance**

        The service provider may determine what is considered a sufficient degree of separation between the primary and alternate processing sites, based on the types of threats that are of concern. For one particular type of threat (i.e., hostile cyber attack), the degree of separation between sites will be less relevant.

---

### Restore Within Time Period { #cp-10-04-restore-within-time-period }

??? abstract "CP-10(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CP-10(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide the capability to restore system components within [Assignment: organization-defined restoration time periods] from configuration-controlled and integrity-protected information representing a known, operational state for the components.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cp-10.04_odp` | restoration time periods | time period consistent with the restoration time-periods defined in the service provider and organization SLA |

---

## Identification and Authentication (IA) { #identification-and-authentication-ia }

### Identification and Authentication (Organizational Users) { #ia-02-identification-and-authentication-organizational-users }

??? abstract "IA-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

    !!! note ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Multi-factor Authentication to Privileged Accounts { #ia-02-01-multi-factor-authentication-to-privileged-accounts }

??? abstract "IA-02(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for access to privileged accounts.

    !!! note ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Multi-factor Authentication to Non-privileged Accounts { #ia-02-02-multi-factor-authentication-to-non-privileged-accounts }

??? abstract "IA-02(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for access to non-privileged accounts.

    !!! note ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Access to Accounts —separate Device { #ia-02-06-access-to-accounts-separate-device }

??? abstract "IA-02(06)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(06)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for [Selection: one or more of: local; network; remote] access to [Selection: one or more of: privileged accounts; non-privileged accounts] such that:
    
    - **(a)** One of the factors is provided by a device separate from the system gaining access; and
    - **(b)** The device meets [Assignment: organization-defined strength of mechanism requirements].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.06_odp.01` | one or more of: local; network; remote | local, network and remote |
        | `ia-02.06_odp.02` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

---

### Access to Accounts — Replay Resistant { #ia-02-08-access-to-accounts--replay-resistant }

??? abstract "IA-02(08)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(08)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement replay-resistant authentication mechanisms for access to [Selection: one or more of: privileged accounts; non-privileged accounts].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.08_odp` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

---

### Identify User Status { #ia-04-04-identify-user-status }

??? abstract "IA-04(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-04(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Manage individual identifiers by uniquely identifying each individual as [Assignment: organization-defined characteristics].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-04.04_odp` | characteristics | contractors; foreign nationals |

---

### Authenticator Management { #ia-05-authenticator-management }

??? abstract "IA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Manage system authenticators by:
    
    - **a.** Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, service, or device receiving the authenticator;
    - **b.** Establishing initial authenticator content for any authenticators issued by the organization;
    - **c.** Ensuring that authenticators have sufficient strength of mechanism for their intended use;
    - **d.** Establishing and implementing administrative procedures for initial authenticator distribution, for lost or compromised or damaged authenticators, and for revoking authenticators;
    - **e.** Changing default authenticators prior to first use;
    - **f.** Changing or refreshing authenticators [Assignment: organization-defined time period by authenticator type] or when [Assignment: organization-defined events] occur;
    - **g.** Protecting authenticator content from unauthorized disclosure and modification;
    - **h.** Requiring individuals to take, and having devices implement, specific controls to protect authenticators; and
    - **i.** Changing authenticators for group or role accounts when membership to those accounts changes.

    !!! note ""
        === "Class B"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 1. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

        === "Class C"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 2. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

        === "Class D"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 3. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

---

## Incident Response (IR) { #incident-response-ir }

### Policy and Procedures { #ir-01-policy-and-procedures }

??? abstract "IR-01"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-01`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] incident response policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the incident response policy and the associated incident response controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the incident response policy and procedures; and
    - **c.** Review and update the current incident response:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Response Training { #ir-02-incident-response-training }

??? abstract "IR-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Provide incident response training to system users consistent with assigned roles and responsibilities:
        - **1.** Within [Assignment: organization-defined time period] of assuming an incident response role or responsibility or acquiring system access;
        - **2.** When required by system changes; and
        - **3.** [Assignment: organization-defined frequency] thereafter; and
    - **b.** Review and update incident response training content [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Simulated Events { #ir-02-01-simulated-events }

??? abstract "IR-02(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-02(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Incorporate simulated events into incident response training to facilitate the required response by personnel in crisis situations.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Automated Training Environments { #ir-02-02-automated-training-environments }

??? abstract "IR-02(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-02(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide an incident response training environment using [Assignment: organization-defined automated mechanisms].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Response Testing { #ir-03-incident-response-testing }

??? abstract "IR-03"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-03`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Test the effectiveness of the incident response capability for the system [Assignment: organization-defined frequency] using the following tests: [Assignment: organization-defined tests].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Coordination with Related Plans { #ir-03-02-coordination-with-related-plans }

??? abstract "IR-03(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-03(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Coordinate incident response testing with organizational elements responsible for related plans.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Handling { #ir-04-incident-handling }

??? abstract "IR-04"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Implement an incident handling capability for incidents that is consistent with the incident response plan and includes preparation, detection and analysis, containment, eradication, and recovery;
    - **b.** Coordinate incident handling activities with contingency planning activities;
    - **c.** Incorporate lessons learned from ongoing incident handling activities into incident response procedures, training, and testing, and implement the resulting changes accordingly; and
    - **d.** Ensure the rigor, intensity, scope, and results of incident handling activities are comparable and predictable across the organization.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Automated Incident Handling Processes { #ir-04-01-automated-incident-handling-processes }

??? abstract "IR-04(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Support the incident handling process using [Assignment: organization-defined automated mechanisms].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Dynamic Reconfiguration { #ir-04-02-dynamic-reconfiguration }

??? abstract "IR-04(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Include the following types of dynamic reconfiguration for [Assignment: organization-defined system components] as part of the incident response capability: [Assignment: organization-defined types of dynamic reconfiguration].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Information Correlation { #ir-04-04-information-correlation }

??? abstract "IR-04(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Correlate incident information and individual incident responses to achieve an organization-wide perspective on incident awareness and response.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Insider Threats { #ir-04-06-insider-threats }

??? abstract "IR-04(06)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04(06)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement an incident handling capability for incidents involving insider threats.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Integrated Incident Response Team { #ir-04-11-integrated-incident-response-team }

??? abstract "IR-04(11)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-04(11)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Establish and maintain an integrated incident response team that can be deployed to any location identified by the organization in [Assignment: organization-defined time period].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Monitoring { #ir-05-incident-monitoring }

??? abstract "IR-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Track and document incidents.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Automated Tracking, Data Collection, and Analysis { #ir-05-01-automated-tracking-data-collection-and-analysis }

??? abstract "IR-05(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-05(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Track incidents and collect and analyze incident information using [Assignment: organization-defined automated mechanisms].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Reporting { #ir-06-incident-reporting }

??? abstract "IR-06"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-06`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Require personnel to report suspected incidents to the organizational incident response capability within [Assignment: organization-defined time period]; and
    - **b.** Report incident information to [Assignment: organization-defined authorities].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Automated Reporting { #ir-06-01-automated-reporting }

??? abstract "IR-06(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-06(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Report incidents using [Assignment: organization-defined automated mechanisms].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Supply Chain Coordination { #ir-06-03-supply-chain-coordination }

??? abstract "IR-06(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-06(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide incident information to the provider of the product or service and other organizations involved in the supply chain or supply chain governance for systems or system components related to the incident.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Response Assistance { #ir-07-incident-response-assistance }

??? abstract "IR-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide an incident response support resource, integral to the organizational incident response capability, that offers advice and assistance to users of the system for the handling and reporting of incidents.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Automation Support for Availability of Information and Support { #ir-07-01-automation-support-for-availability-of-information-and-support }

??? abstract "IR-07(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-07(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Increase the availability of incident response information and support using [Assignment: organization-defined automated mechanisms].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Incident Response Plan { #ir-08-incident-response-plan }

??? abstract "IR-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop an incident response plan that:
        - **1.** Provides the organization with a roadmap for implementing its incident response capability;
        - **2.** Describes the structure and organization of the incident response capability;
        - **3.** Provides a high-level approach for how the incident response capability fits into the overall organization;
        - **4.** Meets the unique requirements of the organization, which relate to mission, size, structure, and functions;
        - **5.** Defines reportable incidents;
        - **6.** Provides metrics for measuring the incident response capability within the organization;
        - **7.** Defines the resources and management support needed to effectively maintain and mature an incident response capability;
        - **8.** Addresses the sharing of incident information;
        - **9.** Is reviewed and approved by [Assignment: organization-defined personnel or roles] [Assignment: organization-defined frequency]; and
        - **10.** Explicitly designates responsibility for incident response to [Assignment: organization-defined entities, personnel, or roles].
    - **b.** Distribute copies of the incident response plan to [Assignment: organization-defined incident response personnel];
    - **c.** Update the incident response plan to address system and organizational changes or problems encountered during plan implementation, execution, or testing;
    - **d.** Communicate incident response plan changes to [Assignment: organization-defined incident response personnel (identified by name and/or by role) and organizational elements]; and
    - **e.** Protect the incident response plan from unauthorized disclosure and modification.

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Information Spillage Response { #ir-09-information-spillage-response }

??? abstract "IR-09"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-09`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Respond to information spills by:
    
    - **a.** Assigning [Assignment: organization-defined personnel or roles] with responsibility for responding to information spills;
    - **b.** Identifying the specific information involved in the system contamination;
    - **c.** Alerting [Assignment: organization-defined personnel or roles] of the information spill using a method of communication not associated with the spill;
    - **d.** Isolating the contaminated system or system component;
    - **e.** Eradicating the information from the contaminated system or component;
    - **f.** Identifying other systems or system components that may have been subsequently contaminated; and
    - **g.** Performing the following additional actions: [Assignment: organization-defined actions].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Training { #ir-09-02-training }

??? abstract "IR-09(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-09(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide information spillage response training [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Post-spill Operations { #ir-09-03-post-spill-operations }

??? abstract "IR-09(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-09(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement the following procedures to ensure that organizational personnel impacted by information spills can continue to carry out assigned tasks while contaminated systems are undergoing corrective actions: [Assignment: organization-defined procedures].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

### Exposure to Unauthorized Personnel { #ir-09-04-exposure-to-unauthorized-personnel }

??? abstract "IR-09(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IR-09(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Employ the following controls for personnel exposed to information not within assigned access authorizations: [Assignment: organization-defined controls].

    !!! note ""
        **FedRAMP Guidance**

        Follow all guidelines associated with FedRAMP Incident Evaluation and Reporting.

---

## Maintenance (MA) { #maintenance-ma }

### Maintenance Personnel { #ma-05-maintenance-personnel }

??? abstract "MA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `MA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish a process for maintenance personnel authorization and maintain a list of authorized maintenance organizations or personnel;
    - **b.** Verify that non-escorted personnel performing maintenance on the system possess the required access authorizations; and
    - **c.** Designate organizational personnel with required access authorizations and technical competence to supervise the maintenance activities of personnel who do not possess the required access authorizations.

    !!! note ""
        **FedRAMP Guidance**

        CSPs should clearly document nationality requirements (or lack of) for maintenance personnel where applicable.

---

### Individuals Without Appropriate Access { #ma-05-01-individuals-without-appropriate-access }

??? abstract "MA-05(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `MA-05(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **(a)** Implement procedures for the use of maintenance personnel that lack appropriate security clearances or are not U.S. citizens, that include the following requirements:
        - **(1)** Maintenance personnel who do not have needed access authorizations, clearances, or formal access approvals are escorted and supervised during the performance of maintenance and diagnostic activities on the system by approved organizational personnel who are fully cleared, have appropriate access authorizations, and are technically qualified; and
        - **(2)** Prior to initiating maintenance or diagnostic activities by personnel who do not have needed access authorizations, clearances or formal access approvals, all volatile information storage components within the system are sanitized and all nonvolatile storage media are removed or physically disconnected from the system and secured; and
    - **(b)** Develop and implement [Assignment: organization-defined alternate controls] in the event a system component cannot be sanitized, removed, or disconnected from the system.

    !!! note ""
        **FedRAMP Guidance**

        Only MA-5 (1) (a) (1) is required by FedRAMP Moderate Baseline

---

## Personnel Security (PS) { #personnel-security-ps }

### External Personnel Security { #ps-07-external-personnel-security }

??? abstract "PS-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `PS-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish personnel security requirements, including security roles and responsibilities for external providers;
    - **b.** Require external providers to comply with personnel security policies and procedures established by the organization;
    - **c.** Document personnel security requirements;
    - **d.** Require external providers to notify [Assignment: organization-defined personnel or roles] of any personnel transfers or terminations of external personnel who possess organizational credentials and/or badges, or who have system privileges within [Assignment: organization-defined time period]; and
    - **e.** Monitor provider compliance with personnel security requirements.

    !!! note ""
        **FedRAMP Guidance**

        CSPs MUST clearly document any nationality requirements for any account type within its platform.  If none exists, this must also be explicitly stated.

---

## Risk Assessment (RA) { #risk-assessment-ra }

### Vulnerability Monitoring and Scanning { #ra-05-vulnerability-monitoring-and-scanning }

??? abstract "RA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Monitor and scan for vulnerabilities in the system and hosted applications [Assignment: organization-defined frequency and/or randomly in accordance with organization-defined process] and when new vulnerabilities potentially affecting the system are identified and reported;
    - **b.** Employ vulnerability monitoring tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
        - **1.** Enumerating platforms, software flaws, and improper configurations;
        - **2.** Formatting checklists and test procedures; and
        - **3.** Measuring vulnerability impact;
    - **c.** Analyze vulnerability scan reports and results from vulnerability monitoring;
    - **d.** Remediate legitimate vulnerabilities [Assignment: organization-defined response times] in accordance with an organizational assessment of risk;
    - **e.** Share information obtained from the vulnerability monitoring process and control assessments with [Assignment: organization-defined personnel or roles] to help eliminate similar vulnerabilities in other systems; and
    - **f.** Employ vulnerability monitoring tools that include the capability to readily update the vulnerabilities to be scanned.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Update Vulnerabilities to Be Scanned { #ra-05-02-update-vulnerabilities-to-be-scanned }

??? abstract "RA-05(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Update the system vulnerabilities to be scanned [Selection: one or more of: prior to a new scan; when new vulnerabilities are identified and reported].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ra-05.02_odp.02` | frequency | prior to a new scan |

---

### Breadth and Depth of Coverage { #ra-05-03-breadth-and-depth-of-coverage }

??? abstract "RA-05(03)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(03)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Define the breadth and depth of vulnerability scanning coverage.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Discoverable Information { #ra-05-04-discoverable-information }

??? abstract "RA-05(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Determine information about the system that is discoverable and take [Assignment: organization-defined corrective actions].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Privileged Access { #ra-05-05-privileged-access }

??? abstract "RA-05(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement privileged access authorization to [Assignment: organization-defined system components] for [Assignment: organization-defined vulnerability scanning activities].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Review Historic Audit Logs { #ra-05-08-review-historic-audit-logs }

??? abstract "RA-05(08)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(08)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Review historic audit logs to determine if a vulnerability identified in a [Assignment: organization-defined system] has been previously exploited within an [Assignment: organization-defined time period].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Public Disclosure Program { #ra-05-11-public-disclosure-program }

??? abstract "RA-05(11)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-05(11)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Establish a public reporting channel for receiving reports of vulnerabilities in organizational systems and system components.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Risk Response { #ra-07-risk-response }

??? abstract "RA-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `RA-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Respond to findings from security and privacy assessments, monitoring, and audits in accordance with organizational risk tolerance.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

## System and Services Acquisition (SA) { #system-and-services-acquisition-sa }

### System Documentation { #sa-05-system-documentation }

??? abstract "SA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Obtain or develop administrator documentation for the system, system component, or system service that describes:
        - **1.** Secure configuration, installation, and operation of the system, component, or service;
        - **2.** Effective use and maintenance of security and privacy functions and mechanisms; and
        - **3.** Known vulnerabilities regarding configuration and use of administrative or privileged functions;
    - **b.** Obtain or develop user documentation for the system, system component, or system service that describes:
        - **1.** User-accessible security and privacy functions and mechanisms and how to effectively use those functions and mechanisms;
        - **2.** Methods for user interaction, which enables individuals to use the system, component, or service in a more secure manner and protect individual privacy; and
        - **3.** User responsibilities in maintaining the security of the system, component, or service and privacy of individuals;
    - **c.** Document attempts to obtain system, system component, or system service documentation when such documentation is either unavailable or nonexistent and take [Assignment: organization-defined actions] in response; and
    - **d.** Distribute documentation to [Assignment: organization-defined personnel or roles].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the FedRAMP Security Configuration Guidance

---

### Identification of Functions, Ports, Protocols, and Services { #sa-09-02-identification-of-functions-ports-protocols-and-services }

??? abstract "SA-09(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-09(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Require providers of the following external system services to identify the functions, ports, protocols, and other services required for the use of such services: [Assignment: organization-defined external system services].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `sa-09.02_odp` | external system services | all external systems where federal customer data is processed or stored |

---

### Processing, Storage, and Service Location { #sa-09-05-processing-storage-and-service-location }

??? abstract "SA-09(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-09(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Restrict the location of [Selection: one or more of: information processing; information or data; system services] to [Assignment: organization-defined locations] based on [Assignment: organization-defined requirements].

    !!! note ""
        === "Class C"
            **FedRAMP Parameters**

            | Parameter ID | NIST assignment | FedRAMP value |
            | --- | --- | --- |
            | `sa-09.05_odp.01` | one or more of: information processing; information or data; system services | information processing, information or data, AND system services |
            | `sa-09.05_odp.03` | requirements | all Federal customer data |

        === "Class D"
            **FedRAMP Parameters**

            | Parameter ID | NIST assignment | FedRAMP value |
            | --- | --- | --- |
            | `sa-09.05_odp.01` | one or more of: information processing; information or data; system services | information processing, information or data, AND system services |
            | `sa-09.05_odp.02` | locations | U.S./U.S. Territories or geographic locations where there is U.S. jurisdiction |
            | `sa-09.05_odp.03` | requirements | all Federal customer data |

---

## System and Communications Protection (SC) { #system-and-communications-protection-sc }

### Boundary Protection { #sc-07-boundary-protection }

??? abstract "SC-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SC-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Monitor and control communications at the external managed interfaces to the system and at key internal managed interfaces within the system;
    - **b.** Implement subnetworks for publicly accessible system components that are [Selection: one of: physically; logically] separated from internal organizational networks; and
    - **c.** Connect to external networks or systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security and privacy architecture.

    !!! note ""
        **FedRAMP Guidance**

        SC-7 (b) MAY be met by using any technical capability or complement of capabilities that ensures logical separation between publicly accessible components and internal networks by preventing traversal without inspection and authorization; traffic may not flow unrestricted from publicly accessible components to internal networks.

---

### Cryptographic Protection { #sc-13-cryptographic-protection }

??? abstract "SC-13"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SC-13`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Determine the [Assignment: organization-defined cryptographic uses]; and
    - **b.** Implement the following types of cryptography required for each specified cryptographic use: [Assignment: organization-defined types of cryptography].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Using Cryptographics Modules  guidance.

---

## System and Information Integrity (SI) { #system-and-information-integrity-si }

### Flaw Remediation { #si-02-flaw-remediation }

??? abstract "SI-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Identify, report, and correct system flaws;
    - **b.** Test software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
    - **c.** Install security-relevant software and firmware updates within [Assignment: organization-defined time period] of the release of the updates; and
    - **d.** Incorporate flaw remediation into the organizational configuration management process.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Automated Flaw Remediation Status { #si-02-02-automated-flaw-remediation-status }

??? abstract "SI-02(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-02(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Determine if system components have applicable security-relevant software and firmware updates installed using [Assignment: organization-defined automated mechanisms] [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### System Monitoring { #si-04-system-monitoring }

??? abstract "SI-04"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Monitor the system to detect:
        - **1.** Attacks and indicators of potential attacks in accordance with the following monitoring objectives: [Assignment: organization-defined monitoring objectives]; and
        - **2.** Unauthorized local, network, and remote connections;
    - **b.** Identify unauthorized use of the system through the following techniques and methods: [Assignment: organization-defined techniques and methods];
    - **c.** Invoke internal monitoring capabilities or deploy monitoring devices:
        - **1.** Strategically within the system to collect organization-determined essential information; and
        - **2.** At ad hoc locations within the system to track specific types of transactions of interest to the organization;
    - **d.** Analyze detected events and anomalies;
    - **e.** Adjust the level of system monitoring activity when there is a change in risk to organizational operations and assets, individuals, other organizations, or the Nation;
    - **f.** Obtain legal opinion regarding system monitoring activities; and
    - **g.** Provide [Assignment: organization-defined system monitoring information] to [Assignment: organization-defined personnel or roles] [Selection: one or more of: as needed].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response and Incident Communication Procedure guidance.

---

### System-wide Intrusion Detection System { #si-04-01-system-wide-intrusion-detection-system }

??? abstract "SI-04(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Connect and configure individual intrusion detection tools into a system-wide intrusion detection system.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Automated Tools and Mechanisms for Real-time Analysis { #si-04-02-automated-tools-and-mechanisms-for-real-time-analysis }

??? abstract "SI-04(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Employ automated tools and mechanisms to support near real-time analysis of events.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Inbound and Outbound Communications Traffic { #si-04-04-inbound-and-outbound-communications-traffic }

??? abstract "SI-04(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **(a)** Determine criteria for unusual or unauthorized activities or conditions for inbound and outbound communications traffic;
    - **(b)** Monitor inbound and outbound communications traffic [Assignment: organization-defined frequency] for [Assignment: organization-defined unusual or unauthorized activities or conditions].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### System-generated Alerts { #si-04-05-system-generated-alerts }

??? abstract "SI-04(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Alert [Assignment: organization-defined personnel or roles] when the following system-generated indications of compromise or potential compromise occur: [Assignment: organization-defined compromise indicators].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Security Alerts, Advisories, and Directives { #si-05-security-alerts-advisories-and-directives }

??? abstract "SI-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Receive system security alerts, advisories, and directives from [Assignment: organization-defined external organizations] on an ongoing basis;
    - **b.** Generate internal security alerts, advisories, and directives as deemed necessary;
    - **c.** Disseminate security alerts, advisories, and directives to: [Assignment: si-05_odp.02]; and
    - **d.** Implement security directives in accordance with established time frames, or notify the issuing organization of the degree of noncompliance.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the FedRAMP Secure Inbox (FSI) guidance.

---

### Spam Protection { #si-08-spam-protection }

??? abstract "SI-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Employ spam protection mechanisms at system entry and exit points to detect and act on unsolicited messages; and
    - **b.** Update spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.

    !!! note ""
        **FedRAMP Guidance**

        When CSO sends email on behalf of the government as part of the business offering, Control Description should include implementation of Domain-based Message Authentication, Reporting & Conformance (DMARC) on the sending domain for outgoing messages as described in DHS Binding Operational Directive (BOD) 18-01. [https://www.cisa.gov/news-events/directives](https://www.cisa.gov/news-events/directives)

        SI-8 Guidance: CSPs should confirm DMARC configuration (where appropriate) to ensure that policy=reject and the rua parameter includes reports@dmarc.cyber.dhs.gov.  DMARC compliance should be documented in the SI-08 control implementation solution description, and list the FROM: domain(s) when emails are sent on behalf of the government.

---

## Supply Chain Risk Management (SR) { #supply-chain-risk-management-sr }

### Supply Chain Controls and Processes { #sr-03-supply-chain-controls-and-processes }

??? abstract "SR-03"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SR-03`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish a process or processes to identify and address weaknesses or deficiencies in the supply chain elements and processes of [Assignment: organization-defined system or system component] in coordination with [Assignment: organization-defined supply chain personnel];
    - **b.** Employ the following controls to protect against supply chain risks to the system, system component, or system service and to limit the harm or consequences from supply chain-related events: [Assignment: organization-defined supply chain controls]; and
    - **c.** Document the selected and implemented supply chain processes and controls in [Selection: one or more of: security and privacy plans; supply chain risk management plan].

    !!! note ""
        **FedRAMP Guidance**

        CSO must document and maintain the supply chain custody, including replacement devices, to ensure the integrity of the devices before being introduced to the boundary.

---

### Notification Agreements { #sr-08-notification-agreements }

??? abstract "SR-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SR-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Establish agreements and procedures with entities involved in the supply chain for the system, system component, or system service for the [Selection: one or more of: notification of supply chain compromises].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Incident Communication Procedure guidance.

---
