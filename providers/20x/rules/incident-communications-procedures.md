---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Incident Communications Procedures

The Incident Communications Procedures rules explain how providers must communicate incident information to FedRAMP and government customers.


## Activity Workflow: Incident Communications

This workflow illustrates the process for evaluating incidents and persistently notifying all affected parties during the incident if it is a FedRAMP Reportable Incident.

``` mermaid
flowchart TD
  node_an_incident_is_identified(["An incident is identified."])
  node_icp_cso_efr{"ICP-CSO-EFR<br/>Evaluate FedRAMP Reportability"}
  node_incident_communication_procedures_are_complete(["Incident Communication Procedures are complete."])
  node_icp_cso_efi{"ICP-CSO-EFI<br/>Estimate Federal Impact"}
  node_icp_cso_dpr("ICP-CSO-DPR<br/>Default PAIN Rating")
  node_icp_cso_iir("ICP-CSO-IIR<br/>Initial Incident Report")
  node_icp_cso_oir("ICP-CSO-OIR<br/>Ongoing Incident Reports")
  node_icp_cso_fir("ICP-CSO-FIR<br/>Final Incident Report")
  node_an_incident_is_identified --> node_icp_cso_efr
  node_icp_cso_efr -->|"No"| node_incident_communication_procedures_are_complete
  node_icp_cso_efr -->|"Yes, and the PAIN will be estimated."| node_icp_cso_efi
  node_icp_cso_efr -->|"Yes, but the PAIN will not be estimated."| node_icp_cso_dpr
  node_icp_cso_dpr -->|"Reporting clock starts, using default PAIN-5 timeframes for reporting."| node_icp_cso_iir
  node_icp_cso_efi -->|"Reporting clock starts, using estimated PAIN timeframes for reporting."| node_icp_cso_iir
  node_icp_cso_iir -->|"Ongoing persistent reporting until incident is resolved."| node_icp_cso_oir
  node_icp_cso_oir -->|"Incident is resolved."| node_icp_cso_fir
  node_icp_cso_fir --> node_incident_communication_procedures_are_complete
  click node_icp_cso_efr href "#evaluate-fedramp-reportability" "Jump to ICP-CSO-EFR"
  click node_icp_cso_dpr href "#default-pain-rating" "Jump to ICP-CSO-DPR"
  click node_icp_cso_iir href "#initial-incident-report" "Jump to ICP-CSO-IIR"
  click node_icp_cso_oir href "#ongoing-incident-reports" "Jump to ICP-CSO-OIR"
  click node_icp_cso_fir href "#final-incident-report" "Jump to ICP-CSO-FIR"
  click node_icp_cso_efi href "#estimate-federal-impact" "Jump to ICP-CSO-EFI"
```


---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with FedRAMP Certifications of any type.

### Evaluate FedRAMP Reportability

??? abstract "ICP-CSO-EFR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST promptly evaluate incidents to determine if they affect confidentiality or integrity of federal customer data or are likely to affect confidentiality or integrity of federal customer data; such incidents are FedRAMP Reportable Incidents and must be reported following the FedRAMP Incident Communications Procedures.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Default PAIN Rating

??? abstract "ICP-CSO-DPR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST treat FedRAMP Reportable Incidents as if they have a Potential Agency Impact N-rating (PAIN) of 5 UNLESS they promptly estimate the PAIN rating following the rule in [ICP-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview }.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Initial Incident Report

??? abstract "ICP-CSO-IIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by update using incident contact procedures documented in contract agreement.
    - Notify All Necessary Parties by update using trust center.

