---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Security Decision Record

The Security Decision Record replaced a traditional System Security Plan with a persistently maintained, verified, and validated record of the security decisions made by the cloud service provider over the lifecycle of their cloud service offering.

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
    - **Maintain:** 2027-08-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-08-01
    - **Sign-up Form:** [ADDME](ADDME)



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications of any type.

### FedRAMP Rules

??? abstract "SDR-CSO-FRR"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! schema "Related JSON Schema: [FedRAMP Security Decision Record Schema](https://fedramp.gov/schemas/fedramp-security-decision-record-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    Providers MUST supply a Security Decision Record, in both human-readable and JSON formats, that includes at least all of the following information for each applicable FedRAMP Rule:

    1. Explanation of how the rule is followed, or an explanation of the reason and resulting risk to customers for not following the rule.
    1. Verification that the implementation is appropriate for the rule, or that the reason for not implementing is accepted by a senior official.
    1. Validation that the implementation is in place and working as intended, or that the reason for not implementing is accepted by a senior official.
    1. Independent verification.
    1. Independent validation.
    1. Any responses or clarifications to the comments in the independent verification or validation.
    1. Rule-specific artifacts (if applicable).


    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Security Decision Record Metadata

??? abstract "SDR-CSO-MTD"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST also include the following basic metadata in their Security Decision Record:

    1. Version
    1. Date and time of last update
    1. Source of update


## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

### Key Security Indicators

??? abstract "SDR-CSX-KSI"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! schema "Related JSON Schema: [FedRAMP Security Decision Record Schema](https://fedramp.gov/schemas/fedramp-security-decision-record-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    Providers MUST also include short and simple high-level summaries of at least the following for each applicable Key Security Indicator:

    1. Explanation of measures (and their objectives) that demonstrate the Key Security Indicator, or an explanation of the reason and resulting risk to customers for not having measures available for that Key Security Indicator.
    1. Explanation of the cycle for any measures that are implemented persistently (if applicable).
    1. Verification that the measures demonstrate the Key Security Indicator, or that the reason for not having them is accepted.
    1. Verification that the automation in place is accurate and sufficient to demonstrate appropriate measures for the Key Security Indicator, or that automation is not necessary for each measure.
    1. Validation that the measures are accurately produced and are in place and working as intended, or that the reason for not having them is valid.


    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Key Security Indicator Metrics

??? abstract "SDR-CSX-KMT"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! schema "Related JSON Schema: [FedRAMP Security Decision Record Schema](https://fedramp.gov/schemas/fedramp-security-decision-record-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    === "Class A"
        Providers with 20x Class A Certifications MAY also include historical metrics in their Security Decision Record.

    === "Class B"
        Providers with 20x Class B Certifications MUST also include historical metrics in their Security Decision Record, supplying at least the following information for each applicable Key Security Indicator:

        1. Summary of each metric over the past 30 days
        1. Summary of metric up to the past year (where available)

    === "Class C"
        Providers with 20x Class C Certifications MUST also include historical metrics in their Security Decision Record, supplying at least the following information for each applicable Key Security Indicator:

        1. Summary of each metric over the past 30 days
        1. Summary of metric up to the past year (where available)
        1. All daily metric data up to the past year (where available)

    === "Class D"
        Providers with 20x Class D Certifications MUST significantly supersede the minimum requirements for lower Classes, with specifics to be set during the 20x Phase 4 Pilot.


## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### Rev5 Controls

??? abstract "SDR-CSF-CTF"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST also include short and simple high-level summaries of at least the following for each applicable Rev5 Control:

    1. Any organization-defined parameter values.
    1. Implementation status, one of Implemented, Partially Implemented, Planned, Alternative Implementation, or Not Applicable.
    1. The mechanisms or activities that address the control, including inheritance from another cloud service offering if applicable.
    1. The verification that is in place to ensure the implementation is appropriate for the control.
    1. The validation that is in place to ensure the implementation is working as intended.
    1. Independent verification.
    1. Independent validation.
    1. Any responses or clarifications to the comments in the independent verification or validation.
    1. Control-specific artifacts (if applicable).


    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Organization-Defined Parameters

??? abstract "SDR-CSF-ODP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST define all required organization-defined parameters tied all Rev5 Controls, following FedRAMP Rules if applicable, UNLESS the parameter is assigned by FedRAMP.
