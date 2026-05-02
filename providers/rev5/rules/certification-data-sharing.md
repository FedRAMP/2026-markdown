---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Certification Data Sharing


---


## General Provider Responsibilities

These rules apply to providers for FedRAMP Certifications of any type.

### Public Information

??? abstract "CDS-CSO-PUB"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST publicly share up-to-date information about the cloud service offering in both human-readable and machine-readable formats, including at least:

    1. Direct link to the FedRAMP Marketplace for the offering
    1. Service Model
    1. Deployment Model
    1. Business Category
    1. UEI Number
    1. Contact Information
    1. Overall Service Description
    1. Detailed list of specific services and their security categories (see CDS-CSO-SVC)
    1. Summary of customer responsibilities and secure configuration guidance (if applicable, see the FedRAMP Secure Configuration Guide process)
    1. Process for accessing information in the trust center (if applicable)
    1. Availability status and recent disruptions for the trust center (if applicable)
    1. Customer support information for the trust center (if applicable)
    1. Next Ongoing Certification Report date (see CCM-OCR-NRD)


    ---

    _**Note:** Generally, this information should be available on a public webpage._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Service List

??? abstract "CDS-CSO-SVC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST publicly share a detailed list of specific services and their security categories that are included in the cloud service offering using clear feature or service names that align with standard public marketing materials; this list MUST be complete enough for a potential customer to determine which services are and are not included in the FedRAMP Minimum Assessment Scope without requesting access to underlying FedRAMP Certification Data.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }
### Use Trust Centers

??? abstract "CDS-CSO-UTC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST use a FedRAMP-compatible trust center to store and share FedRAMP Certification Data with all necessary parties.


    ---

    _**Note:** Rules for FedRAMP-Compatible Trust Centers are explained in the Certification Data Sharing Rules under the FedRAMP-Compatible Trust Centers section (id: CDS-TRC)._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Consistency Between Formats

??? abstract "CDS-CSO-CBF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST use automation to ensure information remains consistent between human-readable and machine-readable formats when FedRAMP Certification Data is provided in both formats.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
### Responsible Information Sharing

??? abstract "CDS-CSO-RIS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST provide sufficient information in FedRAMP Certification Data to support agency authorization decisions but SHOULD NOT include sensitive information that would likely enable a threat actor to gain unauthorized access, cause harm, disrupt operations, or otherwise have a negative adverse impact on the cloud service offering.


    ---

    _**Note:** This is not a license to exclude accurate risk information, but specifics that would likely lead to compromise should be abstracted. A breach of confidentiality with FedRAMP Certification Data should be anticipated by a secure cloud service provider._


    ??? tip "Tips on sensitive information in FedRAMP Certification Data"

        **Key Tests:**

        - Passwords, API keys, access credentials, etc.


        - Excessive detail about methodology that exposes weaknesses


        - Personally identifiable information about employees


        **Examples:**

        - DON'T: "In an emergency, an administrator with physical access to a system can log in using "secretadmin" with the password "pleasewutno""


        - DO: "In an emergency, administrators with physical access can log in directly."


        - DON'T: "All backup MFA credentials are stored in a SuperSafe Series 9000 safe in the CEOs office."


        - DO: "All backup MFA credentials are stored in a UL Class 350 safe in a secure location with limited access."


        - DON'T: "During an incident, the incident response team lead by Jim Smith (555-0505) will open a channel at the conference line (555-0101 #97808 passcode 99731)..."


        - DO: "During an incident, the incident response team will coordinate over secure channels."


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
### Historical FedRAMP Certification Data