!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting:

        1. Contact information for the federal incident response coordinator.
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Adverse Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [ICP-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 6 hours |
        | PAIN-4 | 6 hours |
        | PAIN-3 | 6 hours |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |

    === "Class B"
        Providers with Class B Certifications MUST responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting:

        1. Contact information for the federal incident response coordinator.
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Adverse Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [ICP-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 6 hours |
        | PAIN-4 | 6 hours |
        | PAIN-3 | 6 hours |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |

    === "Class C"
        Providers with Class C Certifications MUST responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting:

        1. Contact information for the federal incident response coordinator.
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Adverse Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [ICP-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 1 hours |
        | PAIN-4 | 1 hours |
        | PAIN-3 | 1 hours |
        | PAIN-2 | 24 hours |
        | PAIN-1 | 1 business day |

    === "Class D"
        Providers with Class D Certifications MUST responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting:

        1. Contact information for the federal incident response coordinator.
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Adverse Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [ICP-CSO-EFI (Estimate Federal Impact)](#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 0.25 hours |
        | PAIN-4 | 0.25 hours |
        | PAIN-3 | 0.25 hours |
        | PAIN-2 | 1 hours |
        | PAIN-1 | 1 hours |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Ongoing Incident Reports

??? abstract "ICP-CSO-OIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by update using incident contact procedures documented in contract agreement.
    - Notify All Necessary Parties by update using trust center.

!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available:

        1. Observed incident activity
        1. Indicators of compromise
        1. Related Common Vulnerabilities and Exposures (CVE) identifier (if applicable)
        1. Root cause
        1. Response and recovery activities


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Ongoing Incident Report |
        |--------------------------|---|
        | PAIN-5 | 1 business day |
        | PAIN-4 | 1 business day |
        | PAIN-3 | 1 business day |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |

    === "Class B"
        Providers with Class B Certifications MUST responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available:

        1. Observed incident activity
        1. Indicators of compromise
        1. Related Common Vulnerabilities and Exposures (CVE) identifier, if applicable
        1. Root cause
        1. Response and recovery activities


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Ongoing Incident Report |
        |--------------------------|---|
        | PAIN-5 | 1 business day |
        | PAIN-4 | 1 business day |
        | PAIN-3 | 1 business day |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |

    === "Class C"
        Providers with Class C Certifications MUST responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available:

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

    === "Class D"
        Providers with Class D Certifications MUST responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available:

        1. Observed incident activity
        1. Indicators of compromise
        1. Related Common Vulnerabilities and Exposures (CVE) identifier, if applicable
        1. Root cause
        1. Response and recovery activities


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Ongoing Incident Report |
        |--------------------------|---|
        | PAIN-5 | 3 hours |
        | PAIN-4 | 3 hours |
        | PAIN-3 | 3 hours |
        | PAIN-2 | 6 hours |
        | PAIN-1 | 24 hours |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Final Incident Report

??? abstract "ICP-CSO-FIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by update using incident contact procedures documented in contract agreement.
    - Notify All Necessary Parties by update using trust center.

!!! quote ""
    === "Class A"
        Providers with Class A Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Final Incident Report |
        |--------------------------|---|
        | PAIN-5 | 3 business days |
        | PAIN-4 | 3 business days |
        | PAIN-3 | 3 business days |
        | PAIN-2 | 3 business days |
        | PAIN-1 | 3 business days |

    === "Class B"
        Providers with Class B Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Final Incident Report |
        |--------------------------|---|
        | PAIN-5 | 3 business days |
        | PAIN-4 | 3 business days |
        | PAIN-3 | 3 business days |
        | PAIN-2 | 3 business days |
        | PAIN-1 | 3 business days |

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

    === "Class D"
        Providers with Class D Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Final Incident Report |
        |--------------------------|---|
        | PAIN-5 | 3 hours |
        | PAIN-4 | 3 hours |
        | PAIN-3 | 3 hours |
        | PAIN-2 | 6 hours |
        | PAIN-1 | 24 hours |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Final Incident Report (FIR)](../../../definitions/#final-incident-report-fir){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Estimate Federal Impact

??? abstract "ICP-CSO-EFI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD promptly estimate the likely adverse impact of an incident on agency customers to assign a Potential Agency Impact N-rating; this step is called Incident Rating.

    - **N1** for a likely minimal customer effect on 1 or more agencies.
    - **N2** for a likely narrow customer effect on 1 or more agencies.
    - **N3** for a likely disruptive customer effect on 1 agency.
    - **N4** for a likely debilitating customer effect on 1 agency or a likely disruptive customer effect on more than 1 agency.
    - **N5** for a likely debilitating customer effect on more than 1 agency.


    ---

    _**Note:** All incidents must be assigned a default PAIN-5 as required by [ICP-CSO-DPR (Default PAIN Rating)](#default-pain-rating){ data-preview } if this step is not completed._

    ---
    **Terms:** [Debilitating Customer Effect](../../../definitions/#debilitating-customer-effect){ data-preview }, [Disruptive Customer Effect](../../../definitions/#disruptive-customer-effect){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Minimal Customer Effect](../../../definitions/#minimal-customer-effect){ data-preview }, [Narrow Customer Effect](../../../definitions/#narrow-customer-effect){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Automated Incident Reporting

??? abstract "ICP-CSO-AIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD use automation to minimize human intervention in the process of reporting FedRAMP Reportable Incidents to all affected parties.

    ---

    !!! danger "Modern cloud services should not be reporting incidents by hand-crafting emails!"

    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }
