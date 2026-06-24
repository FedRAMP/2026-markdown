---
tags:
  - 20x
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Certification Package Overview

The Certification Package Overview rules outline the expectations for a simple overview of the cloud service offering that must be included within a FedRAMP Certification Package. This overview replaces the historically required base System Security Plan for FedRAMP Rev5 and is intended to provide a clear, concise, and consistent summary of the offering and the information included in the package to help customers understand the offering at a high level.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
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
    - **Maintain:** 2027-07-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Overview of the Cloud Service Offering

??? abstract "CPO-CSO-OVR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Certification Package Overview Schema](https://fedramp.gov/schemas/fedramp-certification-package-overview-schema-v2026.06.06.01.json)"


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
    **Terms:** [Certification Class](../definitions/#certification-class){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../definitions/#initial-incident-report-iir){ data-preview }, [Security Category](../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../definitions/#third-party-information-resource){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Certification Package Overview Metadata

??? abstract "CPO-CSO-MTD"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST also include the following basic metadata in their Certification Package Overview:

    1. Name, title, and contact information of official that is responsible and accountable for the FedRAMP Certification Package
    1. Version
    1. Date and time of last update
    1. Source of update


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Certification Package Maintenance for 20x

??? abstract "CPO-CSX-CPM"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with 20x Class A Certifications SHOULD persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every 3 months.

        **Timeframe:** 3 months

    === "Class B"
        Providers with 20x Class B Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every month.

        **Timeframe:** 1 month

    === "Class C"
        Providers with 20x Class C Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every 2 weeks.

        **Timeframe:** 2 weeks

    === "Class D"
        Providers with 20x Class D Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every week.

        **Timeframe:** 1 week


    ---

    _**Notes:**_

    - _Providers are expected to maintain their FedRAMP Certification Package using automation as changes occur to ensure they are never out of date._
    - _This rule does not require or expect persistent human review of all materials in this cadence._
    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Certification Package Maintenance for Rev5

??? abstract "CPO-CSF-CPM"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Rev5 Class A Certifications SHOULD persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every year.

        **Timeframe:** 1 year

    === "Class B"
        Providers with Rev5 Class B Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every year.

        **Timeframe:** 1 year

    === "Class C"
        Providers with Rev5 Class C Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every year.

        **Timeframe:** 1 year

    === "Class D"
        Providers with Rev5 Class D Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every six months.

        **Timeframe:** 6 months


    ---

    _**Notes:**_

    - _This maximum timeframe for Rev5 is the absolutely poorest worst case for horrible customer experience and is based on legacy FedRAMP Rev5 allowing providers to leave their packages unmaintained for up to a year. Rev5 providers should maintain their packages far more frequently than this requirement to ensure potential customers have access to up-to-date information, updating it at least after every transformative significant change._
    - _FedRAMP 20x Certifications expect providers to maintain their FedRAMP Certification Packages as changes occur to ensure they are never out of date._
    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }, [Significant Change](../definitions/#significant-change){ data-preview }, [Transformative Change](../definitions/#transformative-change){ data-preview }
