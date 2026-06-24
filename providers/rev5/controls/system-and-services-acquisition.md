---
tags:
  - Rev5
  - Cloud Service Providers
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# System and Services Acquisition

### System Documentation { #sa-05-system-documentation }

??? abstract "SA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Obtain or develop administrator documentation for the system, system component, or system service that describes:
        - **1.** Secure configuration, installation, and operation of the system, component, or service;
        - **2.** Effective use and maintenance of security and privacy functions and mechanisms; and
        - **3.** Known vulnerabilities regarding configuration and use of administrative or privileged functions;
    - **b.** Obtain or develop user documentation for the system, system component, or system service that describes:
        - **1.** User-accessible security and privacy functions and mechanisms and how to effectively use those functions and mechanisms;
        - **2.** Methods for user interaction, which enables individuals to use the system, component, or service in a more secure manner and protect individual privacy; and
        - **3.** User responsibilities in maintaining the security of the system, component, or service and privacy of individuals;
    - **c.** Document attempts to obtain system, system component, or system service documentation when such documentation is either unavailable or nonexistent and take [Assignment: organization-defined actions] in response; and
    - **d.** Distribute documentation to [Assignment: organization-defined personnel or roles].

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Secure Configuration Guide rules.

---

### Identification of Functions, Ports, Protocols, and Services { #sa-09-02-identification-of-functions-ports-protocols-and-services }

??? abstract "SA-09(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-09(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Require providers of the following external system services to identify the functions, ports, protocols, and other services required for the use of such services: [Assignment: organization-defined external system services].

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `sa-09.02_odp` | external system services | all external systems where federal customer data is processed or stored |

---

### Processing, Storage, and Service Location { #sa-09-05-processing-storage-and-service-location }

??? abstract "SA-09(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SA-09(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Restrict the location of [Selection: one or more of: information processing; information or data; system services] to [Assignment: organization-defined locations] based on [Assignment: organization-defined requirements].

    !!! info ""
        === "Class C"
            **FedRAMP Parameters**

            | Parameter ID | NIST assignment | FedRAMP value |
            | --- | --- | --- |
            | `sa-09.05_odp.01` | one or more of: information processing; information or data; system services | information processing, information or data, AND system services |
            | `sa-09.05_odp.03` | requirements | all federal customer data |

        === "Class D"
            **FedRAMP Parameters**

            | Parameter ID | NIST assignment | FedRAMP value |
            | --- | --- | --- |
            | `sa-09.05_odp.01` | one or more of: information processing; information or data; system services | information processing, information or data, AND system services |
            | `sa-09.05_odp.02` | locations | U.S./U.S. Territories or geographic locations where there is U.S. jurisdiction |
            | `sa-09.05_odp.03` | requirements | all federal customer data |

---
