---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Security Decision Record

The Security Decision Record replaced a traditional System Security Plan with a persistently maintained, verified, and validated record of the security decisions made by the cloud service provider over the lifecycle of their cloud service offering.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)



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
    **Terms:** [Artifacts](../../../definitions/#artifacts){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Security Decision Record Metadata

??? abstract "SDR-CSO-MTD"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST also include the following basic metadata in their Security Decision Record:

    1. Version
    1. Date and time of last update
    1. Source of update


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
    **Terms:** [Artifacts](../../../definitions/#artifacts){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Organization-Defined Parameters

??? abstract "SDR-CSF-ODP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST define all required organization-defined parameters tied all Rev5 Controls, following FedRAMP Rules if applicable, UNLESS the parameter is assigned by FedRAMP.
