---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# FedRAMP Certification

This ruleset explains how cloud service offerings obtain and maintain FedRAMP Certification across certification classes and paths.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Applying for FedRAMP Certification](#applying-for-fedramp-certification)
- [Applying for FedRAMP Certification with an Agency Sponsor](#applying-for-fedramp-certification-with-an-agency-sponsor)
- [Changing Certification Class](#changing-certification-class)
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
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### FedRAMP Certification Profile

??? abstract "FRC-CSO-FCP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST identify a target FedRAMP Certification Profile and apply all relevant FedRAMP Practices to the cloud service offering.


    ---

    _**Note:** Information resources (including third-party information resources) MAY vary by security category as appropriate to the type of information handled by or impacted by the information resource._

    ---
    **Terms:** [Certification Profile](../../../definitions/#certification-profile){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Handle](../../../definitions/#handle){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../../../definitions/#third-party-information-resource){ data-preview }
### FedRAMP Certification Package

??? abstract "FRC-CSO-PKG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Certification Overview Package (FRC-CSO-PKG)](https://fedramp.gov/schemas/fedramp-certification-overview-package-schema-2026-06-24.json)"


!!! quote ""
    Providers seeking a Class B Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

    1. A Certification Package Overview
    1. A Security Decision Record
    1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Certification Report](../../../definitions/#fedramp-certification-report){ data-preview }, [Initial Certification](../../../definitions/#initial-certification){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
### FedRAMP JSON Schemas

??? abstract "FRC-CSO-JSN"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply machine-readable information in JSON documents that are valid against the corresponding JSON schema when a rule contains a FedRAMP JSON schema, UNLESS otherwise specified in the rule.


    ---

    _**Note:** FedRAMP JSON schemas are designed to be lightweight and flexible to establish a minimum set of structured information while allowing providers to improve on the format and structure of the information as needed to meet their needs and the needs of their customers._

    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### Maintain Responsibility and Accountability

??? abstract "FRC-CSO-MRA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST maintain responsibility and accountability for the accuracy and completeness of all information in the FedRAMP Certification Package, especially when they engage a third party (such as an independent assessor, advisory service, or external tools) to supply information on their behalf.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
### Pick One Program Certification Type

??? abstract "FRC-CSO-POP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST NOT seek both FedRAMP Rev5 Program Certification and FedRAMP 20x Program Certification for the same cloud service offering; pick one type.


    ---

    _**Note:** This rule does not prevent a provider from seeking and maintaining a FedRAMP Rev5 Agency Certification and a FedRAMP 20x Program Certification for the same cloud service offering, however, doing so is strongly discouraged due to the increased complexity and risk of confusion for all parties._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Marketplace Listing First

??? abstract "FRC-APP-MLF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST be listed in the FedRAMP Marketplace before applying for FedRAMP Certification, including:

    1. FedRAMP Marketplace: [MKT-CSO-MLR (Marketplace Listing Requirements)](marketplace-listing.md#marketplace-listing-requirements){ data-preview },
    1. FedRAMP Marketplace: [MKT-CSO-PML (Provider Marketplace Listing Requests)](marketplace-listing.md#provider-marketplace-listing-requests){ data-preview }
    1. FedRAMP Marketplace: [MKT-IIP-AGU (Agency Use Cases)](marketplace-listing.md#agency-use-cases){ data-preview }
    1. FedRAMP Marketplace: [MKT-IIP-DCP (Demonstrating Continuous Progress)](marketplace-listing.md#demonstrating-continuous-progress){ data-preview }


### Applying for FedRAMP Certification

??? abstract "FRC-APP-AFC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via form: [\[For CSPs\] FedRAMP Certification Application Form](https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51137131584283).


!!! quote ""
    Providers MUST complete the FedRAMP Certification Application Form in full to request an initial assessment by FedRAMP.


### Fresh FedRAMP Certification Package

??? abstract "FRC-APP-FCP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply a fresh initial FedRAMP Certification Package that shows the current status of the cloud service offering as verified and validated by the provider within the previous 7 days.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Fresh Independent Assessment

??? abstract "FRC-APP-FIA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class B"
        Providers seeking Class B Certification MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

        **Timeframe:** 3 months


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }
### No Third-Party Applicants

??? abstract "FRC-APP-NTP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST NOT use a third party to apply for a FedRAMP Certification on their behalf; this includes independent assessment services.


    ---

    _**Notes:**_

    - _FedRAMP previously allowed independent assessment services to submit applications on behalf of providers, but this caused confusion about who was responsible for the application and the information in it. Providers should apply directly to ensure clear accountability._
    - _Providers may use third parties to help them prepare their application and assessment materials for submission._
### Updating Stale Assessments

??? abstract "FRC-APP-USA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY freshen a stale initial independent verification and validation assessment by having a FedRAMP Recognized independent assessment service review any changes between the original assessment and the current status of the cloud service offering in place of a full re-assessment, UNLESS the stale assessment is more than 9 months old.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification with an Agency Sponsor {#applying-for-fedramp-certification-with-an-agency-sponsor}

These rules apply to cloud service providers with an Agency Sponsor who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Agency Authorization to Operate

??? abstract "FRC-APS-ATO"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Rev5 Agency Certification MUST have completed the Authorization to Operate (ATO) process with their agency sponsor for the cloud service offering, concluding with a formal signed ATO letter that the agency has sent over official government channels to FedRAMP.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
## Changing Certification Class {#changing-certification-class}

These rules apply to cloud service providers when changing their FedRAMP Certification Class.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Upgrading Certification Class

??? abstract "FRC-CCL-UCC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST apply for a new FedRAMP Certification to upgrade their Certification Class; all applicable requirements MUST be met in advance.


    ---

    _**Notes:**_

    - _Upgrade paths include moving from A to B, C, or D; B to C or D; and C to D._
    - _The preferred path is to incrementally update the implementation and assurance commitments within the current Certification Class until the provider has met all requirements for the target Certification Class, then apply for the new Certification Class._
    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }
### Downgrading Certification Class

??? abstract "FRC-CCL-DCC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST apply for a new FedRAMP Certification to downgrade their Certification Class.


    ---

    _**Notes:**_

    - _Downgrade paths include moving from D to C, B, or A; C to B or A; or B to A._
    - _[FRC-CCL-DNP (Downgrade Notification Period)](#downgrade-notification-period){ data-preview } applies - please DO NOT downgrade Certification Class with providing advance notification to all necessary parties!_
    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Class](../../../definitions/#certification-class){ data-preview }
### Downgrade Notification Period

??? abstract "FRC-CCL-DNP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD notify all necessary parties at least 120 days in advance of an intended downgrade or cancellation of FedRAMP Certification.


    ---

    _**Note:** Downgrading or canceling FedRAMP Certification will have severe negative consequences for the provider and their agency customers and should only be done after careful consideration and planning... but if it must be done, notify all necessary parties as soon as possible._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### FedRAMP Rev5 Baselines

??? abstract "FRC-CSF-BSL"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class B"
        Providers seeking FedRAMP Rev5 Class B Certification MUST include at least the following NIST SP 800-53 Rev. 5 controls in their Security Decision Record:

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-01` ([Policy and Procedures](../../controls/access-control.md#ac-01){ data-preview })
                - `AC-02` ([Account Management](../../controls/access-control.md#ac-02){ data-preview })
                - `AC-03` ([Access Enforcement](../../controls/access-control.md#ac-03){ data-preview })
                - `AC-07` ([Unsuccessful Logon Attempts](../../controls/access-control.md#ac-07){ data-preview })
                - `AC-08` ([System Use Notification](../../controls/access-control.md#ac-08){ data-preview })
                - `AC-14` ([Permitted Actions Without Identification or Authentication](../../controls/access-control.md#ac-14){ data-preview })
                - `AC-17` ([Remote Access](../../controls/access-control.md#ac-17){ data-preview })
                - `AC-18` ([Wireless Access](../../controls/access-control.md#ac-18){ data-preview })
                - `AC-19` ([Access Control for Mobile Devices](../../controls/access-control.md#ac-19){ data-preview })
                - `AC-20` ([Use of External Systems](../../controls/access-control.md#ac-20){ data-preview })
                - `AC-22` ([Publicly Accessible Content](../../controls/access-control.md#ac-22){ data-preview })
            - **Awareness and Training (AT)**
                - `AT-01` ([Policy and Procedures](../../controls/awareness-and-training.md#at-01){ data-preview })
                - `AT-02` ([Literacy Training and Awareness](../../controls/awareness-and-training.md#at-02){ data-preview })
                - `AT-02 (02)` ([Insider Threat](../../controls/awareness-and-training.md#at-02-02){ data-preview })
                - `AT-03` ([Role-based Training](../../controls/awareness-and-training.md#at-03){ data-preview })
                - `AT-04` ([Training Records](../../controls/awareness-and-training.md#at-04){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-01` ([Policy and Procedures](../../controls/audit-and-accountability.md#au-01){ data-preview })
                - `AU-02` ([Event Logging](../../controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](../../controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](../../controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](../../controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](../../controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-08` ([Time Stamps](../../controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-09` ([Protection of Audit Information](../../controls/audit-and-accountability.md#au-09){ data-preview })
                - `AU-11` ([Audit Record Retention](../../controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](../../controls/audit-and-accountability.md#au-12){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-01` ([Policy and Procedures](../../controls/assessment-authorization-and-monitoring.md#ca-01){ data-preview })
                - `CA-02` ([Control Assessments](../../controls/assessment-authorization-and-monitoring.md#ca-02){ data-preview })
                - `CA-02 (01)` ([Independent Assessors](../../controls/assessment-authorization-and-monitoring.md#ca-02-01){ data-preview })
                - `CA-03` ([Information Exchange](../../controls/assessment-authorization-and-monitoring.md#ca-03){ data-preview })
                - `CA-06` ([Authorization](../../controls/assessment-authorization-and-monitoring.md#ca-06){ data-preview })
                - `CA-07` ([Continuous Monitoring](../../controls/assessment-authorization-and-monitoring.md#ca-07){ data-preview })
                - `CA-07 (04)` ([Risk Monitoring](../../controls/assessment-authorization-and-monitoring.md#ca-07-04){ data-preview })
                - `CA-08` ([Penetration Testing](../../controls/assessment-authorization-and-monitoring.md#ca-08){ data-preview })
                - `CA-09` ([Internal System Connections](../../controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview })
            - **Configuration Management (CM)**
                - `CM-01` ([Policy and Procedures](../../controls/configuration-management.md#cm-01){ data-preview })
                - `CM-02` ([Baseline Configuration](../../controls/configuration-management.md#cm-02){ data-preview })
                - `CM-04` ([Impact Analyses](../../controls/configuration-management.md#cm-04){ data-preview })
                - `CM-05` ([Access Restrictions for Change](../../controls/configuration-management.md#cm-05){ data-preview })
                - `CM-06` ([Configuration Settings](../../controls/configuration-management.md#cm-06){ data-preview })
                - `CM-07` ([Least Functionality](../../controls/configuration-management.md#cm-07){ data-preview })
                - `CM-08` ([System Component Inventory](../../controls/configuration-management.md#cm-08){ data-preview })
                - `CM-10` ([Software Usage Restrictions](../../controls/configuration-management.md#cm-10){ data-preview })
                - `CM-11` ([User-installed Software](../../controls/configuration-management.md#cm-11){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-01` ([Policy and Procedures](../../controls/contingency-planning.md#cp-01){ data-preview })
                - `CP-02` ([Contingency Plan](../../controls/contingency-planning.md#cp-02){ data-preview })
                - `CP-03` ([Contingency Training](../../controls/contingency-planning.md#cp-03){ data-preview })
                - `CP-04` ([Contingency Plan Testing](../../controls/contingency-planning.md#cp-04){ data-preview })
                - `CP-09` ([System Backup](../../controls/contingency-planning.md#cp-09){ data-preview })
                - `CP-10` ([System Recovery and Reconstitution](../../controls/contingency-planning.md#cp-10){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-01` ([Policy and Procedures](../../controls/identification-and-authentication.md#ia-01){ data-preview })
                - `IA-02` ([Identification and Authentication (Organizational Users)](../../controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](../../controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](../../controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](../../controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](../../controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-04` ([Identifier Management](../../controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-05` ([Authenticator Management](../../controls/identification-and-authentication.md#ia-05){ data-preview })
                - `IA-05 (01)` ([Password-based Authentication](../../controls/identification-and-authentication.md#ia-05-01){ data-preview })
                - `IA-06` ([Authentication Feedback](../../controls/identification-and-authentication.md#ia-06){ data-preview })
                - `IA-07` ([Cryptographic Module Authentication](../../controls/identification-and-authentication.md#ia-07){ data-preview })
                - `IA-08` ([Identification and Authentication (Non-organizational Users)](../../controls/identification-and-authentication.md#ia-08){ data-preview })
                - `IA-08 (01)` ([Acceptance of PIV Credentials from Other Agencies](../../controls/identification-and-authentication.md#ia-08-01){ data-preview })
                - `IA-08 (02)` ([Acceptance of External Authenticators](../../controls/identification-and-authentication.md#ia-08-02){ data-preview })
                - `IA-08 (04)` ([Use of Defined Profiles](../../controls/identification-and-authentication.md#ia-08-04){ data-preview })
                - `IA-11` ([Re-authentication](../../controls/identification-and-authentication.md#ia-11){ data-preview })
            - **Incident Response (IR)**
                - `IR-01` ([Policy and Procedures](../../controls/incident-response.md#ir-01){ data-preview })
                - `IR-02` ([Incident Response Training](../../controls/incident-response.md#ir-02){ data-preview })
                - `IR-04` ([Incident Handling](../../controls/incident-response.md#ir-04){ data-preview })
                - `IR-05` ([Incident Monitoring](../../controls/incident-response.md#ir-05){ data-preview })
                - `IR-06` ([Incident Reporting](../../controls/incident-response.md#ir-06){ data-preview })
                - `IR-07` ([Incident Response Assistance](../../controls/incident-response.md#ir-07){ data-preview })
                - `IR-08` ([Incident Response Plan](../../controls/incident-response.md#ir-08){ data-preview })
            - **Maintenance (MA)**
                - `MA-01` ([Policy and Procedures](../../controls/maintenance.md#ma-01){ data-preview })
                - `MA-02` ([Controlled Maintenance](../../controls/maintenance.md#ma-02){ data-preview })
                - `MA-04` ([Nonlocal Maintenance](../../controls/maintenance.md#ma-04){ data-preview })
                - `MA-05` ([Maintenance Personnel](../../controls/maintenance.md#ma-05){ data-preview })
            - **Media Protection (MP)**
                - `MP-01` ([Policy and Procedures](../../controls/media-protection.md#mp-01){ data-preview })
                - `MP-02` ([Media Access](../../controls/media-protection.md#mp-02){ data-preview })
                - `MP-06` ([Media Sanitization](../../controls/media-protection.md#mp-06){ data-preview })
                - `MP-07` ([Media Use](../../controls/media-protection.md#mp-07){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-01` ([Policy and Procedures](../../controls/physical-and-environmental-protection.md#pe-01){ data-preview })
                - `PE-02` ([Physical Access Authorizations](../../controls/physical-and-environmental-protection.md#pe-02){ data-preview })
                - `PE-03` ([Physical Access Control](../../controls/physical-and-environmental-protection.md#pe-03){ data-preview })
                - `PE-06` ([Monitoring Physical Access](../../controls/physical-and-environmental-protection.md#pe-06){ data-preview })
                - `PE-08` ([Visitor Access Records](../../controls/physical-and-environmental-protection.md#pe-08){ data-preview })
                - `PE-12` ([Emergency Lighting](../../controls/physical-and-environmental-protection.md#pe-12){ data-preview })
                - `PE-13` ([Fire Protection](../../controls/physical-and-environmental-protection.md#pe-13){ data-preview })
                - `PE-14` ([Environmental Controls](../../controls/physical-and-environmental-protection.md#pe-14){ data-preview })
                - `PE-15` ([Water Damage Protection](../../controls/physical-and-environmental-protection.md#pe-15){ data-preview })
                - `PE-16` ([Delivery and Removal](../../controls/physical-and-environmental-protection.md#pe-16){ data-preview })
            - **Planning (PL)**
                - `PL-01` ([Policy and Procedures](../../controls/planning.md#pl-01){ data-preview })
                - `PL-02` ([System Security and Privacy Plans](../../controls/planning.md#pl-02){ data-preview })
                - `PL-04` ([Rules of Behavior](../../controls/planning.md#pl-04){ data-preview })
                - `PL-04 (01)` ([Social Media and External Site/Application Usage Restrictions](../../controls/planning.md#pl-04-01){ data-preview })
                - `PL-08` ([Security and Privacy Architectures](../../controls/planning.md#pl-08){ data-preview })
                - `PL-10` ([Baseline Selection](../../controls/planning.md#pl-10){ data-preview })
                - `PL-11` ([Baseline Tailoring](../../controls/planning.md#pl-11){ data-preview })
            - **Personnel Security (PS)**
                - `PS-01` ([Policy and Procedures](../../controls/personnel-security.md#ps-01){ data-preview })
                - `PS-02` ([Position Risk Designation](../../controls/personnel-security.md#ps-02){ data-preview })
                - `PS-03` ([Personnel Screening](../../controls/personnel-security.md#ps-03){ data-preview })
                - `PS-04` ([Personnel Termination](../../controls/personnel-security.md#ps-04){ data-preview })
                - `PS-05` ([Personnel Transfer](../../controls/personnel-security.md#ps-05){ data-preview })
                - `PS-06` ([Access Agreements](../../controls/personnel-security.md#ps-06){ data-preview })
                - `PS-07` ([External Personnel Security](../../controls/personnel-security.md#ps-07){ data-preview })
                - `PS-08` ([Personnel Sanctions](../../controls/personnel-security.md#ps-08){ data-preview })
                - `PS-09` ([Position Descriptions](../../controls/personnel-security.md#ps-09){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-01` ([Policy and Procedures](../../controls/risk-assessment.md#ra-01){ data-preview })
                - `RA-02` ([Security Categorization](../../controls/risk-assessment.md#ra-02){ data-preview })
                - `RA-03` ([Risk Assessment](../../controls/risk-assessment.md#ra-03){ data-preview })
                - `RA-03 (01)` ([Supply Chain Risk Assessment](../../controls/risk-assessment.md#ra-03-01){ data-preview })
                - `RA-05` ([Vulnerability Monitoring and Scanning](../../controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](../../controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (11)` ([Public Disclosure Program](../../controls/risk-assessment.md#ra-05-11){ data-preview })
                - `RA-07` ([Risk Response](../../controls/risk-assessment.md#ra-07){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-01` ([Policy and Procedures](../../controls/system-and-services-acquisition.md#sa-01){ data-preview })
                - `SA-02` ([Allocation of Resources](../../controls/system-and-services-acquisition.md#sa-02){ data-preview })
                - `SA-03` ([System Development Life Cycle](../../controls/system-and-services-acquisition.md#sa-03){ data-preview })
                - `SA-04` ([Acquisition Process](../../controls/system-and-services-acquisition.md#sa-04){ data-preview })
                - `SA-04 (10)` ([Use of Approved PIV Products](../../controls/system-and-services-acquisition.md#sa-04-10){ data-preview })
                - `SA-05` ([System Documentation](../../controls/system-and-services-acquisition.md#sa-05){ data-preview })
                - `SA-08` ([Security and Privacy Engineering Principles](../../controls/system-and-services-acquisition.md#sa-08){ data-preview })
                - `SA-09` ([External System Services](../../controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-22` ([Unsupported System Components](../../controls/system-and-services-acquisition.md#sa-22){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-01` ([Policy and Procedures](../../controls/system-and-communications-protection.md#sc-01){ data-preview })
                - `SC-05` ([Denial-of-service Protection](../../controls/system-and-communications-protection.md#sc-05){ data-preview })
                - `SC-07` ([Boundary Protection](../../controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](../../controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-08 (01)` ([Cryptographic Protection](../../controls/system-and-communications-protection.md#sc-08-01){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](../../controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](../../controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-15` ([Collaborative Computing Devices and Applications](../../controls/system-and-communications-protection.md#sc-15){ data-preview })
                - `SC-20` ([Secure Name/Address Resolution Service (Authoritative Source)](../../controls/system-and-communications-protection.md#sc-20){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](../../controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-22` ([Architecture and Provisioning for Name/Address Resolution Service](../../controls/system-and-communications-protection.md#sc-22){ data-preview })
                - `SC-28` ([Protection of Information at Rest](../../controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-28 (01)` ([Cryptographic Protection](../../controls/system-and-communications-protection.md#sc-28-01){ data-preview })
                - `SC-39` ([Process Isolation](../../controls/system-and-communications-protection.md#sc-39){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-01` ([Policy and Procedures](../../controls/system-and-information-integrity.md#si-01){ data-preview })
                - `SI-02` ([Flaw Remediation](../../controls/system-and-information-integrity.md#si-02){ data-preview })
                - `SI-03` ([Malicious Code Protection](../../controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04` ([System Monitoring](../../controls/system-and-information-integrity.md#si-04){ data-preview })
                - `SI-05` ([Security Alerts, Advisories, and Directives](../../controls/system-and-information-integrity.md#si-05){ data-preview })
                - `SI-12` ([Information Management and Retention](../../controls/system-and-information-integrity.md#si-12){ data-preview })
            - **Supply Chain Risk Management (SR)**
                - `SR-01` ([Policy and Procedures](../../controls/supply-chain-risk-management.md#sr-01){ data-preview })
                - `SR-02` ([Supply Chain Risk Management Plan](../../controls/supply-chain-risk-management.md#sr-02){ data-preview })
                - `SR-02 (01)` ([Establish SCRM Team](../../controls/supply-chain-risk-management.md#sr-02-01){ data-preview })
                - `SR-03` ([Supply Chain Controls and Processes](../../controls/supply-chain-risk-management.md#sr-03){ data-preview })
                - `SR-05` ([Acquisition Strategies, Tools, and Methods](../../controls/supply-chain-risk-management.md#sr-05){ data-preview })
                - `SR-08` ([Notification Agreements](../../controls/supply-chain-risk-management.md#sr-08){ data-preview })
                - `SR-10` ([Inspection of Systems or Components](../../controls/supply-chain-risk-management.md#sr-10){ data-preview })
                - `SR-11` ([Component Authenticity](../../controls/supply-chain-risk-management.md#sr-11){ data-preview })
                - `SR-11 (01)` ([Anti-counterfeit Training](../../controls/supply-chain-risk-management.md#sr-11-01){ data-preview })
                - `SR-11 (02)` ([Configuration Control for Component Service and Repair](../../controls/supply-chain-risk-management.md#sr-11-02){ data-preview })
                - `SR-12` ([Component Disposal](../../controls/supply-chain-risk-management.md#sr-12){ data-preview })
        


    **Reference:** [NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)

    ---
    **Terms:** [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
### Assign Control Parameters

??? abstract "FRC-CSF-ACP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST assign all organization-defined control parameters, following FedRAMP Rev5 Controls Guidance, and ensure that all control parameter assignments are documented in the Security Decision Record (SDR).


    ---
    **Terms:** [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
### Follow FedRAMP Rev5 Controls Guidance

??? abstract "FRC-CSF-FFG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST follow FedRAMP Rev5 Controls Guidance for the implementation and documentation of all applicable controls.


### FedRAMP Ready Conversion

??? abstract "FRC-CSF-RDY"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers with FedRAMP Rev5 Ready status MUST convert to a FedRAMP Certification by whichever of the follow dates is later: the expiration of their annual assessment or November 17, 2026 (the legacy FedRAMP Ready status will be entirely removed on December 31, 2027).


    ---

    _**Notes:**_

    - _The simplest conversion in most cases would be to a FedRAMP 20x Class A Certification._
    - _Cloud services that do not wish to convert or do not meet conversion criteria will be renamed Legacy FedRAMP Ready and otherwise retired from FedRAMP Ready._
