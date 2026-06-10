---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Certification Data Sharing

The Certification Data Sharing rules allow providers to store and share FedRAMP certification information through the platform they choose as long as it follows FedRAMP rules for access, accuracy, and transparency. This helps customers and the public review consistent, current security and compliance information while recognizing that the information usually remains the provider's intellectual property and is not federal information.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [FedRAMP-Compatible Trust Centers](#fedramp-compatible-trust-centers)
- [Using a Trust Center](#using-a-trust-center)
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
    - **Maintain:** 2027-08-01
    - **Grace Ends:** 2028-02-01
    - **Sign-up Form:** [ADDME](ADDME)



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications of any type.

### Public Information

??? abstract "CDS-CSO-PUB"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! schema "Related JSON Schema: [FedRAMP Public Marketplace Information Schema](https://fedramp.gov/schemas/fedramp-public-marketplace-information-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    Providers MUST publicly share up-to-date information about the cloud service offering in both human-readable and JSON formats, including at least the following information that is available and applicable:

    1. Direct link to the FedRAMP Marketplace for the offering
    1. Service Model
    1. Deployment Model
    1. Business Category
    1. UEI Number
    1. Sales Contact Information
    1. Security Contact Information
    1. Product Website Link
    1. Link to Product Logo
    1. Overall Service Description
    1. Detailed list of specific services and their security categories (see [CDS-CSO-SVC (Service List)](#service-list){ data-preview })
    1. Link to Secure Configuration Guidance
    1. Overview of documentation supplied by the provider for the cloud service offering
    1. Link to Trust Center landing page that includes instructions on accessing information in the trust center
    1. Next Ongoing Certification Report date (see [CCM-OCR-NRD (Next Report Date)](collaborative-continuous-monitoring.md#next-report-date){ data-preview })
    1. Current FedRAMP Recognized Independent Assessment Service


    ---

    _**Note:** Generally, this information should be available on a public webpage or publicly shared in a FedRAMP-compatible trust center._

    ---
    **Terms:** [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Recognized](../definitions/#fedramp-recognized){ data-preview }, [Ongoing Certification](../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Security Category](../definitions/#security-category){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Service List

??? abstract "CDS-CSO-SVC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST publicly share a detailed list of specific services and their security categories that are included in the cloud service offering using clear feature or service names that align with standard public marketing materials; this list MUST be complete enough for a potential customer to determine which services are and are not included in the FedRAMP Minimum Assessment Scope without requesting access to underlying FedRAMP Certification Data.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Security Category](../definitions/#security-category){ data-preview }
### Availability Reporting

??? abstract "CDS-CSO-AVR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service SHOULD be available even if the primary cloud service offering is unavailable.

        ---

        _**Note:** This service may be separate from the trust center._

    === "Class B"
        Providers with Class B Certifications MUST maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service MUST be available even if the primary cloud service offering is unavailable.

        ---

        _**Note:** This service may be separate from the trust center._

    === "Class C"
        Providers with Class C Certifications MUST maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service MUST be available even if the primary cloud service offering is unavailable.

        ---

        _**Note:** This service may be separate from the trust center._

    === "Class D"
        Providers with Class D Certifications MUST maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service MUST be available even if the primary cloud service offering is unavailable.

        ---

        _**Note:** This service may be separate from the trust center._


    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Incident](../definitions/#incident){ data-preview }, [Machine-Readable](../definitions/#machine-readable){ data-preview }
### Use Trust Centers

??? abstract "CDS-CSO-UTC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST use a FedRAMP-compatible trust center to store and share FedRAMP Certification Data with all necessary parties.


    ---

    _**Note:** Rules for FedRAMP-Compatible Trust Centers are explained in the Certification Data Sharing Rules under the FedRAMP-Compatible Trust Centers section (id: CDS-TRC)._

    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Consistency Between Formats

??? abstract "CDS-CSO-CBF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST use automation to ensure information remains consistent between human-readable and machine-readable formats when FedRAMP Certification Data is provided in both formats.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Machine-Readable](../definitions/#machine-readable){ data-preview }
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
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Likely](../definitions/#likely){ data-preview }
### Historical FedRAMP Certification Data

??? abstract "CDS-CSO-HAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST make historical versions of FedRAMP Certification Data available for three years to all necessary parties UNLESS otherwise specified by applicable FedRAMP rules; deltas between versions MAY be consolidated quarterly.


    ---

    _**Note:** Consolidating changes quarterly means that the historical status at the end of each quarter or at the time of the Ongoing Certification Report or Quarterly Review is sufficient, instead of maintaining separate versions with every single change that took place throughout the quarter._

    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Ongoing Certification](../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../definitions/#ongoing-certification-report-ocr){ data-preview }, [Quarterly Review](../definitions/#quarterly-review){ data-preview }
### Per-Service Certification Materials

??? abstract "CDS-CSO-PSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY supply per-service FedRAMP Certification materials.

    === "Class B"
        Providers with Class B Certifications MAY supply per-service FedRAMP Certification materials.

    === "Class C"
        Providers with Class C Certifications MAY supply per-service FedRAMP Certification materials.

    === "Class D"
        Providers with Class D Certifications MUST supply per-service FedRAMP Certification materials.


    ---

    _**Notes:**_

    - _Providers determine what they consider to be separate services, based on maximizing the customer experience for agencies who may only adopt some services and not others._
    - _Providers are encouraged to provide a single comprehensive set of materials for all shared aspects of the service offering and only provide separate materials for unique aspects of each service to minimize the burden on providers and agencies._
### Responsible Public Package Sharing

??? abstract "CDS-CSO-RPS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MAY responsibly share some or all of the information in a FedRAMP Certification Package publicly or with other parties if the provider determines doing so will NOT likely have an adverse effect on the cloud service offering.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../definitions/#cloud-service-offering){ data-preview }, [Likely](../definitions/#likely){ data-preview }, [Responsibly](../definitions/#responsibly){ data-preview }
## FedRAMP-Compatible Trust Centers {#fedramp-compatible-trust-centers}

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
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Programmatic Access

??? abstract "CDS-TRC-PAC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Trust centers MUST provide documented programmatic access to all FedRAMP Certification Data, including programmatic access to human-readable materials.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Agency Access Inventory

??? abstract "CDS-TRC-AAI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Trust centers MUST maintain an inventory and history of federal agency users or systems with access to FedRAMP Certification Data and MUST make this information available to FedRAMP upon request.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Access Logging

??? abstract "CDS-TRC-ACL"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Trust centers MUST log access to FedRAMP Certification Data and store summaries of access for at least six months; such information, as it pertains to specific parties, SHOULD be made available upon request by those parties.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Human and Machine-Readable Certification Data

??? abstract "CDS-TRC-HMR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Trust centers SHOULD make FedRAMP Certification Data available to view and download in both human-readable and machine-readable formats.


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }, [Machine-Readable](../definitions/#machine-readable){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
### Self-Service Access Management

??? abstract "CDS-TRC-SSM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Trust centers SHOULD include features that encourage all necessary parties to provision and manage access to FedRAMP Certification Data for their users and services directly.


    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
## Using a Trust Center {#using-a-trust-center}

These rules apply to providers that are using a FedRAMP-compatible trust center instead of USDA Connect; they DO NOT apply to providers using USDA Connect.

### Agency Access Denial

??? abstract "CDS-UTC-AAD"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using info@fedramp.gov.


!!! quote ""
    Providers MUST notify FedRAMP within 5 business days of denying an agency access request for FedRAMP Certification Data.

    **Timeframe:** 5 business days


    ---
    **Terms:** [Certification Data](../definitions/#certification-data){ data-preview }
### Agency Access

??? abstract "CDS-UTC-AGA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD supply access to the FedRAMP Certification package with agencies upon request.


    ---
    **Terms:** [Certification Package](../definitions/#certification-package){ data-preview }
## Rev5-Specific Provider Responsibilities {#rev5-specific-provider-responsibilities}

These rules apply to providers for FedRAMP Rev5 Certifications.

### Trust Center Migration

??? abstract "CDS-CSF-TCM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify All Necessary Parties by update using FedRAMP Certification Data.


!!! quote ""
    Providers MUST notify all necessary parties when migrating to a trust center and MUST provide information in their existing USDA Connect Community Portal secure folders explaining how to use the trust center to obtain FedRAMP Certification Data.


    ---
    **Terms:** [All Necessary Parties](../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../definitions/#certification-data){ data-preview }, [Trust Center](../definitions/#trust-center){ data-preview }
