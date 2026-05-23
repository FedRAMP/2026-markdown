---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# FedRAMP Certification

The FedRAMP Certification rules define how cloud service offerings obtain and maintain FedRAMP Certification across certification classes and paths. They give providers, assessors, agencies, and FedRAMP a common set of expectations for required rule sets, current evidence, independent verification and validation, and ongoing certification decisions.

**Rule Sections**

- [CSX](#csx)
- [FedRAMP Class A Certification Rules](#fedramp-class-a-certification-rules)


---


## CSX {#csx}

### Implementation Summaries

??? abstract "FRC-CSX-SUM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST maintain simple high-level summaries of at least the following for each Key Security Indicator:

    1. Goals for how it will be implemented and validated, including clear pass/fail criteria and traceability
    1. The consolidated _information resources_ that will be validated (this should include consolidated summaries such as "all employees with privileged access that are members of the Admin group")
    1. The machine-based processes for _validation_ and the _persistent_ cycle on which they will be performed (or an explanation of why this doesn't apply)
    1. The non-machine-based processes for _validation_ and the _persistent_ cycle on which they will be performed (or an explanation of why this doesn't apply)
    1. Current implementation status
    1. Any clarifications or responses to the assessment summary


    ---
    **Terms:** [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Application within MAS

??? abstract "FRC-CSX-MAS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }
### Persistent Machine Verification and Validation

??? abstract "FRC-CSX-PMV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    === "Class A"
        Providers of FedRAMP 20x Class A offerings SHOULD verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month

    === "Class B"
        Providers of FedRAMP 20x Class B offerings MUST verify and validate the status of machine-based information resources at least once every 7 days.

        **Timeframe:** 7 days

    === "Class C"
        Providers of FedRAMP 20x Class C offerings MUST verify and validate the status of machine-based information resources at least once every 3 days.

        **Timeframe:** 3 days


    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These rules apply to providers seeking FedRAMP Class A Certifications.

### Key Security Indicator Mapping

??? abstract "FRC-CLA-KSM"
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
