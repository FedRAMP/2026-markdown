---
tags:
  - Rev5
  - Cloud Service Providers
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Maintenance

### Maintenance Personnel { #ma-05-maintenance-personnel }

??? abstract "MA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `MA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish a process for maintenance personnel authorization and maintain a list of authorized maintenance organizations or personnel;
    - **b.** Verify that non-escorted personnel performing maintenance on the system possess the required access authorizations; and
    - **c.** Designate organizational personnel with required access authorizations and technical competence to supervise the maintenance activities of personnel who do not possess the required access authorizations.

    !!! info ""
        **FedRAMP Guidance**

        CSPs should clearly document nationality requirements (or lack of) for maintenance personnel where applicable.

---

### Individuals Without Appropriate Access { #ma-05-01-individuals-without-appropriate-access }

??? abstract "MA-05(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `MA-05(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **(a)** Implement procedures for the use of maintenance personnel that lack appropriate security clearances or are not U.S. citizens, that include the following requirements:
        - **(1)** Maintenance personnel who do not have needed access authorizations, clearances, or formal access approvals are escorted and supervised during the performance of maintenance and diagnostic activities on the system by approved organizational personnel who are fully cleared, have appropriate access authorizations, and are technically qualified; and
        - **(2)** Prior to initiating maintenance or diagnostic activities by personnel who do not have needed access authorizations, clearances or formal access approvals, all volatile information storage components within the system are sanitized and all nonvolatile storage media are removed or physically disconnected from the system and secured; and
    - **(b)** Develop and implement [Assignment: organization-defined alternate controls] in the event a system component cannot be sanitized, removed, or disconnected from the system.

    !!! info ""
        **FedRAMP Guidance**

        Only MA-5 (1) (a) (1) is required by FedRAMP Class C Baseline.

---
