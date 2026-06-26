---
tags:
  - 20x
  - FedRAMP
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Incident Evaluation and Communication

The Incident Evaluation and Communication rules explain how providers must communicate incident information to FedRAMP and government customers when they are affected by an incident or likely to be affected by an incident.

**Subsets**

- [FedRAMP Responsibilities](#fedramp-responsibilities)
- [General Provider Responsibilities](#general-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-01-01


## Activity Workflow: Incident Evaluation and Communication

This workflow illustrates the process for evaluating incidents and persistently notifying all affected parties during the incident if it is a FedRAMP Reportable Incident.

``` mermaid
flowchart TD
  node_an_incident_is_identified(["An incident is identified."])
  node_iec_cso_efr{"IEC-CSO-EFR<br/>Evaluate FedRAMP Reportability"}
  node_incident_evaluation_and_reporting_is_complete(["Incident Evaluation and Reporting is complete."])
  node_iec_cso_efi{"IEC-CSO-EFI<br/>Estimate Federal Impact"}
  node_iec_cso_dpr("IEC-CSO-DPR<br/>Default PAIN Rating")
  node_iec_cso_iir("IEC-CSO-IIR<br/>Initial Incident Report")
  node_iec_cso_oir("IEC-CSO-OIR<br/>Ongoing Incident Reports")
  node_iec_cso_fir("IEC-CSO-FIR<br/>Final Incident Report")
  node_incident_evaluation_and_reporting_are_complete(["Incident Evaluation and Reporting are complete."])
  node_an_incident_is_identified --> node_iec_cso_efr
  node_iec_cso_efr -->|"No"| node_incident_evaluation_and_reporting_is_complete
  node_iec_cso_efr -->|"Yes, and the PAIN will be estimated."| node_iec_cso_efi
  node_iec_cso_efr -->|"Yes, but the PAIN will not be estimated."| node_iec_cso_dpr
  node_iec_cso_dpr -->|"Reporting clock starts, using default PAIN-5 timeframes for reporting."| node_iec_cso_iir
  node_iec_cso_efi -->|"Reporting clock starts, using estimated PAIN timeframes for reporting."| node_iec_cso_iir
  node_iec_cso_iir -->|"Ongoing persistent reporting until incident is resolved."| node_iec_cso_oir
  node_iec_cso_oir -->|"Incident is resolved."| node_iec_cso_fir
  node_iec_cso_fir --> node_incident_evaluation_and_reporting_are_complete
  click node_iec_cso_efr href "#evaluate-fedramp-reportability" "Jump to IEC-CSO-EFR"
  click node_iec_cso_dpr href "#default-pain-rating" "Jump to IEC-CSO-DPR"
  click node_iec_cso_iir href "#initial-incident-report" "Jump to IEC-CSO-IIR"
  click node_iec_cso_oir href "#ongoing-incident-reports" "Jump to IEC-CSO-OIR"
  click node_iec_cso_fir href "#final-incident-report" "Jump to IEC-CSO-FIR"
  click node_iec_cso_efi href "#estimate-federal-impact" "Jump to IEC-CSO-EFI"
```


---


## FedRAMP Responsibilities {#fedramp-responsibilities}

These rules apply to FedRAMP.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">FedRAMP</span></span></span>
</div>

### Ongoing Review

??? abstract "IEC-FRP-ORV"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST periodically review FedRAMP Incident Evaluation and Response implementation with providers based on lack of reporting or other information.

    !!! warning "Corrective Actions"
        - FedRAMP will request a Corrective Action Plan when a provider is unaware of the rules or has failed to implement proper procedures.
        - FedRAMP will grant a 3 month grace period to implement proper procedures pending remediation and possible revocation of FedRAMP Certification.


    ---
    **Terms:** [Incident](../../../definitions/#incident){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">20x</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Evaluate FedRAMP Reportability

??? abstract "IEC-CSO-EFR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST promptly evaluate incidents to determine if they affect confidentiality or integrity of federal customer data or are likely to affect confidentiality or integrity of federal customer data; such incidents are FedRAMP Reportable Incidents and must be reported following the FedRAMP Incident Evaluation and Response rules.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Default PAIN Rating

??? abstract "IEC-CSO-DPR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST treat FedRAMP Reportable Incidents as if they have a Potential Agency Impact N-rating (PAIN) of 5 UNLESS they promptly estimate the PAIN rating following the rule in [IEC-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview }.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Initial Incident Report

??? abstract "IEC-CSO-IIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via email: [FedRAMP Security Team](mailto:fedramp_security@fedramp.gov).
    - Notify Agency Customers via the appropriate recipient-specific method: Follow agency-specific incident reporting procedures (varies by agency).
    - Notify All Necessary Parties via an update: Provider's Trust Center or USDA Connect (trust center).

!!! schema "Related JSON Schema: [FedRAMP Incident Report (IEC-CSO-IIR / IEC-CSO-OIR / IEC-CSO-FIR)](https://fedramp.gov/schemas/fedramp-incident-report-schema-2026-06-24.json)"


!!! quote ""
    === "Class C"
        Providers with Class C Certifications MUST responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting and/or the current relevant status for each item:

        1. Contact information for the federal incident response coordinator.
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Agency Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [IEC-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 1 hour |
        | PAIN-4 | 1 hour |
        | PAIN-3 | 1 hour |
        | PAIN-2 | 24 hours |
        | PAIN-1 | 1 business day |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Ongoing Incident Reports

??? abstract "IEC-CSO-OIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via email: [FedRAMP Security Team](mailto:fedramp_security@fedramp.gov).
    - Notify Agency Customers via the appropriate recipient-specific method: Follow agency-specific incident reporting procedures (varies by agency).
    - Notify All Necessary Parties via an update: Provider's Trust Center or USDA Connect (trust center).

!!! schema "Related JSON Schema: [FedRAMP Incident Report (IEC-CSO-IIR / IEC-CSO-OIR / IEC-CSO-FIR)](https://fedramp.gov/schemas/fedramp-incident-report-schema-2026-06-24.json)"


!!! quote ""
    === "Class C"
        Providers with Class C Certifications MUST responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available and/or the current relevant status for each item:

        1. Observed incident activity
        1. Indicators of compromise
        1. Related Common Vulnerabilities and Exposures (CVE) identifier, if applicable
        1. Root cause
        1. Response and recovery activities


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Ongoing Incident Report |
        |--------------------------|---|
        | PAIN-5 | 6 hours |
        | PAIN-4 | 6 hours |
        | PAIN-3 | 6 hours |
        | PAIN-2 | 24 hours |
        | PAIN-1 | 1 business day |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Final Incident Report

??? abstract "IEC-CSO-FIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via email: [FedRAMP Security Team](mailto:fedramp_security@fedramp.gov).
    - Notify Agency Customers via the appropriate recipient-specific method: Follow agency-specific incident reporting procedures (varies by agency).
    - Notify All Necessary Parties via an update: Provider's Trust Center or USDA Connect (trust center).

!!! schema "Related JSON Schema: [FedRAMP Incident Report (IEC-CSO-IIR / IEC-CSO-OIR / IEC-CSO-FIR)](https://fedramp.gov/schemas/fedramp-incident-report-schema-2026-06-24.json)"


!!! quote ""
    === "Class C"
        Providers with Class C Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Final Incident Report |
        |--------------------------|---|
        | PAIN-5 | 6 hours |
        | PAIN-4 | 6 hours |
        | PAIN-3 | 6 hours |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Final Incident Report (FIR)](../../../definitions/#final-incident-report-fir){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Estimate Federal Impact

??? abstract "IEC-CSO-EFI"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Incident Report (IEC-CSO-IIR / IEC-CSO-OIR / IEC-CSO-FIR)](https://fedramp.gov/schemas/fedramp-incident-report-schema-2026-06-24.json)"


!!! quote ""
    Providers SHOULD promptly estimate the likely adverse impact of an incident on agency customers to assign a Potential Agency Impact N-rating; this step is called Incident Rating.

    - **N1** for a likely minimal customer effect on 1 or more agencies.
    - **N2** for a likely narrow customer effect on 1 or more agencies.
    - **N3** for a likely disruptive customer effect on 1 agency.
    - **N4** for a likely debilitating customer effect on 1 agency or a likely disruptive customer effect on more than 1 agency.
    - **N5** for a likely debilitating customer effect on more than 1 agency.


    ---

    _**Note:** All incidents must be assigned a default PAIN-5 as required by [IEC-CSO-DPR (Default PAIN Rating)](#default-pain-rating){ data-preview } if this step is not completed._

    ---
    **Terms:** [Debilitating Customer Effect](../../../definitions/#debilitating-customer-effect){ data-preview }, [Disruptive Customer Effect](../../../definitions/#disruptive-customer-effect){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Minimal Customer Effect](../../../definitions/#minimal-customer-effect){ data-preview }, [Narrow Customer Effect](../../../definitions/#narrow-customer-effect){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Automated Incident Reporting

??? abstract "IEC-CSO-AIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD use automation to minimize human intervention in the process of reporting FedRAMP Reportable Incidents to all affected parties.

    ---

    !!! danger "Modern cloud services should not be reporting incidents by hand-crafting emails!"

    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }
