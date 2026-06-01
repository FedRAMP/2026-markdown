---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# FedRAMP's Responsibilities



---


## FedRAMP Certification {#fedramp-certification}

The FedRAMP Certification rules define how cloud service offerings obtain and maintain FedRAMP Certification across certification classes and paths. They give providers, assessors, agencies, and FedRAMP a common set of expectations for required rule sets, current evidence, independent verification and validation, and ongoing certification decisions.

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
## FedRAMP Security Inbox {#fedramp-security-inbox}

The FedRAMP Security Inbox rules ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.

These rules apply to FedRAMP when communicating with cloud service providers.

### Verified Emails

??? abstract "FSI-FRP-VRE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST send messages to cloud service providers using an official @fedramp.gov or @gsa.gov email address with properly configured Sender Policy Framework (SPF), DomainKeys Identified Mail (DKIM), and Domain-based Message Authentication Reporting and Conformance (DMARC) email authentication.


    ---

    _**Note:** Anyone at GSA can send email from @fedramp.gov or @gsa.gov - FedRAMP team members will typically have "FedRAMP" or "Q20B" in their name but this is not universal or enforceable. The nature of government enterprise IT services makes it difficult for FedRAMP to isolate FedRAMP-specific team members with enforceable identifiers._

### Criticality Designators

??? abstract "FSI-FRP-CDS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST convey the criticality of the message in the subject line, IF the message requires an elevated reaction, using one of the following designators:

    1. **Emergency:** There is a potential incident or crisis such that FedRAMP requires an extremely urgent reaction; emergency messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Emergency Test:** FedRAMP requires an extremely urgent reaction to confirm the functionality and effectiveness of the FedRAMP Security Inbox; emergency test messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Important:** There is an important issue that FedRAMP requires the cloud service provider to address; important messages will contain reasonable timeframes for reaction and failure to meet these timeframes may result in corrective action.


    ---

    _**Note:** Messages sent by FedRAMP without one of these designators are considered general communications and do not require an elevated reaction; these may be resolved in the normal course of business by the cloud service provider._

    ---
    **Terms:** [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../definitions/#incident){ data-preview }
### Use FedRAMP_Security Email in Emergencies

??? abstract "FSI-FRP-UFS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST send Emergency and Emergency Test designated messages from fedramp_security@gsa.gov OR fedramp_security@fedramp.gov.


### Public Notice of Emergency Tests

??? abstract "FSI-FRP-PNT"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify publicly by web using fedramp.gov.

!!! quote ""
    FedRAMP MUST post a public notice at least 10 business days in advance of sending an Emergency Test message; such notices MUST include explanation of the likely expected actions and timeframes for the Emergency Test message.

    **Timeframe:** 10 business days


    ---

    _**Notes:**_

    - _Public notice may include blog posts, social media posts, announcements during Community Updates, or e-blasts._
    - _As this process matures, additional confirmed options may become available._
    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }
### Required Actions

??? abstract "FSI-FRP-RQA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the required actions in the body of messages that require an elevated reaction.


### Elevated Reaction Timeframes

