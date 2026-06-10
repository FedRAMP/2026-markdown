---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Independent Verification and Validation

This ruleset explains the expectations for independent verification and validation assessments.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [General Independent Assessor Responsibilities](#general-independent-assessor-responsibilities)
- [20x-Specific Independent Assessor Responsibilities](#20x-specific-independent-assessor-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first annual assessment scheduled after 2027-01-01

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first annual assessment scheduled after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

### Persistent Independent Verification and Validation Assessments

??? abstract "IVV-CSO-PIA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY persistently complete an independent verification and validation assessment at least once per year; these assessments MAY be performed by a FedRAMP Recognized independent assessor OR by FedRAMP directly; the results of these assessments MAY be included in their FedRAMP Certification Data without inappropriate modification.

        **Timeframe:** 1 years

    === "Class B"
        Providers with Class B Certifications MUST persistently complete an independent verification and validation assessment at least once per year; these assessments MUST be performed by a FedRAMP Recognized independent assessor OR by FedRAMP directly; the results of these assessments MUST be included in their FedRAMP Certification Data without inappropriate modification.

        **Timeframe:** 1 years

    === "Class C"
        Providers with Class C Certifications MUST persistently complete an independent verification and validation assessment at least once per year; these assessments MUST be performed by a FedRAMP Recognized independent assessor OR by FedRAMP directly; the results of these assessments MUST be included in their FedRAMP Certification Data without inappropriate modification.

        **Timeframe:** 1 years

    === "Class D"
        Providers with Class D Certifications MUST persistently complete an independent verification and validation assessment at least once per year; these assessments MUST be performed by a FedRAMP Recognized independent assessor OR by FedRAMP directly; the results of these assessments MUST be included in their FedRAMP Certification Data without inappropriate modification.

        **Timeframe:** 1 years


    ---

    _**Notes:**_

    - _The first such completed assessment is typically called an "initial assessment" while following assessments are called "annual assessments."_
    - _The specific requirements for independent verification and validation assessments are documented by the FedRAMP Certification Class and Type._
    - _The option for assessment by FedRAMP directly is limited to cloud services that are explicitly prioritized by FedRAMP, in consultation with the FedRAMP Board and the federal Chief Information Officers Council._
    - _FedRAMP Recognized independent assessors are listed on the FedRAMP Marketplace._
    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Supply Technical Evidence

??? abstract "IVV-CSO-STE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD supply all necessary accessors with technical explanations, demonstrations, and other relevant supporting information about the technical capabilities they employ to address FedRAMP rules; this SHOULD be supplied as necessary to ensure the assessor can effectively complete verification and validation.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Receiving Assessor Advice

??? abstract "IVV-CSO-RAA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY ask for and accept advice from their assessor during assessment regarding techniques and procedures that will improve their security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## General Independent Assessor Responsibilities {#general-independent-assessor-responsibilities}

These rules apply to independent assessment services supporting all FedRAMP Certification types.

### Verify and Validate Processes

??? abstract "IVV-IAS-VVP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST verify and validate the implementation of processes derived from FedRAMP requirements, including rules, controls and Key Security Indicators, to determine whether or not the provider has accurately documented their process and security goals for the cloud service offering.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Outcome Consistency

??? abstract "IVV-IAS-OUC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST verify and validate whether or not the underlying processes are consistently creating the desired security outcome documented by the provider.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Procedure Adherence

??? abstract "IVV-IAS-PAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST assess whether or not procedures are consistently followed, including evaluating the processes in place to ensure this occurs, without relying solely on the existence of procedure documents.


    ---

    _**Note:** This includes evaluating tests or plans for activities that may occur in the future but have not yet occurred._

### Mixed Methods Evaluation

??? abstract "IVV-IAS-MME"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST perform verification and validation using a combination of quantitative and expert qualitative assessment as appropriate AND document which is applied to which aspect of the assessment.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Assessment Summary

??? abstract "IVV-IAS-SUM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST deliver a high-level summary of their assessment process and findings for each FedRAMP requirement, including rules, controls, and Key Security Indicators; this summary will be included in the FedRAMP Certification Data for the cloud service offering.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
### Overall Summary of Assessment

??? abstract "IVV-IAS-OSA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST supply an overall summary of the verification and validation assessment results, including any resulting failures or areas of dispute, to the provider and all necessary assessors.


    ---

    _**Note:** FedRAMP will make the final FedRAMP Certification decision based on the assessor's findings and other relevant information._

    ---
    **Terms:** [All Necessary Assessors](../definitions/#all-necessary-assessors){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Engage Provider Experts

??? abstract "IVV-IAS-EPX"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors SHOULD engage provider experts in discussion to understand the decisions made by the provider and inform expert qualitative assessment, and SHOULD perform independent research to test such information as part of the expert qualitative assessment process.


### Sharing Advice

??? abstract "IVV-IAS-SHA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MAY share advice with providers they are assessing about techniques and procedures that will improve the provider's security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## 20x-Specific Independent Assessor Responsibilities {#20x-specific-independent-assessor-responsibilities}

These rules apply to independent assessment services supporting FedRAMP 20x Certifications.

### Underlying Processes

??? abstract "IVV-IAX-UNP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST verify and validate the underlying processes (both machine-based and non-machine-based) that providers use to validate Key Security Indicators; this should include at least:

    1. The effectiveness, completeness, and integrity of the automated processes that perform validation of the cloud service offering's security posture.
    1. The effectiveness, completeness, and integrity of the human processes that perform validation of the cloud service offering's security posture
    1. The coverage of these processes within the cloud service offering, including if all of the consolidated information resources listed are being validated.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Static Evidence

??? abstract "IVV-IAX-STE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Assessors MUST NOT rely on screenshots, configuration dumps, or other static output as evidence EXCEPT when evaluating the accuracy and reliability of a process that generates such artifacts.


    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### Annual Assessments for Rev5 Certifications

??? abstract "IVV-CSF-ANA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with Rev5 Class A Certifications MUST meet the expectations of their underlying alternative security framework as part of their persistent independent verification and validation assessment.

    === "Class B"
        Providers with Rev5 Class B Certifications MUST include the following controls in their persistent independent verification and validation assessment at least one per year:

        **Timeframe:** 1 years

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

    === "Class C"
        Providers with Rev5 Class C Certifications MUST include the following controls in their persistent independent verification and validation assessment at least one per year:

        **Timeframe:** 1 years

        1. AC-2
        1. AC-2 (1)
        1. AC-2 (2)
        1. AC-2 (3)
        1. AC-2 (4)
        1. AC-2 (5)
        1. AC-2 (7)
        1. AC-2 (9)
        1. AC-2 (12)
        1. AC-2 (13)
        1. AC-3
        1. AC-6
        1. AC-6 (2)
        1. AC-6 (5)
        1. AC-6 (10)
        1. AC-17 (2)
        1. AU-2
        1. AU-3
        1. AU-3 (1)
        1. AU-4
        1. AU-5
        1. AU-6
        1. AU-6 (1)
        1. AU-6 (3)
        1. AU-8
        1. AU-11
        1. AU-12
        1. CA-8 (2)
        1. CM-5
        1. CM-6
        1. CM-6 (1)
        1. CM-7
        1. CM-7 (1)
        1. CM-7 (2)
        1. CM-7 (5)
        1. CM-8
        1. CP-4
        1. IA-2
        1. IA-2 (1)
        1. IA-2 (2)
        1. IA-2 (5)
        1. IA-2 (6)
        1. IA-2 (8)
        1. IA-2 (12)
        1. IA-4
        1. IA-5
        1. IR-3
        1. IR-4
        1. IR-4 (1)
        1. MA-3 (2)
        1. PE-3
        1. RA-5
        1. RA-5 (2)
        1. RA-5 (3)
        1. SA-9
        1. SA-11 (1)
        1. SC-7
        1. SC-7 (3)
        1. SC-7 (4)
        1. SC-7 (5)
        1. SC-7 (7)
        1. SC-7 (8)
        1. SC-7 (12)
        1. SC-7 (18)
        1. SC-8
        1. SC-12
        1. SC-13
        1. SC-21
        1. SC-28
        1. SC-45 (1)
        1. SI-3
        1. SI-4 (1)
        1. SI-4 (2)
        1. SI-4 (16)
        1. SI-4 (23)
        1. SI-6
        1. SI-7
        1. SI-7 (1)
        1. SI-10

    === "Class D"
        Providers with Rev5 Class D Certifications MUST include the following controls in their persistent independent verification and validation assessment at least one per year:

        **Timeframe:** 1 years

        1. AC-2
        1. AC-2 (1)
        1. AC-2 (2)
        1. AC-2 (3)
        1. AC-2 (4)
        1. AC-2 (5)
        1. AC-2 (7)
        1. AC-2 (9)
        1. AC-2 (11)
        1. AC-2 (12)
        1. AC-2 (13)
        1. AC-3
        1. AC-6
        1. AC-6 (2)
        1. AC-6 (3)
        1. AC-6 (5)
        1. AC-6 (8)
        1. AC-6 (10)
        1. AC-17 (2)
        1. AU-2
        1. AU-3
        1. AU-3 (1)
        1. AU-4
        1. AU-5
        1. AU-5 (1)
        1. AU-5 (2)
        1. AU-6
        1. AU-6 (1)
        1. AU-6 (3)
        1. AU-6 (4)
        1. AU-6 (5)
        1. AU-6 (6)
        1. AU-6 (7)
        1. AU-8
        1. AU-10
        1. AU-11
        1. AU-12
        1. AU-12 (1)
        1. AU-12 (3)
        1. CA-8 (2)
        1. CM-5
        1. CM-6
        1. CM-6 (1)
        1. CM-6 (2)
        1. CM-7
        1. CM-7 (1)
        1. CM-7 (2)
        1. CM-7 (5)
        1. CM-8
        1. CP-4
        1. IA-2
        1. IA-2 (1)
        1. IA-2 (2)
        1. IA-2 (5)
        1. IA-2 (6)
        1. IA-2 (8)
        1. IA-2 (12)
        1. IA-4
        1. IA-5
        1. IR-3
        1. IR-4
        1. IR-4 (1)
        1. IR-4 (2)
        1. IR-4 (4)
        1. IR-4 (6)
        1. MA-3 (2)
        1. PE-3
        1. RA-5
        1. RA-5 (2)
        1. RA-5 (3)
        1. SA-9
        1. SA-11 (1)
        1. SC-7
        1. SC-7 (3)
        1. SC-7 (4)
        1. SC-7 (5)
        1. SC-7 (7)
        1. SC-7 (8)
        1. SC-7 (12)
        1. SC-7 (18)
        1. SC-7 (20)
        1. SC-7 (21)
        1. SC-8
        1. SC-12
        1. SC-13
        1. SC-21
        1. SC-28
        1. SC-45 (1)
        1. SI-3
        1. SI-4 (1)
        1. SI-4 (2)
        1. SI-4 (10)
        1. SI-4 (16)
        1. SI-4 (19)
        1. SI-4 (20)
        1. SI-4 (23)
        1. SI-6
        1. SI-7
        1. SI-7 (1)
        1. SI-10


    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Integrating FedRAMP Changes

??? abstract "IVV-CSF-IFC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST include any changes to FedRAMP rules in their persistent independent verification and validation assessment at least once per year, based on the mandatory effective date of the rules.

    !!! warning "Corrective Actions"
        - If a provider fails to include changes to FedRAMP rules in a persistent independent verification and validation assessment within 6 months of the mandatory effective date of the rules, FedRAMP will remove their listing from the Marketplace until they provide evidence of an updated assessment that includes the changes to FedRAMP rules.
        - Alternative correction actions may be specified in specific rules that will override this corrective action.


    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
