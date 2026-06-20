---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Independent Verification and Validation

This ruleset explains the expectations for independent verification and validation assessments.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [General Independent Assessor Responsibilities](#general-independent-assessor-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### FedRAMP Independent Assessments

??? abstract "IVV-CSO-FIA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class B"
        Providers with Class B Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 year


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


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the implementation of the measures that have been documented to meet FedRAMP Practices; this evidence is the result of verification.


    ---

    _**Note:** For example, if the documentation says that firewall rules are used to block traffic then the cloud service provider would verify that firewall rules are in place to block traffic and supply that evidence to assessors (preferably by allowing them to see how firewall configurations are deployed from a source of truth)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Evidence of Effectiveness

??? abstract "IVV-CSO-SEE"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply evidence to all necessary assessors of the effectiveness of the measures that have been implemented to meet FedRAMP Practices; this evidence is the result of validation.


    ---

    _**Note:** For example, after verifying that firewalls are configured to block traffic following [IVV-CSO-SEI (Supply Evidence of Implementation)](#supply-evidence-of-implementation){ data-preview }, the provider would validate that traffic is actually being blocked and supply evidence of that validation to assessors (such as by allowing them to see metrics on the traffic that is blocked vs not)._

    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Inclusion in Certification Package

??? abstract "IVV-CSO-ICP"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply the results of FedRAMP independent assessments in their FedRAMP Certification Package without inappropriate modification.


    ---

    _**Notes:**_

    - _Inappropriate modification in this context means changing the underlying intent/etc. of the content provided by the independent assessment service - the content itself may be modified for presentation, formatting, etc. as needed._
    - _This rule is related to [IVV-IAS-VIP (Verify Inclusion in Certification Package)](#verify-inclusion-in-certification-package){ data-preview }._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Document Use of Representative Samples

??? abstract "IVV-CSO-DUS"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST document and explain the use of representative samples during verification and validation when using representative samples as allowed by [IVV-CSO-USR (Use Representative Samples)](#use-representative-samples){ data-preview }.


    ---
    **Terms:** [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Supply Technical Explanations

??? abstract "IVV-CSO-STE"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD supply all necessary assessors with technical explanations, demonstrations, and other relevant supporting information about the technical capabilities they employ to address FedRAMP rules; this SHOULD be supplied as necessary to ensure the assessor can effectively complete verification and validation.


    ---
    **Terms:** [All Necessary Assessors](../../../definitions/#all-necessary-assessors){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Use Representative Samples

??? abstract "IVV-CSO-USR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY use representative samples as appropriate during verification and validation.


    ---

    _**Note:** Many modern cloud services using effective automation do not need to use representative sampling and are capable of persistently verifying and validating the majority of their security measures automatically._

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Receiving Assessor Advice

??? abstract "IVV-CSO-RAA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY ask for and accept advice from their assessor during assessment regarding techniques and procedures that will improve their security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../../../definitions/#likely){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## General Independent Assessor Responsibilities {#general-independent-assessor-responsibilities}

These rules apply to independent assessment services supporting all FedRAMP Certification types.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Assessors</span></span></span>
</div>

### Verify Implementation

??? abstract "IVV-IAS-VIM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MUST verify that the measures implemented by the cloud service offering matches the measures they documented to meet FedRAMP Practices.


    ---

    _**Note:** This requires reviewing the actual measures themselves at a technical level, such as reviewing underlying code as appropriate; don't simply review documentation or screenshots._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Validate Effectiveness

??? abstract "IVV-IAS-VEF"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MUST validate the effectiveness of the implemented measures to ensure they have the intended outcome for meeting FedRAMP Practices.


    ---

    _**Note:** This requires reviewing the actual measures themselves at a technical level, such as reviewing underlying code as appropriate; don't simply review documentation or screenshots._

    ---
    **Terms:** [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Assessment Summary

??? abstract "IVV-IAS-SUM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MUST supply the provider with a high-level summary of their assessment process and findings for each FedRAMP Practice; this summary will be included by the provider in the FedRAMP Security Decision Record for the cloud service offering.


    ---

    _**Note:** FedRAMP does not require a separate Security Assessment Plan or Security Assessment Report for FedRAMP 20x or FedRAMP Rev5 Certifications; this information is expected to be included in the Security Decision Record by the cloud service provider._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
### Overall Summary of Assessment

??? abstract "IVV-IAS-OSA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MUST supply the provider with an overall summary of the verification and validation assessment results, including any resulting failures or areas of dispute; this summary will be included by the provider in the FedRAMP Certification Package Overview for the cloud service offering.


    ---

    _**Note:** FedRAMP does not supply a template for this summary and encourages independent assessment services to optimize for the best customer experience in the creation of these materials._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Verify Inclusion in Certification Package

??? abstract "IVV-IAS-VIP"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MUST verify that information supplied during a FedRAMP independent assessment is included in the FedRAMP Certification Package by the provider without inappropriate modification.


    ---

    _**Note:** This rule is related to [IVV-CSO-ICP (Inclusion in Certification Package)](#inclusion-in-certification-package){ data-preview }._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Engage Provider Experts

??? abstract "IVV-IAS-EPX"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors SHOULD engage provider experts in discussion to understand the decisions made by the provider and inform expert qualitative assessment, and SHOULD perform independent research to test such information as part of the expert qualitative assessment process.


### Sharing Advice

??? abstract "IVV-IAS-SHA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Assessors MAY share advice with providers they are assessing about techniques and procedures that will improve the provider's security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../../../definitions/#likely){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Annual Independent Assessments for Rev5

??? abstract "IVV-CSF-AIA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class B"
        Providers with Rev5 Class B Certifications MUST include the following Rev5 Controls in a FedRAMP independent assessment at least once per year:

        **Timeframe:** 1 year

        1. AC-2
        1. AC-3
        1. AU-2
        1. AU-3
        1. AU-4
        1. AU-5
        1. AU-6
        1. AU-8
        1. AU-11
        1. AU-12
        1. CM-5
        1. CM-6
        1. CM-7
        1. CM-8
        1. CP-4
        1. IA-2
        1. IA-2 (1)
        1. IA-2 (2)
        1. IA-2 (8)
        1. IA-2 (12)
        1. IA-4
        1. IA-5
        1. IR-4
        1. PE-3
        1. RA-5
        1. RA-5 (2)
        1. SA-9
        1. SC-7
        1. SC-8
        1. SC-12
        1. SC-13
        1. SC-21
        1. SC-28
        1. SI-3


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Mandatory Control Assessment

??? abstract "IVV-CSF-MCA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST have all applicable Rev5 Controls included in FedRAMP independent assessments every 3 years but are not required to have all Rev5 Controls included in the same FedRAMP independent assessment.


    ---

    _**Note:** Traditionally this has been done by reviewing a rotating selection of Rev5 Controls at each annual assessment, however this requirement is a ceiling and not a floor. See [IVV-CSF-PCA (Preferred Control Assessment)](#preferred-control-assessment){ data-preview } for FedRAMP's recommended approach to Rev5 control assessments._

    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Assessment of Rev5 Controls with Findings

??? abstract "IVV-CSF-ACF"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST have Rev5 Controls with negative findings from the previous FedRAMP independent assessment included in the next FedRAMP independent assessment.


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### Preferred Control Assessment

??? abstract "IVV-CSF-PCA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD include all applicable Rev5 Controls in each FedRAMP independent assessment.


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
