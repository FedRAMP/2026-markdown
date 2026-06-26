---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Security Decision Record

The Security Decision Record replaced a traditional System Security Plan with a persistently maintained, verified, and validated record of the security decisions made by the cloud service provider over the lifecycle of their cloud service offering.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-08-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-08-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### FedRAMP Rules

??? abstract "SDR-CSO-FRR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Security Decision Record Schema](https://fedramp.gov/schemas/fedramp-security-decision-record-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST supply a Security Decision Record, in both human-readable and JSON formats, that includes at least all of the following information for each applicable FedRAMP rule:

    1. Explanation of how the rule is followed, or an explanation of the reason and resulting risk to customers for not following the rule.
    1. Verification that the implementation is appropriate for the rule, or that the reason for not implementing is accepted by a senior official.
    1. Validation that the implementation is in place and working as intended, or that the reason for not implementing is accepted by a senior official.
    1. Independent verification.
    1. Independent validation.
    1. Any responses or clarifications to the comments in the independent verification or validation.
    1. Rule-specific artifacts (if applicable).


    ---
    **Terms:** [Artifacts](../../../definitions/#artifacts){ data-preview }, [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Security Decision Record Metadata

??? abstract "SDR-CSO-MTD"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST also include the following basic metadata in their Security Decision Record:

    1. Version
    1. Date and time of last update
    1. Source of update


    ---
    **Terms:** [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Rev5 Controls

??? abstract "SDR-CSF-CTF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




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
