---
tags:
  - 20x
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# FedRAMP Certification

This ruleset explains how cloud service offerings obtain and maintain FedRAMP Certification across certification classes and paths.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [FedRAMP Class A Certification Rules](#fedramp-class-a-certification-rules)
- [Applying for FedRAMP Certification](#applying-for-fedramp-certification)
- [20x-Specific Provider Responsibilities](#20x-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
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



!!! schema "Related JSON Schema: [FedRAMP Certification Overview Package (FRC-CSO-PKG)](https://fedramp.gov/schemas/fedramp-certification-package-overview-schema-2026-06-24.json)"


!!! quote ""
    Providers seeking a Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

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
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These are specific rules that apply to providers seeking FedRAMP Class A Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Approved Alternative Security Frameworks

??? abstract "FRC-CLA-ASF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST have completed a certification or equivalent process, including an independent assessment if applicable, from one of the following alternative security frameworks within the past 12 months:

    1. FedRAMP Rev5 (including FedRAMP Ready) at any historical Impact Level
    1. SOC 2 Type II
    1. GovRAMP at any Impact Level


    ---
    **Terms:** [Security Category](../../../definitions/#security-category){ data-preview }
### External Assessment Materials

??? abstract "FRC-CLA-EAM"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST supply the following materials from their alternative security framework assessment to all necessary parties:

    1. SOC 2 Type II: Complete report, bridge or gap letter (if applicable), verified audit engagement documentation, estimated schedule for upcoming report, supplemental compliance evidence (if applicable)
    1. FedRAMP Ready: Readiness Assessment Report, Security Assessment Plan, and any other materials required by FedRAMP.
    1. GovRAMP: Readiness Assessment Report, Security Assessment Plan, and any other materials required by GovRAMP.


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Mandatory FedRAMP Rules for Class A

??? abstract "FRC-CLA-MFR"
    **Changelog:**


    - **2026-07-01:** Removed reference to Independent Verification and Validation: IVV-CSF-AIA (Annual Independent Assessments for Rev5); Removed CDS-CSO-AVR (Availability Reporting) since this rule is defined as SHOULD and included in FRC-CLA-RFR (Recommended FedRAMP Rules for Class A)


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification MUST address all rules in this FedRAMP Class A Certification subset (FRC-CLA) AND the following additional FedRAMP Class A rules; the appropriate artifacts or information mapping for all rules MUST be supplied in the FedRAMP Certification Package.

    1. FedRAMP Certification: [FRC-CSO-PKG (FedRAMP Certification Package)](#fedramp-certification-package){ data-preview }
    1. FedRAMP Certification: [FRC-CSO-JSN (FedRAMP JSON Schemas)](#fedramp-json-schemas){ data-preview }
    1. FedRAMP Certification: [FRC-CSO-POP (Pick One Program Certification Type)](#pick-one-program-certification-type){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-IIR (Identify Information Resources)](minimum-assessment-scope.md#identify-information-resources){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PUB (Public Information)](certification-data-sharing.md#public-information){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-UTC (Use Trust Centers)](certification-data-sharing.md#use-trust-centers){ data-preview }
    1. Certification Data Sharing: [CDS-UTC-AAD (Agency Access Denial)](certification-data-sharing.md#agency-access-denial){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-INB (Maintain a FedRAMP Security Inbox)](addressing-fedramp-communication.md#maintain-a-fedramp-security-inbox){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-RCV (Receive Email Without Disruption)](addressing-fedramp-communication.md#receive-email-without-disruption){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-CRA (Complete Required Actions)](addressing-fedramp-communication.md#complete-required-actions){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-EFR (Evaluate FedRAMP Reportability)](incident-evaluation-and-communication.md#evaluate-fedramp-reportability){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-FIR (Final Incident Report)](incident-evaluation-and-communication.md#final-incident-report){ data-preview }
    1. Vulnerability Detection and Response: [VDR-CSO-DET (Vulnerability Detection)](vulnerability-detection-and-response.md#vulnerability-detection){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview }
    1. Independent Verification and Validation: [IVV-CSX-AIA (Annual Independent Assessments for 20x)](independent-verification-and-validation.md#annual-independent-assessments-for-20x){ data-preview }
    1. Key Security Indicators: [KSI-CMT-LMC (Logging Changes)](../key-security-indicators/change-management.md#logging-changes){ data-preview }
    1. Key Security Indicators: [KSI-CNA-RNT (Restricting Network Traffic)](../key-security-indicators/cloud-native-architecture.md#restricting-network-traffic){ data-preview }
    1. Key Security Indicators: [KSI-CED-RAT (Reviewing All Training)](../key-security-indicators/cybersecurity-education.md#reviewing-all-training){ data-preview }
    1. Key Security Indicators: [KSI-IAM-AAM (Automating Account Management)](../key-security-indicators/identity-and-access-management.md#automating-account-management){ data-preview }
    1. Key Security Indicators: [KSI-IAM-APM (Adopting Passwordless Methods)](../key-security-indicators/identity-and-access-management.md#adopting-passwordless-methods){ data-preview }
    1. Key Security Indicators: [KSI-INR-RIR (Reviewing Incident Response Procedures)](../key-security-indicators/incident-response.md#reviewing-incident-response-procedures){ data-preview }
    1. Key Security Indicators: [KSI-SVC-SIN (Securing Information)](../key-security-indicators/service-configuration.md#securing-information){ data-preview }


    ---

    _**Notes:**_

    - _Some of these specific FedRAMP rules may not have similar counterparts in external frameworks and providers will need to implement new processes to follow these rules._
    - _In general, for each of these FedRAMP requirements, providers should include a sufficiently detailed summary that reviewers will not need to dig into the related security framework materials to understand the related decisions - just saying "see SOC 2 report" is not particularly helpful._
    - _Information about how the provider addresses the included Key Security Indicators are required for both Rev5 and 20x Class A Certifications._
    ---
    **Terms:** [Artifacts](../../../definitions/#artifacts){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [Certification Type](../../../definitions/#certification-type){ data-preview }, [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Final Incident Report (FIR)](../../../definitions/#final-incident-report-fir){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Recommended FedRAMP Rules for Class A

??? abstract "FRC-CLA-RFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification SHOULD address the following additional recommended FedRAMP Class A rules (if applicable):

    1. Certification Data Sharing: [CDS-CSO-AVR (Availability Reporting)](certification-data-sharing.md#availability-reporting){ data-preview }
    1. Certification Package Overview: [CPO-CSF-CPM (Certification Package Maintenance for Rev5)](../../rev5/rules/certification-package-overview.md#certification-package-maintenance-for-rev5){ data-preview }
    1. Certification Package Overview: [CPO-CSX-CPM (Certification Package Maintenance for 20x)](certification-package-overview.md#certification-package-maintenance-for-20x){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-IIR (Initial Incident Report)](incident-evaluation-and-communication.md#initial-incident-report){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-OIR (Ongoing Incident Reports)](incident-evaluation-and-communication.md#ongoing-incident-reports){ data-preview }
    1. Vulnerability Detection and Response: [VDR-TFR-MVX (Persistent Machine Verification and Validation for 20x)](vulnerability-detection-and-response.md#persistent-machine-verification-and-validation-for-20x){ data-preview }
    1. Vulnerability Detection and Response: [VDR-TFR-PCD (Persistently Complete Detection)](vulnerability-detection-and-response.md#persistently-complete-detection){ data-preview }
    1. Vulnerability Detection and Response: [VDR-TFR-PDD (Persistent Drift Detection)](vulnerability-detection-and-response.md#persistent-drift-detection){ data-preview }
    1. Vulnerability Detection and Response: [VDR-TFR-PSD (Persistent Sample Detection)](vulnerability-detection-and-response.md#persistent-sample-detection){ data-preview }
    1. Vulnerability Detection and Response: [VDR-TFR-PVR (Mitigation and Remediation Expectations)](vulnerability-detection-and-response.md#mitigation-and-remediation-expectations){ data-preview }
    1. Vulnerability Evaluation and Reporting: [VER-TFR-EVU (Evaluate Vulnerabilities Quickly)](vulnerability-evaluation-and-reporting.md#evaluate-vulnerabilities-quickly){ data-preview }


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [Drift](../../../definitions/#drift){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Incident Report (OIR)](../../../definitions/#ongoing-incident-report-oir){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Address Optional FedRAMP Rules for Class A

??? abstract "FRC-CLA-OFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification MAY address the following additional optional FedRAMP Class A rules (if applicable):

    1. Collaborative Continuous Monitoring: [CCM-QTR-MTG (Quarterly Review Meeting)](collaborative-continuous-monitoring.md#quarterly-review-meeting){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PSM (Per-Service Certification Materials)](certification-data-sharing.md#per-service-certification-materials){ data-preview }
    1. Cryptographic Module Use: [CMU-CSO-UVM (Using Validated Cryptographic Modules)](cryptographic-module-use.md#using-validated-cryptographic-modules){ data-preview }
    1. FedRAMP Certification: [FRC-APP-FIA (Fresh Independent Assessment)](#fresh-independent-assessment){ data-preview }
    1. Independent Verification and Validation: [IVV-CSO-FIA (FedRAMP Independent Assessments)](independent-verification-and-validation.md#fedramp-independent-assessments){ data-preview }
    1. Security Decision Record: [SDR-CSX-KMT (Key Security Indicator Metrics)](security-decision-record.md#key-security-indicator-metrics){ data-preview }
    1. Vulnerability Evaluation and Reporting: [VER-TFR-IRI (Internet-Reachable Incidents)](vulnerability-evaluation-and-reporting.md#internet-reachable-incidents){ data-preview }
    1. Vulnerability Evaluation and Reporting: [VER-TFR-MRH (Historical Activity)](vulnerability-evaluation-and-reporting.md#historical-activity){ data-preview }
    1. Vulnerability Evaluation and Reporting: [VER-TFR-NRI (Non-Internet-Reachable Incidents)](vulnerability-evaluation-and-reporting.md#non-internet-reachable-incidents){ data-preview }


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Quarterly Review](../../../definitions/#quarterly-review){ data-preview }, [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
### Optional Independent Verification and Validation

??? abstract "FRC-CLA-IVV"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MAY have the FedRAMP Certification Package independently verified and validated by a FedRAMP Recognized assessor before submission to FedRAMP.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
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
    === "Class A"
        Providers seeking Class A Certification MAY supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

        **Timeframe:** 3 months

    === "Class B"
        Providers seeking Class B Certification MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

        **Timeframe:** 3 months

    === "Class C"
        Providers seeking Class C Certification MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

        **Timeframe:** 3 months

    === "Class D"
        Providers seeking Class D Certification MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

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
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Automated Verification and Validation of Key Security Indicators

??? abstract "FRC-CSX-VVK"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers seeking 20x Class A Certification MAY implement automated methods to persistently verify and validate the accuracy and completeness of Key Security Indicators.

    === "Class B"
        Providers seeking 20x Class B Certification SHOULD implement automated methods to persistently verify and validate the accuracy and completeness of Key Security Indicators with at least 1 automated method for each Key Security Indicator.

    === "Class C"
        Providers seeking 20x Class C Certification MUST implement automated methods to persistently verify and validate the accuracy and completeness of Key Security Indicators with at least 2 automated methods for each Key Security Indicator.

    === "Class D"
        Providers seeking 20x Class D Certification MUST implement automated methods to persistently verify and validate the accuracy and completeness of Key Security Indicators with at least 4 automated methods for each Key Security Indicator.


    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Metrics Over Time for Key Security Indicators

??? abstract "FRC-CSX-MOT"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers seeking 20x Class A Certification MAY supply historical metrics for Key Security Indicators.

    === "Class B"
        Providers seeking 20x Class B Certification SHOULD supply historical metrics for Key Security Indicators.

    === "Class C"
        Providers seeking 20x Class C Certification MUST supply historical metrics including status from persistent validation over at least the past 6 months for all Key Security Indicators.

    === "Class D"
        Providers seeking 20x Class D Certification MUST provide historical metrics including status from persistent validation over at least the past 18 months for all Key Security Indicators.


    ---

    _**Note:** For initial FedRAMP Certification, providers will need to have mechanisms in place and agree to meet this requirement in the event the cloud service has not been operating with related metrics available for the required period prior to applying for initial certification._

    ---
    **Terms:** [Initial Certification](../../../definitions/#initial-certification){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Automated Verification and Validation of FedRAMP Rules

??? abstract "FRC-CSX-VVR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers seeking 20x Class A Certification MAY implement automated methods to persistently verify and validate the accuracy and completeness of the Security Decision Record for FedRAMP rules when applicable.

    === "Class B"
        Providers seeking 20x Class B Certification SHOULD implement automated methods to persistently verify and validate the accuracy and completeness of the Security Decision Record for FedRAMP rules when applicable.

    === "Class C"
        Providers seeking 20x Class C Certification SHOULD implement automated methods to persistently verify and validate the accuracy and completeness of the Security Decision Record for FedRAMP rules when applicable.

    === "Class D"
        Providers seeking 20x Class D Certification SHOULD implement automated methods to persistently verify and validate the accuracy and completeness of the Security Decision Record for FedRAMP rules when applicable.


    ---

    _**Note:** Different rules will be easy to automate for different providers, depending on the implementation, so FedRAMP generally leaves this implementation up to providers based on what makes the most sense for their own business and approach._

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Application within MAS

??? abstract "FRC-CSX-MAS"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
