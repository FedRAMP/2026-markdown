---
search:
  exclude: true
tags:
  - 20x
  - Cloud Service Providers
  - Key Security Indicators
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Cloud Native Architecture






### Defining Functionality and Privileges

??? abstract "KSI-CNA-DFP"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added cm-8.4, cp-10.4, ir-9.4.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    The functionality and privileges for infrastructure and services are strictly defined.



    **Related SP 800-53 Controls:** [CM-02](../../../reference/controls/configuration-management.md#cm-02){ data-preview }, [CM-08 (04)](../../../reference/controls/configuration-management.md#cm-08-04){ data-preview }, [CP-10 (04)](../../../reference/controls/contingency-planning.md#cp-10-04){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [SI-03](../../../reference/controls/system-and-information-integrity.md#si-03){ data-preview }

### Enforcing Intended State

??? abstract "KSI-CNA-EIS"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added cm-11, cm-6.2, cp-10.4, ir-9.4, sc-24, sc-7.18, si-4.22, si-7, si-7.1, si-7.5, si-7.7; removed ca-7.1.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class B"
        **Optional:** Automated services are used to persistently assess the security of all machine-based information resources and automatically enforce their intended operational state.

    === "Class C"
        Automated services are used to persistently assess the security of all machine-based information resources and automatically enforce their intended operational state.



    **Related SP 800-53 Controls:** [CA-02 (01)](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-02-01){ data-preview }, [CM-11](../../../reference/controls/configuration-management.md#cm-11){ data-preview }, [CM-06 (02)](../../../reference/controls/configuration-management.md#cm-06-02){ data-preview }, [CP-10 (04)](../../../reference/controls/contingency-planning.md#cp-10-04){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [SC-24](../../../reference/controls/system-and-communications-protection.md#sc-24){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SI-04 (22)](../../../reference/controls/system-and-information-integrity.md#si-04-22){ data-preview }, [SI-07](../../../reference/controls/system-and-information-integrity.md#si-07){ data-preview }, [SI-07 (01)](../../../reference/controls/system-and-information-integrity.md#si-07-01){ data-preview }, [SI-07 (05)](../../../reference/controls/system-and-information-integrity.md#si-07-05){ data-preview }, [SI-07 (07)](../../../reference/controls/system-and-information-integrity.md#si-07-07){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Implementing Best Practices

??? abstract "KSI-CNA-IBP"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added sc-7.18.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    The use and configuration of third-party machine-based information resources is persistently compared against the original provider's best practices and guidance.



    **Related SP 800-53 Controls:** [AC-17 (03)](../../../reference/controls/access-control.md#ac-17-03){ data-preview }, [CM-02](../../../reference/controls/configuration-management.md#cm-02){ data-preview }, [PL-10](../../../reference/controls/planning.md#pl-10){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Minimizing Attack Surface

??? abstract "KSI-CNA-MAT"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added sc-7.18.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Machine-based information resources are persistently reviewed to ensure they have a minimal attack surface and that lateral movement is minimized if compromised.



    **Related SP 800-53 Controls:** [AC-17 (03)](../../../reference/controls/access-control.md#ac-17-03){ data-preview }, [AC-18 (01)](../../../reference/controls/access-control.md#ac-18-01){ data-preview }, [AC-18 (03)](../../../reference/controls/access-control.md#ac-18-03){ data-preview }, [AC-20 (01)](../../../reference/controls/access-control.md#ac-20-01){ data-preview }, [CA-09](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview }, [SC-10](../../../reference/controls/system-and-communications-protection.md#sc-10){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SC-07 (03)](../../../reference/controls/system-and-communications-protection.md#sc-07-03){ data-preview }, [SC-07 (04)](../../../reference/controls/system-and-communications-protection.md#sc-07-04){ data-preview }, [SC-07 (05)](../../../reference/controls/system-and-communications-protection.md#sc-07-05){ data-preview }, [SC-07 (08)](../../../reference/controls/system-and-communications-protection.md#sc-07-08){ data-preview }, [SC-08](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview }, [SI-10](../../../reference/controls/system-and-information-integrity.md#si-10){ data-preview }, [SI-11](../../../reference/controls/system-and-information-integrity.md#si-11){ data-preview }, [SI-16](../../../reference/controls/system-and-information-integrity.md#si-16){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Optimizing for Availability

??? abstract "KSI-CNA-OFA"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added cp-2.5, sc-12.1.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Machine-based information resources are persistently reviewed to ensure they are appropriately optimized for high availability and rapid recovery.



    **Related SP 800-53 Controls:** [CP-02 (05)](../../../reference/controls/contingency-planning.md#cp-02-05){ data-preview }, [SC-12 (01)](../../../reference/controls/system-and-communications-protection.md#sc-12-01){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Restricting Network Traffic

??? abstract "KSI-CNA-RNT"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added sc-7.10, sc-7.18, sc-7.20, sc-7.21, si-10, si-4.11, si-4.18, si-4.4.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Machine-based information resources are persistently reviewed to ensure they are appropriately configured to limit inbound and outbound network traffic.



    **Related SP 800-53 Controls:** [AC-17 (03)](../../../reference/controls/access-control.md#ac-17-03){ data-preview }, [CA-09](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview }, [CM-07 (01)](../../../reference/controls/configuration-management.md#cm-07-01){ data-preview }, [SC-07 (10)](../../../reference/controls/system-and-communications-protection.md#sc-07-10){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SC-07 (20)](../../../reference/controls/system-and-communications-protection.md#sc-07-20){ data-preview }, [SC-07 (21)](../../../reference/controls/system-and-communications-protection.md#sc-07-21){ data-preview }, [SC-07 (05)](../../../reference/controls/system-and-communications-protection.md#sc-07-05){ data-preview }, [SI-10](../../../reference/controls/system-and-information-integrity.md#si-10){ data-preview }, [SI-04 (11)](../../../reference/controls/system-and-information-integrity.md#si-04-11){ data-preview }, [SI-04 (18)](../../../reference/controls/system-and-information-integrity.md#si-04-18){ data-preview }, [SI-04 (04)](../../../reference/controls/system-and-information-integrity.md#si-04-04){ data-preview }, [SI-08](../../../reference/controls/system-and-information-integrity.md#si-08){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Reviewing Protections

??? abstract "KSI-CNA-RVP"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ir-4.2, sc-7.18.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    The effectiveness of protection against denial of service attacks and other unwanted activity for machine-based information resources is persistently reviewed.



    **Related SP 800-53 Controls:** [IR-04 (02)](../../../reference/controls/incident-response.md#ir-04-02){ data-preview }, [SC-05](../../../reference/controls/system-and-communications-protection.md#sc-05){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SI-08](../../../reference/controls/system-and-information-integrity.md#si-08){ data-preview }, [SI-08 (02)](../../../reference/controls/system-and-information-integrity.md#si-08-02){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Using Logical Networking

??? abstract "KSI-CNA-ULN"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-4.21, cm-11, sc-7.20, sc-7.21.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Logical networking and related capabilities are used and persistently reviewed to enforce traffic flow controls.



    **Related SP 800-53 Controls:** [AC-12](../../../reference/controls/access-control.md#ac-12){ data-preview }, [AC-17 (03)](../../../reference/controls/access-control.md#ac-17-03){ data-preview }, [AC-04 (21)](../../../reference/controls/access-control.md#ac-04-21){ data-preview }, [CA-09](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-09){ data-preview }, [CM-11](../../../reference/controls/configuration-management.md#cm-11){ data-preview }, [SC-10](../../../reference/controls/system-and-communications-protection.md#sc-10){ data-preview }, [SC-04](../../../reference/controls/system-and-communications-protection.md#sc-04){ data-preview }, [SC-07](../../../reference/controls/system-and-communications-protection.md#sc-07){ data-preview }, [SC-07 (20)](../../../reference/controls/system-and-communications-protection.md#sc-07-20){ data-preview }, [SC-07 (21)](../../../reference/controls/system-and-communications-protection.md#sc-07-21){ data-preview }, [SC-07 (07)](../../../reference/controls/system-and-communications-protection.md#sc-07-07){ data-preview }, [SC-08](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview }

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }
