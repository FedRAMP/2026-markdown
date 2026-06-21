---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Access Control

### Authorize Access to Security Functions { #ac-06-01-authorize-access-to-security-functions }

??? abstract "AC-06(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Authorize access for [Assignment: organization-defined individuals and roles] to:
    
    - **(a)** [Assignment: organization-defined security functions (deployed in hardware, software, and firmware)]; and
    - **(b)** [Assignment: organization-defined security-relevant information].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.01_odp.02` | security functions (deployed in hardware) | all functions not publicly accessible |
        | `ac-06.01_odp.05` | security-relevant information | all security-relevant information not publicly available |

---

### Non-privileged Access for Nonsecurity Functions { #ac-06-02-non-privileged-access-for-nonsecurity-functions }

??? abstract "AC-06(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Require that users of system accounts (or roles) with access to [Assignment: organization-defined security functions or security-relevant information] use non-privileged accounts or roles, when accessing nonsecurity functions.

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.02_odp` | security functions or security-relevant information | all security functions |

---

### Privilege Levels for Code Execution { #ac-06-08-privilege-levels-for-code-execution }

??? abstract "AC-06(08)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-06(08)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Prevent the following software from executing at higher privilege levels than users executing the software: [Assignment: organization-defined software].

    !!! note ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.08_odp` | software | any software except software explicitly documented |

---

### Use of External Systems { #ac-20-use-of-external-systems }

??? abstract "AC-20"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `AC-20`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** [Selection: one or more of: establish; identify], consistent with the trust relationships established with other organizations owning, operating, and/or maintaining external systems, allowing authorized individuals to:
        - **1.** Access the system from external systems; and
        - **2.** Process, store, or transmit organization-controlled information using external systems; or
    - **b.** Prohibit the use of [Assignment: organization-defined prohibited types of external systems].

    !!! note ""
        **FedRAMP Guidance**

        The interrelated controls of AC-20, CA-3, and SA-9 should be differentiated as follows:

        AC-20 describes system access to and from external systems.

        CA-3 describes documentation of an agreement between the respective system owners when data is exchanged between the CSO and an external system.

        SA-9 describes the responsibilities of external system owners. These responsibilities would typically be captured in the agreement required by CA-3.

---
