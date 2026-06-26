---
tags:
  - 20x
  - Rev5
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
- [Applying for FedRAMP Certification with an Agency Sponsor](#applying-for-fedramp-certification-with-an-agency-sponsor)
- [Changing Certification Class](#changing-certification-class)
- [20x-Specific Provider Responsibilities](#20x-specific-provider-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-01-01

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
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
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
    **Terms:** [Certification Profile](../definitions/#certification-profile){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../definitions/#fedramp-practices){ data-preview }, [Handle](../definitions/#handle){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Security Category](../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../definitions/#third-party-information-resource){ data-preview }
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
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [FedRAMP Certification Report](../definitions/#fedramp-certification-report){ data-preview }, [Initial Certification](../definitions/#initial-certification){ data-preview }, [Ongoing Certification](../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Security Decision Record (SDR)](../definitions/#security-decision-record-sdr){ data-preview }
### FedRAMP JSON Schemas

??? abstract "FRC-CSO-JSN"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply machine-readable information in JSON documents that are valid against the corresponding JSON schema when a rule contains a FedRAMP JSON schema, UNLESS otherwise specified in the rule.


    ---

    _**Note:** FedRAMP JSON schemas are designed to be lightweight and flexible to establish a minimum set of structured information while allowing providers to improve on the format and structure of the information as needed to meet their needs and the needs of their customers._

    ---
    **Terms:** [Machine-Readable](../definitions/#machine-readable){ data-preview }
### Maintain Responsibility and Accountability

??? abstract "FRC-CSO-MRA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST maintain responsibility and accountability for the accuracy and completeness of all information in the FedRAMP Certification Package, especially when they engage a third party (such as an independent assessor, advisory service, or external tools) to supply information on their behalf.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }
### Pick One Program Certification Type

??? abstract "FRC-CSO-POP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST NOT seek both FedRAMP Rev5 Program Certification and FedRAMP 20x Program Certification for the same cloud service offering; pick one type.


    ---

    _**Note:** This rule does not prevent a provider from seeking and maintaining a FedRAMP Rev5 Agency Certification and a FedRAMP 20x Program Certification for the same cloud service offering, however, doing so is strongly discouraged due to the increased complexity and risk of confusion for all parties._

    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These are specific rules that apply to providers seeking FedRAMP Class A Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
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
    **Terms:** [Security Category](../definitions/#security-category){ data-preview }
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
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Mandatory FedRAMP Rules for Class A

??? abstract "FRC-CLA-MFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification MUST address all rules in this FedRAMP Class A Certification subset (FRC-CLA) AND the following additional FedRAMP Class Arules; the appropriate artifacts or information mapping for all rules MUST be supplied in the FedRAMP Certification Package.

    1. FedRAMP Certification: [FRC-CSO-PKG (FedRAMP Certification Package)](#fedramp-certification-package){ data-preview }
    1. FedRAMP Certification: [FRC-CSO-JSN (FedRAMP JSON Schemas)](#fedramp-json-schemas){ data-preview }
    1. FedRAMP Certification: [FRC-CSO-POP (Pick One Program Certification Type)](#pick-one-program-certification-type){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-IIR (Identify Information Resources)](minimum-assessment-scope.md#identify-information-resources){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PUB (Public Information)](certification-data-sharing.md#public-information){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-UTC (Use Trust Centers)](certification-data-sharing.md#use-trust-centers){ data-preview }
    1. Certification Data Sharing: [CDS-UTC-AAD (Agency Access Denial)](certification-data-sharing.md#agency-access-denial){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-AVR (Availability Reporting)](certification-data-sharing.md#availability-reporting){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-INB (Maintain a FedRAMP Security Inbox)](addressing-fedramp-communication.md#maintain-a-fedramp-security-inbox){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-RCV (Receive Email Without Disruption)](addressing-fedramp-communication.md#receive-email-without-disruption){ data-preview }
    1. Addressing FedRAMP Communication: [AFC-CSO-CRA (Complete Required Actions)](addressing-fedramp-communication.md#complete-required-actions){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-EFR (Evaluate FedRAMP Reportability)](incident-evaluation-and-communication.md#evaluate-fedramp-reportability){ data-preview }
    1. Incident Evaluation and Communication: [IEC-CSO-FIR (Final Incident Report)](incident-evaluation-and-communication.md#final-incident-report){ data-preview }
    1. Vulnerability Detection and Response: [VDR-CSO-DET (Vulnerability Detection)](vulnerability-detection-and-response.md#vulnerability-detection){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview }
    1. Independent Verification and Validation: [IVV-CSX-AIA (Annual Independent Assessments for 20x)](independent-verification-and-validation.md#annual-independent-assessments-for-20x){ data-preview }
    1. Independent Verification and Validation: [IVV-CSF-AIA (Annual Independent Assessments for Rev5)](independent-verification-and-validation.md#annual-independent-assessments-for-rev5){ data-preview }
    1. Key Security Indicators: [KSI-CMT-LMC (Logging Changes)](key-security-indicators.md#logging-changes){ data-preview }
    1. Key Security Indicators: [KSI-CNA-RNT (Restricting Network Traffic)](key-security-indicators.md#restricting-network-traffic){ data-preview }
    1. Key Security Indicators: [KSI-CED-RAT (Reviewing All Training)](key-security-indicators.md#reviewing-all-training){ data-preview }
    1. Key Security Indicators: [KSI-IAM-AAM (Automating Account Management)](key-security-indicators.md#automating-account-management){ data-preview }
    1. Key Security Indicators: [KSI-IAM-APM (Adopting Passwordless Methods)](key-security-indicators.md#adopting-passwordless-methods){ data-preview }
    1. Key Security Indicators: [KSI-INR-RIR (Reviewing Incident Response Procedures)](key-security-indicators.md#reviewing-incident-response-procedures){ data-preview }
    1. Key Security Indicators: [KSI-SVC-SIN (Securing Information)](key-security-indicators.md#securing-information){ data-preview }


    ---

    _**Notes:**_

    - _Some of these specific FedRAMP rules may not have similar counterparts in external frameworks and providers will need to implement new processes to follow these rules._
    - _In general, for each of these FedRAMP requirements, providers should include a sufficiently detailed summary that reviewers will not need to dig into the related security framework materials to understand the related decisions - just saying "see SOC 2 report" is not particularly helpful._
    - _Information about how the provider addresses the included Key Security Indicators are required for both Rev5 and 20x Class A Certifications._
    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }, [Certification Type](../definitions/#certification-type){ data-preview }, [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Final Incident Report (FIR)](../definitions/#final-incident-report-fir){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
### Recommended FedRAMP Rules for Class A

??? abstract "FRC-CLA-RFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification SHOULD address the following additional recommended FedRAMP Class A rules (if applicable):

    1. Certification Data Sharing: [CDS-CSO-AVR (Availability Reporting)](certification-data-sharing.md#availability-reporting){ data-preview }
    1. Certification Package Overview: [CPO-CSF-CPM (Certification Package Maintenance for Rev5)](certification-package-overview.md#certification-package-maintenance-for-rev5){ data-preview }
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
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }, [Drift](../definitions/#drift){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Incident Report (OIR)](../definitions/#ongoing-incident-report-oir){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
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
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [FedRAMP Independent Assessment](../definitions/#fedramp-independent-assessment){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Quarterly Review](../definitions/#quarterly-review){ data-preview }, [Security Decision Record (SDR)](../definitions/#security-decision-record-sdr){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }
### Optional Independent Verification and Validation

??? abstract "FRC-CLA-IVV"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MAY have the FedRAMP Certification Package independently verified and validated by a FedRAMP Recognized assessor before submission to FedRAMP.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
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
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
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
    **Terms:** [FedRAMP Independent Assessment](../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }
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
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification with an Agency Sponsor {#applying-for-fedramp-certification-with-an-agency-sponsor}

These rules apply to cloud service providers with an Agency Sponsor who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Agency Authorization to Operate

??? abstract "FRC-APS-ATO"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers seeking a FedRAMP Rev5 Agency Certification MUST have completed the Authorization to Operate (ATO) process with their agency sponsor for the cloud service offering, concluding with a formal signed ATO letter that the agency has sent over official government channels to FedRAMP.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## Changing Certification Class {#changing-certification-class}

These rules apply to cloud service providers when changing their FedRAMP Certification Class.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
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
    **Terms:** [Certification Class](../definitions/#certification-class){ data-preview }
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
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Class](../definitions/#certification-class){ data-preview }
### Downgrade Notification Period

??? abstract "FRC-CCL-DNP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD notify all necessary parties at least 120 days in advance of an intended downgrade or cancellation of FedRAMP Certification.


    ---

    _**Note:** Downgrading or canceling FedRAMP Certification will have severe negative consequences for the provider and their agency customers and should only be done after careful consideration and planning... but if it must be done, notify all necessary parties as soon as possible._

    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }
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
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
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
    **Terms:** [Initial Certification](../definitions/#initial-certification){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }
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
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Security Decision Record (SDR)](../definitions/#security-decision-record-sdr){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Application within MAS

??? abstract "FRC-CSX-MAS"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
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
                - `AC-01` ([Policy and Procedures](controls/access-control.md#ac-01){ data-preview })
                - `AC-02` ([Account Management](controls/access-control.md#ac-02){ data-preview })
                - `AC-03` ([Access Enforcement](controls/access-control.md#ac-03){ data-preview })
                - `AC-07` ([Unsuccessful Logon Attempts](controls/access-control.md#ac-07){ data-preview })
                - `AC-08` ([System Use Notification](controls/access-control.md#ac-08){ data-preview })
                - `AC-14` ([Permitted Actions Without Identification or Authentication](controls/access-control.md#ac-14){ data-preview })
                - `AC-17` ([Remote Access](controls/access-control.md#ac-17){ data-preview })
                - `AC-18` ([Wireless Access](controls/access-control.md#ac-18){ data-preview })
                - `AC-19` ([Access Control for Mobile Devices](controls/access-control.md#ac-19){ data-preview })
                - `AC-20` ([Use of External Systems](controls/access-control.md#ac-20){ data-preview })
                - `AC-22` ([Publicly Accessible Content](controls/access-control.md#ac-22){ data-preview })
            - **Awareness and Training (AT)**
                - `AT-01` ([Policy and Procedures](controls/awareness-and-training.md#at-01){ data-preview })
                - `AT-02` ([Literacy Training and Awareness](controls/awareness-and-training.md#at-02){ data-preview })
                - `AT-02 (02)` ([Insider Threat](controls/awareness-and-training.md#at-02-02){ data-preview })
                - `AT-03` ([Role-based Training](controls/awareness-and-training.md#at-03){ data-preview })
                - `AT-04` ([Training Records](controls/awareness-and-training.md#at-04){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-01` ([Policy and Procedures](controls/audit-and-accountability.md#au-01){ data-preview })
                - `AU-02` ([Event Logging](controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-08` ([Time Stamps](controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-09` ([Protection of Audit Information](controls/audit-and-accountability.md#au-09){ data-preview })
                - `AU-11` ([Audit Record Retention](controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](controls/audit-and-accountability.md#au-12){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-01` ([Policy and Procedures](controls/assessment-authorization-and-monitoring.md#ca-01){ data-preview })
                - `CA-02` ([Control Assessments](controls/assessment-authorization-and-monitoring.md#ca-02){ data-preview })
                - `CA-02 (01)` ([Independent Assessors](controls/assessment-authorization-and-monitoring.md#ca-02-01){ data-preview })
                - `CA-03` ([Information Exchange](controls/assessment-authorization-and-monitoring.md#ca-03){ data-preview })
                - `CA-06` ([Authorization](controls/assessment-authorization-and-monitoring.md#ca-06){ data-preview })
                - `CA-07` ([Continuous Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07){ data-preview })
                - `CA-07 (04)` ([Risk Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07-04){ data-preview })
                - `CA-08` ([Penetration Testing](controls/assessment-authorization-and-monitoring.md#ca-08){ data-preview })
                - `CA-09` ([Internal System Connections](controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview })
            - **Configuration Management (CM)**
                - `CM-01` ([Policy and Procedures](controls/configuration-management.md#cm-01){ data-preview })
                - `CM-02` ([Baseline Configuration](controls/configuration-management.md#cm-02){ data-preview })
                - `CM-04` ([Impact Analyses](controls/configuration-management.md#cm-04){ data-preview })
                - `CM-05` ([Access Restrictions for Change](controls/configuration-management.md#cm-05){ data-preview })
                - `CM-06` ([Configuration Settings](controls/configuration-management.md#cm-06){ data-preview })
                - `CM-07` ([Least Functionality](controls/configuration-management.md#cm-07){ data-preview })
                - `CM-08` ([System Component Inventory](controls/configuration-management.md#cm-08){ data-preview })
                - `CM-10` ([Software Usage Restrictions](controls/configuration-management.md#cm-10){ data-preview })
                - `CM-11` ([User-installed Software](controls/configuration-management.md#cm-11){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-01` ([Policy and Procedures](controls/contingency-planning.md#cp-01){ data-preview })
                - `CP-02` ([Contingency Plan](controls/contingency-planning.md#cp-02){ data-preview })
                - `CP-03` ([Contingency Training](controls/contingency-planning.md#cp-03){ data-preview })
                - `CP-04` ([Contingency Plan Testing](controls/contingency-planning.md#cp-04){ data-preview })
                - `CP-09` ([System Backup](controls/contingency-planning.md#cp-09){ data-preview })
                - `CP-10` ([System Recovery and Reconstitution](controls/contingency-planning.md#cp-10){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-01` ([Policy and Procedures](controls/identification-and-authentication.md#ia-01){ data-preview })
                - `IA-02` ([Identification and Authentication (Organizational Users)](controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-04` ([Identifier Management](controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-05` ([Authenticator Management](controls/identification-and-authentication.md#ia-05){ data-preview })
                - `IA-05 (01)` ([Password-based Authentication](controls/identification-and-authentication.md#ia-05-01){ data-preview })
                - `IA-06` ([Authentication Feedback](controls/identification-and-authentication.md#ia-06){ data-preview })
                - `IA-07` ([Cryptographic Module Authentication](controls/identification-and-authentication.md#ia-07){ data-preview })
                - `IA-08` ([Identification and Authentication (Non-organizational Users)](controls/identification-and-authentication.md#ia-08){ data-preview })
                - `IA-08 (01)` ([Acceptance of PIV Credentials from Other Agencies](controls/identification-and-authentication.md#ia-08-01){ data-preview })
                - `IA-08 (02)` ([Acceptance of External Authenticators](controls/identification-and-authentication.md#ia-08-02){ data-preview })
                - `IA-08 (04)` ([Use of Defined Profiles](controls/identification-and-authentication.md#ia-08-04){ data-preview })
                - `IA-11` ([Re-authentication](controls/identification-and-authentication.md#ia-11){ data-preview })
            - **Incident Response (IR)**
                - `IR-01` ([Policy and Procedures](controls/incident-response.md#ir-01){ data-preview })
                - `IR-02` ([Incident Response Training](controls/incident-response.md#ir-02){ data-preview })
                - `IR-04` ([Incident Handling](controls/incident-response.md#ir-04){ data-preview })
                - `IR-05` ([Incident Monitoring](controls/incident-response.md#ir-05){ data-preview })
                - `IR-06` ([Incident Reporting](controls/incident-response.md#ir-06){ data-preview })
                - `IR-07` ([Incident Response Assistance](controls/incident-response.md#ir-07){ data-preview })
                - `IR-08` ([Incident Response Plan](controls/incident-response.md#ir-08){ data-preview })
            - **Maintenance (MA)**
                - `MA-01` ([Policy and Procedures](controls/maintenance.md#ma-01){ data-preview })
                - `MA-02` ([Controlled Maintenance](controls/maintenance.md#ma-02){ data-preview })
                - `MA-04` ([Nonlocal Maintenance](controls/maintenance.md#ma-04){ data-preview })
                - `MA-05` ([Maintenance Personnel](controls/maintenance.md#ma-05){ data-preview })
            - **Media Protection (MP)**
                - `MP-01` ([Policy and Procedures](controls/media-protection.md#mp-01){ data-preview })
                - `MP-02` ([Media Access](controls/media-protection.md#mp-02){ data-preview })
                - `MP-06` ([Media Sanitization](controls/media-protection.md#mp-06){ data-preview })
                - `MP-07` ([Media Use](controls/media-protection.md#mp-07){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-01` ([Policy and Procedures](controls/physical-and-environmental-protection.md#pe-01){ data-preview })
                - `PE-02` ([Physical Access Authorizations](controls/physical-and-environmental-protection.md#pe-02){ data-preview })
                - `PE-03` ([Physical Access Control](controls/physical-and-environmental-protection.md#pe-03){ data-preview })
                - `PE-06` ([Monitoring Physical Access](controls/physical-and-environmental-protection.md#pe-06){ data-preview })
                - `PE-08` ([Visitor Access Records](controls/physical-and-environmental-protection.md#pe-08){ data-preview })
                - `PE-12` ([Emergency Lighting](controls/physical-and-environmental-protection.md#pe-12){ data-preview })
                - `PE-13` ([Fire Protection](controls/physical-and-environmental-protection.md#pe-13){ data-preview })
                - `PE-14` ([Environmental Controls](controls/physical-and-environmental-protection.md#pe-14){ data-preview })
                - `PE-15` ([Water Damage Protection](controls/physical-and-environmental-protection.md#pe-15){ data-preview })
                - `PE-16` ([Delivery and Removal](controls/physical-and-environmental-protection.md#pe-16){ data-preview })
            - **Planning (PL)**
                - `PL-01` ([Policy and Procedures](controls/planning.md#pl-01){ data-preview })
                - `PL-02` ([System Security and Privacy Plans](controls/planning.md#pl-02){ data-preview })
                - `PL-04` ([Rules of Behavior](controls/planning.md#pl-04){ data-preview })
                - `PL-04 (01)` ([Social Media and External Site/Application Usage Restrictions](controls/planning.md#pl-04-01){ data-preview })
                - `PL-08` ([Security and Privacy Architectures](controls/planning.md#pl-08){ data-preview })
                - `PL-10` ([Baseline Selection](controls/planning.md#pl-10){ data-preview })
                - `PL-11` ([Baseline Tailoring](controls/planning.md#pl-11){ data-preview })
            - **Personnel Security (PS)**
                - `PS-01` ([Policy and Procedures](controls/personnel-security.md#ps-01){ data-preview })
                - `PS-02` ([Position Risk Designation](controls/personnel-security.md#ps-02){ data-preview })
                - `PS-03` ([Personnel Screening](controls/personnel-security.md#ps-03){ data-preview })
                - `PS-04` ([Personnel Termination](controls/personnel-security.md#ps-04){ data-preview })
                - `PS-05` ([Personnel Transfer](controls/personnel-security.md#ps-05){ data-preview })
                - `PS-06` ([Access Agreements](controls/personnel-security.md#ps-06){ data-preview })
                - `PS-07` ([External Personnel Security](controls/personnel-security.md#ps-07){ data-preview })
                - `PS-08` ([Personnel Sanctions](controls/personnel-security.md#ps-08){ data-preview })
                - `PS-09` ([Position Descriptions](controls/personnel-security.md#ps-09){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-01` ([Policy and Procedures](controls/risk-assessment.md#ra-01){ data-preview })
                - `RA-02` ([Security Categorization](controls/risk-assessment.md#ra-02){ data-preview })
                - `RA-03` ([Risk Assessment](controls/risk-assessment.md#ra-03){ data-preview })
                - `RA-03 (01)` ([Supply Chain Risk Assessment](controls/risk-assessment.md#ra-03-01){ data-preview })
                - `RA-05` ([Vulnerability Monitoring and Scanning](controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (11)` ([Public Disclosure Program](controls/risk-assessment.md#ra-05-11){ data-preview })
                - `RA-07` ([Risk Response](controls/risk-assessment.md#ra-07){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-01` ([Policy and Procedures](controls/system-and-services-acquisition.md#sa-01){ data-preview })
                - `SA-02` ([Allocation of Resources](controls/system-and-services-acquisition.md#sa-02){ data-preview })
                - `SA-03` ([System Development Life Cycle](controls/system-and-services-acquisition.md#sa-03){ data-preview })
                - `SA-04` ([Acquisition Process](controls/system-and-services-acquisition.md#sa-04){ data-preview })
                - `SA-04 (10)` ([Use of Approved PIV Products](controls/system-and-services-acquisition.md#sa-04-10){ data-preview })
                - `SA-05` ([System Documentation](controls/system-and-services-acquisition.md#sa-05){ data-preview })
                - `SA-08` ([Security and Privacy Engineering Principles](controls/system-and-services-acquisition.md#sa-08){ data-preview })
                - `SA-09` ([External System Services](controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-22` ([Unsupported System Components](controls/system-and-services-acquisition.md#sa-22){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-01` ([Policy and Procedures](controls/system-and-communications-protection.md#sc-01){ data-preview })
                - `SC-05` ([Denial-of-service Protection](controls/system-and-communications-protection.md#sc-05){ data-preview })
                - `SC-07` ([Boundary Protection](controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-08 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-08-01){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-15` ([Collaborative Computing Devices and Applications](controls/system-and-communications-protection.md#sc-15){ data-preview })
                - `SC-20` ([Secure Name/Address Resolution Service (Authoritative Source)](controls/system-and-communications-protection.md#sc-20){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-22` ([Architecture and Provisioning for Name/Address Resolution Service](controls/system-and-communications-protection.md#sc-22){ data-preview })
                - `SC-28` ([Protection of Information at Rest](controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-28 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-28-01){ data-preview })
                - `SC-39` ([Process Isolation](controls/system-and-communications-protection.md#sc-39){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-01` ([Policy and Procedures](controls/system-and-information-integrity.md#si-01){ data-preview })
                - `SI-02` ([Flaw Remediation](controls/system-and-information-integrity.md#si-02){ data-preview })
                - `SI-03` ([Malicious Code Protection](controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04` ([System Monitoring](controls/system-and-information-integrity.md#si-04){ data-preview })
                - `SI-05` ([Security Alerts, Advisories, and Directives](controls/system-and-information-integrity.md#si-05){ data-preview })
                - `SI-12` ([Information Management and Retention](controls/system-and-information-integrity.md#si-12){ data-preview })
            - **Supply Chain Risk Management (SR)**
                - `SR-01` ([Policy and Procedures](controls/supply-chain-risk-management.md#sr-01){ data-preview })
                - `SR-02` ([Supply Chain Risk Management Plan](controls/supply-chain-risk-management.md#sr-02){ data-preview })
                - `SR-02 (01)` ([Establish SCRM Team](controls/supply-chain-risk-management.md#sr-02-01){ data-preview })
                - `SR-03` ([Supply Chain Controls and Processes](controls/supply-chain-risk-management.md#sr-03){ data-preview })
                - `SR-05` ([Acquisition Strategies, Tools, and Methods](controls/supply-chain-risk-management.md#sr-05){ data-preview })
                - `SR-08` ([Notification Agreements](controls/supply-chain-risk-management.md#sr-08){ data-preview })
                - `SR-10` ([Inspection of Systems or Components](controls/supply-chain-risk-management.md#sr-10){ data-preview })
                - `SR-11` ([Component Authenticity](controls/supply-chain-risk-management.md#sr-11){ data-preview })
                - `SR-11 (01)` ([Anti-counterfeit Training](controls/supply-chain-risk-management.md#sr-11-01){ data-preview })
                - `SR-11 (02)` ([Configuration Control for Component Service and Repair](controls/supply-chain-risk-management.md#sr-11-02){ data-preview })
                - `SR-12` ([Component Disposal](controls/supply-chain-risk-management.md#sr-12){ data-preview })
        
    === "Class C"
        Providers seeking FedRAMP Rev5 Class C Certification MUST include at least the following NIST SP 800-53 Rev. 5 controls in their Security Decision Record:

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-01` ([Policy and Procedures](controls/access-control.md#ac-01){ data-preview })
                - `AC-02` ([Account Management](controls/access-control.md#ac-02){ data-preview })
                - `AC-02 (01)` ([Automated System Account Management](controls/access-control.md#ac-02-01){ data-preview })
                - `AC-02 (02)` ([Automated Temporary and Emergency Account Management](controls/access-control.md#ac-02-02){ data-preview })
                - `AC-02 (03)` ([Disable Accounts](controls/access-control.md#ac-02-03){ data-preview })
                - `AC-02 (04)` ([Automated Audit Actions](controls/access-control.md#ac-02-04){ data-preview })
                - `AC-02 (05)` ([Inactivity Logout](controls/access-control.md#ac-02-05){ data-preview })
                - `AC-02 (07)` ([Privileged User Accounts](controls/access-control.md#ac-02-07){ data-preview })
                - `AC-02 (09)` ([Restrictions on Use of Shared and Group Accounts](controls/access-control.md#ac-02-09){ data-preview })
                - `AC-02 (12)` ([Account Monitoring for Atypical Usage](controls/access-control.md#ac-02-12){ data-preview })
                - `AC-02 (13)` ([Disable Accounts for High-risk Individuals](controls/access-control.md#ac-02-13){ data-preview })
                - `AC-03` ([Access Enforcement](controls/access-control.md#ac-03){ data-preview })
                - `AC-04` ([Information Flow Enforcement](controls/access-control.md#ac-04){ data-preview })
                - `AC-04 (21)` ([Physical or Logical Separation of Information Flows](controls/access-control.md#ac-04-21){ data-preview })
                - `AC-05` ([Separation of Duties](controls/access-control.md#ac-05){ data-preview })
                - `AC-06` ([Least Privilege](controls/access-control.md#ac-06){ data-preview })
                - `AC-06 (01)` ([Authorize Access to Security Functions](controls/access-control.md#ac-06-01){ data-preview })
                - `AC-06 (02)` ([Non-privileged Access for Nonsecurity Functions](controls/access-control.md#ac-06-02){ data-preview })
                - `AC-06 (05)` ([Privileged Accounts](controls/access-control.md#ac-06-05){ data-preview })
                - `AC-06 (07)` ([Review of User Privileges](controls/access-control.md#ac-06-07){ data-preview })
                - `AC-06 (09)` ([Log Use of Privileged Functions](controls/access-control.md#ac-06-09){ data-preview })
                - `AC-06 (10)` ([Prohibit Non-privileged Users from Executing Privileged Functions](controls/access-control.md#ac-06-10){ data-preview })
                - `AC-07` ([Unsuccessful Logon Attempts](controls/access-control.md#ac-07){ data-preview })
                - `AC-08` ([System Use Notification](controls/access-control.md#ac-08){ data-preview })
                - `AC-11` ([Device Lock](controls/access-control.md#ac-11){ data-preview })
                - `AC-11 (01)` ([Pattern-hiding Displays](controls/access-control.md#ac-11-01){ data-preview })
                - `AC-12` ([Session Termination](controls/access-control.md#ac-12){ data-preview })
                - `AC-14` ([Permitted Actions Without Identification or Authentication](controls/access-control.md#ac-14){ data-preview })
                - `AC-17` ([Remote Access](controls/access-control.md#ac-17){ data-preview })
                - `AC-17 (01)` ([Monitoring and Control](controls/access-control.md#ac-17-01){ data-preview })
                - `AC-17 (02)` ([Protection of Confidentiality and Integrity Using Encryption](controls/access-control.md#ac-17-02){ data-preview })
                - `AC-17 (03)` ([Managed Access Control Points](controls/access-control.md#ac-17-03){ data-preview })
                - `AC-17 (04)` ([Privileged Commands and Access](controls/access-control.md#ac-17-04){ data-preview })
                - `AC-18` ([Wireless Access](controls/access-control.md#ac-18){ data-preview })
                - `AC-18 (01)` ([Authentication and Encryption](controls/access-control.md#ac-18-01){ data-preview })
                - `AC-18 (03)` ([Disable Wireless Networking](controls/access-control.md#ac-18-03){ data-preview })
                - `AC-19` ([Access Control for Mobile Devices](controls/access-control.md#ac-19){ data-preview })
                - `AC-19 (05)` ([Full Device or Container-based Encryption](controls/access-control.md#ac-19-05){ data-preview })
                - `AC-20` ([Use of External Systems](controls/access-control.md#ac-20){ data-preview })
                - `AC-20 (01)` ([Limits on Authorized Use](controls/access-control.md#ac-20-01){ data-preview })
                - `AC-20 (02)` ([Portable Storage Devices — Restricted Use](controls/access-control.md#ac-20-02){ data-preview })
                - `AC-21` ([Information Sharing](controls/access-control.md#ac-21){ data-preview })
                - `AC-22` ([Publicly Accessible Content](controls/access-control.md#ac-22){ data-preview })
            - **Awareness and Training (AT)**
                - `AT-01` ([Policy and Procedures](controls/awareness-and-training.md#at-01){ data-preview })
                - `AT-02` ([Literacy Training and Awareness](controls/awareness-and-training.md#at-02){ data-preview })
                - `AT-02 (02)` ([Insider Threat](controls/awareness-and-training.md#at-02-02){ data-preview })
                - `AT-02 (03)` ([Social Engineering and Mining](controls/awareness-and-training.md#at-02-03){ data-preview })
                - `AT-03` ([Role-based Training](controls/awareness-and-training.md#at-03){ data-preview })
                - `AT-04` ([Training Records](controls/awareness-and-training.md#at-04){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-01` ([Policy and Procedures](controls/audit-and-accountability.md#au-01){ data-preview })
                - `AU-02` ([Event Logging](controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-03 (01)` ([Additional Audit Information](controls/audit-and-accountability.md#au-03-01){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-06 (01)` ([Automated Process Integration](controls/audit-and-accountability.md#au-06-01){ data-preview })
                - `AU-06 (03)` ([Correlate Audit Record Repositories](controls/audit-and-accountability.md#au-06-03){ data-preview })
                - `AU-07` ([Audit Record Reduction and Report Generation](controls/audit-and-accountability.md#au-07){ data-preview })
                - `AU-07 (01)` ([Automatic Processing](controls/audit-and-accountability.md#au-07-01){ data-preview })
                - `AU-08` ([Time Stamps](controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-09` ([Protection of Audit Information](controls/audit-and-accountability.md#au-09){ data-preview })
                - `AU-09 (04)` ([Access by Subset of Privileged Users](controls/audit-and-accountability.md#au-09-04){ data-preview })
                - `AU-11` ([Audit Record Retention](controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](controls/audit-and-accountability.md#au-12){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-01` ([Policy and Procedures](controls/assessment-authorization-and-monitoring.md#ca-01){ data-preview })
                - `CA-02` ([Control Assessments](controls/assessment-authorization-and-monitoring.md#ca-02){ data-preview })
                - `CA-02 (01)` ([Independent Assessors](controls/assessment-authorization-and-monitoring.md#ca-02-01){ data-preview })
                - `CA-02 (03)` ([Leveraging Results from External Organizations](controls/assessment-authorization-and-monitoring.md#ca-02-03){ data-preview })
                - `CA-03` ([Information Exchange](controls/assessment-authorization-and-monitoring.md#ca-03){ data-preview })
                - `CA-06` ([Authorization](controls/assessment-authorization-and-monitoring.md#ca-06){ data-preview })
                - `CA-07` ([Continuous Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07){ data-preview })
                - `CA-07 (01)` ([Independent Assessment](controls/assessment-authorization-and-monitoring.md#ca-07-01){ data-preview })
                - `CA-07 (04)` ([Risk Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07-04){ data-preview })
                - `CA-08` ([Penetration Testing](controls/assessment-authorization-and-monitoring.md#ca-08){ data-preview })
                - `CA-08 (01)` ([Independent Penetration Testing Agent or Team](controls/assessment-authorization-and-monitoring.md#ca-08-01){ data-preview })
                - `CA-08 (02)` ([Red Team Exercises](controls/assessment-authorization-and-monitoring.md#ca-08-02){ data-preview })
                - `CA-09` ([Internal System Connections](controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview })
            - **Configuration Management (CM)**
                - `CM-01` ([Policy and Procedures](controls/configuration-management.md#cm-01){ data-preview })
                - `CM-02` ([Baseline Configuration](controls/configuration-management.md#cm-02){ data-preview })
                - `CM-02 (02)` ([Automation Support for Accuracy and Currency](controls/configuration-management.md#cm-02-02){ data-preview })
                - `CM-02 (03)` ([Retention of Previous Configurations](controls/configuration-management.md#cm-02-03){ data-preview })
                - `CM-02 (07)` ([Configure Systems and Components for High-risk Areas](controls/configuration-management.md#cm-02-07){ data-preview })
                - `CM-03` ([Configuration Change Control](controls/configuration-management.md#cm-03){ data-preview })
                - `CM-03 (02)` ([Testing, Validation, and Documentation of Changes](controls/configuration-management.md#cm-03-02){ data-preview })
                - `CM-03 (04)` ([Security and Privacy Representatives](controls/configuration-management.md#cm-03-04){ data-preview })
                - `CM-04` ([Impact Analyses](controls/configuration-management.md#cm-04){ data-preview })
                - `CM-04 (02)` ([Verification of Controls](controls/configuration-management.md#cm-04-02){ data-preview })
                - `CM-05` ([Access Restrictions for Change](controls/configuration-management.md#cm-05){ data-preview })
                - `CM-05 (01)` ([Automated Access Enforcement and Audit Records](controls/configuration-management.md#cm-05-01){ data-preview })
                - `CM-05 (05)` ([Privilege Limitation for Production and Operation](controls/configuration-management.md#cm-05-05){ data-preview })
                - `CM-06` ([Configuration Settings](controls/configuration-management.md#cm-06){ data-preview })
                - `CM-06 (01)` ([Automated Management, Application, and Verification](controls/configuration-management.md#cm-06-01){ data-preview })
                - `CM-07` ([Least Functionality](controls/configuration-management.md#cm-07){ data-preview })
                - `CM-07 (01)` ([Periodic Review](controls/configuration-management.md#cm-07-01){ data-preview })
                - `CM-07 (02)` ([Prevent Program Execution](controls/configuration-management.md#cm-07-02){ data-preview })
                - `CM-07 (05)` ([Authorized Software — Allow-by-exception](controls/configuration-management.md#cm-07-05){ data-preview })
                - `CM-08` ([System Component Inventory](controls/configuration-management.md#cm-08){ data-preview })
                - `CM-08 (01)` ([Updates During Installation and Removal](controls/configuration-management.md#cm-08-01){ data-preview })
                - `CM-08 (03)` ([Automated Unauthorized Component Detection](controls/configuration-management.md#cm-08-03){ data-preview })
                - `CM-09` ([Configuration Management Plan](controls/configuration-management.md#cm-09){ data-preview })
                - `CM-10` ([Software Usage Restrictions](controls/configuration-management.md#cm-10){ data-preview })
                - `CM-11` ([User-installed Software](controls/configuration-management.md#cm-11){ data-preview })
                - `CM-12` ([Information Location](controls/configuration-management.md#cm-12){ data-preview })
                - `CM-12 (01)` ([Automated Tools to Support Information Location](controls/configuration-management.md#cm-12-01){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-01` ([Policy and Procedures](controls/contingency-planning.md#cp-01){ data-preview })
                - `CP-02` ([Contingency Plan](controls/contingency-planning.md#cp-02){ data-preview })
                - `CP-02 (01)` ([Coordinate with Related Plans](controls/contingency-planning.md#cp-02-01){ data-preview })
                - `CP-02 (03)` ([Resume Mission and Business Functions](controls/contingency-planning.md#cp-02-03){ data-preview })
                - `CP-02 (08)` ([Identify Critical Assets](controls/contingency-planning.md#cp-02-08){ data-preview })
                - `CP-03` ([Contingency Training](controls/contingency-planning.md#cp-03){ data-preview })
                - `CP-04` ([Contingency Plan Testing](controls/contingency-planning.md#cp-04){ data-preview })
                - `CP-04 (01)` ([Coordinate with Related Plans](controls/contingency-planning.md#cp-04-01){ data-preview })
                - `CP-06` ([Alternate Storage Site](controls/contingency-planning.md#cp-06){ data-preview })
                - `CP-06 (01)` ([Separation from Primary Site](controls/contingency-planning.md#cp-06-01){ data-preview })
                - `CP-06 (03)` ([Accessibility](controls/contingency-planning.md#cp-06-03){ data-preview })
                - `CP-07` ([Alternate Processing Site](controls/contingency-planning.md#cp-07){ data-preview })
                - `CP-07 (01)` ([Separation from Primary Site](controls/contingency-planning.md#cp-07-01){ data-preview })
                - `CP-07 (02)` ([Accessibility](controls/contingency-planning.md#cp-07-02){ data-preview })
                - `CP-07 (03)` ([Priority of Service](controls/contingency-planning.md#cp-07-03){ data-preview })
                - `CP-08` ([Telecommunications Services](controls/contingency-planning.md#cp-08){ data-preview })
                - `CP-08 (01)` ([Priority of Service Provisions](controls/contingency-planning.md#cp-08-01){ data-preview })
                - `CP-08 (02)` ([Single Points of Failure](controls/contingency-planning.md#cp-08-02){ data-preview })
                - `CP-09` ([System Backup](controls/contingency-planning.md#cp-09){ data-preview })
                - `CP-09 (01)` ([Testing for Reliability and Integrity](controls/contingency-planning.md#cp-09-01){ data-preview })
                - `CP-09 (08)` ([Cryptographic Protection](controls/contingency-planning.md#cp-09-08){ data-preview })
                - `CP-10` ([System Recovery and Reconstitution](controls/contingency-planning.md#cp-10){ data-preview })
                - `CP-10 (02)` ([Transaction Recovery](controls/contingency-planning.md#cp-10-02){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-01` ([Policy and Procedures](controls/identification-and-authentication.md#ia-01){ data-preview })
                - `IA-02` ([Identification and Authentication (Organizational Users)](controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (05)` ([Individual Authentication with Group Authentication](controls/identification-and-authentication.md#ia-02-05){ data-preview })
                - `IA-02 (06)` ([Access to Accounts —separate Device](controls/identification-and-authentication.md#ia-02-06){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-03` ([Device Identification and Authentication](controls/identification-and-authentication.md#ia-03){ data-preview })
                - `IA-04` ([Identifier Management](controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-04 (04)` ([Identify User Status](controls/identification-and-authentication.md#ia-04-04){ data-preview })
                - `IA-05` ([Authenticator Management](controls/identification-and-authentication.md#ia-05){ data-preview })
                - `IA-05 (01)` ([Password-based Authentication](controls/identification-and-authentication.md#ia-05-01){ data-preview })
                - `IA-05 (02)` ([Public Key-based Authentication](controls/identification-and-authentication.md#ia-05-02){ data-preview })
                - `IA-05 (06)` ([Protection of Authenticators](controls/identification-and-authentication.md#ia-05-06){ data-preview })
                - `IA-05 (07)` ([No Embedded Unencrypted Static Authenticators](controls/identification-and-authentication.md#ia-05-07){ data-preview })
                - `IA-06` ([Authentication Feedback](controls/identification-and-authentication.md#ia-06){ data-preview })
                - `IA-07` ([Cryptographic Module Authentication](controls/identification-and-authentication.md#ia-07){ data-preview })
                - `IA-08` ([Identification and Authentication (Non-organizational Users)](controls/identification-and-authentication.md#ia-08){ data-preview })
                - `IA-08 (01)` ([Acceptance of PIV Credentials from Other Agencies](controls/identification-and-authentication.md#ia-08-01){ data-preview })
                - `IA-08 (02)` ([Acceptance of External Authenticators](controls/identification-and-authentication.md#ia-08-02){ data-preview })
                - `IA-08 (04)` ([Use of Defined Profiles](controls/identification-and-authentication.md#ia-08-04){ data-preview })
                - `IA-11` ([Re-authentication](controls/identification-and-authentication.md#ia-11){ data-preview })
                - `IA-12` ([Identity Proofing](controls/identification-and-authentication.md#ia-12){ data-preview })
                - `IA-12 (02)` ([Identity Evidence](controls/identification-and-authentication.md#ia-12-02){ data-preview })
                - `IA-12 (03)` ([Identity Evidence Validation and Verification](controls/identification-and-authentication.md#ia-12-03){ data-preview })
                - `IA-12 (05)` ([Address Confirmation](controls/identification-and-authentication.md#ia-12-05){ data-preview })
            - **Incident Response (IR)**
                - `IR-01` ([Policy and Procedures](controls/incident-response.md#ir-01){ data-preview })
                - `IR-02` ([Incident Response Training](controls/incident-response.md#ir-02){ data-preview })
                - `IR-03` ([Incident Response Testing](controls/incident-response.md#ir-03){ data-preview })
                - `IR-03 (02)` ([Coordination with Related Plans](controls/incident-response.md#ir-03-02){ data-preview })
                - `IR-04` ([Incident Handling](controls/incident-response.md#ir-04){ data-preview })
                - `IR-04 (01)` ([Automated Incident Handling Processes](controls/incident-response.md#ir-04-01){ data-preview })
                - `IR-05` ([Incident Monitoring](controls/incident-response.md#ir-05){ data-preview })
                - `IR-06` ([Incident Reporting](controls/incident-response.md#ir-06){ data-preview })
                - `IR-06 (01)` ([Automated Reporting](controls/incident-response.md#ir-06-01){ data-preview })
                - `IR-06 (03)` ([Supply Chain Coordination](controls/incident-response.md#ir-06-03){ data-preview })
                - `IR-07` ([Incident Response Assistance](controls/incident-response.md#ir-07){ data-preview })
                - `IR-07 (01)` ([Automation Support for Availability of Information and Support](controls/incident-response.md#ir-07-01){ data-preview })
                - `IR-08` ([Incident Response Plan](controls/incident-response.md#ir-08){ data-preview })
                - `IR-09` ([Information Spillage Response](controls/incident-response.md#ir-09){ data-preview })
                - `IR-09 (02)` ([Training](controls/incident-response.md#ir-09-02){ data-preview })
                - `IR-09 (03)` ([Post-spill Operations](controls/incident-response.md#ir-09-03){ data-preview })
                - `IR-09 (04)` ([Exposure to Unauthorized Personnel](controls/incident-response.md#ir-09-04){ data-preview })
            - **Maintenance (MA)**
                - `MA-01` ([Policy and Procedures](controls/maintenance.md#ma-01){ data-preview })
                - `MA-02` ([Controlled Maintenance](controls/maintenance.md#ma-02){ data-preview })
                - `MA-03` ([Maintenance Tools](controls/maintenance.md#ma-03){ data-preview })
                - `MA-03 (01)` ([Inspect Tools](controls/maintenance.md#ma-03-01){ data-preview })
                - `MA-03 (02)` ([Inspect Media](controls/maintenance.md#ma-03-02){ data-preview })
                - `MA-03 (03)` ([Prevent Unauthorized Removal](controls/maintenance.md#ma-03-03){ data-preview })
                - `MA-04` ([Nonlocal Maintenance](controls/maintenance.md#ma-04){ data-preview })
                - `MA-05` ([Maintenance Personnel](controls/maintenance.md#ma-05){ data-preview })
                - `MA-05 (01)` ([Individuals Without Appropriate Access](controls/maintenance.md#ma-05-01){ data-preview })
                - `MA-06` ([Timely Maintenance](controls/maintenance.md#ma-06){ data-preview })
            - **Media Protection (MP)**
                - `MP-01` ([Policy and Procedures](controls/media-protection.md#mp-01){ data-preview })
                - `MP-02` ([Media Access](controls/media-protection.md#mp-02){ data-preview })
                - `MP-03` ([Media Marking](controls/media-protection.md#mp-03){ data-preview })
                - `MP-04` ([Media Storage](controls/media-protection.md#mp-04){ data-preview })
                - `MP-05` ([Media Transport](controls/media-protection.md#mp-05){ data-preview })
                - `MP-06` ([Media Sanitization](controls/media-protection.md#mp-06){ data-preview })
                - `MP-07` ([Media Use](controls/media-protection.md#mp-07){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-01` ([Policy and Procedures](controls/physical-and-environmental-protection.md#pe-01){ data-preview })
                - `PE-02` ([Physical Access Authorizations](controls/physical-and-environmental-protection.md#pe-02){ data-preview })
                - `PE-03` ([Physical Access Control](controls/physical-and-environmental-protection.md#pe-03){ data-preview })
                - `PE-04` ([Access Control for Transmission](controls/physical-and-environmental-protection.md#pe-04){ data-preview })
                - `PE-05` ([Access Control for Output Devices](controls/physical-and-environmental-protection.md#pe-05){ data-preview })
                - `PE-06` ([Monitoring Physical Access](controls/physical-and-environmental-protection.md#pe-06){ data-preview })
                - `PE-06 (01)` ([Intrusion Alarms and Surveillance Equipment](controls/physical-and-environmental-protection.md#pe-06-01){ data-preview })
                - `PE-08` ([Visitor Access Records](controls/physical-and-environmental-protection.md#pe-08){ data-preview })
                - `PE-09` ([Power Equipment and Cabling](controls/physical-and-environmental-protection.md#pe-09){ data-preview })
                - `PE-10` ([Emergency Shutoff](controls/physical-and-environmental-protection.md#pe-10){ data-preview })
                - `PE-11` ([Emergency Power](controls/physical-and-environmental-protection.md#pe-11){ data-preview })
                - `PE-12` ([Emergency Lighting](controls/physical-and-environmental-protection.md#pe-12){ data-preview })
                - `PE-13` ([Fire Protection](controls/physical-and-environmental-protection.md#pe-13){ data-preview })
                - `PE-13 (01)` ([Detection Systems — Automatic Activation and Notification](controls/physical-and-environmental-protection.md#pe-13-01){ data-preview })
                - `PE-13 (02)` ([Suppression Systems — Automatic Activation and Notification](controls/physical-and-environmental-protection.md#pe-13-02){ data-preview })
                - `PE-14` ([Environmental Controls](controls/physical-and-environmental-protection.md#pe-14){ data-preview })
                - `PE-15` ([Water Damage Protection](controls/physical-and-environmental-protection.md#pe-15){ data-preview })
                - `PE-16` ([Delivery and Removal](controls/physical-and-environmental-protection.md#pe-16){ data-preview })
                - `PE-17` ([Alternate Work Site](controls/physical-and-environmental-protection.md#pe-17){ data-preview })
            - **Planning (PL)**
                - `PL-01` ([Policy and Procedures](controls/planning.md#pl-01){ data-preview })
                - `PL-02` ([System Security and Privacy Plans](controls/planning.md#pl-02){ data-preview })
                - `PL-04` ([Rules of Behavior](controls/planning.md#pl-04){ data-preview })
                - `PL-04 (01)` ([Social Media and External Site/Application Usage Restrictions](controls/planning.md#pl-04-01){ data-preview })
                - `PL-08` ([Security and Privacy Architectures](controls/planning.md#pl-08){ data-preview })
                - `PL-10` ([Baseline Selection](controls/planning.md#pl-10){ data-preview })
                - `PL-11` ([Baseline Tailoring](controls/planning.md#pl-11){ data-preview })
            - **Personnel Security (PS)**
                - `PS-01` ([Policy and Procedures](controls/personnel-security.md#ps-01){ data-preview })
                - `PS-02` ([Position Risk Designation](controls/personnel-security.md#ps-02){ data-preview })
                - `PS-03` ([Personnel Screening](controls/personnel-security.md#ps-03){ data-preview })
                - `PS-03 (03)` ([Information Requiring Special Protective Measures](controls/personnel-security.md#ps-03-03){ data-preview })
                - `PS-04` ([Personnel Termination](controls/personnel-security.md#ps-04){ data-preview })
                - `PS-05` ([Personnel Transfer](controls/personnel-security.md#ps-05){ data-preview })
                - `PS-06` ([Access Agreements](controls/personnel-security.md#ps-06){ data-preview })
                - `PS-07` ([External Personnel Security](controls/personnel-security.md#ps-07){ data-preview })
                - `PS-08` ([Personnel Sanctions](controls/personnel-security.md#ps-08){ data-preview })
                - `PS-09` ([Position Descriptions](controls/personnel-security.md#ps-09){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-01` ([Policy and Procedures](controls/risk-assessment.md#ra-01){ data-preview })
                - `RA-02` ([Security Categorization](controls/risk-assessment.md#ra-02){ data-preview })
                - `RA-03` ([Risk Assessment](controls/risk-assessment.md#ra-03){ data-preview })
                - `RA-03 (01)` ([Supply Chain Risk Assessment](controls/risk-assessment.md#ra-03-01){ data-preview })
                - `RA-05` ([Vulnerability Monitoring and Scanning](controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (03)` ([Breadth and Depth of Coverage](controls/risk-assessment.md#ra-05-03){ data-preview })
                - `RA-05 (05)` ([Privileged Access](controls/risk-assessment.md#ra-05-05){ data-preview })
                - `RA-05 (11)` ([Public Disclosure Program](controls/risk-assessment.md#ra-05-11){ data-preview })
                - `RA-07` ([Risk Response](controls/risk-assessment.md#ra-07){ data-preview })
                - `RA-09` ([Criticality Analysis](controls/risk-assessment.md#ra-09){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-01` ([Policy and Procedures](controls/system-and-services-acquisition.md#sa-01){ data-preview })
                - `SA-02` ([Allocation of Resources](controls/system-and-services-acquisition.md#sa-02){ data-preview })
                - `SA-03` ([System Development Life Cycle](controls/system-and-services-acquisition.md#sa-03){ data-preview })
                - `SA-04` ([Acquisition Process](controls/system-and-services-acquisition.md#sa-04){ data-preview })
                - `SA-04 (01)` ([Functional Properties of Controls](controls/system-and-services-acquisition.md#sa-04-01){ data-preview })
                - `SA-04 (02)` ([Design and Implementation Information for Controls](controls/system-and-services-acquisition.md#sa-04-02){ data-preview })
                - `SA-04 (09)` ([Functions, Ports, Protocols, and Services in Use](controls/system-and-services-acquisition.md#sa-04-09){ data-preview })
                - `SA-04 (10)` ([Use of Approved PIV Products](controls/system-and-services-acquisition.md#sa-04-10){ data-preview })
                - `SA-05` ([System Documentation](controls/system-and-services-acquisition.md#sa-05){ data-preview })
                - `SA-08` ([Security and Privacy Engineering Principles](controls/system-and-services-acquisition.md#sa-08){ data-preview })
                - `SA-09` ([External System Services](controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-09 (01)` ([Risk Assessments and Organizational Approvals](controls/system-and-services-acquisition.md#sa-09-01){ data-preview })
                - `SA-09 (02)` ([Identification of Functions, Ports, Protocols, and Services](controls/system-and-services-acquisition.md#sa-09-02){ data-preview })
                - `SA-09 (05)` ([Processing, Storage, and Service Location](controls/system-and-services-acquisition.md#sa-09-05){ data-preview })
                - `SA-10` ([Developer Configuration Management](controls/system-and-services-acquisition.md#sa-10){ data-preview })
                - `SA-11` ([Developer Testing and Evaluation](controls/system-and-services-acquisition.md#sa-11){ data-preview })
                - `SA-11 (01)` ([Static Code Analysis](controls/system-and-services-acquisition.md#sa-11-01){ data-preview })
                - `SA-11 (02)` ([Threat Modeling and Vulnerability Analyses](controls/system-and-services-acquisition.md#sa-11-02){ data-preview })
                - `SA-15` ([Development Process, Standards, and Tools](controls/system-and-services-acquisition.md#sa-15){ data-preview })
                - `SA-15 (03)` ([Criticality Analysis](controls/system-and-services-acquisition.md#sa-15-03){ data-preview })
                - `SA-22` ([Unsupported System Components](controls/system-and-services-acquisition.md#sa-22){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-01` ([Policy and Procedures](controls/system-and-communications-protection.md#sc-01){ data-preview })
                - `SC-02` ([Separation of System and User Functionality](controls/system-and-communications-protection.md#sc-02){ data-preview })
                - `SC-04` ([Information in Shared System Resources](controls/system-and-communications-protection.md#sc-04){ data-preview })
                - `SC-05` ([Denial-of-service Protection](controls/system-and-communications-protection.md#sc-05){ data-preview })
                - `SC-07` ([Boundary Protection](controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-07 (03)` ([Access Points](controls/system-and-communications-protection.md#sc-07-03){ data-preview })
                - `SC-07 (04)` ([External Telecommunications Services](controls/system-and-communications-protection.md#sc-07-04){ data-preview })
                - `SC-07 (05)` ([Deny by Default — Allow by Exception](controls/system-and-communications-protection.md#sc-07-05){ data-preview })
                - `SC-07 (07)` ([Split Tunneling for Remote Devices](controls/system-and-communications-protection.md#sc-07-07){ data-preview })
                - `SC-07 (08)` ([Route Traffic to Authenticated Proxy Servers](controls/system-and-communications-protection.md#sc-07-08){ data-preview })
                - `SC-07 (12)` ([Host-based Protection](controls/system-and-communications-protection.md#sc-07-12){ data-preview })
                - `SC-07 (18)` ([Fail Secure](controls/system-and-communications-protection.md#sc-07-18){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-08 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-08-01){ data-preview })
                - `SC-10` ([Network Disconnect](controls/system-and-communications-protection.md#sc-10){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-13` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-15` ([Collaborative Computing Devices and Applications](controls/system-and-communications-protection.md#sc-15){ data-preview })
                - `SC-17` ([Public Key Infrastructure Certificates](controls/system-and-communications-protection.md#sc-17){ data-preview })
                - `SC-18` ([Mobile Code](controls/system-and-communications-protection.md#sc-18){ data-preview })
                - `SC-20` ([Secure Name/Address Resolution Service (Authoritative Source)](controls/system-and-communications-protection.md#sc-20){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-22` ([Architecture and Provisioning for Name/Address Resolution Service](controls/system-and-communications-protection.md#sc-22){ data-preview })
                - `SC-23` ([Session Authenticity](controls/system-and-communications-protection.md#sc-23){ data-preview })
                - `SC-28` ([Protection of Information at Rest](controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-28 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-28-01){ data-preview })
                - `SC-39` ([Process Isolation](controls/system-and-communications-protection.md#sc-39){ data-preview })
                - `SC-45` ([System Time Synchronization](controls/system-and-communications-protection.md#sc-45){ data-preview })
                - `SC-45 (01)` ([Synchronization with Authoritative Time Source](controls/system-and-communications-protection.md#sc-45-01){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-01` ([Policy and Procedures](controls/system-and-information-integrity.md#si-01){ data-preview })
                - `SI-02` ([Flaw Remediation](controls/system-and-information-integrity.md#si-02){ data-preview })
                - `SI-02 (02)` ([Automated Flaw Remediation Status](controls/system-and-information-integrity.md#si-02-02){ data-preview })
                - `SI-02 (03)` ([Time to Remediate Flaws and Benchmarks for Corrective Actions](controls/system-and-information-integrity.md#si-02-03){ data-preview })
                - `SI-03` ([Malicious Code Protection](controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04` ([System Monitoring](controls/system-and-information-integrity.md#si-04){ data-preview })
                - `SI-04 (01)` ([System-wide Intrusion Detection System](controls/system-and-information-integrity.md#si-04-01){ data-preview })
                - `SI-04 (02)` ([Automated Tools and Mechanisms for Real-time Analysis](controls/system-and-information-integrity.md#si-04-02){ data-preview })
                - `SI-04 (04)` ([Inbound and Outbound Communications Traffic](controls/system-and-information-integrity.md#si-04-04){ data-preview })
                - `SI-04 (05)` ([System-generated Alerts](controls/system-and-information-integrity.md#si-04-05){ data-preview })
                - `SI-04 (16)` ([Correlate Monitoring Information](controls/system-and-information-integrity.md#si-04-16){ data-preview })
                - `SI-04 (18)` ([Analyze Traffic and Covert Exfiltration](controls/system-and-information-integrity.md#si-04-18){ data-preview })
                - `SI-04 (23)` ([Host-based Devices](controls/system-and-information-integrity.md#si-04-23){ data-preview })
                - `SI-05` ([Security Alerts, Advisories, and Directives](controls/system-and-information-integrity.md#si-05){ data-preview })
                - `SI-06` ([Security and Privacy Function Verification](controls/system-and-information-integrity.md#si-06){ data-preview })
                - `SI-07` ([Software, Firmware, and Information Integrity](controls/system-and-information-integrity.md#si-07){ data-preview })
                - `SI-07 (01)` ([Integrity Checks](controls/system-and-information-integrity.md#si-07-01){ data-preview })
                - `SI-07 (07)` ([Integration of Detection and Response](controls/system-and-information-integrity.md#si-07-07){ data-preview })
                - `SI-08` ([Spam Protection](controls/system-and-information-integrity.md#si-08){ data-preview })
                - `SI-08 (02)` ([Automatic Updates](controls/system-and-information-integrity.md#si-08-02){ data-preview })
                - `SI-10` ([Information Input Validation](controls/system-and-information-integrity.md#si-10){ data-preview })
                - `SI-11` ([Error Handling](controls/system-and-information-integrity.md#si-11){ data-preview })
                - `SI-12` ([Information Management and Retention](controls/system-and-information-integrity.md#si-12){ data-preview })
                - `SI-16` ([Memory Protection](controls/system-and-information-integrity.md#si-16){ data-preview })
            - **Supply Chain Risk Management (SR)**
                - `SR-01` ([Policy and Procedures](controls/supply-chain-risk-management.md#sr-01){ data-preview })
                - `SR-02` ([Supply Chain Risk Management Plan](controls/supply-chain-risk-management.md#sr-02){ data-preview })
                - `SR-02 (01)` ([Establish SCRM Team](controls/supply-chain-risk-management.md#sr-02-01){ data-preview })
                - `SR-03` ([Supply Chain Controls and Processes](controls/supply-chain-risk-management.md#sr-03){ data-preview })
                - `SR-05` ([Acquisition Strategies, Tools, and Methods](controls/supply-chain-risk-management.md#sr-05){ data-preview })
                - `SR-06` ([Supplier Assessments and Reviews](controls/supply-chain-risk-management.md#sr-06){ data-preview })
                - `SR-08` ([Notification Agreements](controls/supply-chain-risk-management.md#sr-08){ data-preview })
                - `SR-10` ([Inspection of Systems or Components](controls/supply-chain-risk-management.md#sr-10){ data-preview })
                - `SR-11` ([Component Authenticity](controls/supply-chain-risk-management.md#sr-11){ data-preview })
                - `SR-11 (01)` ([Anti-counterfeit Training](controls/supply-chain-risk-management.md#sr-11-01){ data-preview })
                - `SR-11 (02)` ([Configuration Control for Component Service and Repair](controls/supply-chain-risk-management.md#sr-11-02){ data-preview })
                - `SR-12` ([Component Disposal](controls/supply-chain-risk-management.md#sr-12){ data-preview })
        
    === "Class D"
        Providers seeking FedRAMP Rev5 Class D Certification MUST include at least the following NIST SP 800-53 Rev. 5 controls in their Security Decision Record:

        ???+ info "Rev5 Control List"
            - **Access Control (AC)**
                - `AC-01` ([Policy and Procedures](controls/access-control.md#ac-01){ data-preview })
                - `AC-02` ([Account Management](controls/access-control.md#ac-02){ data-preview })
                - `AC-02 (01)` ([Automated System Account Management](controls/access-control.md#ac-02-01){ data-preview })
                - `AC-02 (02)` ([Automated Temporary and Emergency Account Management](controls/access-control.md#ac-02-02){ data-preview })
                - `AC-02 (03)` ([Disable Accounts](controls/access-control.md#ac-02-03){ data-preview })
                - `AC-02 (04)` ([Automated Audit Actions](controls/access-control.md#ac-02-04){ data-preview })
                - `AC-02 (05)` ([Inactivity Logout](controls/access-control.md#ac-02-05){ data-preview })
                - `AC-02 (07)` ([Privileged User Accounts](controls/access-control.md#ac-02-07){ data-preview })
                - `AC-02 (09)` ([Restrictions on Use of Shared and Group Accounts](controls/access-control.md#ac-02-09){ data-preview })
                - `AC-02 (11)` ([Usage Conditions](controls/access-control.md#ac-02-11){ data-preview })
                - `AC-02 (12)` ([Account Monitoring for Atypical Usage](controls/access-control.md#ac-02-12){ data-preview })
                - `AC-02 (13)` ([Disable Accounts for High-risk Individuals](controls/access-control.md#ac-02-13){ data-preview })
                - `AC-03` ([Access Enforcement](controls/access-control.md#ac-03){ data-preview })
                - `AC-04` ([Information Flow Enforcement](controls/access-control.md#ac-04){ data-preview })
                - `AC-04 (04)` ([Flow Control of Encrypted Information](controls/access-control.md#ac-04-04){ data-preview })
                - `AC-04 (21)` ([Physical or Logical Separation of Information Flows](controls/access-control.md#ac-04-21){ data-preview })
                - `AC-05` ([Separation of Duties](controls/access-control.md#ac-05){ data-preview })
                - `AC-06` ([Least Privilege](controls/access-control.md#ac-06){ data-preview })
                - `AC-06 (01)` ([Authorize Access to Security Functions](controls/access-control.md#ac-06-01){ data-preview })
                - `AC-06 (02)` ([Non-privileged Access for Nonsecurity Functions](controls/access-control.md#ac-06-02){ data-preview })
                - `AC-06 (03)` ([Network Access to Privileged Commands](controls/access-control.md#ac-06-03){ data-preview })
                - `AC-06 (05)` ([Privileged Accounts](controls/access-control.md#ac-06-05){ data-preview })
                - `AC-06 (07)` ([Review of User Privileges](controls/access-control.md#ac-06-07){ data-preview })
                - `AC-06 (08)` ([Privilege Levels for Code Execution](controls/access-control.md#ac-06-08){ data-preview })
                - `AC-06 (09)` ([Log Use of Privileged Functions](controls/access-control.md#ac-06-09){ data-preview })
                - `AC-06 (10)` ([Prohibit Non-privileged Users from Executing Privileged Functions](controls/access-control.md#ac-06-10){ data-preview })
                - `AC-07` ([Unsuccessful Logon Attempts](controls/access-control.md#ac-07){ data-preview })
                - `AC-08` ([System Use Notification](controls/access-control.md#ac-08){ data-preview })
                - `AC-10` ([Concurrent Session Control](controls/access-control.md#ac-10){ data-preview })
                - `AC-11` ([Device Lock](controls/access-control.md#ac-11){ data-preview })
                - `AC-11 (01)` ([Pattern-hiding Displays](controls/access-control.md#ac-11-01){ data-preview })
                - `AC-12` ([Session Termination](controls/access-control.md#ac-12){ data-preview })
                - `AC-14` ([Permitted Actions Without Identification or Authentication](controls/access-control.md#ac-14){ data-preview })
                - `AC-17` ([Remote Access](controls/access-control.md#ac-17){ data-preview })
                - `AC-17 (01)` ([Monitoring and Control](controls/access-control.md#ac-17-01){ data-preview })
                - `AC-17 (02)` ([Protection of Confidentiality and Integrity Using Encryption](controls/access-control.md#ac-17-02){ data-preview })
                - `AC-17 (03)` ([Managed Access Control Points](controls/access-control.md#ac-17-03){ data-preview })
                - `AC-17 (04)` ([Privileged Commands and Access](controls/access-control.md#ac-17-04){ data-preview })
                - `AC-18` ([Wireless Access](controls/access-control.md#ac-18){ data-preview })
                - `AC-18 (01)` ([Authentication and Encryption](controls/access-control.md#ac-18-01){ data-preview })
                - `AC-18 (03)` ([Disable Wireless Networking](controls/access-control.md#ac-18-03){ data-preview })
                - `AC-18 (04)` ([Restrict Configurations by Users](controls/access-control.md#ac-18-04){ data-preview })
                - `AC-18 (05)` ([Antennas and Transmission Power Levels](controls/access-control.md#ac-18-05){ data-preview })
                - `AC-19` ([Access Control for Mobile Devices](controls/access-control.md#ac-19){ data-preview })
                - `AC-19 (05)` ([Full Device or Container-based Encryption](controls/access-control.md#ac-19-05){ data-preview })
                - `AC-20` ([Use of External Systems](controls/access-control.md#ac-20){ data-preview })
                - `AC-20 (01)` ([Limits on Authorized Use](controls/access-control.md#ac-20-01){ data-preview })
                - `AC-20 (02)` ([Portable Storage Devices — Restricted Use](controls/access-control.md#ac-20-02){ data-preview })
                - `AC-21` ([Information Sharing](controls/access-control.md#ac-21){ data-preview })
                - `AC-22` ([Publicly Accessible Content](controls/access-control.md#ac-22){ data-preview })
            - **Awareness and Training (AT)**
                - `AT-01` ([Policy and Procedures](controls/awareness-and-training.md#at-01){ data-preview })
                - `AT-02` ([Literacy Training and Awareness](controls/awareness-and-training.md#at-02){ data-preview })
                - `AT-02 (02)` ([Insider Threat](controls/awareness-and-training.md#at-02-02){ data-preview })
                - `AT-02 (03)` ([Social Engineering and Mining](controls/awareness-and-training.md#at-02-03){ data-preview })
                - `AT-03` ([Role-based Training](controls/awareness-and-training.md#at-03){ data-preview })
                - `AT-04` ([Training Records](controls/awareness-and-training.md#at-04){ data-preview })
            - **Audit and Accountability (AU)**
                - `AU-01` ([Policy and Procedures](controls/audit-and-accountability.md#au-01){ data-preview })
                - `AU-02` ([Event Logging](controls/audit-and-accountability.md#au-02){ data-preview })
                - `AU-03` ([Content of Audit Records](controls/audit-and-accountability.md#au-03){ data-preview })
                - `AU-03 (01)` ([Additional Audit Information](controls/audit-and-accountability.md#au-03-01){ data-preview })
                - `AU-04` ([Audit Log Storage Capacity](controls/audit-and-accountability.md#au-04){ data-preview })
                - `AU-05` ([Response to Audit Logging Process Failures](controls/audit-and-accountability.md#au-05){ data-preview })
                - `AU-05 (01)` ([Storage Capacity Warning](controls/audit-and-accountability.md#au-05-01){ data-preview })
                - `AU-05 (02)` ([Real-time Alerts](controls/audit-and-accountability.md#au-05-02){ data-preview })
                - `AU-06` ([Audit Record Review, Analysis, and Reporting](controls/audit-and-accountability.md#au-06){ data-preview })
                - `AU-06 (01)` ([Automated Process Integration](controls/audit-and-accountability.md#au-06-01){ data-preview })
                - `AU-06 (03)` ([Correlate Audit Record Repositories](controls/audit-and-accountability.md#au-06-03){ data-preview })
                - `AU-06 (04)` ([Central Review and Analysis](controls/audit-and-accountability.md#au-06-04){ data-preview })
                - `AU-06 (05)` ([Integrated Analysis of Audit Records](controls/audit-and-accountability.md#au-06-05){ data-preview })
                - `AU-06 (06)` ([Correlation with Physical Monitoring](controls/audit-and-accountability.md#au-06-06){ data-preview })
                - `AU-06 (07)` ([Permitted Actions](controls/audit-and-accountability.md#au-06-07){ data-preview })
                - `AU-07` ([Audit Record Reduction and Report Generation](controls/audit-and-accountability.md#au-07){ data-preview })
                - `AU-07 (01)` ([Automatic Processing](controls/audit-and-accountability.md#au-07-01){ data-preview })
                - `AU-08` ([Time Stamps](controls/audit-and-accountability.md#au-08){ data-preview })
                - `AU-09` ([Protection of Audit Information](controls/audit-and-accountability.md#au-09){ data-preview })
                - `AU-09 (02)` ([Store on Separate Physical Systems or Components](controls/audit-and-accountability.md#au-09-02){ data-preview })
                - `AU-09 (03)` ([Cryptographic Protection](controls/audit-and-accountability.md#au-09-03){ data-preview })
                - `AU-09 (04)` ([Access by Subset of Privileged Users](controls/audit-and-accountability.md#au-09-04){ data-preview })
                - `AU-10` ([Non-repudiation](controls/audit-and-accountability.md#au-10){ data-preview })
                - `AU-11` ([Audit Record Retention](controls/audit-and-accountability.md#au-11){ data-preview })
                - `AU-12` ([Audit Record Generation](controls/audit-and-accountability.md#au-12){ data-preview })
                - `AU-12 (01)` ([System-wide and Time-correlated Audit Trail](controls/audit-and-accountability.md#au-12-01){ data-preview })
                - `AU-12 (03)` ([Changes by Authorized Individuals](controls/audit-and-accountability.md#au-12-03){ data-preview })
            - **Assessment, Authorization, and Monitoring (CA)**
                - `CA-01` ([Policy and Procedures](controls/assessment-authorization-and-monitoring.md#ca-01){ data-preview })
                - `CA-02` ([Control Assessments](controls/assessment-authorization-and-monitoring.md#ca-02){ data-preview })
                - `CA-02 (01)` ([Independent Assessors](controls/assessment-authorization-and-monitoring.md#ca-02-01){ data-preview })
                - `CA-02 (02)` ([Specialized Assessments](controls/assessment-authorization-and-monitoring.md#ca-02-02){ data-preview })
                - `CA-02 (03)` ([Leveraging Results from External Organizations](controls/assessment-authorization-and-monitoring.md#ca-02-03){ data-preview })
                - `CA-03` ([Information Exchange](controls/assessment-authorization-and-monitoring.md#ca-03){ data-preview })
                - `CA-03 (06)` ([Transfer Authorizations](controls/assessment-authorization-and-monitoring.md#ca-03-06){ data-preview })
                - `CA-06` ([Authorization](controls/assessment-authorization-and-monitoring.md#ca-06){ data-preview })
                - `CA-07` ([Continuous Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07){ data-preview })
                - `CA-07 (01)` ([Independent Assessment](controls/assessment-authorization-and-monitoring.md#ca-07-01){ data-preview })
                - `CA-07 (04)` ([Risk Monitoring](controls/assessment-authorization-and-monitoring.md#ca-07-04){ data-preview })
                - `CA-08` ([Penetration Testing](controls/assessment-authorization-and-monitoring.md#ca-08){ data-preview })
                - `CA-08 (01)` ([Independent Penetration Testing Agent or Team](controls/assessment-authorization-and-monitoring.md#ca-08-01){ data-preview })
                - `CA-08 (02)` ([Red Team Exercises](controls/assessment-authorization-and-monitoring.md#ca-08-02){ data-preview })
                - `CA-09` ([Internal System Connections](controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview })
            - **Configuration Management (CM)**
                - `CM-01` ([Policy and Procedures](controls/configuration-management.md#cm-01){ data-preview })
                - `CM-02` ([Baseline Configuration](controls/configuration-management.md#cm-02){ data-preview })
                - `CM-02 (02)` ([Automation Support for Accuracy and Currency](controls/configuration-management.md#cm-02-02){ data-preview })
                - `CM-02 (03)` ([Retention of Previous Configurations](controls/configuration-management.md#cm-02-03){ data-preview })
                - `CM-02 (07)` ([Configure Systems and Components for High-risk Areas](controls/configuration-management.md#cm-02-07){ data-preview })
                - `CM-03` ([Configuration Change Control](controls/configuration-management.md#cm-03){ data-preview })
                - `CM-03 (01)` ([Automated Documentation, Notification, and Prohibition of Changes](controls/configuration-management.md#cm-03-01){ data-preview })
                - `CM-03 (02)` ([Testing, Validation, and Documentation of Changes](controls/configuration-management.md#cm-03-02){ data-preview })
                - `CM-03 (04)` ([Security and Privacy Representatives](controls/configuration-management.md#cm-03-04){ data-preview })
                - `CM-03 (06)` ([Cryptography Management](controls/configuration-management.md#cm-03-06){ data-preview })
                - `CM-04` ([Impact Analyses](controls/configuration-management.md#cm-04){ data-preview })
                - `CM-04 (01)` ([Separate Test Environments](controls/configuration-management.md#cm-04-01){ data-preview })
                - `CM-04 (02)` ([Verification of Controls](controls/configuration-management.md#cm-04-02){ data-preview })
                - `CM-05` ([Access Restrictions for Change](controls/configuration-management.md#cm-05){ data-preview })
                - `CM-05 (01)` ([Automated Access Enforcement and Audit Records](controls/configuration-management.md#cm-05-01){ data-preview })
                - `CM-05 (05)` ([Privilege Limitation for Production and Operation](controls/configuration-management.md#cm-05-05){ data-preview })
                - `CM-06` ([Configuration Settings](controls/configuration-management.md#cm-06){ data-preview })
                - `CM-06 (01)` ([Automated Management, Application, and Verification](controls/configuration-management.md#cm-06-01){ data-preview })
                - `CM-06 (02)` ([Respond to Unauthorized Changes](controls/configuration-management.md#cm-06-02){ data-preview })
                - `CM-07` ([Least Functionality](controls/configuration-management.md#cm-07){ data-preview })
                - `CM-07 (01)` ([Periodic Review](controls/configuration-management.md#cm-07-01){ data-preview })
                - `CM-07 (02)` ([Prevent Program Execution](controls/configuration-management.md#cm-07-02){ data-preview })
                - `CM-07 (05)` ([Authorized Software — Allow-by-exception](controls/configuration-management.md#cm-07-05){ data-preview })
                - `CM-08` ([System Component Inventory](controls/configuration-management.md#cm-08){ data-preview })
                - `CM-08 (01)` ([Updates During Installation and Removal](controls/configuration-management.md#cm-08-01){ data-preview })
                - `CM-08 (02)` ([Automated Maintenance](controls/configuration-management.md#cm-08-02){ data-preview })
                - `CM-08 (03)` ([Automated Unauthorized Component Detection](controls/configuration-management.md#cm-08-03){ data-preview })
                - `CM-08 (04)` ([Accountability Information](controls/configuration-management.md#cm-08-04){ data-preview })
                - `CM-09` ([Configuration Management Plan](controls/configuration-management.md#cm-09){ data-preview })
                - `CM-10` ([Software Usage Restrictions](controls/configuration-management.md#cm-10){ data-preview })
                - `CM-11` ([User-installed Software](controls/configuration-management.md#cm-11){ data-preview })
                - `CM-12` ([Information Location](controls/configuration-management.md#cm-12){ data-preview })
                - `CM-12 (01)` ([Automated Tools to Support Information Location](controls/configuration-management.md#cm-12-01){ data-preview })
                - `CM-14` ([Signed Components](controls/configuration-management.md#cm-14){ data-preview })
            - **Contingency Planning (CP)**
                - `CP-01` ([Policy and Procedures](controls/contingency-planning.md#cp-01){ data-preview })
                - `CP-02` ([Contingency Plan](controls/contingency-planning.md#cp-02){ data-preview })
                - `CP-02 (01)` ([Coordinate with Related Plans](controls/contingency-planning.md#cp-02-01){ data-preview })
                - `CP-02 (02)` ([Capacity Planning](controls/contingency-planning.md#cp-02-02){ data-preview })
                - `CP-02 (03)` ([Resume Mission and Business Functions](controls/contingency-planning.md#cp-02-03){ data-preview })
                - `CP-02 (05)` ([Continue Mission and Business Functions](controls/contingency-planning.md#cp-02-05){ data-preview })
                - `CP-02 (08)` ([Identify Critical Assets](controls/contingency-planning.md#cp-02-08){ data-preview })
                - `CP-03` ([Contingency Training](controls/contingency-planning.md#cp-03){ data-preview })
                - `CP-03 (01)` ([Simulated Events](controls/contingency-planning.md#cp-03-01){ data-preview })
                - `CP-04` ([Contingency Plan Testing](controls/contingency-planning.md#cp-04){ data-preview })
                - `CP-04 (01)` ([Coordinate with Related Plans](controls/contingency-planning.md#cp-04-01){ data-preview })
                - `CP-04 (02)` ([Alternate Processing Site](controls/contingency-planning.md#cp-04-02){ data-preview })
                - `CP-06` ([Alternate Storage Site](controls/contingency-planning.md#cp-06){ data-preview })
                - `CP-06 (01)` ([Separation from Primary Site](controls/contingency-planning.md#cp-06-01){ data-preview })
                - `CP-06 (02)` ([Recovery Time and Recovery Point Objectives](controls/contingency-planning.md#cp-06-02){ data-preview })
                - `CP-06 (03)` ([Accessibility](controls/contingency-planning.md#cp-06-03){ data-preview })
                - `CP-07` ([Alternate Processing Site](controls/contingency-planning.md#cp-07){ data-preview })
                - `CP-07 (01)` ([Separation from Primary Site](controls/contingency-planning.md#cp-07-01){ data-preview })
                - `CP-07 (02)` ([Accessibility](controls/contingency-planning.md#cp-07-02){ data-preview })
                - `CP-07 (03)` ([Priority of Service](controls/contingency-planning.md#cp-07-03){ data-preview })
                - `CP-07 (04)` ([Preparation for Use](controls/contingency-planning.md#cp-07-04){ data-preview })
                - `CP-08` ([Telecommunications Services](controls/contingency-planning.md#cp-08){ data-preview })
                - `CP-08 (01)` ([Priority of Service Provisions](controls/contingency-planning.md#cp-08-01){ data-preview })
                - `CP-08 (02)` ([Single Points of Failure](controls/contingency-planning.md#cp-08-02){ data-preview })
                - `CP-08 (03)` ([Separation of Primary and Alternate Providers](controls/contingency-planning.md#cp-08-03){ data-preview })
                - `CP-08 (04)` ([Provider Contingency Plan](controls/contingency-planning.md#cp-08-04){ data-preview })
                - `CP-09` ([System Backup](controls/contingency-planning.md#cp-09){ data-preview })
                - `CP-09 (01)` ([Testing for Reliability and Integrity](controls/contingency-planning.md#cp-09-01){ data-preview })
                - `CP-09 (02)` ([Test Restoration Using Sampling](controls/contingency-planning.md#cp-09-02){ data-preview })
                - `CP-09 (03)` ([Separate Storage for Critical Information](controls/contingency-planning.md#cp-09-03){ data-preview })
                - `CP-09 (05)` ([Transfer to Alternate Storage Site](controls/contingency-planning.md#cp-09-05){ data-preview })
                - `CP-09 (08)` ([Cryptographic Protection](controls/contingency-planning.md#cp-09-08){ data-preview })
                - `CP-10` ([System Recovery and Reconstitution](controls/contingency-planning.md#cp-10){ data-preview })
                - `CP-10 (02)` ([Transaction Recovery](controls/contingency-planning.md#cp-10-02){ data-preview })
                - `CP-10 (04)` ([Restore Within Time Period](controls/contingency-planning.md#cp-10-04){ data-preview })
            - **Identification and Authentication (IA)**
                - `IA-01` ([Policy and Procedures](controls/identification-and-authentication.md#ia-01){ data-preview })
                - `IA-02` ([Identification and Authentication (Organizational Users)](controls/identification-and-authentication.md#ia-02){ data-preview })
                - `IA-02 (01)` ([Multi-factor Authentication to Privileged Accounts](controls/identification-and-authentication.md#ia-02-01){ data-preview })
                - `IA-02 (02)` ([Multi-factor Authentication to Non-privileged Accounts](controls/identification-and-authentication.md#ia-02-02){ data-preview })
                - `IA-02 (05)` ([Individual Authentication with Group Authentication](controls/identification-and-authentication.md#ia-02-05){ data-preview })
                - `IA-02 (06)` ([Access to Accounts —separate Device](controls/identification-and-authentication.md#ia-02-06){ data-preview })
                - `IA-02 (08)` ([Access to Accounts — Replay Resistant](controls/identification-and-authentication.md#ia-02-08){ data-preview })
                - `IA-02 (12)` ([Acceptance of PIV Credentials](controls/identification-and-authentication.md#ia-02-12){ data-preview })
                - `IA-03` ([Device Identification and Authentication](controls/identification-and-authentication.md#ia-03){ data-preview })
                - `IA-04` ([Identifier Management](controls/identification-and-authentication.md#ia-04){ data-preview })
                - `IA-04 (04)` ([Identify User Status](controls/identification-and-authentication.md#ia-04-04){ data-preview })
                - `IA-05` ([Authenticator Management](controls/identification-and-authentication.md#ia-05){ data-preview })
                - `IA-05 (01)` ([Password-based Authentication](controls/identification-and-authentication.md#ia-05-01){ data-preview })
                - `IA-05 (02)` ([Public Key-based Authentication](controls/identification-and-authentication.md#ia-05-02){ data-preview })
                - `IA-05 (06)` ([Protection of Authenticators](controls/identification-and-authentication.md#ia-05-06){ data-preview })
                - `IA-05 (07)` ([No Embedded Unencrypted Static Authenticators](controls/identification-and-authentication.md#ia-05-07){ data-preview })
                - `IA-05 (08)` ([Multiple System Accounts](controls/identification-and-authentication.md#ia-05-08){ data-preview })
                - `IA-05 (13)` ([Expiration of Cached Authenticators](controls/identification-and-authentication.md#ia-05-13){ data-preview })
                - `IA-06` ([Authentication Feedback](controls/identification-and-authentication.md#ia-06){ data-preview })
                - `IA-07` ([Cryptographic Module Authentication](controls/identification-and-authentication.md#ia-07){ data-preview })
                - `IA-08` ([Identification and Authentication (Non-organizational Users)](controls/identification-and-authentication.md#ia-08){ data-preview })
                - `IA-08 (01)` ([Acceptance of PIV Credentials from Other Agencies](controls/identification-and-authentication.md#ia-08-01){ data-preview })
                - `IA-08 (02)` ([Acceptance of External Authenticators](controls/identification-and-authentication.md#ia-08-02){ data-preview })
                - `IA-08 (04)` ([Use of Defined Profiles](controls/identification-and-authentication.md#ia-08-04){ data-preview })
                - `IA-11` ([Re-authentication](controls/identification-and-authentication.md#ia-11){ data-preview })
                - `IA-12` ([Identity Proofing](controls/identification-and-authentication.md#ia-12){ data-preview })
                - `IA-12 (02)` ([Identity Evidence](controls/identification-and-authentication.md#ia-12-02){ data-preview })
                - `IA-12 (03)` ([Identity Evidence Validation and Verification](controls/identification-and-authentication.md#ia-12-03){ data-preview })
                - `IA-12 (04)` ([In-person Validation and Verification](controls/identification-and-authentication.md#ia-12-04){ data-preview })
                - `IA-12 (05)` ([Address Confirmation](controls/identification-and-authentication.md#ia-12-05){ data-preview })
            - **Incident Response (IR)**
                - `IR-01` ([Policy and Procedures](controls/incident-response.md#ir-01){ data-preview })
                - `IR-02` ([Incident Response Training](controls/incident-response.md#ir-02){ data-preview })
                - `IR-02 (01)` ([Simulated Events](controls/incident-response.md#ir-02-01){ data-preview })
                - `IR-02 (02)` ([Automated Training Environments](controls/incident-response.md#ir-02-02){ data-preview })
                - `IR-03` ([Incident Response Testing](controls/incident-response.md#ir-03){ data-preview })
                - `IR-03 (02)` ([Coordination with Related Plans](controls/incident-response.md#ir-03-02){ data-preview })
                - `IR-04` ([Incident Handling](controls/incident-response.md#ir-04){ data-preview })
                - `IR-04 (01)` ([Automated Incident Handling Processes](controls/incident-response.md#ir-04-01){ data-preview })
                - `IR-04 (02)` ([Dynamic Reconfiguration](controls/incident-response.md#ir-04-02){ data-preview })
                - `IR-04 (04)` ([Information Correlation](controls/incident-response.md#ir-04-04){ data-preview })
                - `IR-04 (06)` ([Insider Threats](controls/incident-response.md#ir-04-06){ data-preview })
                - `IR-04 (11)` ([Integrated Incident Response Team](controls/incident-response.md#ir-04-11){ data-preview })
                - `IR-05` ([Incident Monitoring](controls/incident-response.md#ir-05){ data-preview })
                - `IR-05 (01)` ([Automated Tracking, Data Collection, and Analysis](controls/incident-response.md#ir-05-01){ data-preview })
                - `IR-06` ([Incident Reporting](controls/incident-response.md#ir-06){ data-preview })
                - `IR-06 (01)` ([Automated Reporting](controls/incident-response.md#ir-06-01){ data-preview })
                - `IR-06 (03)` ([Supply Chain Coordination](controls/incident-response.md#ir-06-03){ data-preview })
                - `IR-07` ([Incident Response Assistance](controls/incident-response.md#ir-07){ data-preview })
                - `IR-07 (01)` ([Automation Support for Availability of Information and Support](controls/incident-response.md#ir-07-01){ data-preview })
                - `IR-08` ([Incident Response Plan](controls/incident-response.md#ir-08){ data-preview })
                - `IR-09` ([Information Spillage Response](controls/incident-response.md#ir-09){ data-preview })
                - `IR-09 (02)` ([Training](controls/incident-response.md#ir-09-02){ data-preview })
                - `IR-09 (03)` ([Post-spill Operations](controls/incident-response.md#ir-09-03){ data-preview })
                - `IR-09 (04)` ([Exposure to Unauthorized Personnel](controls/incident-response.md#ir-09-04){ data-preview })
            - **Maintenance (MA)**
                - `MA-01` ([Policy and Procedures](controls/maintenance.md#ma-01){ data-preview })
                - `MA-02` ([Controlled Maintenance](controls/maintenance.md#ma-02){ data-preview })
                - `MA-02 (02)` ([Automated Maintenance Activities](controls/maintenance.md#ma-02-02){ data-preview })
                - `MA-03` ([Maintenance Tools](controls/maintenance.md#ma-03){ data-preview })
                - `MA-03 (01)` ([Inspect Tools](controls/maintenance.md#ma-03-01){ data-preview })
                - `MA-03 (02)` ([Inspect Media](controls/maintenance.md#ma-03-02){ data-preview })
                - `MA-03 (03)` ([Prevent Unauthorized Removal](controls/maintenance.md#ma-03-03){ data-preview })
                - `MA-04` ([Nonlocal Maintenance](controls/maintenance.md#ma-04){ data-preview })
                - `MA-04 (03)` ([Comparable Security and Sanitization](controls/maintenance.md#ma-04-03){ data-preview })
                - `MA-05` ([Maintenance Personnel](controls/maintenance.md#ma-05){ data-preview })
                - `MA-05 (01)` ([Individuals Without Appropriate Access](controls/maintenance.md#ma-05-01){ data-preview })
                - `MA-06` ([Timely Maintenance](controls/maintenance.md#ma-06){ data-preview })
            - **Media Protection (MP)**
                - `MP-01` ([Policy and Procedures](controls/media-protection.md#mp-01){ data-preview })
                - `MP-02` ([Media Access](controls/media-protection.md#mp-02){ data-preview })
                - `MP-03` ([Media Marking](controls/media-protection.md#mp-03){ data-preview })
                - `MP-04` ([Media Storage](controls/media-protection.md#mp-04){ data-preview })
                - `MP-05` ([Media Transport](controls/media-protection.md#mp-05){ data-preview })
                - `MP-06` ([Media Sanitization](controls/media-protection.md#mp-06){ data-preview })
                - `MP-06 (01)` ([Review, Approve, Track, Document, and Verify](controls/media-protection.md#mp-06-01){ data-preview })
                - `MP-06 (02)` ([Equipment Testing](controls/media-protection.md#mp-06-02){ data-preview })
                - `MP-06 (03)` ([Nondestructive Techniques](controls/media-protection.md#mp-06-03){ data-preview })
                - `MP-07` ([Media Use](controls/media-protection.md#mp-07){ data-preview })
            - **Physical and Environmental Protection (PE)**
                - `PE-01` ([Policy and Procedures](controls/physical-and-environmental-protection.md#pe-01){ data-preview })
                - `PE-02` ([Physical Access Authorizations](controls/physical-and-environmental-protection.md#pe-02){ data-preview })
                - `PE-03` ([Physical Access Control](controls/physical-and-environmental-protection.md#pe-03){ data-preview })
                - `PE-03 (01)` ([System Access](controls/physical-and-environmental-protection.md#pe-03-01){ data-preview })
                - `PE-04` ([Access Control for Transmission](controls/physical-and-environmental-protection.md#pe-04){ data-preview })
                - `PE-05` ([Access Control for Output Devices](controls/physical-and-environmental-protection.md#pe-05){ data-preview })
                - `PE-06` ([Monitoring Physical Access](controls/physical-and-environmental-protection.md#pe-06){ data-preview })
                - `PE-06 (01)` ([Intrusion Alarms and Surveillance Equipment](controls/physical-and-environmental-protection.md#pe-06-01){ data-preview })
                - `PE-06 (04)` ([Monitoring Physical Access to Systems](controls/physical-and-environmental-protection.md#pe-06-04){ data-preview })
                - `PE-08` ([Visitor Access Records](controls/physical-and-environmental-protection.md#pe-08){ data-preview })
                - `PE-08 (01)` ([Automated Records Maintenance and Review](controls/physical-and-environmental-protection.md#pe-08-01){ data-preview })
                - `PE-09` ([Power Equipment and Cabling](controls/physical-and-environmental-protection.md#pe-09){ data-preview })
                - `PE-10` ([Emergency Shutoff](controls/physical-and-environmental-protection.md#pe-10){ data-preview })
                - `PE-11` ([Emergency Power](controls/physical-and-environmental-protection.md#pe-11){ data-preview })
                - `PE-11 (01)` ([Alternate Power Supply — Minimal Operational Capability](controls/physical-and-environmental-protection.md#pe-11-01){ data-preview })
                - `PE-12` ([Emergency Lighting](controls/physical-and-environmental-protection.md#pe-12){ data-preview })
                - `PE-13` ([Fire Protection](controls/physical-and-environmental-protection.md#pe-13){ data-preview })
                - `PE-13 (01)` ([Detection Systems — Automatic Activation and Notification](controls/physical-and-environmental-protection.md#pe-13-01){ data-preview })
                - `PE-13 (02)` ([Suppression Systems — Automatic Activation and Notification](controls/physical-and-environmental-protection.md#pe-13-02){ data-preview })
                - `PE-14` ([Environmental Controls](controls/physical-and-environmental-protection.md#pe-14){ data-preview })
                - `PE-14 (02)` ([Monitoring with Alarms and Notifications](controls/physical-and-environmental-protection.md#pe-14-02){ data-preview })
                - `PE-15` ([Water Damage Protection](controls/physical-and-environmental-protection.md#pe-15){ data-preview })
                - `PE-15 (01)` ([Automation Support](controls/physical-and-environmental-protection.md#pe-15-01){ data-preview })
                - `PE-16` ([Delivery and Removal](controls/physical-and-environmental-protection.md#pe-16){ data-preview })
                - `PE-17` ([Alternate Work Site](controls/physical-and-environmental-protection.md#pe-17){ data-preview })
                - `PE-18` ([Location of System Components](controls/physical-and-environmental-protection.md#pe-18){ data-preview })
            - **Planning (PL)**
                - `PL-01` ([Policy and Procedures](controls/planning.md#pl-01){ data-preview })
                - `PL-02` ([System Security and Privacy Plans](controls/planning.md#pl-02){ data-preview })
                - `PL-04` ([Rules of Behavior](controls/planning.md#pl-04){ data-preview })
                - `PL-04 (01)` ([Social Media and External Site/Application Usage Restrictions](controls/planning.md#pl-04-01){ data-preview })
                - `PL-08` ([Security and Privacy Architectures](controls/planning.md#pl-08){ data-preview })
                - `PL-10` ([Baseline Selection](controls/planning.md#pl-10){ data-preview })
                - `PL-11` ([Baseline Tailoring](controls/planning.md#pl-11){ data-preview })
            - **Personnel Security (PS)**
                - `PS-01` ([Policy and Procedures](controls/personnel-security.md#ps-01){ data-preview })
                - `PS-02` ([Position Risk Designation](controls/personnel-security.md#ps-02){ data-preview })
                - `PS-03` ([Personnel Screening](controls/personnel-security.md#ps-03){ data-preview })
                - `PS-03 (03)` ([Information Requiring Special Protective Measures](controls/personnel-security.md#ps-03-03){ data-preview })
                - `PS-04` ([Personnel Termination](controls/personnel-security.md#ps-04){ data-preview })
                - `PS-04 (02)` ([Automated Actions](controls/personnel-security.md#ps-04-02){ data-preview })
                - `PS-05` ([Personnel Transfer](controls/personnel-security.md#ps-05){ data-preview })
                - `PS-06` ([Access Agreements](controls/personnel-security.md#ps-06){ data-preview })
                - `PS-07` ([External Personnel Security](controls/personnel-security.md#ps-07){ data-preview })
                - `PS-08` ([Personnel Sanctions](controls/personnel-security.md#ps-08){ data-preview })
                - `PS-09` ([Position Descriptions](controls/personnel-security.md#ps-09){ data-preview })
            - **Risk Assessment (RA)**
                - `RA-01` ([Policy and Procedures](controls/risk-assessment.md#ra-01){ data-preview })
                - `RA-02` ([Security Categorization](controls/risk-assessment.md#ra-02){ data-preview })
                - `RA-03` ([Risk Assessment](controls/risk-assessment.md#ra-03){ data-preview })
                - `RA-03 (01)` ([Supply Chain Risk Assessment](controls/risk-assessment.md#ra-03-01){ data-preview })
                - `RA-05` ([Vulnerability Monitoring and Scanning](controls/risk-assessment.md#ra-05){ data-preview })
                - `RA-05 (02)` ([Update Vulnerabilities to Be Scanned](controls/risk-assessment.md#ra-05-02){ data-preview })
                - `RA-05 (03)` ([Breadth and Depth of Coverage](controls/risk-assessment.md#ra-05-03){ data-preview })
                - `RA-05 (04)` ([Discoverable Information](controls/risk-assessment.md#ra-05-04){ data-preview })
                - `RA-05 (05)` ([Privileged Access](controls/risk-assessment.md#ra-05-05){ data-preview })
                - `RA-05 (08)` ([Review Historic Audit Logs](controls/risk-assessment.md#ra-05-08){ data-preview })
                - `RA-05 (11)` ([Public Disclosure Program](controls/risk-assessment.md#ra-05-11){ data-preview })
                - `RA-07` ([Risk Response](controls/risk-assessment.md#ra-07){ data-preview })
                - `RA-09` ([Criticality Analysis](controls/risk-assessment.md#ra-09){ data-preview })
            - **System and Services Acquisition (SA)**
                - `SA-01` ([Policy and Procedures](controls/system-and-services-acquisition.md#sa-01){ data-preview })
                - `SA-02` ([Allocation of Resources](controls/system-and-services-acquisition.md#sa-02){ data-preview })
                - `SA-03` ([System Development Life Cycle](controls/system-and-services-acquisition.md#sa-03){ data-preview })
                - `SA-04` ([Acquisition Process](controls/system-and-services-acquisition.md#sa-04){ data-preview })
                - `SA-04 (01)` ([Functional Properties of Controls](controls/system-and-services-acquisition.md#sa-04-01){ data-preview })
                - `SA-04 (02)` ([Design and Implementation Information for Controls](controls/system-and-services-acquisition.md#sa-04-02){ data-preview })
                - `SA-04 (05)` ([System, Component, and Service Configurations](controls/system-and-services-acquisition.md#sa-04-05){ data-preview })
                - `SA-04 (09)` ([Functions, Ports, Protocols, and Services in Use](controls/system-and-services-acquisition.md#sa-04-09){ data-preview })
                - `SA-04 (10)` ([Use of Approved PIV Products](controls/system-and-services-acquisition.md#sa-04-10){ data-preview })
                - `SA-05` ([System Documentation](controls/system-and-services-acquisition.md#sa-05){ data-preview })
                - `SA-08` ([Security and Privacy Engineering Principles](controls/system-and-services-acquisition.md#sa-08){ data-preview })
                - `SA-09` ([External System Services](controls/system-and-services-acquisition.md#sa-09){ data-preview })
                - `SA-09 (01)` ([Risk Assessments and Organizational Approvals](controls/system-and-services-acquisition.md#sa-09-01){ data-preview })
                - `SA-09 (02)` ([Identification of Functions, Ports, Protocols, and Services](controls/system-and-services-acquisition.md#sa-09-02){ data-preview })
                - `SA-09 (05)` ([Processing, Storage, and Service Location](controls/system-and-services-acquisition.md#sa-09-05){ data-preview })
                - `SA-10` ([Developer Configuration Management](controls/system-and-services-acquisition.md#sa-10){ data-preview })
                - `SA-11` ([Developer Testing and Evaluation](controls/system-and-services-acquisition.md#sa-11){ data-preview })
                - `SA-11 (01)` ([Static Code Analysis](controls/system-and-services-acquisition.md#sa-11-01){ data-preview })
                - `SA-11 (02)` ([Threat Modeling and Vulnerability Analyses](controls/system-and-services-acquisition.md#sa-11-02){ data-preview })
                - `SA-15` ([Development Process, Standards, and Tools](controls/system-and-services-acquisition.md#sa-15){ data-preview })
                - `SA-15 (03)` ([Criticality Analysis](controls/system-and-services-acquisition.md#sa-15-03){ data-preview })
                - `SA-16` ([Developer-provided Training](controls/system-and-services-acquisition.md#sa-16){ data-preview })
                - `SA-17` ([Developer Security and Privacy Architecture and Design](controls/system-and-services-acquisition.md#sa-17){ data-preview })
                - `SA-21` ([Developer Screening](controls/system-and-services-acquisition.md#sa-21){ data-preview })
                - `SA-22` ([Unsupported System Components](controls/system-and-services-acquisition.md#sa-22){ data-preview })
            - **System and Communications Protection (SC)**
                - `SC-01` ([Policy and Procedures](controls/system-and-communications-protection.md#sc-01){ data-preview })
                - `SC-02` ([Separation of System and User Functionality](controls/system-and-communications-protection.md#sc-02){ data-preview })
                - `SC-03` ([Security Function Isolation](controls/system-and-communications-protection.md#sc-03){ data-preview })
                - `SC-04` ([Information in Shared System Resources](controls/system-and-communications-protection.md#sc-04){ data-preview })
                - `SC-05` ([Denial-of-service Protection](controls/system-and-communications-protection.md#sc-05){ data-preview })
                - `SC-07` ([Boundary Protection](controls/system-and-communications-protection.md#sc-07){ data-preview })
                - `SC-07 (03)` ([Access Points](controls/system-and-communications-protection.md#sc-07-03){ data-preview })
                - `SC-07 (04)` ([External Telecommunications Services](controls/system-and-communications-protection.md#sc-07-04){ data-preview })
                - `SC-07 (05)` ([Deny by Default — Allow by Exception](controls/system-and-communications-protection.md#sc-07-05){ data-preview })
                - `SC-07 (07)` ([Split Tunneling for Remote Devices](controls/system-and-communications-protection.md#sc-07-07){ data-preview })
                - `SC-07 (08)` ([Route Traffic to Authenticated Proxy Servers](controls/system-and-communications-protection.md#sc-07-08){ data-preview })
                - `SC-07 (10)` ([Prevent Exfiltration](controls/system-and-communications-protection.md#sc-07-10){ data-preview })
                - `SC-07 (12)` ([Host-based Protection](controls/system-and-communications-protection.md#sc-07-12){ data-preview })
                - `SC-07 (18)` ([Fail Secure](controls/system-and-communications-protection.md#sc-07-18){ data-preview })
                - `SC-07 (20)` ([Dynamic Isolation and Segregation](controls/system-and-communications-protection.md#sc-07-20){ data-preview })
                - `SC-07 (21)` ([Isolation of System Components](controls/system-and-communications-protection.md#sc-07-21){ data-preview })
                - `SC-08` ([Transmission Confidentiality and Integrity](controls/system-and-communications-protection.md#sc-08){ data-preview })
                - `SC-08 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-08-01){ data-preview })
                - `SC-10` ([Network Disconnect](controls/system-and-communications-protection.md#sc-10){ data-preview })
                - `SC-12` ([Cryptographic Key Establishment and Management](controls/system-and-communications-protection.md#sc-12){ data-preview })
                - `SC-12 (01)` ([Availability](controls/system-and-communications-protection.md#sc-12-01){ data-preview })
                - `SC-13` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-13){ data-preview })
                - `SC-15` ([Collaborative Computing Devices and Applications](controls/system-and-communications-protection.md#sc-15){ data-preview })
                - `SC-17` ([Public Key Infrastructure Certificates](controls/system-and-communications-protection.md#sc-17){ data-preview })
                - `SC-18` ([Mobile Code](controls/system-and-communications-protection.md#sc-18){ data-preview })
                - `SC-20` ([Secure Name/Address Resolution Service (Authoritative Source)](controls/system-and-communications-protection.md#sc-20){ data-preview })
                - `SC-21` ([Secure Name/Address Resolution Service (Recursive or Caching Resolver)](controls/system-and-communications-protection.md#sc-21){ data-preview })
                - `SC-22` ([Architecture and Provisioning for Name/Address Resolution Service](controls/system-and-communications-protection.md#sc-22){ data-preview })
                - `SC-23` ([Session Authenticity](controls/system-and-communications-protection.md#sc-23){ data-preview })
                - `SC-24` ([Fail in Known State](controls/system-and-communications-protection.md#sc-24){ data-preview })
                - `SC-28` ([Protection of Information at Rest](controls/system-and-communications-protection.md#sc-28){ data-preview })
                - `SC-28 (01)` ([Cryptographic Protection](controls/system-and-communications-protection.md#sc-28-01){ data-preview })
                - `SC-39` ([Process Isolation](controls/system-and-communications-protection.md#sc-39){ data-preview })
                - `SC-45` ([System Time Synchronization](controls/system-and-communications-protection.md#sc-45){ data-preview })
                - `SC-45 (01)` ([Synchronization with Authoritative Time Source](controls/system-and-communications-protection.md#sc-45-01){ data-preview })
            - **System and Information Integrity (SI)**
                - `SI-01` ([Policy and Procedures](controls/system-and-information-integrity.md#si-01){ data-preview })
                - `SI-02` ([Flaw Remediation](controls/system-and-information-integrity.md#si-02){ data-preview })
                - `SI-02 (02)` ([Automated Flaw Remediation Status](controls/system-and-information-integrity.md#si-02-02){ data-preview })
                - `SI-02 (03)` ([Time to Remediate Flaws and Benchmarks for Corrective Actions](controls/system-and-information-integrity.md#si-02-03){ data-preview })
                - `SI-03` ([Malicious Code Protection](controls/system-and-information-integrity.md#si-03){ data-preview })
                - `SI-04` ([System Monitoring](controls/system-and-information-integrity.md#si-04){ data-preview })
                - `SI-04 (01)` ([System-wide Intrusion Detection System](controls/system-and-information-integrity.md#si-04-01){ data-preview })
                - `SI-04 (02)` ([Automated Tools and Mechanisms for Real-time Analysis](controls/system-and-information-integrity.md#si-04-02){ data-preview })
                - `SI-04 (04)` ([Inbound and Outbound Communications Traffic](controls/system-and-information-integrity.md#si-04-04){ data-preview })
                - `SI-04 (05)` ([System-generated Alerts](controls/system-and-information-integrity.md#si-04-05){ data-preview })
                - `SI-04 (10)` ([Visibility of Encrypted Communications](controls/system-and-information-integrity.md#si-04-10){ data-preview })
                - `SI-04 (11)` ([Analyze Communications Traffic Anomalies](controls/system-and-information-integrity.md#si-04-11){ data-preview })
                - `SI-04 (12)` ([Automated Organization-generated Alerts](controls/system-and-information-integrity.md#si-04-12){ data-preview })
                - `SI-04 (14)` ([Wireless Intrusion Detection](controls/system-and-information-integrity.md#si-04-14){ data-preview })
                - `SI-04 (16)` ([Correlate Monitoring Information](controls/system-and-information-integrity.md#si-04-16){ data-preview })
                - `SI-04 (18)` ([Analyze Traffic and Covert Exfiltration](controls/system-and-information-integrity.md#si-04-18){ data-preview })
                - `SI-04 (19)` ([Risk for Individuals](controls/system-and-information-integrity.md#si-04-19){ data-preview })
                - `SI-04 (20)` ([Privileged Users](controls/system-and-information-integrity.md#si-04-20){ data-preview })
                - `SI-04 (22)` ([Unauthorized Network Services](controls/system-and-information-integrity.md#si-04-22){ data-preview })
                - `SI-04 (23)` ([Host-based Devices](controls/system-and-information-integrity.md#si-04-23){ data-preview })
                - `SI-05` ([Security Alerts, Advisories, and Directives](controls/system-and-information-integrity.md#si-05){ data-preview })
                - `SI-05 (01)` ([Automated Alerts and Advisories](controls/system-and-information-integrity.md#si-05-01){ data-preview })
                - `SI-06` ([Security and Privacy Function Verification](controls/system-and-information-integrity.md#si-06){ data-preview })
                - `SI-07` ([Software, Firmware, and Information Integrity](controls/system-and-information-integrity.md#si-07){ data-preview })
                - `SI-07 (01)` ([Integrity Checks](controls/system-and-information-integrity.md#si-07-01){ data-preview })
                - `SI-07 (02)` ([Automated Notifications of Integrity Violations](controls/system-and-information-integrity.md#si-07-02){ data-preview })
                - `SI-07 (05)` ([Automated Response to Integrity Violations](controls/system-and-information-integrity.md#si-07-05){ data-preview })
                - `SI-07 (07)` ([Integration of Detection and Response](controls/system-and-information-integrity.md#si-07-07){ data-preview })
                - `SI-07 (15)` ([Code Authentication](controls/system-and-information-integrity.md#si-07-15){ data-preview })
                - `SI-08` ([Spam Protection](controls/system-and-information-integrity.md#si-08){ data-preview })
                - `SI-08 (02)` ([Automatic Updates](controls/system-and-information-integrity.md#si-08-02){ data-preview })
                - `SI-10` ([Information Input Validation](controls/system-and-information-integrity.md#si-10){ data-preview })
                - `SI-11` ([Error Handling](controls/system-and-information-integrity.md#si-11){ data-preview })
                - `SI-12` ([Information Management and Retention](controls/system-and-information-integrity.md#si-12){ data-preview })
                - `SI-16` ([Memory Protection](controls/system-and-information-integrity.md#si-16){ data-preview })
            - **Supply Chain Risk Management (SR)**
                - `SR-01` ([Policy and Procedures](controls/supply-chain-risk-management.md#sr-01){ data-preview })
                - `SR-02` ([Supply Chain Risk Management Plan](controls/supply-chain-risk-management.md#sr-02){ data-preview })
                - `SR-02 (01)` ([Establish SCRM Team](controls/supply-chain-risk-management.md#sr-02-01){ data-preview })
                - `SR-03` ([Supply Chain Controls and Processes](controls/supply-chain-risk-management.md#sr-03){ data-preview })
                - `SR-05` ([Acquisition Strategies, Tools, and Methods](controls/supply-chain-risk-management.md#sr-05){ data-preview })
                - `SR-06` ([Supplier Assessments and Reviews](controls/supply-chain-risk-management.md#sr-06){ data-preview })
                - `SR-08` ([Notification Agreements](controls/supply-chain-risk-management.md#sr-08){ data-preview })
                - `SR-09` ([Tamper Resistance and Detection](controls/supply-chain-risk-management.md#sr-09){ data-preview })
                - `SR-09 (01)` ([Multiple Stages of System Development Life Cycle](controls/supply-chain-risk-management.md#sr-09-01){ data-preview })
                - `SR-10` ([Inspection of Systems or Components](controls/supply-chain-risk-management.md#sr-10){ data-preview })
                - `SR-11` ([Component Authenticity](controls/supply-chain-risk-management.md#sr-11){ data-preview })
                - `SR-11 (01)` ([Anti-counterfeit Training](controls/supply-chain-risk-management.md#sr-11-01){ data-preview })
                - `SR-11 (02)` ([Configuration Control for Component Service and Repair](controls/supply-chain-risk-management.md#sr-11-02){ data-preview })
                - `SR-12` ([Component Disposal](controls/supply-chain-risk-management.md#sr-12){ data-preview })
        


    **Reference:** [NIST SP 800-53 Rev. 5, Security and Privacy Controls for Information Systems and Organizations](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)

    ---
    **Terms:** [Security Decision Record (SDR)](../definitions/#security-decision-record-sdr){ data-preview }
### Assign Control Parameters

??? abstract "FRC-CSF-ACP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST assign all organization-defined control parameters, following FedRAMP Rev5 Controls Guidance, and ensure that all control parameter assignments are documented in the Security Decision Record (SDR).


    ---
    **Terms:** [Security Decision Record (SDR)](../definitions/#security-decision-record-sdr){ data-preview }
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
