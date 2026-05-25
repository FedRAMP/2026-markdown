---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# FedRAMP Certification

The FedRAMP Certification rules define how cloud service offerings obtain and maintain FedRAMP Certification across certification classes and paths. They give providers, assessors, agencies, and FedRAMP a common set of expectations for required rule sets, current evidence, independent verification and validation, and ongoing certification decisions.

**Subsets**

- [FedRAMP Responsibilities](#fedramp-responsibilities)
- [General Provider Responsibilities](#general-provider-responsibilities)
- [General Independent Assessor Responsibilities](#general-independent-assessor-responsibilities)
- [FedRAMP Class A Certification Rules](#fedramp-class-a-certification-rules)
- [Applying for FedRAMP Certification](#applying-for-fedramp-certification)
- [Applying for FedRAMP Certification with an Agency Sponsor](#applying-for-fedramp-certification-with-an-agency-sponsor)
- [20x-Specific Provider Responsibilities](#20x-specific-provider-responsibilities)
- [20x-Specific Independent Assessor Responsibilities](#20x-specific-independent-assessor-responsibilities)
- [Rev5-Specific Provider Responsibilities](#rev5-specific-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-05-04
    - **Grace Ends:** 2027-05-04

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** 2027-01-01



---


## FedRAMP Responsibilities {#fedramp-responsibilities}

These rules apply to FedRAMP.

### Minimum Continuous Monitoring

??? abstract "FRC-FRP-MCM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST perform a minimum level of continuous monitoring for cloud service offerings with FedRAMP Program Certification, including at least reviewing Ongoing Certification Reports.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Ongoing Certification](../definitions/#ongoing-certification){ data-preview }
### Exemptions from Certification Rules

??? abstract "FRC-FRP-ECR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY approve exemptions from some FedRAMP Certification rules in rare circumstances by supplying an explicit waiver, based on a prioritization and risk assessment completed by FedRAMP.


    ---

    _**Notes:**_

    - _FedRAMP will determine when such exemptions are appropriate._
    - _Exemptions will typically be part of a public prioritization process and criteria will be published publicly._
    - _Do not ask FedRAMP for an exemption unless the publicly published criteria is met._
## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to cloud service providers obtaining and maintaining any FedRAMP Certification.

### FedRAMP Certification Data Sharing

??? abstract "FRC-CSO-CDS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Certification Data Sharing (CDS) rules, based on the applicability and effective date(s) in those rules.



    **Related SP 800-53 Controls:** [AC-3](https://controlfreak.risk-redux.io/controls/AC-03), [AC-4](https://controlfreak.risk-redux.io/controls/AC-04), [AU-2](https://controlfreak.risk-redux.io/controls/AU-02), [AU-3](https://controlfreak.risk-redux.io/controls/AU-03), [AU-6](https://controlfreak.risk-redux.io/controls/AU-06), [CA-2](https://controlfreak.risk-redux.io/controls/CA-02), [IR-4](https://controlfreak.risk-redux.io/controls/IR-04), [RA-5](https://controlfreak.risk-redux.io/controls/RA-05), [SC-8](https://controlfreak.risk-redux.io/controls/SC-08)


    **Reference:** [FedRAMP Certification Data Sharing](../certification-data-sharing/)

    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }
### Collaborative Continuous Monitoring

??? abstract "FRC-CSO-CCM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the Collaborative Continuous Monitoring (CCM) rules, based on the applicability and effective date(s) in those rules.



    **Reference:** [Collaborative Continuous Monitoring](../collaborative-continuous-monitoring/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }
### FedRAMP Security Inbox

??? abstract "FRC-CSO-FSI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Security Inbox (FSI) rules, based on the applicability and effective date(s) in those rules.



    **Reference:** [FedRAMP Security Inbox](../fedramp-security-inbox/)

    ---
    **Terms:** [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }
### Incident Communications Procedures

??? abstract "FRC-CSO-ICP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Incident Communications Procedures (ICP) rules, based on the applicability and effective date(s) in those rules.



    **Reference:** [Incident Communications Procedures](../incident-communications-procedures/)

    ---
    **Terms:** [Incident](../definitions/#incident){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }
### Minimum Assessment Scope

??? abstract "FRC-CSO-MAS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Minimum Assessment Scope (MAS) rules, based on the applicability and effective date(s) in those rules.



    **Related SP 800-53 Controls:** [AC-1](https://controlfreak.risk-redux.io/controls/AC-01), [AC-21](https://controlfreak.risk-redux.io/controls/AC-21), [AT-1](https://controlfreak.risk-redux.io/controls/AT-01), [AU-1](https://controlfreak.risk-redux.io/controls/AU-01), [CA-1](https://controlfreak.risk-redux.io/controls/CA-01), [CM-1](https://controlfreak.risk-redux.io/controls/CM-01), [CP-1](https://controlfreak.risk-redux.io/controls/CP-01), [CP-2.1](https://controlfreak.risk-redux.io/controls/CP-02(01)), [CP-2.8](https://controlfreak.risk-redux.io/controls/CP-02(08)), [CP-4.1](https://controlfreak.risk-redux.io/controls/CP-04(01)), [IA-1](https://controlfreak.risk-redux.io/controls/IA-01), [IR-1](https://controlfreak.risk-redux.io/controls/IR-01), [MA-1](https://controlfreak.risk-redux.io/controls/MA-01), [MP-1](https://controlfreak.risk-redux.io/controls/MP-01), [PE-1](https://controlfreak.risk-redux.io/controls/PE-01), [PL-1](https://controlfreak.risk-redux.io/controls/PL-01), [PL-2](https://controlfreak.risk-redux.io/controls/PL-02), [PL-4](https://controlfreak.risk-redux.io/controls/PL-04), [PL-4.1](https://controlfreak.risk-redux.io/controls/PL-04(01)), [PS-1](https://controlfreak.risk-redux.io/controls/PS-01), [RA-1](https://controlfreak.risk-redux.io/controls/RA-01), [RA-9](https://controlfreak.risk-redux.io/controls/RA-09), [SA-1](https://controlfreak.risk-redux.io/controls/SA-01), [SC-1](https://controlfreak.risk-redux.io/controls/SC-01), [SI-1](https://controlfreak.risk-redux.io/controls/SI-01), [SR-1](https://controlfreak.risk-redux.io/controls/SR-01), [SR-2](https://controlfreak.risk-redux.io/controls/SR-02), [SR-3](https://controlfreak.risk-redux.io/controls/SR-03), [SR-11](https://controlfreak.risk-redux.io/controls/SR-11)


    **Reference:** [Minimum Assessment Scope](../minimum-assessment-scope/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }
### Secure Configuration Guide

??? abstract "FRC-CSO-SCG"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Secure Configuration Guide (SCG) rules, based on the applicability and effective date(s) in those rules.



    **Reference:** [Secure Configuration Guide](../secure-configuration-guide/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }
### Significant Change Notifications

??? abstract "FRC-CSO-SCN"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Significant Change Notifications (SCN) rules, based on the applicability and effective date(s) in those rules.



    **Related SP 800-53 Controls:** [CA-7.4](https://controlfreak.risk-redux.io/controls/CA-07(04)), [CM-3.4](https://controlfreak.risk-redux.io/controls/CM-03(04)), [CM-4](https://controlfreak.risk-redux.io/controls/CM-04), [CM-7.1](https://controlfreak.risk-redux.io/controls/CM-07(01)), [AU-5](https://controlfreak.risk-redux.io/controls/AU-05), [CA-5](https://controlfreak.risk-redux.io/controls/CA-05), [CA-7](https://controlfreak.risk-redux.io/controls/CA-07), [RA-5](https://controlfreak.risk-redux.io/controls/RA-05), [RA-5.2](https://controlfreak.risk-redux.io/controls/RA-05(02)), [SA-22](https://controlfreak.risk-redux.io/controls/SA-22), [SI-2](https://controlfreak.risk-redux.io/controls/SI-02), [SI-2.2](https://controlfreak.risk-redux.io/controls/SI-02(02)), [SI-3](https://controlfreak.risk-redux.io/controls/SI-03), [SI-5](https://controlfreak.risk-redux.io/controls/SI-05), [SI-7.7](https://controlfreak.risk-redux.io/controls/SI-07(07)), [SI-10](https://controlfreak.risk-redux.io/controls/SI-10), [SI-11](https://controlfreak.risk-redux.io/controls/SI-11)


    **Reference:** [Significant Change Notifications](../significant-change-notifications/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Significant Change](../definitions/#significant-change){ data-preview }
### Using Cryptographic Modules

??? abstract "FRC-CSO-UCM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Using Cryptographic Modules (UCM) rules, based on the applicability and effective date(s) in those rules.



    **Reference:** [Using Cryptographic Modules](../using-cryptographic-modules/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }
### Vulnerability Detection and Response

??? abstract "FRC-CSO-VDR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST follow and persistently address the FedRAMP Vulnerability Detection and Response (VDR) rules, based on the applicability and effective date(s) in those rules.



    **Related SP 800-53 Controls:** [CA-2](https://controlfreak.risk-redux.io/controls/CA-02), [CA-7](https://controlfreak.risk-redux.io/controls/CA-07), [CA-7.6](https://controlfreak.risk-redux.io/controls/CA-07(06)), [IR-1](https://controlfreak.risk-redux.io/controls/IR-01), [IR-4](https://controlfreak.risk-redux.io/controls/IR-04), [IR-4.1](https://controlfreak.risk-redux.io/controls/IR-04(01)), [IR-5](https://controlfreak.risk-redux.io/controls/IR-05), [IR-5.1](https://controlfreak.risk-redux.io/controls/IR-05(01)), [IR-6](https://controlfreak.risk-redux.io/controls/IR-06), [IR-6.1](https://controlfreak.risk-redux.io/controls/IR-06(01)), [IR-6.2](https://controlfreak.risk-redux.io/controls/IR-06(02)), [PM-3](https://controlfreak.risk-redux.io/controls/PM-03), [PM-5](https://controlfreak.risk-redux.io/controls/PM-05), [PM-31](https://controlfreak.risk-redux.io/controls/PM-31), [RA-2](https://controlfreak.risk-redux.io/controls/RA-02), [RA-2.1](https://controlfreak.risk-redux.io/controls/RA-02(01)), [RA-3](https://controlfreak.risk-redux.io/controls/RA-03), [RA-3.3](https://controlfreak.risk-redux.io/controls/RA-03(03)), [RA-5](https://controlfreak.risk-redux.io/controls/RA-05), [RA-5.2](https://controlfreak.risk-redux.io/controls/RA-05(02)), [RA-5.3](https://controlfreak.risk-redux.io/controls/RA-05(03)), [RA-5.4](https://controlfreak.risk-redux.io/controls/RA-05(04)), [RA-5.5](https://controlfreak.risk-redux.io/controls/RA-05(05)), [RA-5.6](https://controlfreak.risk-redux.io/controls/RA-05(06)), [RA-5.7](https://controlfreak.risk-redux.io/controls/RA-05(07)), [RA-5.11](https://controlfreak.risk-redux.io/controls/RA-05(11)), [RA-9](https://controlfreak.risk-redux.io/controls/RA-09), [RA-10](https://controlfreak.risk-redux.io/controls/RA-10), [SI-2](https://controlfreak.risk-redux.io/controls/SI-02), [SI-2.1](https://controlfreak.risk-redux.io/controls/SI-02(01)), [SI-2.2](https://controlfreak.risk-redux.io/controls/SI-02(02)), [SI-2.4](https://controlfreak.risk-redux.io/controls/SI-02(04)), [SI-2.5](https://controlfreak.risk-redux.io/controls/SI-02(05)), [SI-3](https://controlfreak.risk-redux.io/controls/SI-03), [SI-3.1](https://controlfreak.risk-redux.io/controls/SI-03(01)), [SI-3.2](https://controlfreak.risk-redux.io/controls/SI-03(02)), [SI-4](https://controlfreak.risk-redux.io/controls/SI-04), [SI-4.2](https://controlfreak.risk-redux.io/controls/SI-04(02)), [SI-4.3](https://controlfreak.risk-redux.io/controls/SI-04(03)), [SI-4.7](https://controlfreak.risk-redux.io/controls/SI-04(07)), [CA-7.4](https://controlfreak.risk-redux.io/controls/CA-07(04)), [RA-7](https://controlfreak.risk-redux.io/controls/RA-07)


    **Reference:** [Vulnerability Detection and Response](../vulnerability-detection-and-response/)

    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
### Pick One Program Certification Type

??? abstract "FRC-CSO-POP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST NOT seek both FedRAMP Rev5 Program Certification and FedRAMP 20x Program Certification for the same cloud service offering; pick one type.


    ---

    _**Note:** This rule does not prevent a provider from seeking and maintaining a FedRAMP Rev5 Agency Certification and a FedRAMP 20x Program Certification for the same cloud service offering, however, doing so is strongly discouraged due to the increased complexity and risk of confusion for all parties._

    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
### Persistent Verification and Validation

??? abstract "FRC-CSO-PVV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST persistently verify and validate that their information resources are operating as intended; this process is called Persistent Verification and Validation (PVV) and is part of vulnerability detection.


    ---
    **Terms:** [Information Resource](../definitions/#information-resource){ data-preview }, [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }
### Failures Are Vulnerabilities

??? abstract "FRC-CSO-FAV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST treat problems detected during persistent verification and validation as vulnerabilities, including failures of the verification and validation process it; FedRAMP Vulnerability Detection and Response rules MUST be followed for such findings.


    ---
    **Terms:** [Persistently](../definitions/#persistently){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
### Non-Machine Verification and Validation

??? abstract "FRC-CSO-NMV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST verify and validate the status of non-machine-based information resources at least once every 3 months.


    ---
    **Terms:** [Information Resource](../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Independent Verification and Validation

??? abstract "FRC-CSO-IVV"
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

??? abstract "FRC-CSO-STE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD supply all necessary accessors with technical explanations, demonstrations, and other relevant supporting information about the technical capabilities they employ to address FedRAMP rules; this SHOULD be supplied as necessary to ensure the assessor can effectively complete verification and validation.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Receiving Assessor Advice

??? abstract "FRC-CSO-RAA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MAY ask for and accept advice from their assessor during assessment regarding techniques and procedures that will improve their security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## General Independent Assessor Responsibilities {#general-independent-assessor-responsibilities}

These rules apply to independent assessment services supporting all FedRAMP Certification types.

### Verify and Validate Processes

??? abstract "FRC-IAS-VVP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST verify and validate the implementation of processes derived from FedRAMP requirements, including rules, controls and Key Security Indicators, to determine whether or not the provider has accurately documented their process and security goals for the cloud service offering.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Outcome Consistency

??? abstract "FRC-IAS-OUC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST verify and validate whether or not the underlying processes are consistently creating the desired security outcome documented by the provider.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Procedure Adherence

??? abstract "FRC-IAS-PAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST assess whether or not procedures are consistently followed, including evaluating the processes in place to ensure this occurs, without relying solely on the existence of procedure documents.


    ---

    _**Note:** This includes evaluating tests or plans for activities that may occur in the future but have not yet occurred._

### Mixed Methods Evaluation

??? abstract "FRC-IAS-MME"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST perform verification and validation using a combination of quantitative and expert qualitative assessment as appropriate AND document which is applied to which aspect of the assessment.


    ---
    **Terms:** [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Assessment Summary

??? abstract "FRC-IAS-SUM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST deliver a high-level summary of their assessment process and findings for each FedRAMP requirement, including rules, controls, and Key Security Indicators; this summary will be included in the FedRAMP Certification Data for the cloud service offering.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
### Overall Summary of Assessment

??? abstract "FRC-IAS-OSA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST supply an overall summary of the verification and validation assessment results, including any resulting failures or areas of dispute, to the provider and all necessary assessors.


    ---

    _**Note:** FedRAMP will make the final FedRAMP Certification decision based on the assessor's findings and other relevant information._

    ---
    **Terms:** [All Necessary Assessors](../definitions/#all-necessary-assessors){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Engage Provider Experts

??? abstract "FRC-IAS-EPX"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors SHOULD engage provider experts in discussion to understand the decisions made by the provider and inform expert qualitative assessment, and SHOULD perform independent research to test such information as part of the expert qualitative assessment process.


### Sharing Advice

??? abstract "FRC-IAS-SHA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MAY share advice with providers they are assessing about techniques and procedures that will improve the provider's security posture or the effectiveness, clarity, and accuracy of their verification, validation and reporting procedures, UNLESS doing so is likely to compromise the objectivity and integrity of the assessment.


    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## FedRAMP Class A Certification Rules {#fedramp-class-a-certification-rules}

These rules apply to providers seeking FedRAMP Class A Certifications.

### Approved Alternative Security Frameworks

??? abstract "FRC-CLA-ASF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST have completed a certification or equivalent process, including an independent assessment, from one of the following alternative security frameworks:

    1. FedRAMP Ready
    1. SOC 2 Type II
    1. GovRAMP


### External Assessment Materials

??? abstract "FRC-CLA-EAM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Class A Certification MUST supply the full materials from the alternative security assessment to all necessary parties as part of the FedRAMP Certification Package.


    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }
### Address FedRAMP Rules

??? abstract "FRC-CLA-AFR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a Class A FedRAMP Certification MUST address the following FedRAMP rules and supply the appropriate artifacts or information mapping in the FedRAMP Certification Package:

    1. FedRAMP Certification: [FRC-CSO-POP (Pick One Program Certification Type)](#pick-one-program-certification-type){ data-preview }
    1. Minimum Assessment Scope: [MAS-CSO-IIR (Identify Information Resources)](minimum-assessment-scope.md#identify-information-resources){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-PUB (Public Information)](certification-data-sharing.md#public-information){ data-preview }
    1. Certification Data Sharing: [CDS-CSO-UTC (Use Trust Centers)](certification-data-sharing.md#use-trust-centers){ data-preview }
    1. Certification Data Sharing: [CDS-UTC-PGD (Public Guidance)](certification-data-sharing.md#public-guidance){ data-preview }
    1. Certification Data Sharing: [CDS-UTC-AAD (Agency Access Denial)](certification-data-sharing.md#agency-access-denial){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-INB (Maintain a FedRAMP Security Inbox)](fedramp-security-inbox.md#maintain-a-fedramp-security-inbox){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-RCV (Receive Email Without Disruption)](fedramp-security-inbox.md#receive-email-without-disruption){ data-preview }
    1. FedRAMP Security Inbox: [FSI-CSO-CRA (Complete Required Actions)](fedramp-security-inbox.md#complete-required-actions){ data-preview }
    1. Incident Communications Procedures: [ICP-CSO-EFR (Evaluate FedRAMP Reportability)](incident-communications-procedures.md#evaluate-fedramp-reportability){ data-preview }
    1. Vulnerability Detection and Response: [VDR-CSO-DET (Vulnerability Detection)](vulnerability-detection-and-response.md#vulnerability-detection){ data-preview }
    1. Continuous Collaborative Monitoring: [CCM-OCR-AVL (Report Availability)](collaborative-continuous-monitoring.md#report-availability){ data-preview }
    1. Continuous Collaborative Monitoring: [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview }


    ---

    _**Note:** If the alternative security framework has existing rules that align with these FedRAMP rules then a mapping to the alternative security framework content may be supplied instead of generating new artifacts._

    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Certification Package](../definitions/#certification-package){ data-preview }, [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../definitions/#initial-incident-report-iir){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
### Optional Independent Verification and Validation

??? abstract "FRC-CLA-IVV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Class A Certification MAY have the FedRAMP Certification Package independently verified and validated by a FedRAMP Recognized assessor before submission to FedRAMP.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
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
    **Terms:** [Machine-Readable](../definitions/#machine-readable){ data-preview }
### Rev5 Class A Certification

??? abstract "FRC-CLA-CAC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Rev5 Class A Certification by leveraging an alternative security framework that is based on the SP 800-53 Revision 5 MUST supply all Security Decision Record materials required for FedRAMP Rev5 Class B Certification.


    ---

    _**Notes:**_

    - _The only approved alternative security frameworks based on the SP 800-53 Revision 5 are FedRAMP Ready and GovRAMP._
    - _An independent assessment is not required for FedRAMP Rev5 Class A Certification._
## Applying for FedRAMP Certification {#applying-for-fedramp-certification}

These rules apply to cloud service providers who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Marketplace Listing First

??? abstract "FRC-APP-MLF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST be listed in the FedRAMP Marketplace before applying for FedRAMP Certification.


    ---

    _**Note:** See FedRAMP's Marketplace Listing rules for information about being listed in the Marketplace in the Preparation Phase prior to receiving a formal FedRAMP Certification._

### Applying for FedRAMP Certification

??? abstract "FRC-APP-AFC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST complete the FedRAMP Certification Application Form at https://fedramp.gov/forms/provider-listing-request/ in full to request an initial assessment by FedRAMP.



    **Reference:** [FedRAMP Certification Application Form](https://fedramp.gov/forms)

### Fresh FedRAMP Certification Package

??? abstract "FRC-APP-FCP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST supply a fresh initial FedRAMP Certification Package that shows the current status of the cloud service offering as verified and validated by the provider within the previous 7 days.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Fresh Independent Assessment

??? abstract "FRC-APP-FIA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST supply a fresh initial independent verification and validation assessment that was completed by a FedRAMP Recognized Independent Assessment Service within the previous 3 months.


    ---
    **Terms:** [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Applying for FedRAMP Certification with an Agency Sponsor {#applying-for-fedramp-certification-with-an-agency-sponsor}

These rules apply to cloud service providers with an Agency Sponsor who have met all other relevant rules and are ready to apply for any FedRAMP Certification.

### Agency Authorization to Operate

??? abstract "FRC-APS-ATO"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Rev5 Agency Certification MUST have completed the Authorization to Operate (ATO) process with their agency sponsor for the cloud service offering, concluding with a formal signed ATO letter that the agency has sent over official government channels to FedRAMP.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## 20x-Specific Provider Responsibilities {#20x-specific-provider-responsibilities}

These rules apply to providers for FedRAMP 20x Certifications.

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
    **Terms:** [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }
### Application within MAS

??? abstract "FRC-CSX-MAS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD apply ALL Key Security Indicators to ALL aspects of their cloud service offering that are within the FedRAMP Minimum Assessment Scope.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
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
    **Terms:** [Information Resource](../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## 20x-Specific Independent Assessor Responsibilities {#20x-specific-independent-assessor-responsibilities}

These rules apply to independent assessment services supporting FedRAMP 20x Certifications.

### Static Evidence

??? abstract "FRC-IAX-STE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST NOT rely on screenshots, configuration dumps, or other static output as evidence EXCEPT when evaluating the accuracy and reliability of a process that generates such artifacts.


    ---
    **Terms:** [Artifacts](../definitions/#artifacts){ data-preview }
### Underlying Processes

??? abstract "FRC-IAX-UNP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Assessors MUST verify and validate the underlying processes (both machine-based and non-machine-based) that providers use to validate Key Security Indicators; this should include at least:

    1. The effectiveness, completeness, and integrity of the automated processes that perform validation of the cloud service offering's security posture.
    1. The effectiveness, completeness, and integrity of the human processes that perform validation of the cloud service offering's security posture
    1. The coverage of these processes within the cloud service offering, including if all of the consolidated information resources listed are being validated.


    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Information Resource](../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### Class D Program Certification Exclusion

??? abstract "FRC-CSF-CDE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers seeking a FedRAMP Rev5 Class D Certification MUST use the FedRAMP Agency Certification path.


    ---

    _**Note:** FedRAMP will not perform FedRAMP Rev5 Class D Program Certifications._

### Persistent Machine Verification and Validation

??? abstract "FRC-CSF-PMV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    === "Class A"
        Providers of FedRAMP Rev5 Class A offerings SHOULD verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month

    === "Class B"
        Providers of FedRAMP Rev5 Class B offerings SHOULD verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month

    === "Class C"
        Providers of FedRAMP Rev5 Class C offerings MUST verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month

    === "Class D"
        Providers of FedRAMP Rev5 Class D offerings MUST verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month


    ---
    **Terms:** [Information Resource](../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../definitions/#machine-based-information-resources){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### FedRAMP Ready Conversion

??? abstract "FRC-CSF-RDY"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers with FedRAMP Rev5 Ready status MUST convert to a FedRAMP Certification before the furthest date of the expiration of their most recently yearly assessment or November 17, 2026; the legacy FedRAMP Ready status will be entirely removed on December 31, 2027.


    ---

    _**Note:** Cloud services that do not wish to convert or do not meet conversion criteria will be renamed Legacy FedRAMP Ready and otherwise retired from FedRAMP Ready._
