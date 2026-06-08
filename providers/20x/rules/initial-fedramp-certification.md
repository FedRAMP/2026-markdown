---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Initial FedRAMP Certification

This ruleset explains how cloud service offerings obtain initial FedRAMP Certification across certification classes and paths.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [FedRAMP Class A Certification Rules](#fedramp-class-a-certification-rules)
- [Applying for FedRAMP Certification](#applying-for-fedramp-certification)
- [Applying for FedRAMP Certification with an Agency Sponsor](#applying-for-fedramp-certification-with-an-agency-sponsor)
- [20x-Specific Provider Responsibilities](#20x-specific-provider-responsibilities)



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

### FedRAMP Certification Package

??? abstract "IFR-CSO-PKG"
    **Changelog:**


    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers seeking a Class A Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification, aligned to the requirements for the target Certification Type, Class, and Path; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. An External Framework Mapping

    === "Class B"
        Providers seeking a Class B Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification, aligned to the requirements for the target Certification Type, Class, and Path; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }

    === "Class C"
        Providers seeking a Class C Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification, aligned to the requirements for the target Certification Type, Class, and Path; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }

    === "Class D"
        Providers seeking a Class D Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification, aligned to the requirements for the target Certification Type, Class, and Path; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Initial Certification](../../../definitions/#initial-certification){ data-preview }
### FedRAMP JSON Schemas

??? abstract "IFR-CSO-JSN"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply machine-readable information in JSON documents that are valid against the corresponding JSON schema when a rule contains a FedRAMP JSON schema, UNLESS otherwise specified in the rule.


    ---

    _**Note:** FedRAMP JSON schemas are designed to be lightweight and flexible to establish a minimum set of structured information while allowing providers to improve on the format and structure of the information as needed to meet their needs and the needs of their customers._

    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### Maintain Responsibility and Accountability

??? abstract "IFR-CSO-MRA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST maintain responsibility and accountability for the accuracy and completeness of all information in the FedRAMP Certification Package, especially when they engage a third party (such as an independent assessor, advisory service, or external tools) to supply information on their behalf.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
### Pick One Program Certification Type

??? abstract "IFR-CSO-POP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST NOT seek both FedRAMP Rev5 Program Certification and FedRAMP 20x Program Certification for the same cloud service offering; pick one type.


    ---

    _**Note:** This rule does not prevent a provider from seeking and maintaining a FedRAMP Rev5 Agency Certification and a FedRAMP 20x Program Certification for the same cloud service offering, however, doing so is strongly discouraged due to the increased complexity and risk of confusion for all parties._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These are specific rules that apply to providers seeking FedRAMP Class A Certifications.

### Approved Alternative Security Frameworks

??? abstract "IFR-CLA-ASF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST have completed a certification or equivalent process, including an independent assessment, from one of the following alternative security frameworks:

    1. FedRAMP Rev5 (including FedRAMP Ready) at any historical Impact Level
    1. SOC 2 Type II
    1. GovRAMP at any Impact Level


    ---
    **Terms:** [Security Category](../../../definitions/#security-category){ data-preview }
### External Assessment Materials

??? abstract "IFR-CLA-EAM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST supply the full materials from the alternative security assessment to all necessary parties as part of the FedRAMP Certification Package.


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }
### Address FedRAMP Rules for Class A

??? abstract "IFR-CLA-AFR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification of any Type MUST address all rules in this FedRAMP Class A Certification subset (IFR-CLA) AND the following additional FedRAMP rules; the appropriate artifacts or information mapping for all rules MUST be supplied in the FedRAMP Certification Package.

    1. FedRAMP Certification: [IFR-CSO-PKG (FedRAMP Certification Package)](#fedramp-certification-package){ data-preview }
    1. FedRAMP Certification: [IFR-CSO-JSN (FedRAMP JSON Schemas)](#fedramp-json-schemas){ data-preview }
    1. FedRAMP Certification: [IFR-CSO-POP (Pick One Program Certification Type)](#pick-one-program-certification-type){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-IIR (Identify Information Resources)](minimum-assessment-scope.md#identify-information-resources){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PUB (Public Information)](certification-data-sharing.md#public-information){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-UTC (Use Trust Centers)](certification-data-sharing.md#use-trust-centers){ data-preview }
    1. Certification Data Sharing: [CDS-UTC-AAD (Agency Access Denial)](certification-data-sharing.md#agency-access-denial){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-INB (Maintain a FedRAMP Security Inbox)](fedramp-security-inbox.md#maintain-a-fedramp-security-inbox){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-RCV (Receive Email Without Disruption)](fedramp-security-inbox.md#receive-email-without-disruption){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-CRA (Complete Required Actions)](fedramp-security-inbox.md#complete-required-actions){ data-preview }
    1. Incident Communications Procedures: [ICP-CSO-EFR (Evaluate FedRAMP Reportability)](incident-communications-procedures.md#evaluate-fedramp-reportability){ data-preview }
    1. Vulnerability Detection and Response: [VDR-CSO-DET (Vulnerability Detection)](vulnerability-detection-and-response.md#vulnerability-detection){ data-preview }
    1. Continuous Collaborative Monitoring: [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }
    1. Continuous Collaborative Monitoring: [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview }
    1. Key Security Indicators: KSI-CMT-LMC (Logging Changes)
    1. Key Security Indicators: KSI-CNA-RNT (Restricting Network Traffic)
    1. Key Security Indicators: KSI-CED-RAT (Reviewing All Training)
    1. Key Security Indicators: KSI-IAM-AAM (Automating Account Management)
    1. Key Security Indicators: KSI-INR-RIR (Reviewing Incident Response Procedures)
    1. Key Security Indicators: KSI-SVC-SNT (Securing Network Traffic)


    ---

    _**Notes:**_

    - _Some of these specific FedRAMP rules may not have similar counterparts in external frameworks and providers will need to implement new processes to follow these rules._
    - _In general, for each of these FedRAMP requirements, providers should include a sufficiently detailed summary that reviewers will not need to dig into the related security framework materials to understand the related decisions - just saying "see SOC 2 report" is not particularly helpful._
    - _Information about how the provider addresses the included Key Security Indicators are required for both Rev5 and 20x Class A Certifications._
    ---
    **Terms:** [Artifacts](../../../definitions/#artifacts){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Optional Independent Verification and Validation

??? abstract "IFR-CLA-IVV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MAY have the FedRAMP Certification Package independently verified and validated by a FedRAMP Recognized assessor before submission to FedRAMP.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Key Security Indicator Mapping

??? abstract "IFR-CLA-KSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP 20x Certification Class A by leveraging an alternative security framework MUST supply a temporary mapping from the alternative security assessment to the following FedRAMP Key Security Indicators:

    1. KSI-CMT-LMC
    1. KSI-CNA-RNT
    1. KSI-CED-RAT
    1. KSI-IAM-AAM
    1. KSI-INR-RIR
    1. KSI-SVC-SNT


    ---

    _**Notes:**_

    - _The mapping must be available in both machine-readable and human-readable formats._
    - _If a mapping is not clear, the provider should supply new information indicating that the Key Security Indicator has not been independently audited._
    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Marketplace Listing First

??? abstract "IFR-APP-MLF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST be listed in the FedRAMP Marketplace before applying for FedRAMP Certification.


    ---

    _**Note:** See FedRAMP's Marketplace Listing rules for information about being listed in the Marketplace in the Initial Implementation Phase prior to receiving a formal FedRAMP Certification._

### Applying for FedRAMP Certification

??? abstract "IFR-APP-AFC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST complete the FedRAMP Certification Application Form at https://fedramp.gov/forms/provider-listing-request/ in full to request an initial assessment by FedRAMP.



    **Reference:** [FedRAMP Certification Application Form](https://fedramp.gov/forms)

### Fresh FedRAMP Certification Package

??? abstract "IFR-APP-FCP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply a fresh initial FedRAMP Certification Package that shows the current status of the cloud service offering as verified and validated by the provider within the previous 7 days.


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Fresh Independent Assessment

??? abstract "IFR-APP-FIA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply a fresh initial independent verification and validation assessment that was completed by a FedRAMP Recognized Independent Assessment Service within the previous 3 months.


    ---
    **Terms:** [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### No Third-Party Applications

??? abstract "IFR-APP-NTP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST NOT use a third party to apply for a FedRAMP Certification on their behalf; this includes independent assessment services.


    ---

    _**Notes:**_

    - _FedRAMP previously allowed independent assessment services to submit applications on behalf of providers, but this caused confusion about who was responsible for the application and the information in it. Providers should apply directly to ensure clear accountability._
    - _Providers may use third parties to help them prepare their application and assessment materials for submission._
### Updating Stale Assessments

??? abstract "IFR-APP-USA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY freshen a stale initial independent verification and validation assessment by having a FedRAMP Recognized Independent Assessment Service review any changes between the original assessment and the current status of the cloud service offering in place of a full re-assessment, UNLESS the stale assessment is more than 9 months old.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification with an Agency Sponsor {#applying-for-fedramp-certification-with-an-agency-sponsor}

These rules apply to cloud service providers with an Agency Sponsor who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Agency Authorization to Operate

??? abstract "IFR-APS-ATO"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Rev5 Agency Certification MUST have completed the Authorization to Operate (ATO) process with their agency sponsor for the cloud service offering, concluding with a formal signed ATO letter that the agency has sent over official government channels to FedRAMP.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

### Initial Implementation Summaries

??? abstract "IFR-CSX-SUM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply simple high-level summaries of at least the following for each Key Security Indicator:

    1. Goals for how it will be implemented and validated, including clear pass/fail criteria and traceability
    1. The consolidated _information resources_ that will be validated (this should include consolidated summaries such as "all employees with privileged access that are members of the Admin group")
    1. The machine-based processes for _validation_ and the _persistent_ cycle on which they will be performed (or an explanation of why this doesn't apply)
    1. The non-machine-based processes for _validation_ and the _persistent_ cycle on which they will be performed (or an explanation of why this doesn't apply)
    1. Current implementation status
    1. Any clarifications or responses to the assessment summary


    ---
    **Terms:** [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Application within MAS

??? abstract "IFR-CSX-MAS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