??? abstract "FSI-FRP-ERT"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the expected timeframe for completing required actions in the body of messages that require an elevated reaction; timeframes for actions will vary depending on the situation but the default timeframes to provide an estimated resolution time for Emergency and Emergency Test designated messages will be as follows:

    1. **Class D:** within 12 hours
    1. **Class C:** by 3:00 p.m. Eastern Time on the 2nd business day
    1. **Class B:** by 3:00 p.m. Eastern Time on the 3rd business day
    1. **Class A:** by 3:00 p.m. Eastern Time on the 5th business day


    ---

    _**Note:** FedRAMP Class D Certified cloud service providers are expected to address Emergency messages (including tests) from FedRAMP with a reaction time appropriate to operating a service where failure to react rapidly might have a severe or debilitating customer effect on the U.S. Government; some Emergency messages may require faster reaction and all such messages should be addressed as quickly as possible._

    ---
    **Terms:** [Debilitating Customer Effect](../definitions/#debilitating-customer-effect){ data-preview }, [FedRAMP Certified](../definitions/#fedramp-certified){ data-preview }
### Explain Corrective Actions

??? abstract "FSI-FRP-COR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the corrective actions that will result from failure to complete the required actions in the body of messages that require an elevated reaction; such actions may vary from negative ratings in the FedRAMP Marketplace to suspension of FedRAMP Certification depending on the severity of the event.


### Reaction Metrics

??? abstract "FSI-FRP-RPM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY track and publicly share the time required by cloud service providers to take the actions specified in messages that require an elevated reaction.


## Incident Communications Procedures {#incident-communications-procedures}

The Incident Communications Procedures rules explain how providers must communicate incident information to FedRAMP and government customers.

These rules apply to FedRAMP.

### Ongoing Review

??? abstract "ICP-FRP-ORV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST periodically review Incident Communications Procedures implementation with providers based on lack of reporting or other information.

    !!! warning "Corrective Actions"
        - FedRAMP will request a Corrective Action Plan when a provider is unaware of the rules or has failed to implement proper procedures.
        - FedRAMP will grant a 3 month grace period to implement proper procedures pending remediation and possible revocation of FedRAMP Certification.


    ---
    **Terms:** [Incident](../definitions/#incident){ data-preview }
## Marketplace Listing {#marketplace-listing}

The Marketplace Listing rules define how FedRAMP decides which cloud service offerings, assessors, and advisors may be listed in the FedRAMP Marketplace. These rules help agencies and other customers rely on the Marketplace as a consistent source of eligible services and supporting organizations, while requiring listed organizations to supply accurate, accessible, and machine-readable information.

These rules apply to FedRAMP activities related to the FedRAMP Marketplace.

### Decision Summaries

??? abstract "MKT-FRP-DSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST include a summary with any Marketplace listing decision that explains why the decision was made, including an explanation of deficiencies if applicable.


### Marketplace JSON Schemas

??? abstract "MKT-FRP-MJS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST publish and maintain JSON schemas for required machine-readable Marketplace web information supplied by advisors and assessors.



    **Reference:** [FedRAMP JSON Schemas on GitHub](https://github.com/FedRAMP/schemas)

    ---
    **Terms:** [Machine-Readable](../definitions/#machine-readable){ data-preview }
### Scope of FedRAMP

??? abstract "MKT-FRP-SOF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST NOT list cloud service offerings in the Marketplace or perform any FedRAMP Certification activities unless it determines the cloud service offering is within the scope of FedRAMP.



    **Reference:** [Scope of FedRAMP](https://fedramp.gov/docs/authority/scope)

    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }
## FedRAMP Recognition of Independent Assessment Services {#fedramp-recognition-of-independent-assessment-services}

The FedRAMP Recognition of Independent Assessment Services rules explain the requirements for assessors to obtain and maintain FedRAMP Recognition in order to support the FedRAMP Certification process.

These rules apply to FedRAMP when evaluating independent assessment services for initial or ongoing FedRAMP Recognition.

### Foreign Ownership Collection

??? abstract "REC-FRP-FOC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST maintain a process to collect foreign ownership, control, or influence declarations from FedRAMP Recognized assessors and updates to those declarations.


    ---
    **Terms:** [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }
### Recognized Assessors Only

??? abstract "REC-FRP-RAO"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST NOT accept verification, validation, or other attestations from independent assessors who are not FedRAMP Recognized.


    ---
    **Terms:** [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Validation](../definitions/#validation){ data-preview }, [Verification](../definitions/#verification){ data-preview }
### Double Revocation Disqualification

??? abstract "REC-FRP-DRD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST NOT restore FedRAMP Recognition for an assessor after FedRAMP has revoked that assessor's FedRAMP Recognition 2 times.


    ---
    **Terms:** [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }
## Significant Change Notifications {#significant-change-notifications}

The Significant Change Notifications rules supply a simple framework allowing providers to make significant changes to their own products while keeping agency customers in the loop. These rules organize significant changes into clear categories so agencies can understand the expected risk and make authorization decisions accordingly.

These rules apply to FedRAMP.

### Corrective Action Plan Conditions

??? abstract "SCN-FRP-CAP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY require providers to delay significant changes beyond the standard Significant Change Notification period and/or submit significant changes for approval in advance as a condition of a formal FedRAMP Corrective Action Plan or other agreement.


    ---

    _**Note:** The circumstances and conditions of such a Corrective Action Plan will vary and be documented in the Correcive Action Plan._

    ---
    **Terms:** [Significant Change](../definitions/#significant-change){ data-preview }
## Vulnerability Detection and Response {#vulnerability-detection-and-response}

The Vulnerability Detection and Response rules require providers to continuously identify, analyze, prioritize, mitigate, and remediate vulnerabilities and related exposures through automated systems. These rules give providers flexibility in implementation while ensuring agencies receive the information needed to support ongoing authorization decisions.

These rules apply to FedRAMP when setting expectations for specific cloud service providers.

### Additional Requirements

??? abstract "VDR-FRP-ARP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY require providers to share additional vulnerability information, alternative reports, or to report at an alternative frequency as a condition of a FedRAMP Corrective Action Plan or other agreements with federal agencies.


    ---
    **Terms:** [Vulnerability](../definitions/#vulnerability){ data-preview }
### Sensitive Details

??? abstract "VDR-FRP-ADV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY require providers to share additional information or details about vulnerabilities, including sensitive information that would likely lead to exploitation, as part of review, response or investigation by necessary parties.


    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }, [Vulnerability](../definitions/#vulnerability){ data-preview }, [Vulnerability Response](../definitions/#vulnerability-response){ data-preview }
