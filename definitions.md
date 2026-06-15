---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# FedRAMP Definitions

FedRAMP Definitions establish a shared understanding for terms when the plain-language meaning is not precise enough to support consistent use across the rules. When a defined term appears in a rule, the definition is a critical part of that rule and must be followed precisely, even if the term is commonly used differently elsewhere; when no definition exists, the plain-language meaning is expected.



---

## Important Related Terms

| Related Terms Group | Terms |
| --- | --- |
| <span id="related-terms-group-accounts"></span>Accounts | [Privileged Account](#privileged-account){ data-preview }<br>[Top-Level Administrative Account](#top-level-administrative-account){ data-preview } |
| <span id="related-terms-group-assessment"></span>Assessment | [Initial FedRAMP Assessment](#initial-fedramp-assessment){ data-preview }<br>[Persistent FedRAMP Assessment](#persistent-fedramp-assessment){ data-preview } |
| <span id="related-terms-group-certification"></span>Certification | [Artifacts](#artifacts){ data-preview }<br>[Certification Class](#certification-class){ data-preview }<br>[Certification Data](#certification-data){ data-preview }<br>[Certification Package](#certification-package){ data-preview }<br>[Certification Path](#certification-path){ data-preview }<br>[Certification Profile](#certification-profile){ data-preview }<br>[Certification Type](#certification-type){ data-preview }<br>[FedRAMP Certified](#fedramp-certified){ data-preview }<br>[Initial Certification](#initial-certification){ data-preview }<br>[Ongoing Certification](#ongoing-certification){ data-preview }<br>[Quarterly Review](#quarterly-review){ data-preview } |
| <span id="related-terms-group-customer-effect"></span>Customer Effect | [Debilitating Customer Effect](#debilitating-customer-effect){ data-preview }<br>[Disruptive Customer Effect](#disruptive-customer-effect){ data-preview }<br>[Minimal Customer Effect](#minimal-customer-effect){ data-preview }<br>[Narrow Customer Effect](#narrow-customer-effect){ data-preview } |
| <span id="related-terms-group-incident"></span>Incident | [FedRAMP Reportable Incident](#fedramp-reportable-incident){ data-preview }<br>[Final Incident Report (FIR)](#final-incident-report-fir){ data-preview }<br>[Incident](#incident){ data-preview }<br>[Initial Incident Report (IIR)](#initial-incident-report-iir){ data-preview }<br>[Ongoing Incident Report (OIR)](#ongoing-incident-report-oir){ data-preview } |
| <span id="related-terms-group-information-resource"></span>Information Resource | [Information Resource](#information-resource){ data-preview }<br>[Machine-Based (Information Resources)](#machine-based-information-resources){ data-preview }<br>[Third-Party Information Resource](#third-party-information-resource){ data-preview } |
| <span id="related-terms-group-significant-changes"></span>Significant Changes | [Adaptive Change](#adaptive-change){ data-preview }<br>[Certification Class Change](#certification-class-change){ data-preview }<br>[Routine Recurring Change](#routine-recurring-change){ data-preview }<br>[Significant Change](#significant-change){ data-preview }<br>[Transformative Change](#transformative-change){ data-preview } |
| <span id="related-terms-group-stakeholder"></span>Stakeholder | [Advisor](#advisor){ data-preview }<br>[Agency](#agency){ data-preview }<br>[All Affected Parties](#all-affected-parties){ data-preview }<br>[All Necessary Assessors](#all-necessary-assessors){ data-preview }<br>[All Necessary Parties](#all-necessary-parties){ data-preview }<br>[Assessor](#assessor){ data-preview }<br>[Provider](#provider){ data-preview } |
| <span id="related-terms-group-vulnerability"></span>Vulnerability | [Accepted Vulnerability](#accepted-vulnerability){ data-preview }<br>[False Positive Vulnerability](#false-positive-vulnerability){ data-preview }<br>[Fully Mitigated Vulnerability](#fully-mitigated-vulnerability){ data-preview }<br>[Internet-Reachable Vulnerability (IRV)](#internet-reachable-vulnerability-irv){ data-preview }<br>[Known Exploited Vulnerability (KEV)](#known-exploited-vulnerability-kev){ data-preview }<br>[Likely Exploitable Vulnerability (LEV)](#likely-exploitable-vulnerability-lev){ data-preview }<br>[Overdue Vulnerability](#overdue-vulnerability){ data-preview }<br>[Partially Mitigated Vulnerability](#partially-mitigated-vulnerability){ data-preview }<br>[Remediated Vulnerability](#remediated-vulnerability){ data-preview }<br>[Vulnerability](#vulnerability){ data-preview }<br>[Vulnerability Detection](#vulnerability-detection){ data-preview }<br>[Vulnerability Response](#vulnerability-response){ data-preview } |

---

## Accepted Vulnerability

??? abstract "**ID:** FRD-ACV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability that the provider does not intend to fully mitigate or remediate, OR that has not or will not be fully mitigated or remediated within the maximum overdue period in FedRAMP Vulnerability Detection and Response rules.


    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** accepted vulnerability, accepted vulnerabilities
## Adaptive Change

??? abstract "**ID:** FRD-ADP"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A type of significant change that does not routinely recur and does not introduce substantive potential security risks that need to be assessed in depth.

    ---

    _**Note:** Adaptive changes typically require careful planning that focuses on engineering execution instead of customer adoption, can be verified with minor changes to existing automated validation procedures, and do not require large changes to operational procedures, deployment plans, or documentation._

    **Related Terms Group:** [Significant Changes](#related-terms-group-significant-changes)

    **Also:** adaptive, adaptive change, adaptive changes
## Advisor

??? abstract "**ID:** FRD-ADV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An entity that helps a provider understand, prepare for, or maintain FedRAMP Certification without replacing the provider's responsibility or the assessor's independence.


    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** advisor, advisors
## Agency

??? abstract "**ID:** FRD-AGY"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning given in 44 U.S. Code § 3502 (1), which is "any executive department, military department, Government corporation, Government controlled corporation, or other establishment in the executive branch of the Government (including the Executive Office of the President), or any independent regulatory agency, but does not include—(A) the Government Accountability Office; (B) Federal Election Commission; (C) the governments of the District of Columbia and of the territories and possessions of the United States, and their various subdivisions; or (D) Government-owned contractor-operated facilities, including laboratories engaged in national defense research and production activities."


    **Reference:** [44 U.S. Code § 3502 (1)](https://www.govinfo.gov/app/details/USCODE-2023-title44/USCODE-2023-title44-chap35-subchapI-sec3502)

    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** agency, agencies
## All Affected Parties

??? abstract "**ID:** FRD-AAP"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    All federal entities whose interests are affected directly or are likely to be affected directly in the event of a vulnerability or incident related to federal customer data. This always includes FedRAMP and directly impacted federal customer agencies.


    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** all affected parties
## All Necessary Assessors

??? abstract "**ID:** FRD-ANA"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    All entities who participate in the FedRAMP assessment of a cloud service offering in the context of a FedRAMP Certification. This always includes FedRAMP and any FedRAMP Recognized independent assessor contracted by a provider to perform a FedRAMP assessment.


    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** all necessary assessors
## All Necessary Parties

??? abstract "**ID:** FRD-ANP"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    All entities whose interests are affected directly by activity related to a specific cloud service offering in the context of FedRAMP Certifications. This always includes FedRAMP and any agency customer who is using the cloud service offering, but may include additional parties depending on agreements made by the cloud service provider (such as consultants or independent assessors). Potential agency customers or third-party cloud service providers should also be included in most cases but this is not a mandatory requirement under FedRAMP because the cloud service provider may choose who they wish to do business with.


    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** all necessary parties
## Artifacts

??? abstract "**ID:** FRD-ART"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Security-related materials that supply information regarding or evidence of functions, policies, decisions, procedures, operations, or other such activities, for the purposes of obtaining and maintaining a FedRAMP Certification. All such artifacts are considered FedRAMP Certification Data and are included in the FedRAMP Certification Package.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** artifact, artifacts
## Assessor

??? abstract "**ID:** FRD-ASR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An assessor that performs assessment, verification, or validation activities for a cloud service offering seeking to obtain or maintain FedRAMP Certification; FedRAMP is the final assessor for FedRAMP Certification, but FedRAMP Recognized independent assessment services are typically also utilized.

    ---

    _**Note:** FedRAMP has transitioned from using the historical term "Third-Party Assessment Organization (3PAO)" to align with the explicit terminology used in the FedRAMP Authorization Act and to avoid the confusion caused when the same organizations provide both assessment and advisory services to different customers while being referred to as a 3PAO._

    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** assessor, assessors
## Certification Class

??? abstract "**ID:** FRD-CCL"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The category of assurance that a cloud service offering supplies to federal government customers following FedRAMP Practices, increasing from minimal assurance at Class A to significant assurance at Class D; currently available categories are Class A, B, C, or D.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** Certification Class, Certification Classes
## Certification Class Change

??? abstract "**ID:** FRD-CCC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A type of significant change that is likely to change the FedRAMP Certification class for the entire cloud service offering (e.g. from Class B to Class C or from Class D to Class C).


    **Related Terms Group:** [Significant Changes](#related-terms-group-significant-changes)

    **Also:** certification class change, certification class changes
## Certification Data

??? abstract "**ID:** FRD-CRD"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The collective information required by FedRAMP for initial and ongoing FedRAMP Certification of a cloud service offering, including the FedRAMP Certification Package.

    ---

    _**Note:** In FedRAMP documentation, certification data always refers to FedRAMP Certification Data unless otherwise specified._

    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** certification data
## Certification Package

??? abstract "**ID:** FRD-CRP"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has meaning from 44 USC § 3607 (b)(8) given to "authorization package", which is "the essential information that can be used by an agency to determine whether to authorize the operation of an information system or the use of a designated set of common controls for all cloud computing products and services [certified] by FedRAMP."

    ---

    _**Note:** In FedRAMP documentation, certification package always refers to a FedRAMP Certification Package unless otherwise specified._

    **Reference:** [44 USC § 3607 (b)(8)](https://fedramp.gov/docs/authority/law/#b-additional-definitions)

    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** certification package, certification packages
## Certification Path

??? abstract "**ID:** FRD-CPH"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The underlying source of the FedRAMP Certification, either from a federal agency sponsored authorization to operate or directly from FedRAMP itself. The agency path is a legacy path that is only available for FedRAMP Rev5 and still requires review and approval from FedRAMP.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** Certification Path, Certification Paths
## Certification Profile

??? abstract "**ID:** FRD-CPF"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The combination of a FedRAMP Certification Type (Rev5 or 20x), FedRAMP Certification Path (Program or Agency), and FedRAMP Certification Class (A, B, C, or D) for a cloud service offering.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** Certification Profile, Certification Profiles
## Certification Type

??? abstract "**ID:** FRD-CTY"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The form of assurance that a cloud service offering supplies to federal government customers following FedRAMP Practices, either Rev5 or 20x. Rev5 follows a legacy approach based primarily on documented plans while 20x follows a modern approach based primarily on measured outcomes.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** Certification Type, Certification Types
## Cloud Service Offering

??? abstract "**ID:** FRD-CSO"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A specific, packaged cloud computing product or service supplied by a cloud service provider for use by customers, that is the subject of a FedRAMP Certification.

    ---

    _**Note:** The FedRAMP Minimum Assessment Scope defines the full scope of the cloud service offering from the perspective of a FedRAMP Certification._

    **Also:** cloud service offering, cloud service offerings
## Debilitating Customer Effect

??? abstract "**ID:** FRD-DCE"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An unwanted customer effect that interrupts use of the cloud service for most users or compromises the integrity or confidentiality of most federal customer data. If the adverse customer effect is unknown then it should be treated as if it is debilitating until proven otherwise.


    **Related Terms Group:** [Customer Effect](#related-terms-group-customer-effect)

    **Also:** debilitating customer effect, debilitating customer effects
## Deterministic Telemetry

??? abstract "**ID:** FRD-DTM"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Verifiable data collected directly from an authoritative source that represents a factual and reproducible observation of the attributes of a system such as the system's state, configuration, or behavior.

    ---

    _**Note:** Probabilistic inferences, generative outputs, or predictive assessments such as those produced using generative transformer models (commonly referred to as “Generative AI”) do not constitute a factual record of the system state and must not be used to generate deterministic telemetry._

    **Also:** deterministic telemetry
## Disruptive Customer Effect

??? abstract "**ID:** FRD-DCF"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An unwanted customer effect that interrupts use of the cloud service for many users for less than 24 hours, or that compromises the integrity or confidentiality of large amounts or many types of federal customer data.


    **Related Terms Group:** [Customer Effect](#related-terms-group-customer-effect)

    **Also:** disruptive customer effect, disruptive customer effects
## Drift

??? abstract "**ID:** FRD-DFT"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Changes to information resources that cause deviations from the intended and assessed state; common forms of drift include changes to configurations, deployed software, privileges, running processes, and availability.


    **Also:** drift, drifts, drifting
## False Positive Vulnerability

??? abstract "**ID:** FRD-FPV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A detected vulnerability that is not actually present in an exploitable state in the information resource

    ---

    _**Notes:**_
    - _This includes situations where vulnerable software or code exist on a machine-based information resource but are not loaded, running, or otherwise in an operating state required for exploitation._
    - _This only applies if the vulnerability is not and was not present; a remediated vulnerability or a fully mitigated vulnerability cannot also be a false positive vulnerability._

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** false positive vulnerability, false positive vulnerabilities
## Federal Customer Data

??? abstract "**ID:** FRD-FCD"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    All electronic information, content, and materials that an agency or its authorized users upload, store, or otherwise supply to a cloud service for processing or storage. This does NOT include account information, service metadata, analytics, telemetry, or other similar metadata generated by the cloud service provider.

    ---

    _**Note:** In the context of FedRAMP Certification, "federal customer data" ONLY ever refers to data owned by federal agency customers. Agreements and contracts with specific agencies may require providers to protect additional data or even transfer ownership of telemetry or usage data to the agency; always consult a lawyer that is familiar with company agreements and contracts when determining the scope of federal customer data._

    **Also:** federal customer data
## FedRAMP Certified

??? abstract "**ID:** FRD-FCT"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The status of a cloud service offering that has received FedRAMP Certification and meets the legal requirement to be FedRAMP authorized.

    ---

    _**Note:** FedRAMP uses "FedRAMP Certified" as the current program term for cloud service offerings that satisfy the statutory concept of FedRAMP authorization._

    **Reference:** [FedRAMP Certification Act (44 USC § 3608)](https://www.fedramp.gov/docs/authority/law/#sec-3608-federal-risk-and-authorization-management-program)

    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** FedRAMP Certified, FedRAMP certified, certified, FedRAMP authorized, FedRAMP Authorized, authorized
## FedRAMP Independent Assessment

??? abstract "**ID:** FRD-FIN"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An independent verification and validation assessment, performed by a FedRAMP Recognized independent assessment service or FedRAMP following FedRAMP Rules. These assessments are typically first performed to obtain an initial FedRAMP Certification then repeated on an annual basis to maintain FedRAMP Certification.


    **Also:** FedRAMP independent assessment, FedRAMP independent assessments
## FedRAMP Practices

??? abstract "**ID:** FRD-FPR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The security measures, safeguards, precautions, procedures, activities, policies, capabilities, mechanisms, etc. that are expected to be in place by FedRAMP to demonstrate that information resources are properly protected, expressed in FedRAMP 20x Key Security Indicators or FedRAMP Rev5 Controls and supplemented by FedRAMP Rules.


    **Also:** FedRAMP Practice, FedRAMP Practices
## FedRAMP Recognized

??? abstract "**ID:** FRD-FRA"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The status of independent assessment services that are recognized by FedRAMP to perform assessment activities on behalf of FedRAMP for cloud service offerings seeking to obtain or maintain FedRAMP Certification.


    **Also:** FedRAMP Recognized, FedRAMP Recognition
## FedRAMP Reportable Incident

??? abstract "**ID:** FRD-FRI"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An incident that affects the confidentiality or integrity of federal customer data or is likely to affect the confidentiality or integrity of federal customer data.


    **Related Terms Group:** [Incident](#related-terms-group-incident)

    **Also:** FedRAMP Reportable Incident, FedRAMP Reportable Incidents
## FedRAMP Security Inbox

??? abstract "**ID:** FRD-FSI"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An email address that follows the FedRAMP Security Inbox rules.


    **Also:** security inbox, security inboxes, FSI
## Final Incident Report (FIR)

??? abstract "**ID:** FRD-FIR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A final report after recovery from an incident that is supplied by FedRAMP Certified cloud service providers to FedRAMP and agency customers, following FedRAMP Incident Communications Procedures.


    **Related Terms Group:** [Incident](#related-terms-group-incident)

    **Also:** final incident report, final incident reports, FIR, FIRs
## Fully Mitigated Vulnerability

??? abstract "**ID:** FRD-FMV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability where the likelihood of exploitation or Potential Agency Impact N-rating has been reduced from the original evaluation until either are negligible, but the vulnerability is still detected.


    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** fully mitigated vulnerability, fully mitigated vulnerabilities, fully mitigate vulnerabilities
## Handle

??? abstract "**ID:** FRD-HAN"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the plain language meaning inclusive of any possible action taken with information, such as access, collect, control, create, display, disclose, disseminate, dispose, maintain, manipulate, process, receive, review, store, transmit, use... etc.


    **Also:** handle, handles, handled, handling
## Incident

??? abstract "**ID:** FRD-INT"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning given in 44 USC § 3552 (b)(2) which is "an occurrence that (A) actually or imminently jeopardizes, without lawful authority, the integrity, confidentiality, or availability of information or an information system; or (B) constitutes a violation or imminent threat of violation of law, security policies, security procedures, or acceptable use policies."


    **Reference:** [44 USC § 3552 (b)(2)](https://www.govinfo.gov/app/details/USCODE-2024-title44/USCODE-2024-title44-chap35-subchapII-sec3552)

    **Related Terms Group:** [Incident](#related-terms-group-incident)

    **Also:** incident, incidents
## Information Resource

??? abstract "**ID:** FRD-IRS"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning from 44 USC § 3502 (6): "information and related resources, such as personnel, equipment, funds, and information technology." This includes any aspect of the cloud service offering, both technical and managerial, including everything that makes up the business of the offering from non-machine-based information resources like organizational policies, procedures, employees, etc. to machine-based information resources like hardware, software, cloud services, code, etc.

    ---

    _**Note:** Information resources are either machine-based or non-machine-based; any requirement or recommendation that references information resources without specifying a type is inclusive of all information resources._

    **Reference:** [44 USC § 3502 (6)](https://www.govinfo.gov/app/details/USCODE-2023-title44/USCODE-2023-title44-chap35-subchapI-sec3502)

    **Related Terms Group:** [Information Resource](#related-terms-group-information-resource)

    **Also:** information resource, information resources
## Initial Certification

??? abstract "**ID:** FRD-INC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The first FedRAMP Certification of a cloud service offering based on the applicable FedRAMP Practices.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** initial certification, initial certifications
## Initial FedRAMP Assessment

??? abstract "**ID:** FRD-IFA"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The first full assessment of a cloud service offering obtaining FedRAMP Certification, coordinated by the provider with all necessary assessors, that results in a FedRAMP Certification.


    **Related Terms Group:** [Assessment](#related-terms-group-assessment)

    **Also:** initial FedRAMP assessment, IFRA
## Initial Incident Report (IIR)

??? abstract "**ID:** FRD-IIR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An initial report about an incident that is supplied by FedRAMP Certified cloud service providers to FedRAMP and agency customers, following FedRAMP Incident Communications Procedures.


    **Related Terms Group:** [Incident](#related-terms-group-incident)

    **Also:** initial incident report, initial incident reports, IIR, IIRs
## Internet-Reachable Vulnerability (IRV)

??? abstract "**ID:** FRD-IRV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability in a machine-based information resource that might be exploited or otherwise triggered by a payload originating from a source on the public internet.

    ---

    _**Notes:**_
    - _This includes machine-based information resources that have no direct route to/from the internet but receive payloads or otherwise take action triggered by internet activity._
    - _Internet-reachability applies only to the specific vulnerable machine-based information resources processing the payload._
    - _The opposite of this is a Not Internet-reachable Vulnerability (NIRV)._

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** internet-reachable vulnerability, internet-reachable vulnerabilities, IRV, IRVs, NIRV, NIRVs
## Known Exploited Vulnerability (KEV)

??? abstract "**ID:** FRD-KEV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning given in CISA Binding Operational Directive 26-04, which is any vulnerability identified in CISA's Known Exploited Vulnerabilities catalog.


    **Reference:** [CISA BOD 26-04](https://www.cisa.gov/news-events/directives/bod-26-04-prioritizing-security-updates-based-risk)

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** known exploited vulnerability, known exploited vulnerabilities, KEV, KEVs
## Likely

??? abstract "**ID:** FRD-LKY"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A reasonable degree of probability based on context.


    **Also:** likely, likelihood
## Likely Exploitable Vulnerability (LEV)

??? abstract "**ID:** FRD-LEV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability that is not fully mitigated AND is reachable by a likely threat actor; AND a likely threat actor with knowledge of the vulnerability would likely gain unauthorized access, cause harm, disrupt operations, or otherwise have an undesired adverse impact within the cloud service offering by exploiting the vulnerability.

    ---

    _**Notes:**_
    - _At the absolute minimum, any vulnerability that an automated unauthenticated system can exploit over the internet is a likely exploitable vulnerability._
    - _The opposite of this is a Not Likely Exploitable Vulnerability (NLEV)._

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** likely exploitable vulnerability, likely exploitable vulnerabilities, LEV, LEVs, NLEV, NLEVs
## Machine-Based (Information Resources)

??? abstract "**ID:** FRD-MBI"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Any information technology information resource—including systems, processes, software, hardware, services, cloud-native capabilities, and any other such capability, component, or resource—that relies primarily on mechanical or electronic devices (i.e. computers) for operation.

    ---

    _**Note:** All other information resources that do not rely on computers are non-machine-based information resources._

    **Related Terms Group:** [Information Resource](#related-terms-group-information-resource)

    **Also:** machine-based, machine based
## Machine-Generated

??? abstract "**ID:** FRD-MGN"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Automatically produced by a computer process, application, or other mechanism without the intervention or manipulation of a human during production.


    **Also:** machine-generated
## Machine-Readable

??? abstract "**ID:** FRD-MRD"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning from 44 U.S. Code § 3502 (18) which is "the term "machine-readable", when used with respect to data, means data in a format that can be easily processed by a computer without human intervention while ensuring no semantic meaning is lost"


    **Reference:** [44 U.S. Code § 3502 (18)](https://www.govinfo.gov/app/details/USCODE-2023-title44/USCODE-2023-title44-chap35-subchapI-sec3502)

    **Also:** machine-readable
## Minimal Customer Effect

??? abstract "**ID:** FRD-MCE"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An unwanted customer effect that is only noticeable by some users. This includes minor inconveniences such as reduced performance.


    **Related Terms Group:** [Customer Effect](#related-terms-group-customer-effect)

    **Also:** minimal customer effect, minimal customer effects
## Narrow Customer Effect

??? abstract "**ID:** FRD-NCE"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An unwanted customer effect that interrupts use of the cloud service for some users for less than 12 hours, or that compromises the integrity or confidentiality of an extremely limited amount and type of federal customer data.


    **Related Terms Group:** [Customer Effect](#related-terms-group-customer-effect)

    **Also:** narrow customer effect, narrow customer effects
## Ongoing Certification

??? abstract "**ID:** FRD-ONC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The continued FedRAMP Certification of a cloud service offering based on the applicable FedRAMP Practices.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** ongoing certification, ongoing certifications
## Ongoing Certification Report (OCR)

??? abstract "**ID:** FRD-OCR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A regular report that is supplied by FedRAMP Certified cloud service providers to agency customers, following FedRAMP Collaborative Continuous Monitoring rules.


    **Also:** ongoing certification report, OCR, OCRs
## Ongoing Incident Report (OIR)

??? abstract "**ID:** FRD-OIR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A recurring report about an ongoing incident that is supplied by FedRAMP Certified cloud service providers to FedRAMP and agency customers, aligned to the rules in the FedRAMP Incident Communications Procedures.


    **Related Terms Group:** [Incident](#related-terms-group-incident)

    **Also:** ongoing incident report, ongoing incident reports, OIR, OIRs
## Overdue Vulnerability

??? abstract "**ID:** FRD-ODV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability that the provider intends to fully mitigate or remediate but has not or will not do so within the time frames recommended or required by FedRAMP.


    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** overdue vulnerability, overdue vulnerabilities
## Partially Mitigated Vulnerability

??? abstract "**ID:** FRD-PMV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability where the likelihood or Potential Agency Impact N-rating has been reduced from the original evaluation but the risk of exploitation still exists and the vulnerability is still detected.


    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** partially mitigated vulnerability, partially mitigated vulnerabilities, partially mitigate vulnerabilities
## Persistent FedRAMP Assessment

??? abstract "**ID:** FRD-PFA"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Follow-on assessments of a cloud service offering focused on Key Security Indicators, coordinated by the provider with all necessary assessors, to maintain FedRAMP Certification or change its FedRAMP Certification class.


    **Related Terms Group:** [Assessment](#related-terms-group-assessment)

    **Also:** persistent FedRAMP assessment, PFRA
## Persistently

??? abstract "**ID:** FRD-PER"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Occurring in a firm, steady way that is repeated over a long period of time in spite of obstacles or difficulties. Persistent activities may vary between actors, may occur irregularly, and may include interruptions or waiting periods between cycles. These attributes of persistent activities should be intentional, understood, and documented; the status of persistent activities will always be known.

    ---

    _**Note:** The use of persistently indicates a process that may not always occur continuously (without interruption or gaps) or regularly (on a consistent, predictable basis) but will repeat frequently in cycles. It aligns generally with historical misuse of "continuous" in federal information security policies._

    **Also:** persistently, persistent
## Potential Agency Impact

??? abstract "**ID:** FRD-PAI"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The estimated cumulative effect of unauthorized access, disruption, harm, or other adverse impacts to all agencies using the cloud service that are likely to result from security incidents or the exploitation of vulnerabilities in the cloud service offering; as estimated following appropriate FedRAMP rules to calculate the Potential Agency Impact N-rating (PAIN).


    **Also:** potential agency impact, potential agency impacts, PAIN, Potential Agency Impact N-rating
## Privileged Account

??? abstract "**ID:** FRD-PAC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    An account with elevated privileges that enables administrative functions over some aspect of the cloud service offering that may affect the confidentiality, integrity, or availability of information beyond those given to normal users; levels of privilege may vary wildly.

    ---

    _**Note:** Any references to privileged accounts in FedRAMP materials should be presumed to apply to privileged roles or other similar capabilities that are used to assign privileges to privileged accounts._

    **Related Terms Group:** [Accounts](#related-terms-group-accounts)

    **Also:** privileged account, privileged accounts
## Promptly

??? abstract "**ID:** FRD-PRO"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Without unnecessary delay.

    ---

    _**Note:** The use of promptly in FedRAMP materials frames conveys a need for urgent action where the expected time frame will vary by circumstance but earlier action is more likely to improve security outcomes and increase the security posture of a cloud service offering._

    **Also:** promptly, prompt
## Provider

??? abstract "**ID:** FRD-PRV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The cloud service provider responsible for a cloud service offering in the context of FedRAMP Certification.

    ---

    _**Note:** FedRAMP Consolidated Rules frequently refer to providers without using the full term "cloud service provider" or acronym "CSP"._

    **Related Terms Group:** [Stakeholder](#related-terms-group-stakeholder)

    **Also:** provider, providers, cloud service provider, cloud service providers
## Quarterly Review

??? abstract "**ID:** FRD-QTR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A regular synchronous meeting hosted by a FedRAMP Certified cloud service provider for agency customers, following FedRAMP Collaborative Continuous Monitoring rules.


    **Related Terms Group:** [Certification](#related-terms-group-certification)

    **Also:** quarterly review, quarterly reviews
## Regularly

??? abstract "**ID:** FRD-RGL"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Performing the activity on a consistent, predictable, and repeated basis, at set intervals, automatically if possible, following a documented plan. These intervals may vary as appropriate between different activities.


    **Also:** regularly, regular
## Remediated Vulnerability

??? abstract "**ID:** FRD-RMV"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A vulnerability that has been neutralized or eliminated and is no longer detected.


    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** remediated vulnerability, remediated vulnerabilities, remediate vulnerabilities
## Responsibly

??? abstract "**ID:** FRD-RSP"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    In a way that shows that you have good judgment and the ability to act correctly and make decisions on your own.

    ---

    _**Note:** Refrain from broadcasting any details that might assist adversaries in their endeavors, disclosing vulnerabilities prior to full remediation, or providing overly specific technical information that could potentially facilitate further compromise._

    **Also:** responsibly
## Routine Recurring Change

??? abstract "**ID:** FRD-RTR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The type of significant change that regularly and routinely recurs as part of ongoing operations, vulnerability mitigation, or vulnerability remediation.


    **Related Terms Group:** [Significant Changes](#related-terms-group-significant-changes)

    **Also:** routine recurring, routine recurring change, routine recurring changes
## Security Category

??? abstract "**ID:** FRD-SCT"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning from NIST FIPS 199, which is "The characterization of information or an information system based on an assessment of the potential impact that a loss of confidentiality, integrity, or availability of such information or information system would have on organizational operations, organizational assets, or individuals." Security categories are often referred to as "impact levels" and include Low, Moderate, and High.


    **Reference:** [NIST FIPS 199 Standards for Security Categorization of Federal Information and Information Systems](https://csrc.nist.gov/pubs/fips/199/final)

    **Also:** security category, security categories, impact level, impact levels
## Significant Change

??? abstract "**ID:** FRD-SGC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning given in NIST SP 800-37 Rev. 2 which is "a change that is likely to substantively affect the security or privacy posture of a system."


    **Reference:** [NIST SP 800-37 Rev. 2](https://csrc.nist.gov/pubs/sp/800/37/r2/final)

    **Related Terms Group:** [Significant Changes](#related-terms-group-significant-changes)

    **Also:** significant change, significant changes
## Third-Party Information Resource

??? abstract "**ID:** FRD-TPR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Any information resource that is not entirely included in the Minimum Assessment Scope for the cloud service offering obtaining FedRAMP Certification.


    **Related Terms Group:** [Information Resource](#related-terms-group-information-resource)

    **Also:** third-party information resource, third-party information resources
## Top-Level Administrative Account

??? abstract "**ID:** FRD-TLA"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The most privileged account with the highest level of access within a cloud service offering for a customer organization, typically with complete control over all aspects of the cloud service offering, including managing resources, users, access, privileges, and the account itself.

    ---

    _**Note:** Any references to top-level administrative accounts in FedRAMP materials should be presumed to apply to top-level administrative roles or other similar capabilities that are used to assign top-level administrative account privileges._

    **Related Terms Group:** [Accounts](#related-terms-group-accounts)

    **Also:** top-level administrative account, top-level administrative accounts
## Transformative Change

??? abstract "**ID:** FRD-TRF"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The type of significant change that introduces substantive potential security risks that are likely to affect existing risk determinations and must be assessed in depth.

    ---

    _**Note:** Transformative changes typically introduce major features or capabilities that may change how a customer uses the service (in whole or in part) and require extensive updates to security assessments, operational procedures, deployment plans, and documentation._

    **Related Terms Group:** [Significant Changes](#related-terms-group-significant-changes)

    **Also:** transformative, transformative change, transformative changes
## Trust Center

??? abstract "**ID:** FRD-TRC"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    A secure repository or service used by cloud service providers to store and share FedRAMP Certification Data. Trust centers are the complete and definitive source for FedRAMP Certification Data and must follow the FedRAMP Certification Data Sharing rules to be FedRAMP-compatible.

    ---

    _**Note:** In FedRAMP documentation, all references to trust centers indicate FedRAMP-compatible trust centers unless otherwise specified._

    **Also:** trust center, trust centers
## Validation

??? abstract "**ID:** FRD-VLN"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Confirmation through objective evidence that implemented security capabilities and related certification data are suitable for their intended FedRAMP Certification use and support the expected security outcomes for a cloud service offering.

    ---

    _**Note:** This adapts the ISO conformity assessment concept of validation to the FedRAMP Certification context._

    **Reference:** [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)

    **Also:** validation, validate, validated
## Verification

??? abstract "**ID:** FRD-VRF"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Confirmation through objective evidence that specified FedRAMP Practices have been fulfilled for a cloud service offering.

    ---

    _**Note:** This adapts the ISO conformity assessment concept of verification to the FedRAMP Certification context._

    **Reference:** [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)

    **Also:** verification, verify, verified
## Vulnerability

??? abstract "**ID:** FRD-VUL"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    Has the meaning given to "security vulnerability" in 6 USC § 650 (25), which is "any attribute of hardware, software, process, or procedure that could enable or facilitate the defeat of [...] management, operational, and technical controls used to protect against an unauthorized effort to adversely affect the confidentiality, integrity, and availability of an information system or its information." This includes gaps in Rev5 Controls and 20x Key Security Indicators, software vulnerabilities, misconfigurations, exposures, weak credentials, insecure services, and all other such potential weaknesses in protection (intentional or unintentional).


    **Reference:** [6 USC § 650 (25)](https://www.govinfo.gov/app/details/USCODE-2024-title6/USCODE-2024-title6-chap1-subchapXVIII-sec650)

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** vulnerability, vulnerabilities
## Vulnerability Detection

??? abstract "**ID:** FRD-VLD"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The systematic process of discovering and identifying security vulnerabilities in information resources through assessment, scanning, threat intelligence, vulnerability disclosure mechanisms, bug bounties, supply chain monitoring, and other capabilities. This process includes the initial discovery of a vulnerability's existence and the determination of affected information resources within a cloud service offering.

    ---

    _**Note:** This definition applies to other forms such as "detect vulnerabilities" or simply "detection" / "detected" used in FedRAMP materials._

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** vulnerability detection, detect vulnerabilities, detect, detection, detected
## Vulnerability Response

??? abstract "**ID:** FRD-VLR"
    **Changelog:**
    - **2026-07-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.

!!! quote ""
    The systematic process of tracking, evaluating, mitigating, monitoring, remediating, assessing exploitation, reporting, and otherwise managing detected vulnerabilities.

    ---

    _**Note:** This definition applies to other forms such as "respond to vulnerabilities" or simply "response" / "responded" used in FedRAMP materials._

    **Related Terms Group:** [Vulnerability](#related-terms-group-vulnerability)

    **Also:** vulnerability response, respond to vulnerabilities, respond, response, responded
