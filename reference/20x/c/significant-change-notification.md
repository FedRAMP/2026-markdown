---
tags:
  - 20x
  - FedRAMP
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Significant Change Notification

The Significant Change Notification rules supply a simple framework allowing providers to make significant changes to their own products while keeping agency customers in the loop. These rules organize significant changes into clear categories so agencies can understand the expected risk and make authorization decisions accordingly.

**Subsets**

- [FedRAMP Responsibilities](#fedramp-responsibilities)
- [General Provider Responsibilities](#general-provider-responsibilities)
- [Adaptive Changes](#adaptive-changes)
- [Routine Recurring Changes](#routine-recurring-changes)
- [Transformative Changes](#transformative-changes)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## FedRAMP Responsibilities {#fedramp-responsibilities}

These rules apply to FedRAMP.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">FedRAMP</span></span></span>
</div>

### Corrective Action Plan Conditions

??? abstract "SCN-FRP-CAP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MAY require providers to delay significant changes beyond the standard Significant Change Notification period and/or submit significant changes for approval in advance as a condition of a formal FedRAMP Corrective Action Plan or other agreement.


    ---

    _**Note:** The circumstances and conditions of such a Corrective Action Plan will vary and be documented in the Correcive Action Plan._

    ---
    **Terms:** [Significant Change](../../../definitions/#significant-change){ data-preview }
## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Evaluate Changes

??? abstract "SCN-CSO-EVA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Significant Change Notification (SCN-CSO-INF)](https://fedramp.gov/schemas/fedramp-significant-change-notification-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST evaluate all potential significant changes to determine the type of significant change and follow the appropriate Significant Change Notification rules.

    1. Is it a significant change? --> Continue evaluation and follow the Significant Change Notification rules.
    1. If it is, is it an FedRAMP Certification class change?  --> This requires a new assessment and cannot be done under the Significant Change Notification rules.
    1. If it is not, is it a routine recurring change? --> Follow the Routine Recurring Change rules (SCN-RTR Routine Recurring Changes).
    1. If it is not, is it a transformative change? --> Follow the Transformative Change rules (SCN-TRF Transformative Changes).
    1. If it is not, then it is an adaptive change --> Follow the Adaptive Change rules (SCN-ADP Adaptive Changes).


    ---
    **Terms:** [Adaptive Change](../../../definitions/#adaptive-change){ data-preview }, [Certification Class](../../../definitions/#certification-class){ data-preview }, [Certification Class Change](../../../definitions/#certification-class-change){ data-preview }, [Routine Recurring Change](../../../definitions/#routine-recurring-change){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
### Maintain Audit Records

??? abstract "SCN-CSO-MAR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST maintain auditable records of the significant change evaluation activities required by [SCN-CSO-EVA (Evaluate Changes)](#evaluate-changes){ data-preview } and make them available to FedRAMP as requested.


    ---

    _**Note:** These audit records must be available to FedRAMP on request; these records do not need to be included in the FedRAMP Certification Package by default and do not need to be emailed to FedRAMP continuously._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }
### Required Information

??? abstract "SCN-CSO-INF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Significant Change Notification (SCN-CSO-INF)](https://fedramp.gov/schemas/fedramp-significant-change-notification-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST include at least the following information in Significant Change Notifications:

    1. Service Offering FedRAMP ID
    1. Assessor Name (if applicable)
    1. Related Vulnerability (if applicable)
    1. Significant Change type and explanation of categorization
    1. Short description of change
    1. Reason for change
    1. Summary of customer impact, including changes to services and customer configuration responsibilities
    1. Plan and timeline for the change, including for the verification, assessment, and/or validation of impacted Key Security Indicators or Rev5 Controls
    1. Copy of the business or security impact analysis
    1. Name and title of approver


    ---

    _**Note:** Structure of the information may vary depending on how the provider tracks this internally._

    ---
    **Terms:** [Significant Change](../../../definitions/#significant-change){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
### Historical Notifications

??? abstract "SCN-CSO-HIS"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST keep 12 months of historical Significant Change Notifications available with their FedRAMP Certification Data.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }
### Human and Machine-Readable Notifications

??? abstract "SCN-CSO-HRM"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Significant Change Notifications Schema](https://fedramp.gov/schemas/fedramp-significant-change-notifications-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST make ALL Significant Change Notifications and related audit records available in human-readable and JSON formats.


    ---
    **Terms:** [Significant Change](../../../definitions/#significant-change){ data-preview }
### Additional Relevant Information

??? abstract "SCN-CSO-ARI"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY include additional relevant information in Significant Change Notifications.


    ---

    _**Note:** This allows providers to convey whatever additional information they think is relevant without worrying about negative consequences from not following an exact template._

    ---
    **Terms:** [Significant Change](../../../definitions/#significant-change){ data-preview }
### Notification Mechanisms

??? abstract "SCN-CSO-NOM"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY notify necessary parties in a variety of ways as long as the mechanism for notification is clearly documented in the FedRAMP Certification Package and easily accessible.


    ---

    _**Notes:**_

    - _The sharing mechanism should be designed based on the needs of the provider and their customers and may vary between providers._
    - _The default sharing mechanism for most providers during the SCN beta was to send an email to agency customers and upload a copy of the notification to the provider's secure sharing location._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
### Emergency Changes

??? abstract "SCN-CSO-EMG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY execute significant changes (including transformative changes) during an emergency or incident without following the Significant Change Notification rules in advance. In such emergencies, providers MUST follow all relevant procedures, notify all necessary parties, retroactively provide all Significant Change Notification materials, and complete appropriate assessment after the incident.


    ---

    _**Note:** Procedures for emergency changes should be documented in the FedRAMP Certification Package._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
## Adaptive Changes {#adaptive-changes}

These rules apply to all adaptive significant changes.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Notification Requirements

??? abstract "SCN-ADP-NTF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties via an update: FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties within 10 business days after finishing adaptive changes, also including the following information:

    **Timeframe:** 10 business days

    1. Summary of any new risks identified and/or vulnerabilities resulting from the change (if applicable)


    ---

    _**Notes:**_

    - _Activities that match the adaptive significant change type are a frequent and normal part of iteratively improving a service by deploying new functionality or modifying existing functionality in a way that is typically transparent to customers and does not introduce significant new security risks._
    - _In general, most changes that do not happen regularly will be adaptive changes. This change type deliberately covers a wide range of activities in a way that requires assessment and consideration._

    ??? tip "Tips on adaptive changes"

        **Key Tests:**

        - Requires minimal changes to security plans or procedures


        - Requires some careful planning and project management to implement, but does not rise to the level of planning required for transformative changes


        - Requires verification of existing functionality and secure configuration after implementation


        **Examples:**

        - Updates to operating systems, containers, virtual machines, software or libraries with known breaking changes, complex steps, or service disruption


        - Deploying larger than normal incremental feature improvements in code or libraries that are the work of multiple weeks of development efforts but are not considered a major new service


        - Changing cryptographic modules where the new module meets the same standards and characteristics of the former


        - Replacing a like-for-like component where some security plan or procedure adjustments are required (e.g., scanning tool or managed database swap)


        - Adding models to existing approved AI services without exposing federal customer data to new services


    ---
    **Terms:** [Adaptive Change](../../../definitions/#adaptive-change){ data-preview }, [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Regularly](../../../definitions/#regularly){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
## Routine Recurring Changes {#routine-recurring-changes}

These rules apply to all routine recurring significant changes.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### No Notification Requirements

??? abstract "SCN-RTR-NNR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD NOT make formal Significant Change Notifications for routine recurring changes; this type of change is exempted from notification requirements.


    ---

    _**Notes:**_

    - _Activities that match the routine recurring significant change type are performed regularly and routinely by cloud service providers to address flaws or vulnerabilities, address incidents, and generally perform the typical maintenance and service delivery changes expected during day-to-day operations._
    - _These changes leverage mature processes and capabilities to identify, mitigate, and remediate risks as part of the change. They are often entirely automated and may occur without human intervention, even though they have an impact on security of the service._
    - _If the activity does not occur regularly and routinely then it cannot be a significant change of this type (e.g., replacing all physical firewalls to remediate a vulnerability is obviously not regular or routine)._

    ??? tip "Tips on ongoing operations"

        **Key Tests:**

        - Routine care and feeding by staff during normal duties


        - No major impact to service availability


        - Does not require executive approval


        **Examples:**

        - Provisioning or deprovisioning capacity to support service elasticity


        - Changing or tuning performance configurations for instances or services


        - Updating and maintaining operational handling of information flows and protection across physical and logical networks (e.g., updating firewall rules)


        - Generating or refreshing API or access tokens



    ??? tip "Tips on vulnerability management"

        **Key Tests:**

        - Minor, incremental patching or updates


        - Significant refactoring or migration process NOT required


        - No breaking changes


        **Examples:**

        - Updating security service or endpoint signatures


        - Routine patching of devices, operating systems, software or libraries


        - Updating and deploying code that applies normal fixes and improvements as part of a regular development cycle


        - Vulnerability remediation activity that simply replaces a known-bad component(s) with a better version of the exact same thing, running in the exact same way with no changes to processes


    ---
    **Terms:** [Incident](../../../definitions/#incident){ data-preview }, [Regularly](../../../definitions/#regularly){ data-preview }, [Routine Recurring Change](../../../definitions/#routine-recurring-change){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
## Transformative Changes {#transformative-changes}

These rules apply to all transformative significant changes.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Notification of Initial Plans

??? abstract "SCN-TRF-NIP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties via an update: FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties of initial plans for transformative changes at least 30 business days before starting transformative changes, including a summary of any likely security impacts or changes in risk.

    **Timeframe:** 30 business days


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
### Notification of Final Plans

??? abstract "SCN-TRF-NFP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties via an update: FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties of final plans for transformative changes at least 10 business days before starting transformative changes, including updates to all previously sent information.

    **Timeframe:** 10 business days


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
### Notification After Finishing

??? abstract "SCN-TRF-NAF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties via an update: FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties within 5 business days after finishing transformative changes, including updates to all previously sent information.

    **Timeframe:** 5 business days


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
### Notification After Verification

??? abstract "SCN-TRF-NAV"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties via an update: FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties within 5 business days after completing the verification, assessment, and/or validation of transformative changes, also including the following information:

    **Timeframe:** 5 business days

    1. Updates to all previously sent information
    1. Summary of any new risks identified and/or vulnerabilities resulting from the change (if applicable)
    1. Copy of the security assessment report (if applicable)


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
### Update Documentation

??? abstract "SCN-TRF-UPD"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST publish updated service documentation and other materials to reflect transformative changes within 30 business days after finishing transformative changes.

    **Timeframe:** 30 business days


    ---

    _**Note:** This requirement is focused on service documentation like user guides, information listed in the marketplace, and other such materials; it does not require updating the system security plan or FedRAMP Certification Package._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
### Third-Party Review

??? abstract "SCN-TRF-TPR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD engage a third-party assessor to review the scope and impact of the planned change before starting transformative changes if human validation is necessary; such reviews SHOULD be limited to security decisions that require human validation.


    ---

    _**Note:** Activities that match the transformative significant change type are rare for a cloud service offering, adjusted for the size, scale, and complexity of the service. Small cloud service offerings may go years without transformative changes, while hyperscale providers may release multiple transformative changes per year._


    ??? tip "Tips on transformative changes"

        **Key Tests:**

        - Alters the service risk profile or require new or significantly different actions to address customer responsibilities


        - Requires significant new design, development and testing with discrete associated project planning, budget, marketing, etc.


        - Requires extensive updates to security assessments, documentation, and how a large number of security requirements are met and validated


        **Examples:**

        - The addition, removal, or replacement of a critical third party service that handles a significant portion of information (e.g., IaaS change)


        - Increasing the security categorization of a service within the offering that actively handles federal customer data (does NOT include impact change of entire offering - see FedRAMP Certification class change)


        - Replacement of underlying management planes or paradigm shift in workload orchestration (e.g., bare-metal servers or virtual machines to containers, migration to kubernetes)


        - Datacenter migration where large amounts of federal customer data is moved across boundaries different from normal day-to-day operations


        - Adding a new AI-based capability that impacts federal customer data in a different way than existing services or capabilities (such as integrating a new third-party service or training on federal customer data)


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