??? abstract "CDS-CSO-HAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST make historical versions of FedRAMP Certification Data available for three years to all necessary parties UNLESS otherwise specified by applicable FedRAMP rules; deltas between versions MAY be consolidated quarterly.

    **Effective Date(s):**
    - **Obtain:** 2027-05-04
    - **Maintain:** 2027-05-04
    - **Grace By Assessment Months:** 2


    ---

    _**Note:** Consolidating changes quarterly means that the historical status at the end of each quarter or at the time of the Ongoing Authorization Report or Quarterly Review is sufficient, instead of maintaining separate versions with every single change that took place throughout the quarter._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Quarterly Review](../../../definitions/#quarterly-review){ data-preview }
### Per-Service Certification Materials

??? abstract "CDS-CSO-PSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    === "Class A"
        Providers of Class A offerings MAY supply per-service FedRAMP Certification materials.

    === "Class B"
        Providers of Class B offerings MAY supply per-service FedRAMP Certification materials.

    === "Class C"
        Providers of Class C offerings MAY supply per-service FedRAMP Certification materials.

    === "Class D"
        Providers of Class D offerings MUST supply per-service FedRAMP Certification materials.

        **Effective Date(s):**
        - **Obtain:** 2027-05-04
        - **Maintain:** 2027-05-04
        - **Grace By Assessment Months:** 2


    ---

    _**Notes:**_

    - _Providers determine what they consider to be separate services, based on maximizing the customer experience for agencies who may only adopt some services and not others._
    - _Providers are encouraged to provide a single comprehensive set of materials for all shared aspects of the service offering and only provide separate materials for unique aspects of each service to minimize the burden on providers and agencies._
    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
## FedRAMP-Compatible Trust Centers

These rules apply to trust centers that are FedRAMP-compatible.

### Uninterrupted Sharing

??? abstract "CDS-TRC-USH"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers MUST share FedRAMP Certification Data with all necessary parties without interruption.


    ---

    _**Note:** "Without interruption" means that parties should not have to request manual approval each time they need to access FedRAMP Certification Data or go through a complicated process. The preferred way of ensuring access without interruption is to use on-demand just-in-time access provisioning._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Programmatic Access

??? abstract "CDS-TRC-PAC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers MUST provide documented programmatic access to all FedRAMP Certification Data, including programmatic access to human-readable materials.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Agency Access Inventory

??? abstract "CDS-TRC-AAI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers MUST maintain an inventory and history of federal agency users or systems with access to FedRAMP Certification Data and MUST make this information available to FedRAMP upon request.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Access Logging

??? abstract "CDS-TRC-ACL"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers MUST log access to FedRAMP Certification Data and store summaries of access for at least six months; such information, as it pertains to specific parties, SHOULD be made available upon request by those parties.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Human and Machine-Readable

??? abstract "CDS-TRC-HMR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers SHOULD make FedRAMP Certification Data available to view and download in both human-readable and machine-readable formats.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Self-Service Access Management

??? abstract "CDS-TRC-SSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Trust centers SHOULD include features that encourage all necessary parties to provision and manage access to FedRAMP Certification Data for their users and services directly.


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
## Using a Trust Center

These rules apply to providers that are using a FedRAMP-compatible trust center instead of USDA Connect; they DO NOT apply to providers using USDA Connect.

### Public Guidance

??? abstract "CDS-UTC-PGD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST publicly provide plain-language policies and guidance for all necessary parties that explains how they can obtain and manage access to FedRAMP Certification Data stored in the trust center.


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Agency Access

??? abstract "CDS-UTC-AGA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD share the FedRAMP Certification package with agencies upon request.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Certification Package](../../../definitions/#certification-package){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
### Agency Access Denial

??? abstract "CDS-UTC-AAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using info@fedramp.gov.

!!! quote ""
    Providers MUST notify FedRAMP by email to info@fedramp.gov within 5 business days of denying an agency access request for FedRAMP Certification Data.

    **Timeframe:** 5 business days


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
## Rev5-Specific Provider Responsibilities

These rules apply to providers for FedRAMP Rev5 Certifications.

### Trust Center Migration

??? abstract "CDS-CSL-TCM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify all necessary parties by update using FedRAMP Certification Data.

!!! quote ""
    Providers MUST notify all necessary parties when migrating to a trust center and MUST provide information in their existing USDA Connect Community Portal secure folders explaining how to use the trust center to obtain FedRAMP Certification Data.


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Structured Certification Data

??? abstract "CDS-CSL-SCD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    === "Class A"
        Providers of Class A offerings MUST supply semi-structured text-based FedRAMP Certification Data.

        **Effective Date(s):**
        - **Obtain:** 2027-01-01
        - **Maintain:** 2027-05-04
        - **Grace By Assessment Months:** 2

    === "Class B"
        Providers of Class B offerings MUST supply semi-structured text-based FedRAMP Certification Data.

        **Effective Date(s):**
        - **Obtain:** 2027-01-01
        - **Maintain:** 2027-05-04
        - **Grace By Assessment Months:** 2

    === "Class C"
        Providers of Class C offerings MUST supply semi-structured text-based FedRAMP Certification Data.

        **Effective Date(s):**
        - **Obtain:** 2027-01-01
        - **Maintain:** 2027-05-04
        - **Grace By Assessment Months:** 2

    === "Class D"
        Providers of Class D offerings MUST supply comprehensive machine-readable FedRAMP Certification Data.

        **Effective Date(s):**
        - **Obtain:** 2027-05-04
        - **Maintain:** 2027-05-04
        - **Grace By Assessment Months:** 2


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
