---
tags:
  - Rev5
---

# Using Cryptographic Modules


---


## CSO

### Cryptographic Module Documentation

??? abstract "UCM-CSO-CMD"
    **Changelog:**


    - **2026-06-01:** Revisited and baselined against the Consolidated Rules for 2026.



!!! quote ""
    Providers MUST document the cryptographic modules used in each service (or groups of services that use the same modules) where cryptographic services are used to protect federal customer data, including whether these modules are validated under the NIST Cryptographic Module Validation Program or are update streams of such modules.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Using Validated Cryptographic Modules

??? abstract "UCM-CSO-UVM"
    **Changelog:**


    - **2026-06-01:** Revisited and baselined against the Consolidated Rules for 2026.



!!! quote ""
    === "Class A"
        Providers of Class A offerings MAY use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.

    === "Class B"
        Providers of Class B offerings MAY use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.

    === "Class C"
        Providers of Class C offerings SHOULD use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.

    === "Class D"
        Providers of Class D offerings MUST use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Configuration of Agency Tenants

??? abstract "UCM-CSO-CAT"
    **Changelog:**


    - **2026-06-01:** Revisited and baselined against the Consolidated Rules for 2026.



!!! quote ""
    Providers SHOULD configure agency tenants by default to use cryptographic services that use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when such modules are available.


    ---
    **Terms:** [Agency](../../../definitions/#agency){ data-preview }, [Provider](../../../definitions/#provider){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
