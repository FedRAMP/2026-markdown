---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Independent Verification and Validation

This ruleset explains the expectations for independent verification and validation assessments.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### FedRAMP Independent Assessments

??? abstract "IVV-CSO-FIA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 year

    === "Class B"
        Providers with Class B Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 year

    === "Class C"
        Providers with Class C Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 year

    === "Class D"
        Providers with Class D Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 year


    ---

    _**Notes:**_

    - _The first such completed assessment is typically called an "initial assessment" while following assessments are called "annual assessments."_
    - _The specific requirements for independent verification and validation assessments are documented by the FedRAMP Certification Class and Type._
    - _The option for assessment by FedRAMP directly is limited to cloud services that are explicitly prioritized by FedRAMP, in consultation with the FedRAMP Board and the federal Chief Information Officers Council; this is _extremely_ rare._
    - _FedRAMP Recognized independent assessment services are listed on the FedRAMP Marketplace._
    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Evidence of Implementation

??? abstract "IVV-CSO-SEI"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the implementation of the measures that have been documented to meet FedRAMP Practices; this evidence is the result of verification.


    ---

    _**Note:** For example, if the documentation says that firewall rules are used to block traffic then the cloud service provider would verify that firewall rules are in place to block traffic and supply that evidence to assessors (preferably by allowing them to see how firewall configurations are deployed from a source of truth)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Evidence of Effectiveness

