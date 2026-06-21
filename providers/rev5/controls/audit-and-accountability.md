---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Audit and Accountability

### Audit Record Review, Analysis, and Reporting { #au-06-audit-record-review-analysis-and-reporting }

??? abstract "AU-06"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-06`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Review and analyze system audit records [Assignment: organization-defined frequency] for indications of [Assignment: organization-defined inappropriate or unusual activity] and the potential impact of the inappropriate or unusual activity;
    - **b.** Report findings to [Assignment: organization-defined personnel or roles]; and
    - **c.** Adjust the level of audit record review, analysis, and reporting within the system when there is a change in risk based on law enforcement information, intelligence information, or other credible sources of information.

    !!! note ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

---

### Integrated Analysis of Audit Records { #au-06-05-integrated-analysis-of-audit-records }

??? abstract "AU-06(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-06(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Integrate analysis of audit records with analysis of [Selection: one or more of: vulnerability scanning information; performance data; system monitoring information] to further enhance the ability to identify inappropriate or unusual activity.

    !!! note ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

---

### Non-repudiation { #au-10-non-repudiation }

??? abstract "AU-10"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-10`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Provide irrefutable evidence that an individual (or process acting on behalf of an individual) has performed [Assignment: organization-defined actions].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-10_odp` | actions | at least actions including the addition, modification, deletion, approval, sending, or receiving of data |

---

### Audit Record Generation { #au-12-audit-record-generation }

??? abstract "AU-12"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AU-12`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Provide audit record generation capability for the event types the system is capable of auditing as defined in AU-2a on [Assignment: organization-defined system components];
    - **b.** Allow [Assignment: organization-defined personnel or roles] to select the event types that are to be logged by specific components of the system; and
    - **c.** Generate audit records for the event types defined in AU-2c that include the audit record content defined in AU-3.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-12_odp.01` | system components | at least all information system and network components where audit capability is deployed/available |

---
