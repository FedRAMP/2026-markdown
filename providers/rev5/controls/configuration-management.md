---
tags:
  - Rev5
  - Cloud Service Providers
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Configuration Management

### Policy and Procedures { #cm-01-policy-and-procedures }

??? abstract "CM-01"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-01`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] configuration management policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the configuration management policy and the associated configuration management controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the configuration management policy and procedures; and
    - **c.** Review and update the current configuration management:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    !!! info ""
        **FedRAMP Guidance**

        Follow the Significant Change Notification rules.

---

### System Component Inventory { #cm-08-system-component-inventory }

??? abstract "CM-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Develop and document an inventory of system components that:
        - **1.** Accurately reflects the system;
        - **2.** Includes all components within the system;
        - **3.** Does not include duplicate accounting of components or components assigned to any other system;
        - **4.** Is at the level of granularity deemed necessary for tracking and reporting; and
        - **5.** Includes the following information to achieve system component accountability: [Assignment: organization-defined information]; and
    - **b.** Review and update the system component inventory [Assignment: organization-defined frequency].

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Continuous Collaborative Monitoring, Significant Change Notification, Vulnerability Detection and Response, and Vulnerability Evaluation and Reporting rules.

---

### User-installed Software { #cm-11-user-installed-software }

??? abstract "CM-11"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-11`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Establish [Assignment: organization-defined policies] governing the installation of software by users;
    - **b.** Enforce software installation policies through the following methods: [Assignment: organization-defined methods]; and
    - **c.** Monitor policy compliance [Assignment: organization-defined frequency].

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cm-11_odp.03` | frequency | Continuously (via CM-7 (5)) |

---

### Information Location { #cm-12-information-location }

??? abstract "CM-12"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-12`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Identify and document the location of [Assignment: organization-defined information] and the specific system components on which the information is processed and stored;
    - **b.** Identify and document the users who have access to the system and system components where the information is processed and stored; and
    - **c.** Document changes to the location (i.e., system or system components) where the information is processed and stored.

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Minimum Assessment Scope rules.

---

### Automated Tools to Support Information Location { #cm-12-01-automated-tools-to-support-information-location }

??? abstract "CM-12(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-12(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Use automated tools to identify [Assignment: organization-defined information by information type] on [Assignment: organization-defined system components] to ensure controls are in place to protect organizational information and individual privacy.

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Minimum Assessment Scope rules.

---

### Signed Components { #cm-14-signed-components }

??? abstract "CM-14"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `CM-14`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Prevent the installation of [Assignment: organization-defined software and firmware components] without verification that the component has been digitally signed using a certificate that is recognized and approved by the organization.

    !!! info ""
        **FedRAMP Guidance**

        If digital signatures/certificates are unavailable, alternative cryptographic integrity checks (hashes, self-signed certs, etc.) can be utilized.

---