??? abstract "IVV-CSO-SEE"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the effectiveness of the measures that have been implemented to meet FedRAMP Practices; this evidence is the result of validation.


    ---

    _**Note:** For example, after verifying that firewalls are configured to block traffic following [IVV-CSO-SEI (Supply Evidence of Implementation)](#supply-evidence-of-implementation){ data-preview }, the provider would validate that traffic is actually being blocked and supply evidence of that validation to assessors (such as by allowing them to see metrics on the traffic that is blocked vs not)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Inclusion in Certification Package

??? abstract "IVV-CSO-ICP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply the results of FedRAMP independent assessments in their FedRAMP Certification Package without inappropriate modification.


    ---

    _**Notes:**_

    - _Inappropriate modification in this context means changing the underlying intent/etc. of the content provided by the independent assessment service - the content itself may be modified for presentation, formatting, etc. as needed._
    - _This rule is related to [IVV-IAS-VIP (Verify Inclusion in Certification Package)](../../../assessors/rules/independent-verification-and-validation.md#verify-inclusion-in-certification-package){ data-preview }._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Document Use of Representative Samples

??? abstract "IVV-CSO-DUS"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST document and explain the use of representative samples during verification and validation when using representative samples as allowed by [IVV-CSO-USR (Use Representative Samples)](#use-representative-samples){ data-preview }.


    ---
    **Terms:** [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Technical Explanations

??? abstract "IVV-CSO-STE"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD supply all necessary assessors with technical explanations, demonstrations, and other relevant supporting information about the technical capabilities they employ to address FedRAMP rules; this SHOULD be supplied as necessary to ensure the assessor can effectively complete verification and validation.


    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Use Representative Samples

??? abstract "IVV-CSO-USR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY use representative samples as appropriate during verification and validation.


    ---

    _**Note:** Many modern cloud services using effective automation do not need to use representative sampling and are capable of persistently verifying and validating the majority of their security measures automatically._

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Receiving Assessor Advice

??? abstract "IVV-CSO-RAA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY ask for and accept advice from their assessor during assessment regarding techniques and procedures that will improve their security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../../../definitions/#likely){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Annual Independent Assessments for Rev5

??? abstract "IVV-CSF-AIA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class B"
        Providers with Rev5 Class B Certifications MUST include the following Rev5 Controls in a FedRAMP independent assessment at least once per year:

        **Timeframe:** 1 year

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-02` ([Account Management](../../../reference/controls/access-control.md#ac-02){ data-preview })
                - `AC-03` ([Access Enforcement](../../../reference/controls/access-control.md#ac-03){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-02` ([Event Logging](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](../../../reference/controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](../../../reference/controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](../../../reference/controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](../../../reference/controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-08` ([Time Stamps](../../../reference/controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-11` ([Audit Record Retention](../../../reference/controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](../../../reference/controls/audit-and-accountability.md#au-12){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-08` ([Penetration Testing](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-08){ data-preview })
            - **Configuration Management (CM)**
                - `CM-05` ([Access Restrictions for Change](../../../reference/controls/configuration-management.md#cm-05){ data-preview })
                - `CM-06` ([Configuration Settings](../../../reference/controls/configuration-management.md#cm-06){ data-preview })
                - `CM-07` ([Least Functionality](../../../reference/controls/configuration-management.md#cm-07){ data-preview })
                - `CM-08` ([System Component Inventory](../../../reference/controls/configuration-management.md#cm-08){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-04` ([Contingency Plan Testing](../../../reference/controls/contingency-planning.md#cp-04){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-02` ([Identification and Authentication (Organizational Users)](../../../reference/controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](../../../reference/controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](../../../reference/controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-04` ([Identifier Management](../../../reference/controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-05` ([Authenticator Management](../../../reference/controls/identification-and-authentication.md#ia-05){ data-preview })
            - **Incident Response (IR)**
                - `IR-04` ([Incident Handling](../../../reference/controls/incident-response.md#ir-04){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-03` ([Physical Access Control](../../../reference/controls/physical-and-environmental-protection.md#pe-03){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-05` ([Vulnerability Monitoring and Scanning](../../../reference/controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](../../../reference/controls/risk-assessment.md#ra-05-02){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-09` ([External System Services](../../../reference/controls/system-and-services-acquisition.md#sa-09){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-07` ([Boundary Protection](../../../reference/controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](../../../reference/controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](../../../reference/controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](../../../reference/controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-28` ([Protection of Information at Rest](../../../reference/controls/system-and-communications-protection.md#sc-28){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-03` ([Malicious Code Protection](../../../reference/controls/system-and-information-integrity.md#si-03){ data-preview })
        
    === "Class C"
        Providers with Rev5 Class C Certifications MUST include the following Rev5 Controls in a FedRAMP independent assessment at least once per year:

        **Timeframe:** 1 year

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-02` ([Account Management](../../../reference/controls/access-control.md#ac-02){ data-preview })
                - `AC-02 (01)` ([Automated System Account Management](../../../reference/controls/access-control.md#ac-02-01){ data-preview })
                - `AC-02 (02)` ([Automated Temporary and Emergency Account Management](../../../reference/controls/access-control.md#ac-02-02){ data-preview })
                - `AC-02 (03)` ([Disable Accounts](../../../reference/controls/access-control.md#ac-02-03){ data-preview })
                - `AC-02 (04)` ([Automated Audit Actions](../../../reference/controls/access-control.md#ac-02-04){ data-preview })
                - `AC-02 (05)` ([Inactivity Logout](../../../reference/controls/access-control.md#ac-02-05){ data-preview })
                - `AC-02 (07)` ([Privileged User Accounts](../../../reference/controls/access-control.md#ac-02-07){ data-preview })
                - `AC-02 (09)` ([Restrictions on Use of Shared and Group Accounts](../../../reference/controls/access-control.md#ac-02-09){ data-preview })
                - `AC-02 (12)` ([Account Monitoring for Atypical Usage](../../../reference/controls/access-control.md#ac-02-12){ data-preview })
                - `AC-02 (13)` ([Disable Accounts for High-risk Individuals](../../../reference/controls/access-control.md#ac-02-13){ data-preview })
                - `AC-03` ([Access Enforcement](../../../reference/controls/access-control.md#ac-03){ data-preview })
                - `AC-06` ([Least Privilege](../../../reference/controls/access-control.md#ac-06){ data-preview })
                - `AC-06 (02)` ([Non-privileged Access for Nonsecurity Functions](../../../reference/controls/access-control.md#ac-06-02){ data-preview })
                - `AC-06 (05)` ([Privileged Accounts](../../../reference/controls/access-control.md#ac-06-05){ data-preview })
                - `AC-06 (10)` ([Prohibit Non-privileged Users from Executing Privileged Functions](../../../reference/controls/access-control.md#ac-06-10){ data-preview })
                - `AC-17 (02)` ([Protection of Confidentiality and Integrity Using Encryption](../../../reference/controls/access-control.md#ac-17-02){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-02` ([Event Logging](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](../../../reference/controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-03 (01)` ([Additional Audit Information](../../../reference/controls/audit-and-accountability.md#au-03-01){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](../../../reference/controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](../../../reference/controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](../../../reference/controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-06 (01)` ([Automated Process Integration](../../../reference/controls/audit-and-accountability.md#au-06-01){ data-preview })
                - `AU-06 (03)` ([Correlate Audit Record Repositories](../../../reference/controls/audit-and-accountability.md#au-06-03){ data-preview })
                - `AU-08` ([Time Stamps](../../../reference/controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-11` ([Audit Record Retention](../../../reference/controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](../../../reference/controls/audit-and-accountability.md#au-12){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-08 (01)` ([Independent Penetration Testing Agent or Team](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-08-01){ data-preview })
                - `CA-08 (02)` ([Red Team Exercises](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-08-02){ data-preview })
            - **Configuration Management (CM)**
                - `CM-05` ([Access Restrictions for Change](../../../reference/controls/configuration-management.md#cm-05){ data-preview })
                - `CM-06` ([Configuration Settings](../../../reference/controls/configuration-management.md#cm-06){ data-preview })
                - `CM-06 (01)` ([Automated Management, Application, and Verification](../../../reference/controls/configuration-management.md#cm-06-01){ data-preview })
                - `CM-07` ([Least Functionality](../../../reference/controls/configuration-management.md#cm-07){ data-preview })
                - `CM-07 (01)` ([Periodic Review](../../../reference/controls/configuration-management.md#cm-07-01){ data-preview })
                - `CM-07 (02)` ([Prevent Program Execution](../../../reference/controls/configuration-management.md#cm-07-02){ data-preview })
                - `CM-07 (05)` ([Authorized Software — Allow-by-exception](../../../reference/controls/configuration-management.md#cm-07-05){ data-preview })
                - `CM-08` ([System Component Inventory](../../../reference/controls/configuration-management.md#cm-08){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-04` ([Contingency Plan Testing](../../../reference/controls/contingency-planning.md#cp-04){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-02` ([Identification and Authentication (Organizational Users)](../../../reference/controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (05)` ([Individual Authentication with Group Authentication](../../../reference/controls/identification-and-authentication.md#ia-02-05){ data-preview })
                - `IA-02 (06)` ([Access to Accounts —separate Device](../../../reference/controls/identification-and-authentication.md#ia-02-06){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](../../../reference/controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](../../../reference/controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-04` ([Identifier Management](../../../reference/controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-05` ([Authenticator Management](../../../reference/controls/identification-and-authentication.md#ia-05){ data-preview })
            - **Incident Response (IR)**
                - `IR-03` ([Incident Response Testing](../../../reference/controls/incident-response.md#ir-03){ data-preview })
                - `IR-04` ([Incident Handling](../../../reference/controls/incident-response.md#ir-04){ data-preview })
                - `IR-04 (01)` ([Automated Incident Handling Processes](../../../reference/controls/incident-response.md#ir-04-01){ data-preview })
            - **Maintenance (MA)**
                - `MA-03 (02)` ([Inspect Media](../../../reference/controls/maintenance.md#ma-03-02){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-03` ([Physical Access Control](../../../reference/controls/physical-and-environmental-protection.md#pe-03){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-05` ([Vulnerability Monitoring and Scanning](../../../reference/controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](../../../reference/controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (03)` ([Breadth and Depth of Coverage](../../../reference/controls/risk-assessment.md#ra-05-03){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-09` ([External System Services](../../../reference/controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-11 (01)` ([Static Code Analysis](../../../reference/controls/system-and-services-acquisition.md#sa-11-01){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-07` ([Boundary Protection](../../../reference/controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-07 (03)` ([Access Points](../../../reference/controls/system-and-communications-protection.md#sc-07-03){ data-preview })
                - `SC-07 (04)` ([External Telecommunications Services](../../../reference/controls/system-and-communications-protection.md#sc-07-04){ data-preview })
                - `SC-07 (05)` ([Deny by Default — Allow by Exception](../../../reference/controls/system-and-communications-protection.md#sc-07-05){ data-preview })
                - `SC-07 (07)` ([Split Tunneling for Remote Devices](../../../reference/controls/system-and-communications-protection.md#sc-07-07){ data-preview })
                - `SC-07 (08)` ([Route Traffic to Authenticated Proxy Servers](../../../reference/controls/system-and-communications-protection.md#sc-07-08){ data-preview })
                - `SC-07 (12)` ([Host-based Protection](../../../reference/controls/system-and-communications-protection.md#sc-07-12){ data-preview })
                - `SC-07 (18)` ([Fail Secure](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](../../../reference/controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](../../../reference/controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](../../../reference/controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-28` ([Protection of Information at Rest](../../../reference/controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-45 (01)` ([Synchronization with Authoritative Time Source](../../../reference/controls/system-and-communications-protection.md#sc-45-01){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-03` ([Malicious Code Protection](../../../reference/controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04 (01)` ([System-wide Intrusion Detection System](../../../reference/controls/system-and-information-integrity.md#si-04-01){ data-preview })
                - `SI-04 (02)` ([Automated Tools and Mechanisms for Real-time Analysis](../../../reference/controls/system-and-information-integrity.md#si-04-02){ data-preview })
                - `SI-04 (16)` ([Correlate Monitoring Information](../../../reference/controls/system-and-information-integrity.md#si-04-16){ data-preview })
                - `SI-04 (23)` ([Host-based Devices](../../../reference/controls/system-and-information-integrity.md#si-04-23){ data-preview })
                - `SI-06` ([Security and Privacy Function Verification](../../../reference/controls/system-and-information-integrity.md#si-06){ data-preview })
                - `SI-07` ([Software, Firmware, and Information Integrity](../../../reference/controls/system-and-information-integrity.md#si-07){ data-preview })
                - `SI-07 (01)` ([Integrity Checks](../../../reference/controls/system-and-information-integrity.md#si-07-01){ data-preview })
                - `SI-10` ([Information Input Validation](../../../reference/controls/system-and-information-integrity.md#si-10){ data-preview })
        
    === "Class D"
        Providers with Rev5 Class D Certifications MUST include the following Rev5 Controls in a FedRAMP independent assessment at least once per year:

        **Timeframe:** 1 year

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-02` ([Account Management](../../../reference/controls/access-control.md#ac-02){ data-preview })
                - `AC-02 (01)` ([Automated System Account Management](../../../reference/controls/access-control.md#ac-02-01){ data-preview })
                - `AC-02 (02)` ([Automated Temporary and Emergency Account Management](../../../reference/controls/access-control.md#ac-02-02){ data-preview })
                - `AC-02 (03)` ([Disable Accounts](../../../reference/controls/access-control.md#ac-02-03){ data-preview })
                - `AC-02 (04)` ([Automated Audit Actions](../../../reference/controls/access-control.md#ac-02-04){ data-preview })
                - `AC-02 (05)` ([Inactivity Logout](../../../reference/controls/access-control.md#ac-02-05){ data-preview })
                - `AC-02 (07)` ([Privileged User Accounts](../../../reference/controls/access-control.md#ac-02-07){ data-preview })
                - `AC-02 (09)` ([Restrictions on Use of Shared and Group Accounts](../../../reference/controls/access-control.md#ac-02-09){ data-preview })
                - `AC-02 (11)` ([Usage Conditions](../../../reference/controls/access-control.md#ac-02-11){ data-preview })
                - `AC-02 (12)` ([Account Monitoring for Atypical Usage](../../../reference/controls/access-control.md#ac-02-12){ data-preview })
                - `AC-02 (13)` ([Disable Accounts for High-risk Individuals](../../../reference/controls/access-control.md#ac-02-13){ data-preview })
                - `AC-03` ([Access Enforcement](../../../reference/controls/access-control.md#ac-03){ data-preview })
                - `AC-06` ([Least Privilege](../../../reference/controls/access-control.md#ac-06){ data-preview })
                - `AC-06 (02)` ([Non-privileged Access for Nonsecurity Functions](../../../reference/controls/access-control.md#ac-06-02){ data-preview })
                - `AC-06 (03)` ([Network Access to Privileged Commands](../../../reference/controls/access-control.md#ac-06-03){ data-preview })
                - `AC-06 (05)` ([Privileged Accounts](../../../reference/controls/access-control.md#ac-06-05){ data-preview })
                - `AC-06 (08)` ([Privilege Levels for Code Execution](../../../reference/controls/access-control.md#ac-06-08){ data-preview })
                - `AC-06 (10)` ([Prohibit Non-privileged Users from Executing Privileged Functions](../../../reference/controls/access-control.md#ac-06-10){ data-preview })
                - `AC-17 (02)` ([Protection of Confidentiality and Integrity Using Encryption](../../../reference/controls/access-control.md#ac-17-02){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-02` ([Event Logging](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](../../../reference/controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-03 (01)` ([Additional Audit Information](../../../reference/controls/audit-and-accountability.md#au-03-01){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](../../../reference/controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](../../../reference/controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-05 (01)` ([Storage Capacity Warning](../../../reference/controls/audit-and-accountability.md#au-05-01){ data-preview })
                - `AU-05 (02)` ([Real-time Alerts](../../../reference/controls/audit-and-accountability.md#au-05-02){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](../../../reference/controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-06 (01)` ([Automated Process Integration](../../../reference/controls/audit-and-accountability.md#au-06-01){ data-preview })
                - `AU-06 (03)` ([Correlate Audit Record Repositories](../../../reference/controls/audit-and-accountability.md#au-06-03){ data-preview })
                - `AU-06 (04)` ([Central Review and Analysis](../../../reference/controls/audit-and-accountability.md#au-06-04){ data-preview })
                - `AU-06 (05)` ([Integrated Analysis of Audit Records](../../../reference/controls/audit-and-accountability.md#au-06-05){ data-preview })
                - `AU-06 (06)` ([Correlation with Physical Monitoring](../../../reference/controls/audit-and-accountability.md#au-06-06){ data-preview })
                - `AU-06 (07)` ([Permitted Actions](../../../reference/controls/audit-and-accountability.md#au-06-07){ data-preview })
                - `AU-08` ([Time Stamps](../../../reference/controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-10` ([Non-repudiation](../../../reference/controls/audit-and-accountability.md#au-10){ data-preview })
                - `AU-11` ([Audit Record Retention](../../../reference/controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](../../../reference/controls/audit-and-accountability.md#au-12){ data-preview })
                - `AU-12 (01)` ([System-wide and Time-correlated Audit Trail](../../../reference/controls/audit-and-accountability.md#au-12-01){ data-preview })
                - `AU-12 (03)` ([Changes by Authorized Individuals](../../../reference/controls/audit-and-accountability.md#au-12-03){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-08 (01)` ([Independent Penetration Testing Agent or Team](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-08-01){ data-preview })
                - `CA-08 (02)` ([Red Team Exercises](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-08-02){ data-preview })
            - **Configuration Management (CM)**
                - `CM-05` ([Access Restrictions for Change](../../../reference/controls/configuration-management.md#cm-05){ data-preview })
                - `CM-06` ([Configuration Settings](../../../reference/controls/configuration-management.md#cm-06){ data-preview })
                - `CM-06 (01)` ([Automated Management, Application, and Verification](../../../reference/controls/configuration-management.md#cm-06-01){ data-preview })
                - `CM-06 (02)` ([Respond to Unauthorized Changes](../../../reference/controls/configuration-management.md#cm-06-02){ data-preview })
                - `CM-07` ([Least Functionality](../../../reference/controls/configuration-management.md#cm-07){ data-preview })
                - `CM-07 (01)` ([Periodic Review](../../../reference/controls/configuration-management.md#cm-07-01){ data-preview })
                - `CM-07 (02)` ([Prevent Program Execution](../../../reference/controls/configuration-management.md#cm-07-02){ data-preview })
                - `CM-07 (05)` ([Authorized Software — Allow-by-exception](../../../reference/controls/configuration-management.md#cm-07-05){ data-preview })
                - `CM-08` ([System Component Inventory](../../../reference/controls/configuration-management.md#cm-08){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-04` ([Contingency Plan Testing](../../../reference/controls/contingency-planning.md#cp-04){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-02` ([Identification and Authentication (Organizational Users)](../../../reference/controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](../../../reference/controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (05)` ([Individual Authentication with Group Authentication](../../../reference/controls/identification-and-authentication.md#ia-02-05){ data-preview })
                - `IA-02 (06)` ([Access to Accounts —separate Device](../../../reference/controls/identification-and-authentication.md#ia-02-06){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](../../../reference/controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](../../../reference/controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-04` ([Identifier Management](../../../reference/controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-05` ([Authenticator Management](../../../reference/controls/identification-and-authentication.md#ia-05){ data-preview })
            - **Incident Response (IR)**
                - `IR-03` ([Incident Response Testing](../../../reference/controls/incident-response.md#ir-03){ data-preview })
                - `IR-04` ([Incident Handling](../../../reference/controls/incident-response.md#ir-04){ data-preview })
                - `IR-04 (01)` ([Automated Incident Handling Processes](../../../reference/controls/incident-response.md#ir-04-01){ data-preview })
                - `IR-04 (02)` ([Dynamic Reconfiguration](../../../reference/controls/incident-response.md#ir-04-02){ data-preview })
                - `IR-04 (04)` ([Information Correlation](../../../reference/controls/incident-response.md#ir-04-04){ data-preview })
                - `IR-04 (06)` ([Insider Threats](../../../reference/controls/incident-response.md#ir-04-06){ data-preview })
            - **Maintenance (MA)**
                - `MA-03 (02)` ([Inspect Media](../../../reference/controls/maintenance.md#ma-03-02){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-03` ([Physical Access Control](../../../reference/controls/physical-and-environmental-protection.md#pe-03){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-05` ([Vulnerability Monitoring and Scanning](../../../reference/controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](../../../reference/controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (03)` ([Breadth and Depth of Coverage](../../../reference/controls/risk-assessment.md#ra-05-03){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-09` ([External System Services](../../../reference/controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-11 (01)` ([Static Code Analysis](../../../reference/controls/system-and-services-acquisition.md#sa-11-01){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-07` ([Boundary Protection](../../../reference/controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-07 (03)` ([Access Points](../../../reference/controls/system-and-communications-protection.md#sc-07-03){ data-preview })
                - `SC-07 (04)` ([External Telecommunications Services](../../../reference/controls/system-and-communications-protection.md#sc-07-04){ data-preview })
                - `SC-07 (05)` ([Deny by Default — Allow by Exception](../../../reference/controls/system-and-communications-protection.md#sc-07-05){ data-preview })
                - `SC-07 (07)` ([Split Tunneling for Remote Devices](../../../reference/controls/system-and-communications-protection.md#sc-07-07){ data-preview })
                - `SC-07 (08)` ([Route Traffic to Authenticated Proxy Servers](../../../reference/controls/system-and-communications-protection.md#sc-07-08){ data-preview })
                - `SC-07 (12)` ([Host-based Protection](../../../reference/controls/system-and-communications-protection.md#sc-07-12){ data-preview })
                - `SC-07 (18)` ([Fail Secure](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview })
                - `SC-07 (20)` ([Dynamic Isolation and Segregation](../../../reference/controls/system-and-communications-protection.md#sc-07-20){ data-preview })
                - `SC-07 (21)` ([Isolation of System Components](../../../reference/controls/system-and-communications-protection.md#sc-07-21){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](../../../reference/controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](../../../reference/controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](../../../reference/controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-28` ([Protection of Information at Rest](../../../reference/controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-45 (01)` ([Synchronization with Authoritative Time Source](../../../reference/controls/system-and-communications-protection.md#sc-45-01){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-03` ([Malicious Code Protection](../../../reference/controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04 (01)` ([System-wide Intrusion Detection System](../../../reference/controls/system-and-information-integrity.md#si-04-01){ data-preview })
                - `SI-04 (02)` ([Automated Tools and Mechanisms for Real-time Analysis](../../../reference/controls/system-and-information-integrity.md#si-04-02){ data-preview })
                - `SI-04 (10)` ([Visibility of Encrypted Communications](../../../reference/controls/system-and-information-integrity.md#si-04-10){ data-preview })
                - `SI-04 (16)` ([Correlate Monitoring Information](../../../reference/controls/system-and-information-integrity.md#si-04-16){ data-preview })
                - `SI-04 (19)` ([Risk for Individuals](../../../reference/controls/system-and-information-integrity.md#si-04-19){ data-preview })
                - `SI-04 (20)` ([Privileged Users](../../../reference/controls/system-and-information-integrity.md#si-04-20){ data-preview })
                - `SI-04 (23)` ([Host-based Devices](../../../reference/controls/system-and-information-integrity.md#si-04-23){ data-preview })
                - `SI-06` ([Security and Privacy Function Verification](../../../reference/controls/system-and-information-integrity.md#si-06){ data-preview })
                - `SI-07` ([Software, Firmware, and Information Integrity](../../../reference/controls/system-and-information-integrity.md#si-07){ data-preview })
                - `SI-07 (01)` ([Integrity Checks](../../../reference/controls/system-and-information-integrity.md#si-07-01){ data-preview })
                - `SI-10` ([Information Input Validation](../../../reference/controls/system-and-information-integrity.md#si-10){ data-preview })
        

    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Mandatory Control Assessment

??? abstract "IVV-CSF-MCA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST have all applicable Rev5 Controls included in FedRAMP independent assessments every 3 years but are not required to have all Rev5 Controls included in the same FedRAMP independent assessment.


    ---

    _**Note:** Traditionally this has been done by reviewing a rotating selection of Rev5 Controls at each annual assessment, however this requirement is a ceiling and not a floor. See [IVV-CSF-PCA (Preferred Control Assessment)](#preferred-control-assessment){ data-preview } for FedRAMP's recommended approach to Rev5 control assessments._

    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Assessment of Rev5 Controls with Findings

??? abstract "IVV-CSF-ACF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST have Rev5 Controls with negative findings from the previous FedRAMP independent assessment included in the next FedRAMP independent assessment.


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Preferred Control Assessment

??? abstract "IVV-CSF-PCA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD include all applicable Rev5 Controls in each FedRAMP independent assessment.


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
