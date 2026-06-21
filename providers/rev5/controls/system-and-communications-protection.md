---
tags:
  - Rev5
  - Cloud Service Providers
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# System and Communications Protection

### Boundary Protection { #sc-07-boundary-protection }

??? abstract "SC-07"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SC-07`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Monitor and control communications at the external managed interfaces to the system and at key internal managed interfaces within the system;
    - **b.** Implement subnetworks for publicly accessible system components that are [Selection: one of: physically; logically] separated from internal organizational networks; and
    - **c.** Connect to external networks or systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security and privacy architecture.

    !!! info ""
        **FedRAMP Guidance**

        SC-7 (b) may be met by using any technical capability or complement of capabilities that ensures logical separation between publicly accessible components and internal networks by preventing traversal without inspection and authorization; traffic may not flow unrestricted from publicly accessible components to internal networks.

---

### Cryptographic Protection { #sc-13-cryptographic-protection }

??? abstract "SC-13"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SC-13`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Determine the [Assignment: organization-defined cryptographic uses]; and
    - **b.** Implement the following types of cryptography required for each specified cryptographic use: [Assignment: organization-defined types of cryptography].

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Cryptographic Module Use rules.

---
