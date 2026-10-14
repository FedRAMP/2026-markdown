---
search:
  exclude: true
tags:
  - 20x
  - Cloud Service Providers
  - Key Security Indicators
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Service Configuration






### Automating Configuration Management

??? abstract "KSI-SVC-ACM"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-6.8, sc-45, sc-45.1, sc-7.18.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    The configuration of machine-based information resources is managed using automation and persistently reviewed for drift.



    **Related SP 800-53 Controls:** [AC-02 (04)](../../../reference/controls/access-control.md#ac-02-04){ data-preview }, [AC-06 (08)](../../../reference/controls/access-control.md#ac-06-08){ data-preview }, [CM-02](../../../reference/controls/configuration-management.md#cm-02){ data-preview }, [CM-02 (02)](../../../reference/controls/configuration-management.md#cm-02-02){ data-preview }, [CM-02 (03)](../../../reference/controls/configuration-management.md#cm-02-03){ data-preview }, [CM-06](../../../reference/controls/configuration-management.md#cm-06){ data-preview }, [CM-07 (01)](../../../reference/controls/configuration-management.md#cm-07-01){ data-preview }, [PL-10](../../../reference/controls/planning.md#pl-10){ data-preview }, [PL-09](../../../reference/controls/planning.md#pl-09){ data-preview }, [SA-05](../../../reference/controls/system-and-services-acquisition.md#sa-05){ data-preview }, [SC-45](../../../reference/controls/system-and-communications-protection.md#sc-45){ data-preview }, [SC-45 (01)](../../../reference/controls/system-and-communications-protection.md#sc-45-01){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SI-05](../../../reference/controls/system-and-information-integrity.md#si-05){ data-preview }, [SR-10](../../../reference/controls/supply-chain-risk-management.md#sr-10){ data-preview }

    ---
    **Terms:** [Drift](../../../definitions/#drift){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Automating Secret Management

??? abstract "KSI-SVC-ASM"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added sc-12.1.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Management, protection, and regular rotation of digital keys, certificates, and other secrets is automated and persistently reviewed.



    **Related SP 800-53 Controls:** [AC-17 (02)](../../../reference/controls/access-control.md#ac-17-02){ data-preview }, [IA-05 (02)](../../../reference/controls/identification-and-authentication.md#ia-05-02){ data-preview }, [IA-05 (06)](../../../reference/controls/identification-and-authentication.md#ia-05-06){ data-preview }, [SC-12](../../../reference/controls/system-and-communications-protection.md#sc-12){ data-preview }, [SC-12 (01)](../../../reference/controls/system-and-communications-protection.md#sc-12-01){ data-preview }, [SC-17](../../../reference/controls/system-and-communications-protection.md#sc-17){ data-preview }

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }, [Regularly](../../../definitions/#regularly){ data-preview }
### Evaluating and Improving Security

??? abstract "KSI-SVC-EIS"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ca-7.4, cm-5.5, ir-9.4, ra-3; removed ma-2.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Information resources are persistently evaluated for opportunities to improve security and those improvements are persistently made.



    **Related SP 800-53 Controls:** [CA-07 (04)](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-07-04){ data-preview }, [CM-12 (01)](../../../reference/controls/configuration-management.md#cm-12-01){ data-preview }, [CM-05 (05)](../../../reference/controls/configuration-management.md#cm-05-05){ data-preview }, [CM-07 (01)](../../../reference/controls/configuration-management.md#cm-07-01){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [PL-08](../../../reference/controls/planning.md#pl-08){ data-preview }, [RA-03](../../../reference/controls/risk-assessment.md#ra-03){ data-preview }, [SC-39](../../../reference/controls/system-and-communications-protection.md#sc-39){ data-preview }, [SC-07](../../../reference/controls/system-and-communications-protection.md#sc-07){ data-preview }, [SI-02 (02)](../../../reference/controls/system-and-information-integrity.md#si-02-02){ data-preview }, [SI-04](../../../reference/controls/system-and-information-integrity.md#si-04){ data-preview }, [SR-10](../../../reference/controls/supply-chain-risk-management.md#sr-10){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Preventing Residual Risk

??? abstract "KSI-SVC-PRR"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-19, ir-9.4, sc-12.1, sc-7.18.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class B"
        **Optional:** Plans, procedures, and the state of information resources are persistently reviewed after making changes to limit and remove unwanted residual elements that would likely negatively affect the confidentiality, integrity, or availability of federal customer data.

    === "Class C"
        Plans, procedures, and the state of information resources are persistently reviewed after making changes to limit and remove unwanted residual elements that would likely negatively affect the confidentiality, integrity, or availability of federal customer data.



    **Related SP 800-53 Controls:** [AC-19](../../../reference/controls/access-control.md#ac-19){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [SC-12 (01)](../../../reference/controls/system-and-communications-protection.md#sc-12-01){ data-preview }, [SC-04](../../../reference/controls/system-and-communications-protection.md#sc-04){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }

    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Removing Unwanted Data

??? abstract "KSI-SVC-RUD"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ir-9, si-8, si-8.2.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class B"
        **Optional:** Unwanted federal customer data is removed promptly when requested by an agency in alignment with customer agreements, including from backups if appropriate; this typically applies when a customer spills information or when a customer seeks to remove information from a service due to a change in usage.

    === "Class C"
        Unwanted federal customer data is removed promptly when requested by an agency in alignment with customer agreements, including from backups if appropriate; this typically applies when a customer spills information or when a customer seeks to remove information from a service due to a change in usage.



    **Related SP 800-53 Controls:** [IR-09](../../../reference/controls/incident-response.md#ir-09){ data-preview }, [SI-12 (03)](../../../reference/controls/system-and-information-integrity.md#si-12-03){ data-preview }, [SI-18 (04)](../../../reference/controls/system-and-information-integrity.md#si-18-04){ data-preview }, [SI-08](../../../reference/controls/system-and-information-integrity.md#si-08){ data-preview }, [SI-08 (02)](../../../reference/controls/system-and-information-integrity.md#si-08-02){ data-preview }

    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Securing Information

??? abstract "KSI-SVC-SIN"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-11, ac-11.1, ac-19.5, ac-21, ir-9.4, sc-4, sc-7.18, si-4.18; removed ac-1.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Information is encrypted or otherwise secured from unwanted access or modification.



    **Related SP 800-53 Controls:** [AC-11](../../../reference/controls/access-control.md#ac-11){ data-preview }, [AC-11 (01)](../../../reference/controls/access-control.md#ac-11-01){ data-preview }, [AC-17 (02)](../../../reference/controls/access-control.md#ac-17-02){ data-preview }, [AC-19 (05)](../../../reference/controls/access-control.md#ac-19-05){ data-preview }, [AC-21](../../../reference/controls/access-control.md#ac-21){ data-preview }, [CP-09 (08)](../../../reference/controls/contingency-planning.md#cp-09-08){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [SC-13](../../../reference/controls/system-and-communications-protection.md#sc-13){ data-preview }, [SC-20](../../../reference/controls/system-and-communications-protection.md#sc-20){ data-preview }, [SC-21](../../../reference/controls/system-and-communications-protection.md#sc-21){ data-preview }, [SC-22](../../../reference/controls/system-and-communications-protection.md#sc-22){ data-preview }, [SC-23](../../../reference/controls/system-and-communications-protection.md#sc-23){ data-preview }, [SC-28](../../../reference/controls/system-and-communications-protection.md#sc-28){ data-preview }, [SC-28 (01)](../../../reference/controls/system-and-communications-protection.md#sc-28-01){ data-preview }, [SC-04](../../../reference/controls/system-and-communications-protection.md#sc-04){ data-preview }, [SC-07 (18)](../../../reference/controls/system-and-communications-protection.md#sc-07-18){ data-preview }, [SC-08](../../../reference/controls/system-and-communications-protection.md#sc-08){ data-preview }, [SC-08 (01)](../../../reference/controls/system-and-communications-protection.md#sc-08-01){ data-preview }, [SI-04 (18)](../../../reference/controls/system-and-information-integrity.md#si-04-18){ data-preview }

### Validating Communications

??? abstract "KSI-SVC-VCM"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-10, ac-17.4, ac-18, ac-19, si-4.22.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class B"
        **Optional:** The authenticity and integrity of communications between machine-based information resources is persistently validated using automation.

    === "Class C"
        The authenticity and integrity of communications between machine-based information resources is persistently validated using automation.



    **Related SP 800-53 Controls:** [AC-10](../../../reference/controls/access-control.md#ac-10){ data-preview }, [AC-17 (04)](../../../reference/controls/access-control.md#ac-17-04){ data-preview }, [AC-18](../../../reference/controls/access-control.md#ac-18){ data-preview }, [AC-19](../../../reference/controls/access-control.md#ac-19){ data-preview }, [SC-23](../../../reference/controls/system-and-communications-protection.md#sc-23){ data-preview }, [SI-04 (22)](../../../reference/controls/system-and-information-integrity.md#si-04-22){ data-preview }, [SI-07 (01)](../../../reference/controls/system-and-information-integrity.md#si-07-01){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Validating Resource Integrity

??? abstract "KSI-SVC-VRI"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-17.4, ac-18, ac-19, au-9.3, cm-14, si-7.15, sr-11.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Use cryptographic methods to validate the integrity of machine-based information resources.



    **Related SP 800-53 Controls:** [AC-17 (04)](../../../reference/controls/access-control.md#ac-17-04){ data-preview }, [AC-18](../../../reference/controls/access-control.md#ac-18){ data-preview }, [AC-19](../../../reference/controls/access-control.md#ac-19){ data-preview }, [AU-09 (03)](../../../reference/controls/audit-and-accountability.md#au-09-03){ data-preview }, [CM-14](../../../reference/controls/configuration-management.md#cm-14){ data-preview }, [CM-02 (02)](../../../reference/controls/configuration-management.md#cm-02-02){ data-preview }, [CM-08 (03)](../../../reference/controls/configuration-management.md#cm-08-03){ data-preview }, [SC-13](../../../reference/controls/system-and-communications-protection.md#sc-13){ data-preview }, [SC-23](../../../reference/controls/system-and-communications-protection.md#sc-23){ data-preview }, [SI-07](../../../reference/controls/system-and-information-integrity.md#si-07){ data-preview }, [SI-07 (01)](../../../reference/controls/system-and-information-integrity.md#si-07-01){ data-preview }, [SI-07 (15)](../../../reference/controls/system-and-information-integrity.md#si-07-15){ data-preview }, [SR-10](../../../reference/controls/supply-chain-risk-management.md#sr-10){ data-preview }, [SR-11](../../../reference/controls/supply-chain-risk-management.md#sr-11){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
