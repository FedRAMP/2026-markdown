---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Agency Use of FedRAMP Certified Cloud Services (Needs Review)

The Agency Use rules summarize the many demands made on agencies by the FedRAMP Authorization Act and OMB Memorandum M-24-15 in a simple, clear, easy-to-follow set of FedRAMP-style rules. These rules align agency policies, authorization letters, machine-readable tools, secure configuration review, continuous monitoring, and communication with FedRAMP so certifications can be reused consistently across government.

**Rule Sections**

- [General Agency Responsibilities](#general-agency-responsibilities)
- [Use of FedRAMP Certifications](#use-of-fedramp-certifications)
- [Agency Sponsored Certifications](#agency-sponsored-certifications)


---


## General Agency Responsibilities {#general-agency-responsibilities}

These rules apply to agencies based on the FedRAMP Authorization Act, OMB M-24-15, and related FedRAMP policies.

### Agency Internal Policies

??? abstract "AGU-AGC-AIP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST maintain agency-wide internal policies aligned with FedRAMP standards and the principles and directives of OMB Memorandum M-24-15.


### Notify FedRAMP After Authorization

??? abstract "AGU-AGC-NAL"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using ato-letter@fedramp.gov.

!!! quote ""
    Agencies MUST notify FedRAMP after authorizing an in-scope cloud service by supplying the agency Authorization to Operate letter to ato-letter@fedramp.gov.


### Governance, Risk, and Compliance Tools

??? abstract "AGU-AGC-GRC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST ensure that internal governance, risk, compliance, and inventory tools can produce and ingest machine-readable artifacts using formats identified by FedRAMP, including at least:

    1. Open Security Controls Assessment Language (OSCAL)
    1. JSON


    ---
    **Terms:** [Artifacts](../../definitions/#artifacts){ data-preview }, [Machine-Readable](../../definitions/#machine-readable){ data-preview }
### Commercial Cloud Adoption

??? abstract "AGU-AGC-CCA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD encourage adoption of commercial cloud services without incentivizing government-specific services.


### No Additional Security Requirements

??? abstract "AGU-AGC-NAR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST NOT place additional security requirements on FedRAMP Certified cloud service offerings beyond those required by FedRAMP UNLESS the head of the agency or an authorized delegate determines there is a demonstrable need; this does not apply to seeking clarification or asking general questions about FedRAMP Certification Data.


    ---

    _**Note:** This is related to the Presumption of Adequacy for a FedRAMP Certification._

    ---
    **Terms:** [Certification Data](../../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### Notify Additional Information Requests

??? abstract "AGU-AGC-NAI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using info@fedramp.gov.

!!! quote ""
    Agencies MUST notify FedRAMP after requesting any additional information or materials from a FedRAMP Certified cloud service offering beyond those FedRAMP requires by sending an email to info@fedramp.gov.


    ---

    _**Note:** Agencies are expected to notify FedRAMP under OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### Lessons Learned Reporting

??? abstract "AGU-AGC-LLR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD contribute to FedRAMP lessons-learned reporting, including sharing risk acceptance rationales, to improve government-wide reuse and transparency.


### FedRAMP Working Groups

??? abstract "AGU-AGC-WKG"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD participate in FedRAMP working groups, communities of practice, and stakeholder engagements to supply feedback and align practices across government.


### Agency Liaison Program

??? abstract "AGU-AGC-LIA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD assign at least 1 federal employee to be an active participant in the FedRAMP agency liaison program.


### Shared FedRAMP Inbox

??? abstract "AGU-AGC-SIN"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD establish and maintain a dedicated shared FedRAMP agency inbox to serve as the official point of contact for communications between FedRAMP and the agency.


    ---

    _**Note:** A shared FedRAMP agency inbox may follow an agency-specific format such as agency-fedramp@agency.gov._

## Use of FedRAMP Certifications {#use-of-fedramp-certifications}

These rules apply when agencies use FedRAMP Certifications to make agency authorization decisions.

### Authorization Before Use

??? abstract "AGU-USE-ABU"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST complete an agency authorization before using a cloud service inside a federal information system.


### Existing Certification Package

??? abstract "AGU-USE-ERP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST use the existing FedRAMP Certification package to make agency authorization decisions for FedRAMP Certified cloud services.


    ---
    **Terms:** [Certification Package](../../definitions/#certification-package){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### Compensating Controls and Risk Acceptance

??? abstract "AGU-USE-CRC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MAY accept compensating controls or risk-acceptance decisions in cases of control misalignment between federal and external frameworks.


### Resolve Certification Package Conflicts

??? abstract "AGU-USE-RCF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST collaborate with FedRAMP when discrepancies or conflicts arise between agency-specific security determinations and the baseline FedRAMP Certification package.


    ---
    **Terms:** [Certification Package](../../definitions/#certification-package){ data-preview }
### Review Secure Configuration Guides

??? abstract "AGU-USE-RSG"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST review the Secure Configuration Guides supplied by Providers and configure relevant security settings.


### Collaborative Continuous Monitoring Plan

??? abstract "AGU-USE-CCP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST develop a plan with the Provider to follow Collaborative Continuous Monitoring rules and complete ongoing authorization activities.


### Review Ongoing Authorization Reports

??? abstract "AGU-USE-ROR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST review each Ongoing Authorization Report to understand how changes to the cloud service offering may impact the risk tolerance documented in the agency Authorization to Operate for the federal information system that includes the cloud service offering in its boundary.


    ---

    _**Note:** This agency review supports agency responsibilities under 44 USC § 35, OMB Circular A-130, FIPS-200, and OMB Memorandum M-24-15._

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }
### Notify FedRAMP of Concerns

??? abstract "AGU-USE-NFC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using info@fedramp.gov.

!!! quote ""
    Agencies MUST notify FedRAMP by sending an email to info@fedramp.gov if information presented in an Ongoing Authorization Report, Quarterly Review, or other ongoing authorization data causes significant concerns that may lead the agency to stop operation of the cloud service offering.


    ---

    _**Note:** Agencies are expected to notify FedRAMP under OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Assign Security Category Resources

??? abstract "AGU-USE-ASC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD consider the Security Category noted in the agency Authorization to Operate and assign appropriate information security resources for reviewing Ongoing Authorization Reports, attending Quarterly Reviews, and reviewing other ongoing authorization data.


    ---
    **Terms:** [Quarterly Review](../../definitions/#quarterly-review){ data-preview }, [Security Category](../../definitions/#security-category){ data-preview }
### Designate Senior Official

??? abstract "AGU-USE-DSO"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD designate a senior information security official to review Ongoing Authorization Reports and represent the agency at Quarterly Reviews for cloud service offerings included in agency information systems.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Notify Provider of Concerns

??? abstract "AGU-USE-NPC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify Provider by email using Provider security contact.

!!! quote ""
    Agencies SHOULD formally notify the Provider if information presented in an Ongoing Authorization Report, Quarterly Review, or other ongoing authorization data causes significant concerns that may lead the agency to remove the cloud service offering from operation.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Review Inherited Services

??? abstract "AGU-USE-INH"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies SHOULD review the certification packages and continuous monitoring information for third-party independent information resources, such as other cloud services, that are used by a FedRAMP Certified cloud service when available.


    ---
    **Terms:** [Certification Package](../../definitions/#certification-package){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }, [Information Resource](../../definitions/#information-resource){ data-preview }
## Agency Sponsored Certifications {#agency-sponsored-certifications}

These rules apply when an agency sponsors a FedRAMP Rev5 Certification after completing an agency authorization.

### Most Recent Consolidated Rules

??? abstract "AGU-SPN-MRC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST follow the most recent FedRAMP Consolidated Rules when initiating agency-sponsored FedRAMP Certification of in-scope cloud services.


### Follow Ongoing Authorization Rules

??? abstract "AGU-SPN-OAR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Agencies MUST follow the ongoing agency authorization rules after FedRAMP issues a FedRAMP Certification they sponsored.
