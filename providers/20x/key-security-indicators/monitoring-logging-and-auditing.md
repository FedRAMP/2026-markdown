---
search:
  exclude: true
tags:
  - 20x
  - Cloud Service Providers
  - Key Security Indicators
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Monitoring, Logging, and Auditing






### Authorizing Log Access

??? abstract "KSI-MLA-ALA"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added au-12.3, au-6.7.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class B"
        **Optional:** A least-privileged, role and attribute-based, and just-in-time access authorization model is used and persistently reviewed for access to log data based on organizationally defined data sensitivity.

    === "Class C"
        A least-privileged, role and attribute-based, and just-in-time access authorization model is used and persistently reviewed for access to log data based on organizationally defined data sensitivity.



    **Related SP 800-53 Controls:** [AU-12 (03)](../../../reference/controls/audit-and-accountability.md#au-12-03){ data-preview }, [AU-06 (07)](../../../reference/controls/audit-and-accountability.md#au-06-07){ data-preview }, [SI-11](../../../reference/controls/system-and-information-integrity.md#si-11){ data-preview }

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }
### Evaluating Configurations

??? abstract "KSI-MLA-EVC"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-19, cm-6.1, ra-3.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    The configuration of machine-based information resources, especially infrastructure as code, is persistently evaluated and tested.



    **Related SP 800-53 Controls:** [AC-19](../../../reference/controls/access-control.md#ac-19){ data-preview }, [CA-07](../../../reference/controls/assessment-authorization-and-monitoring.md#ca-07){ data-preview }, [CM-02](../../../reference/controls/configuration-management.md#cm-02){ data-preview }, [CM-06](../../../reference/controls/configuration-management.md#cm-06){ data-preview }, [CM-06 (01)](../../../reference/controls/configuration-management.md#cm-06-01){ data-preview }, [RA-03](../../../reference/controls/risk-assessment.md#ra-03){ data-preview }, [SI-07 (07)](../../../reference/controls/system-and-information-integrity.md#si-07-07){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Logging Event Types

??? abstract "KSI-MLA-LET"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added au-10, au-7, cm-5.1, ir-9.4, si-4.19, si-4.20.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    A list of information resources and event types that will be logged, monitored, and audited is maintained and persistently reviewed to ensure these activities occur.



    **Related SP 800-53 Controls:** [AC-17 (01)](../../../reference/controls/access-control.md#ac-17-01){ data-preview }, [AC-02 (04)](../../../reference/controls/access-control.md#ac-02-04){ data-preview }, [AC-20 (01)](../../../reference/controls/access-control.md#ac-20-01){ data-preview }, [AC-06 (09)](../../../reference/controls/access-control.md#ac-06-09){ data-preview }, [AU-10](../../../reference/controls/audit-and-accountability.md#au-10){ data-preview }, [AU-12](../../../reference/controls/audit-and-accountability.md#au-12){ data-preview }, [AU-02](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview }, [AU-07](../../../reference/controls/audit-and-accountability.md#au-07){ data-preview }, [AU-07 (01)](../../../reference/controls/audit-and-accountability.md#au-07-01){ data-preview }, [CM-05 (01)](../../../reference/controls/configuration-management.md#cm-05-01){ data-preview }, [IR-09 (04)](../../../reference/controls/incident-response.md#ir-09-04){ data-preview }, [SI-04 (19)](../../../reference/controls/system-and-information-integrity.md#si-04-19){ data-preview }, [SI-04 (20)](../../../reference/controls/system-and-information-integrity.md#si-04-20){ data-preview }, [SI-04 (04)](../../../reference/controls/system-and-information-integrity.md#si-04-04){ data-preview }, [SI-04 (05)](../../../reference/controls/system-and-information-integrity.md#si-04-05){ data-preview }, [SI-07 (07)](../../../reference/controls/system-and-information-integrity.md#si-07-07){ data-preview }

    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }
### Operating SIEM Capability

??? abstract "KSI-MLA-OSM"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added au-12.1, au-5.1, au-6.4, au-6.5, si-4.16; removed si-7.7.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    A Security Information and Event Management (SIEM) or similar system(s) is used and persistently reviewed for centralized, tamper-resistant logging of events, activities, and changes.



    **Related SP 800-53 Controls:** [AC-17 (01)](../../../reference/controls/access-control.md#ac-17-01){ data-preview }, [AC-20 (01)](../../../reference/controls/access-control.md#ac-20-01){ data-preview }, [AU-11](../../../reference/controls/audit-and-accountability.md#au-11){ data-preview }, [AU-12 (01)](../../../reference/controls/audit-and-accountability.md#au-12-01){ data-preview }, [AU-02](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview }, [AU-03](../../../reference/controls/audit-and-accountability.md#au-03){ data-preview }, [AU-03 (01)](../../../reference/controls/audit-and-accountability.md#au-03-01){ data-preview }, [AU-04](../../../reference/controls/audit-and-accountability.md#au-04){ data-preview }, [AU-05](../../../reference/controls/audit-and-accountability.md#au-05){ data-preview }, [AU-05 (01)](../../../reference/controls/audit-and-accountability.md#au-05-01){ data-preview }, [AU-06 (01)](../../../reference/controls/audit-and-accountability.md#au-06-01){ data-preview }, [AU-06 (03)](../../../reference/controls/audit-and-accountability.md#au-06-03){ data-preview }, [AU-06 (04)](../../../reference/controls/audit-and-accountability.md#au-06-04){ data-preview }, [AU-06 (05)](../../../reference/controls/audit-and-accountability.md#au-06-05){ data-preview }, [AU-07](../../../reference/controls/audit-and-accountability.md#au-07){ data-preview }, [AU-07 (01)](../../../reference/controls/audit-and-accountability.md#au-07-01){ data-preview }, [AU-08](../../../reference/controls/audit-and-accountability.md#au-08){ data-preview }, [AU-09](../../../reference/controls/audit-and-accountability.md#au-09){ data-preview }, [IR-04 (01)](../../../reference/controls/incident-response.md#ir-04-01){ data-preview }, [SI-04 (16)](../../../reference/controls/system-and-information-integrity.md#si-04-16){ data-preview }, [SI-04 (02)](../../../reference/controls/system-and-information-integrity.md#si-04-02){ data-preview }, [SI-04 (04)](../../../reference/controls/system-and-information-integrity.md#si-04-04){ data-preview }

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }
### Reviewing Logs

??? abstract "KSI-MLA-RVL"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added au-7, ra-5.8, si-4.19.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Logs are persistently reviewed and audited.



    **Related SP 800-53 Controls:** [AC-02 (04)](../../../reference/controls/access-control.md#ac-02-04){ data-preview }, [AC-06 (09)](../../../reference/controls/access-control.md#ac-06-09){ data-preview }, [AU-02](../../../reference/controls/audit-and-accountability.md#au-02){ data-preview }, [AU-06](../../../reference/controls/audit-and-accountability.md#au-06){ data-preview }, [AU-06 (01)](../../../reference/controls/audit-and-accountability.md#au-06-01){ data-preview }, [AU-07](../../../reference/controls/audit-and-accountability.md#au-07){ data-preview }, [RA-05 (08)](../../../reference/controls/risk-assessment.md#ra-05-08){ data-preview }, [SI-04](../../../reference/controls/system-and-information-integrity.md#si-04){ data-preview }, [SI-04 (19)](../../../reference/controls/system-and-information-integrity.md#si-04-19){ data-preview }, [SI-04 (04)](../../../reference/controls/system-and-information-integrity.md#si-04-04){ data-preview }

    ---
    **Terms:** [Persistently](../../../definitions/#persistently){ data-preview }
