---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Incident Communications Procedures


---


## General Provider Responsibilities

These rules apply to providers with FedRAMP Certifications of any type.

### Public Availability Reporting

??? abstract "ICP-CSO-PAR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    === "Class A"
        Providers of Class A offerings SHOULD maintain a publicly accessible status service that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats.

    === "Class B"
        Providers of Class B offerings SHOULD maintain a publicly accessible status service that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats.

    === "Class C"
        Providers of Class C offerings MUST maintain a publicly accessible status service that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats.

    === "Class D"
        Providers of Class D offerings MUST maintain a publicly accessible status service that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
### Evaluate Federal Reportability

??? abstract "ICP-CSO-EFR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST promptly evaluate incidents to determine if they affect confidentiality or integrity of federal customer data or are likely to affect confidentiality or integrity of federal customer data.


    ---

    _**Note:** An incident that meets this test is a federal reportable incident._

    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
### Estimate Federal Impact

??? abstract "ICP-CSO-EFI"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST evaluate federal reportable incidents to estimate adverse impact on government customers and assign a Potential Adverse Impact N-rating.

    1. N1 means negligible adverse effect on 1 or more agencies.
    1. N2 means limited adverse effect on 1 or more agencies.
    1. N3 means serious adverse effect on 1 agency.
    1. N4 means catastrophic adverse effect on 1 agency or serious adverse effect on more than 1 agency.
    1. N5 means catastrophic adverse effect on more than 1 agency.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Catastrophic Adverse Effect](../../../definitions/#catastrophic-adverse-effect){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Limited Adverse Effect](../../../definitions/#limited-adverse-effect){ data-preview }, [Negligible Adverse Effect](../../../definitions/#negligible-adverse-effect){ data-preview }, [Potential Adverse Impact](../../../definitions/#potential-adverse-impact){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Serious Adverse Effect](../../../definitions/#serious-adverse-effect){ data-preview }
### Notify All Affected Parties

??? abstract "ICP-CSO-AAP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST responsibly notify all affected parties after identifying federal reportable incidents using email, push notification, form submission, secure portal upload, or another method specified by FedRAMP rules or written agency agreement.

    1. Notify FedRAMP via fedramp_security@gsa.gov or fedramp_security@fedramp.gov.
    1. Follow contact arrangements provided by each agency customer's security contact.
    1. Upload notification information to the cloud service offering's secure portal or FedRAMP-compatible trust center.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Notify Cybersecurity and Infrastructure Security Agency

??? abstract "ICP-CSO-CSA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST responsibly notify the Cybersecurity and Infrastructure Security Agency if an incident affects or is likely to affect the confidentiality or integrity of federal customer data, following the Cybersecurity and Infrastructure Security Agency Federal Incident Notification Guidelines.



    **Reference:** [Cybersecurity and Infrastructure Security Agency Federal Incident Notification Guidelines](https://www.cisa.gov/federal-incident-notification-guidelines)

    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Initial Incident Report

??? abstract "ICP-CSO-IIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST responsibly notify all affected parties after identifying federal reportable incidents by providing an Initial Incident Report with all available required information.

    1. Contact information for the federal incident response coordinator.
    1. Provider tracking identifier.
    1. Description of the incident.
    1. Incident timeline.
    1. Historical and current Potential Adverse Impact estimates.
    1. Functional impact to federal agency customers.
    1. Estimated recovery plan, milestones, and timelines.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Potential Adverse Impact](../../../definitions/#potential-adverse-impact){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Ongoing Incident Reports

??? abstract "ICP-CSO-OIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST responsibly notify all affected parties of ongoing activity by providing Ongoing Incident Reports as new information becomes available during incident response for federal reportable incidents.

    1. Updates or lack of updates to previously reported information.
    1. Attack vector, if identified.
    1. Observed incident activity.
    1. Indicators of compromise.
    1. Relevant Cybersecurity and Infrastructure Security Agency identifier, if available.
    1. Related Common Vulnerabilities and Exposures identifier, if applicable.
    1. Root cause.
    1. Response and recovery activities.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Ongoing Incident Report (OIR)](../../../definitions/#ongoing-incident-report-oir){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Final Incident Report

??? abstract "ICP-CSO-FIR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Final Incident Report (FIR)](../../../definitions/#final-incident-report-fir){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Incident Report Timeframes

??? abstract "ICP-CSO-IRT"
    **Changelog:**


    - **2026-04-25:** Drafted for human review from PROPOSED-RULES.md.



!!! quote ""
    === "Class A"
        Providers of Class A offerings MUST notify all affected parties of federal reportable incidents within the maximum timeframes from evaluation or recovery shown below, based on the Potential Adverse Impact N-rating.

        | Potential Adverse Impact | Initial Incident Report | Ongoing Incident Report | Final Incident Report |
        |--------------------------|---|---|---|
        | N5 | 6 hours | 1 business day | 3 business days |
        | N4 | 6 hours | 1 business day | 3 business days |
        | N3 | 12 hours | 1 business day | 3 business days |
        | N2 | 1 business day | 1 business day | 3 business days |
        | N1 | 1 business day | 1 business day | 3 business days |

    === "Class B"
        Providers of Class B offerings MUST notify all affected parties of federal reportable incidents within the maximum timeframes from evaluation or recovery shown below, based on the Potential Adverse Impact N-rating.

        | Potential Adverse Impact | Initial Incident Report | Ongoing Incident Report | Final Incident Report |
        |--------------------------|---|---|---|
        | N5 | 6 hours | 1 business day | 3 business days |
        | N4 | 6 hours | 1 business day | 3 business days |
        | N3 | 12 hours | 1 business day | 3 business days |
        | N2 | 1 business day | 1 business day | 3 business days |
        | N1 | 1 business day | 1 business day | 3 business days |

    === "Class C"
        Providers of Class C offerings MUST notify all affected parties of federal reportable incidents within the maximum timeframes from evaluation or recovery shown below, based on the Potential Adverse Impact N-rating.

        | Potential Adverse Impact | Initial Incident Report | Ongoing Incident Report | Final Incident Report |
        |--------------------------|---|---|---|
        | N5 | 1 hours | 6 hours | 6 hours |
        | N4 | 1 hours | 6 hours | 6 hours |
        | N3 | 6 hours | 24 hours | 1 business day |
        | N2 | 24 hours | 24 hours | 1 business day |
        | N1 | 1 business day | 1 business day | 1 business day |

    === "Class D"
        Providers of Class D offerings MUST notify all affected parties of federal reportable incidents within the maximum timeframes from evaluation or recovery shown below, based on the Potential Adverse Impact N-rating.

        | Potential Adverse Impact | Initial Incident Report | Ongoing Incident Report | Final Incident Report |
        |--------------------------|---|---|---|
        | N5 | 0.25 hours | 3 hours | 3 hours |
        | N4 | 0.5 hours | 6 hours | 6 hours |
        | N3 | 1 hours | 6 hours | 6 hours |
        | N2 | 1 hours | 6 hours | 6 hours |
        | N1 | 1 hours | 24 hours | 24 hours |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Federal Reportable Incident](../../../definitions/#federal-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Potential Adverse Impact](../../../definitions/#potential-adverse-impact){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }
