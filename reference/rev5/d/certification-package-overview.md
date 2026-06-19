---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Certification Package Overview

The Certification Package Overview rules outline the expectations for a simple overview of the cloud service offering that must be included within a FedRAMP Certification Package. This overview replaces the historically required base System Security Plan for FedRAMP Rev5 and is intended to provide a clear, concise, and consistent summary of the offering and the information included in the package to help customers understand the offering at a high level.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-07-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications of any type.

### Overview of the Cloud Service Offering

??? abstract "CPO-CSO-OVR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Certification Package Overview Schema](https://fedramp.gov/schemas/fedramp-certification-package-overview-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    Providers MUST supply a Certification Package Overview within their FedRAMP Certification Package, in both human-readable and JSON formats, that includes at least all of the information required by the following rules:

    1. Certification Package Overview: [CPO-CSO-MTD (Certification Package Overview Metadata)](#certification-package-overview-metadata){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PUB (Public Information)](certification-data-sharing.md#public-information){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-SVC (Public Service List)](certification-data-sharing.md#public-service-list){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-IRP (Include Relevant Policies)](certification-data-sharing.md#include-relevant-policies){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-IIR (Identify Information Resources)](minimum-assessment-scope.md#identify-information-resources){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-FLO (Information Flows and Security Categories)](minimum-assessment-scope.md#information-flows-and-security-categories){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-TPR (Third-Party Information Resources)](minimum-assessment-scope.md#third-party-information-resources){ data-preview }
    1. Using Cryptographic Modules: [CMU-CSO-CMD (Cryptographic Module Documentation)](cryptographic-module-use.md#cryptographic-module-documentation){ data-preview }
    1. Independent Verification and Validation: [IVV-CSO-ICP (Inclusion in Certification Package)](independent-verification-and-validation.md#inclusion-in-certification-package){ data-preview }


    ---

    _**Notes:**_

    - _For FedRAMP Rev5, the Certification Package Overview replaces the historically required System Security Plan (not including appendices)._
    - _This list of rules may not apply to all FedRAMP Certification Classes or Types - if a rule does not apply then the information is not required._
    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../../../definitions/#third-party-information-resource){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Certification Package Overview Metadata

??? abstract "CPO-CSO-MTD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST also include the following basic metadata in their Certification Package Overview:

    1. Name, title, and contact information of official that is responsible and accountable for the FedRAMP Certification Package
    1. Version
    1. Date and time of last update
    1. Source of update


    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### Certification Package Maintenance for Rev5

??? abstract "CPO-CSF-CPM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class D"
        Providers with Rev5 Class D Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every six months.

        **Timeframe:** 6 months


    ---

    _**Notes:**_

    - _This maximum timeframe for Rev5 is the absolutely poorest worst case for horrible customer experience and is based on legacy FedRAMP Rev5 allowing providers to leave their packages unmaintained for up to a year. Rev5 providers should maintain their packages far more frequently than this requirement to ensure potential customers have access to up-to-date information, updating it at least after every transformative significant change._
    - _FedRAMP 20x Certifications expect providers to maintain their FedRAMP Certification Packages as changes occur to ensure they are never out of date._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
