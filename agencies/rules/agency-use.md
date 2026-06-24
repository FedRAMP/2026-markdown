---
tags:
  - 20x
  - Rev5
  - Federal Agencies
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Agency Use of FedRAMP Certified Cloud Services

The Agency Use rules summarize the many demands made on agencies by the FedRAMP Authorization Act and OMB Memorandum M-24-15 in a simple, clear, easy-to-follow set of FedRAMP-style rules. These rules align agency policies, authorization letters, machine-readable tools, secure configuration review, continuous monitoring, and communication with FedRAMP so certifications can be reused consistently across government.

**Subsets**

- [General Agency Responsibilities](#general-agency-responsibilities)
- [Use of FedRAMP Certifications](#use-of-fedramp-certifications)
- [Agency Sponsored Certifications](#agency-sponsored-certifications)

!!! info "Effective Date(s) & Overall Applicability for 20x and Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2026-07-04
    - **Grace Ends:** 2026-07-04



---


## General Agency Responsibilities {#general-agency-responsibilities}

These rules apply to agencies based on the FedRAMP Authorization Act, OMB M-24-15, and related FedRAMP policies.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agencies</span></span></span>
</div>

### Agency Internal Policies

??? abstract "AGU-AGC-AIP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST maintain agency-wide policy that aligns with the requirements in OMB Memorandum M-24-15.


### Notify FedRAMP After Authorization

??? abstract "AGU-AGC-NAA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via form: [Submit an ATO Letter](https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51447926193691).


!!! quote ""
    Agencies MUST notify FedRAMP upon authorizing the use of a cloud service within the scope of FedRAMP, supplying at least the following information:

    1. A copy of the agency's Authorization to Operate letter for the information system leveraging the cloud service, following agency policy and templates.
    1. All other supplemental information requested in the Submit an ATO Letter form by FedRAMP.


### Governance, Risk, and Compliance Tools

??? abstract "AGU-AGC-GRC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST ensure that internal governance, risk, compliance, and inventory tools can produce and ingest machine-readable artifacts using formats identified by FedRAMP, including at least:

    1. Open Security Controls Assessment Language (OSCAL)
    1. JSON


    ---
    **Terms:** [Artifacts](../../definitions/#artifacts){ data-preview }, [Machine-Readable](../../definitions/#machine-readable){ data-preview }
### Notify Additional Information Requests

??? abstract "AGU-AGC-NAI"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via form: [\[For Agencies\] Additional Information, Security Requirements, or Certification Change, or After Request Form](https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51822364715035).


!!! quote ""
    Agencies MUST notify FedRAMP after requesting any additional information or materials from a FedRAMP Certified cloud service offering beyond those required by FedRAMP.


    ---

    _**Note:** Agencies are expected to notify FedRAMP under OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### No Additional Security Requirements

??? abstract "AGU-AGC-NAR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via email: [info@fedramp.gov](mailto:info@fedramp.gov).


!!! quote ""
    Agencies MUST NOT require additional information or materials from FedRAMP Certified cloud service offerings beyond those required by FedRAMP UNLESS the head of the agency or an authorized delegate determines there is a demonstrable need and notifies FedRAMP; this does not apply to seeking clarification or asking general questions about FedRAMP Certification Data.


    ---

    _**Note:** This is related to the Presumption of Adequacy for a FedRAMP Certification and notification is mandated by OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Certification Data](../../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### No Certification Type or Path Preferences

??? abstract "AGU-AGC-TPP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via email: [info@fedramp.gov](mailto:info@fedramp.gov).


!!! quote ""
    Agencies MUST NOT require cloud service offerings to obtain or maintain a specific FedRAMP Certification Type or FedRAMP Certification Path, UNLESS the head of the agency or an authorized delegate determines there is a demonstrable need and notifies FedRAMP.


    ---

    _**Note:** This is related to the Presumption of Adequacy for a FedRAMP Certification and notification is mandated by OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Certification Path](../../definitions/#certification-path){ data-preview }, [Certification Type](../../definitions/#certification-type){ data-preview }, [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### FedRAMP Working Groups

??? abstract "AGU-AGC-WKG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD participate in FedRAMP working groups, communities of practice, and stakeholder engagements to supply feedback and align practices across government.


### Agency Liaison Program

??? abstract "AGU-AGC-LIA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD assign at least 1 federal employee to be an active participant in the FedRAMP Agency Liaison program.



    **Reference:** [Agency Liaison Program](https://www.fedramp.gov/preview/2026/agencies/support/liaisons)

### Shared FedRAMP Inbox

??? abstract "AGU-AGC-SIN"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD establish and maintain a dedicated shared FedRAMP agency inbox to serve as the official point of contact for communications between FedRAMP and the agency.


    ---

    _**Note:** A shared FedRAMP agency inbox may follow an agency-specific format such as agency-fedramp@agency.gov._

## Use of FedRAMP Certifications {#use-of-fedramp-certifications}

These rules apply when agencies use FedRAMP Certifications to make agency authorization decisions.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class A</span><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agencies</span></span></span>
</div>

### Authorization Before Use

??? abstract "AGU-USE-ABU"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST complete the Authorization to Operate process for federal information systems that use FedRAMP Certified cloud service offerings.


    ---

    _**Note:** FedRAMP provides technical assistance to help agencies navigate this process._


    **Reference:** [Using a FedRAMP Certified Cloud Service Offering](https://fedramp.gov/preview/2026/agencies/use)

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### Resolve Certification Package Conflicts

??? abstract "AGU-USE-RCF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST collaborate with FedRAMP when discrepancies or conflicts arise between agency-specific security determinations and the FedRAMP Certification Package.


    ---
    **Terms:** [Certification Package](../../definitions/#certification-package){ data-preview }
### Review Secure Configuration Guides

??? abstract "AGU-USE-RSG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST review the Secure Configuration Guides supplied by Providers and configure relevant security settings.


### Accept FedRAMP Rules

??? abstract "AGU-USE-AFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST allow FedRAMP Certified cloud service offerings to follow FedRAMP rules.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
### Notify FedRAMP of Monitoring Concerns

??? abstract "AGU-USE-NFC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via form: [Report Concerns on Ongoing Certifications](https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51821301979547).


!!! quote ""
    Agencies MUST notify FedRAMP if information presented in an Ongoing Certification Report, Quarterly Review, or other FedRAMP Certification Data causes significant concerns for the authorizing official that would likely result in rescission of their Authorization to Operate.


    ---

    _**Note:** Agencies are expected to notify FedRAMP under OMB Memorandum M-24-15 section IV (a)._

    ---
    **Terms:** [Certification Data](../../definitions/#certification-data){ data-preview }, [FedRAMP Certification Report](../../definitions/#fedramp-certification-report){ data-preview }, [Likely](../../definitions/#likely){ data-preview }, [Ongoing Certification](../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Review Ongoing Certification Reports

??? abstract "AGU-USE-ROR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD review each Ongoing Certification Report to understand how changes to the cloud service offering may impact the risk tolerance documented in the agency Authorization to Operate for the federal information system that includes the cloud service offering in its boundary.


    ---

    _**Note:** This agency review supports agency responsibilities under 44 USC § 35, OMB Circular A-130, FIPS-200, and OMB Memorandum M-24-15._

    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certification Report](../../definitions/#fedramp-certification-report){ data-preview }, [Ongoing Certification](../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../definitions/#ongoing-certification-report-ocr){ data-preview }
### Designate Senior Official

??? abstract "AGU-USE-DSO"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD designate a federal senior information security official to review Ongoing Certification Reports and represent the agency at Quarterly Reviews for cloud service offerings included in agency information systems.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [Ongoing Certification](../../definitions/#ongoing-certification){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Notify Provider of Concerns

??? abstract "AGU-USE-NPC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify Provider via the appropriate recipient-specific method: The provider's security contact email or form (varies by provider).


!!! quote ""
    Agencies SHOULD formally notify the cloud service provider if information presented in an Ongoing Certification Report, Quarterly Review, or other FedRAMP Certification Data causes significant concerns for the authorizing official that would likely result in rescission of their Authorization to Operate.


    ---
    **Terms:** [Certification Data](../../definitions/#certification-data){ data-preview }, [FedRAMP Certification Report](../../definitions/#fedramp-certification-report){ data-preview }, [Likely](../../definitions/#likely){ data-preview }, [Ongoing Certification](../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Quarterly Review](../../definitions/#quarterly-review){ data-preview }
### Review All Information Resources

??? abstract "AGU-USE-RIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD consider third-party information resources used by the cloud service offering during initial and ongoing authorization activities.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [Information Resource](../../definitions/#information-resource){ data-preview }, [Third-Party Information Resource](../../definitions/#third-party-information-resource){ data-preview }
### Using FedRAMP Class A Certifications

??? abstract "AGU-USE-CLA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies SHOULD NOT authorize the use of a FedRAMP Class A Certified cloud service offering for more than 12 months UNLESS the cloud service offering is actively seeking a FedRAMP Class B, C, or D Certification.


    ---
    **Terms:** [Cloud Service Offering](../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../definitions/#fedramp-certified){ data-preview }
## Agency Sponsored Certifications {#agency-sponsored-certifications}

These rules apply when an agency sponsors a FedRAMP Rev5 Certification after completing an agency authorization.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Agencies</span></span></span>
</div>

### Most Recent Consolidated Rules

??? abstract "AGU-SPN-MRC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Agencies MUST follow the most recent FedRAMP Consolidated Rules when initiating agency-sponsored FedRAMP Certification.
