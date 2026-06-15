---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Independent Verification and Validation

This ruleset explains the expectations for independent verification and validation assessments.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [20x-Specific Provider Responsibilities](#20x-specific-provider-responsibilities)



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

### FedRAMP Independent Assessments

??? abstract "IVV-CSO-FIA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY persistently complete an independent verification and validation assessment of all applicable FedRAMP Rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 years

    === "Class B"
        Providers with Class B Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP Rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 years

    === "Class C"
        Providers with Class C Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP Rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 years

    === "Class D"
        Providers with Class D Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP Rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 years


    ---

    _**Notes:**_

    - _The first such completed assessment is typically called an "initial assessment" while following assessments are called "annual assessments."_
    - _The specific requirements for independent verification and validation assessments are documented by the FedRAMP Certification Class and Type._
    - _The option for assessment by FedRAMP directly is limited to cloud services that are explicitly prioritized by FedRAMP, in consultation with the FedRAMP Board and the federal Chief Information Officers Council; this is _extremely_ rare._
    - _FedRAMP Recognized independent assessment services are listed on the FedRAMP Marketplace._
    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Evidence of Implementation

??? abstract "IVV-CSO-SEI"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the implementation of the measures that have been documented to meet FedRAMP Practices; this evidence is the result of verification.


    ---

    _**Note:** For example, if the documentation says that firewall rules are used to block traffic then the cloud service provider would verify that firewall rules are in place to block traffic and supply that evidence to assessors (preferably by allowing them to see how firewall configurations are deployed from a source of truth)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Evidence of Effectiveness

??? abstract "IVV-CSO-SEE"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the effectiveness of the measures that have been implemented to meet FedRAMP Practices; this evidence is the result of validation.


    ---

    _**Note:** For example, after verifying that firewalls are configured to block traffic following [IVV-CSO-SEI (Supply Evidence of Implementation)](#supply-evidence-of-implementation){ data-preview }, the provider would validate that traffic is actually being blocked and supply evidence of that validation to assessors (such as by allowing them to see metrics on the traffic that is blocked vs not)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Inclusion in Certification Package

??? abstract "IVV-CSO-ICP"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST supply the results of FedRAMP independent assessments in their FedRAMP Certification Package without inappropriate modification.


    ---

    _**Notes:**_

    - _Inappropriate modification in this context means changing the underlying intent/etc. of the content provided by the independent assessment service - the content itself may be modified for presentation, formatting, etc. as needed._
    - _This rule is related to [IVV-IAS-VIP (Verify Inclusion in Certification Package)](../../../assessors/rules/independent-verification-and-validation.md#verify-inclusion-in-certification-package){ data-preview }._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Document Use of Representative Samples

??? abstract "IVV-CSO-DUS"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST document and explain the use of representative samples during verification and validation when using representative samples as allowed by [IVV-CSO-USR (Use Representative Samples)](#use-representative-samples){ data-preview }.


    ---
    **Terms:** [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Technical Explanations

??? abstract "IVV-CSO-STE"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD supply all necessary assessors with technical explanations, demonstrations, and other relevant supporting information about the technical capabilities they employ to address FedRAMP rules; this SHOULD be supplied as necessary to ensure the assessor can effectively complete verification and validation.


    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Use Representative Samples

??? abstract "IVV-CSO-USR"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY use representative samples as appropriate during verification and validation.


    ---

    _**Note:** Many modern cloud services using effective automation do not need to use representative sampling and are capable of persistently verifying and validating the majority of their security measures automatically._

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Receiving Assessor Advice

??? abstract "IVV-CSO-RAA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY ask for and accept advice from their assessor during assessment regarding techniques and procedures that will improve their security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../../../definitions/#likely){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

### Annual Independent Assessments for 20x

??? abstract "IVV-CSX-AIA"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with 20x Class A Certifications MUST meet the expectations of their underlying alternative security framework as part of their persistent independent verification and validation assessment.

    === "Class B"
        Providers with 20x Class B Certifications MUST include all Key Security Indicators in a FedRAMP independent assessment at least one per year.

        **Timeframe:** 1 years

    === "Class C"
        Providers with 20x Class C Certifications MUST include all Key Security Indicators in a FedRAMP independent assessment at least one per year.

        **Timeframe:** 1 years

    === "Class D"
        Providers with 20x Class D Certifications MUST include all Key Security Indicators in a FedRAMP independent assessment at least one per year.

        **Timeframe:** 1 years


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
