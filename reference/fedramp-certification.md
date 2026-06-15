---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

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
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

### FedRAMP Certification Profile

??? abstract "FRC-CSO-FCP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST identify a target FedRAMP Certification Profile and apply all relevant FedRAMP Practices to the cloud service offering.


    ---

    _**Note:** Information resources (including third-party information resources) MAY vary by security category as appropriate to the type of information handled by or impacted by the information resource._

    ---
    **Terms:** [Certification Profile](../definitions/#certification-profile){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../definitions/#fedramp-practices){ data-preview }, [Handle](../definitions/#handle){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Security Category](../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../definitions/#third-party-information-resource){ data-preview }
### FedRAMP Certification Package

??? abstract "FRC-CSO-PKG"
    **Changelog:**


    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers seeking a Class A Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. An External Framework Mapping

    === "Class B"
        Providers seeking a Class B Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }

    === "Class C"
        Providers seeking a Class C Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }

    === "Class D"
        Providers seeking a Class D Certification MUST supply a complete FedRAMP Certification Package to FedRAMP for initial certification; the FedRAMP Certification Package MUST include at least the following information:

        1. A Certification Package Overview
        1. A Security Decision Record
        1. A real or example Ongoing Certification Report following [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Initial Certification](../definitions/#initial-certification){ data-preview }
### FedRAMP JSON Schemas

??? abstract "FRC-CSO-JSN"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply machine-readable information in JSON documents that are valid against the corresponding JSON schema when a rule contains a FedRAMP JSON schema, UNLESS otherwise specified in the rule.


    ---

    _**Note:** FedRAMP JSON schemas are designed to be lightweight and flexible to establish a minimum set of structured information while allowing providers to improve on the format and structure of the information as needed to meet their needs and the needs of their customers._

    ---
    **Terms:** [Machine-Readable](../definitions/#machine-readable){ data-preview }
### Maintain Responsibility and Accountability

??? abstract "FRC-CSO-MRA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST maintain responsibility and accountability for the accuracy and completeness of all information in the FedRAMP Certification Package, especially when they engage a third party (such as an independent assessor, advisory service, or external tools) to supply information on their behalf.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }
### Pick One Program Certification Type

??? abstract "FRC-CSO-POP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST NOT seek both FedRAMP Rev5 Program Certification and FedRAMP 20x Program Certification for the same cloud service offering; pick one type.


    ---

    _**Note:** This rule does not prevent a provider from seeking and maintaining a FedRAMP Rev5 Agency Certification and a FedRAMP 20x Program Certification for the same cloud service offering, however, doing so is strongly discouraged due to the increased complexity and risk of confusion for all parties._

    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These are specific rules that apply to providers seeking FedRAMP Class A Certifications.

### Approved Alternative Security Frameworks

??? abstract "FRC-CLA-ASF"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST have completed a certification or equivalent process, including an independent assessment if applicable, from one of the following alternative security frameworks:

    1. FedRAMP Rev5 (including FedRAMP Ready) at any historical Impact Level
    1. SOC 2 Type II
    1. GovRAMP at any Impact Level


    ---
    **Terms:** [Security Category](../definitions/#security-category){ data-preview }
### External Assessment Materials

??? abstract "FRC-CLA-EAM"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST supply the full materials from the alternative security assessment to all necessary parties as part of the FedRAMP Certification Package.


    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }
### Address FedRAMP Rules for Class A

??? abstract "FRC-CLA-AFR"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a Class A FedRAMP Certification of any Type MUST address all rules in this FedRAMP Class A Certification subset (FRC-CLA) AND the following additional FedRAMP rules; the appropriate artifacts or information mapping for all rules MUST be supplied in the FedRAMP Certification Package.

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
    1. Vulnerability Detection and Response: [VDR-CSO-DET (Vulnerability Detection)](vulnerability-detection-and-response.md#vulnerability-detection){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }
    1. Collaborative Continuous Monitoring: [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview }
    1. Key Security Indicators: [KSI-CMT-LMC (Logging Changes)](key-security-indicators.md#logging-changes){ data-preview }
    1. Key Security Indicators: [KSI-CNA-RNT (Restricting Network Traffic)](key-security-indicators.md#restricting-network-traffic){ data-preview }
    1. Key Security Indicators: [KSI-CED-RAT (Reviewing All Training)](key-security-indicators.md#reviewing-all-training){ data-preview }
    1. Key Security Indicators: [KSI-IAM-AAM (Automating Account Management)](key-security-indicators.md#automating-account-management){ data-preview }
    1. Key Security Indicators: [KSI-INR-RIR (Reviewing Incident Response Procedures)](key-security-indicators.md#reviewing-incident-response-procedures){ data-preview }
    1. Key Security Indicators: [KSI-SVC-SIN (Securing Information)](key-security-indicators.md#securing-information){ data-preview }


    ---

    _**Notes:**_

    - _Some of these specific FedRAMP rules may not have similar counterparts in external frameworks and providers will need to implement new processes to follow these rules._
    - _In general, for each of these FedRAMP requirements, providers should include a sufficiently detailed summary that reviewers will not need to dig into the related security framework materials to understand the related decisions - just saying "see SOC 2 report" is not particularly helpful._
    - _Information about how the provider addresses the included Key Security Indicators are required for both Rev5 and 20x Class A Certifications._
    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }, [Certification Type](../definitions/#certification-type){ data-preview }, [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
### Optional Independent Verification and Validation

??? abstract "FRC-CLA-IVV"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Class A Certification MAY have the FedRAMP Certification Package independently verified and validated by a FedRAMP Recognized assessor before submission to FedRAMP.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Marketplace Listing First

??? abstract "FRC-APP-MLF"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST be listed in the FedRAMP Marketplace before applying for FedRAMP Certification, including:

    1. FedRAMP Marketplace: [MKT-CSO-MLR (Marketplace Listing Requirements)](marketplace-listing.md#marketplace-listing-requirements){ data-preview },
    1. FedRAMP Marketplace: [MKT-CSO-PML (Provider Marketplace Listing Requests)](marketplace-listing.md#provider-marketplace-listing-requests){ data-preview }
    1. FedRAMP Marketplace: [MKT-IIP-AGU (Agency Use Cases)](marketplace-listing.md#agency-use-cases){ data-preview }
    1. FedRAMP Marketplace: [MKT-IIP-DCP (Demonstrating Continuous Progress)](marketplace-listing.md#demonstrating-continuous-progress){ data-preview }


### Applying for FedRAMP Certification

??? abstract "FRC-APP-AFC"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST complete the FedRAMP Certification Application Form at https://fedramp.gov/forms/provider-listing-request/ in full to request an initial assessment by FedRAMP.



    **Reference:** [FedRAMP Certification Application Form](https://fedramp.gov/forms)

### Fresh FedRAMP Certification Package

??? abstract "FRC-APP-FCP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply a fresh initial FedRAMP Certification Package that shows the current status of the cloud service offering as verified and validated by the provider within the previous 7 days.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Fresh Independent Assessment

??? abstract "FRC-APP-FIA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized Independent Assessment Service within the previous 3 months.


    ---
    **Terms:** [FedRAMP Independent Assessment](../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }
### No Third-Party Applicants

??? abstract "FRC-APP-NTP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST NOT use a third party to apply for a FedRAMP Certification on their behalf; this includes independent assessment services.


    ---

    _**Notes:**_

    - _FedRAMP previously allowed independent assessment services to submit applications on behalf of providers, but this caused confusion about who was responsible for the application and the information in it. Providers should apply directly to ensure clear accountability._
    - _Providers may use third parties to help them prepare their application and assessment materials for submission._
### Updating Stale Assessments

??? abstract "FRC-APP-USA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY freshen a stale initial independent verification and validation assessment by having a FedRAMP Recognized independent assessment service review any changes between the original assessment and the current status of the cloud service offering in place of a full re-assessment, UNLESS the stale assessment is more than 9 months old.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification with an Agency Sponsor {#applying-for-fedramp-certification-with-an-agency-sponsor}

These rules apply to cloud service providers with an Agency Sponsor who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Agency Authorization to Operate

??? abstract "FRC-APS-ATO"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers seeking a FedRAMP Rev5 Agency Certification MUST have completed the Authorization to Operate (ATO) process with their agency sponsor for the cloud service offering, concluding with a formal signed ATO letter that the agency has sent over official government channels to FedRAMP.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## Changing Certification Class {#changing-certification-class}

These rules apply to cloud service providers when changing their FedRAMP Certification Class.

### Placeholder on Changing Certification Class

??? abstract "FRC-CCL-PLC"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST do things properly in order to change their FedRAMP Certification Class.


    ---

    _**Note:** This is a placeholder rule that must be updated!_

    ---
    **Terms:** [Certification Class](../definitions/#certification-class){ data-preview }
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

### Application within MAS

??? abstract "FRC-CSX-MAS"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### FedRAMP Ready Conversion

??? abstract "FRC-CSF-RDY"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers with FedRAMP Rev5 Ready status MUST convert to a FedRAMP Certification before the furthest date of the expiration of their most recently yearly assessment or November 17, 2026; the legacy FedRAMP Ready status will be entirely removed on December 31, 2027.


    ---

    _**Notes:**_

    - _The simplest conversion in most cases would be to a FedRAMP Rev5 Class A Certification._
    - _Cloud services that do not wish to convert or do not meet conversion criteria will be renamed Legacy FedRAMP Ready and otherwise retired from FedRAMP Ready._
