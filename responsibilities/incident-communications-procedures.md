---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-pencil:{ .placeholder title="This content is a placeholder and is not complete." }</span>

# Incident Communications Procedures

The Incident Communications Procedures rules explain how providers must communicate incident information to FedRAMP and government customers.


## Activity Workflow: Incident Communications

This workflow illustrates the process for evaluating incidents and persistently notifying all affected parties during the incident if it is a FedRAMP Reportable Incident.

``` mermaid
flowchart TD
  node_an_incident_is_identified(["An incident is identified."])
  node_icp_cso_efr{"ICP-CSO-EFR"}
  node_incident_communication_procedures_are_complete(["Incident Communication Procedures are complete."])
  node_icp_cso_efi{"ICP-CSO-EFI"}
  node_icp_cso_dpr("ICP-CSO-DPR")
  node_icp_cso_iir("ICP-CSO-IIR")
  node_icp_cso_oir("ICP-CSO-OIR")
  node_icp_cso_fir("ICP-CSO-FIR")
  node_an_incident_is_identified --> node_icp_cso_efr
  node_icp_cso_efr -->|"No"| node_incident_communication_procedures_are_complete
  node_icp_cso_efr -->|"Yes, and the PAIN will be estimated."| node_icp_cso_efi
  node_icp_cso_efr -->|"Yes, but the PAIN will not be estimated."| node_icp_cso_dpr
  node_icp_cso_dpr -->|"Reporting clock starts, using default PAIN-5 timeframes for reporting."| node_icp_cso_iir
  node_icp_cso_efi -->|"Reporting clock starts, using estimated PAIN timeframes for reporting."| node_icp_cso_iir
  node_icp_cso_iir -->|"Ongoing persistent reporting until incident is resolved."| node_icp_cso_oir
  node_icp_cso_oir -->|"Incident is resolved."| node_icp_cso_fir
  node_icp_cso_fir --> node_incident_communication_procedures_are_complete
```


---


## FedRAMP Responsibilities {#fedramp-responsibilities}

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
