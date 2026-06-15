---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Cryptographic Module Use

The Cryptographic Module Use rules clarify how providers should select and use cryptographic modules. These rules allow risk-based decisions for some services while still encouraging validated cryptographic modules whenever they are technically feasible and reasonable.

!!! info "Effective Date(s) & Overall Applicability for 20x"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2026-07-04
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment completed after 2027-01-01



---


## Cloud Service Provider Responsibilities {#cloud-service-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications.

### Cryptographic Module Documentation

??? abstract "CMU-CSO-CMD"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers MUST document the cryptographic modules used in each service (or groups of services that use the same modules) where cryptographic services are used to protect federal customer data, including whether these modules are validated under the NIST Cryptographic Module Validation Program or are update streams of such modules.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Using Validated Cryptographic Modules

??? abstract "CMU-CSO-UVM"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    === "Class C"
        Providers with Class C Certifications SHOULD use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Configuration of Agency Tenants

??? abstract "CMU-CSO-CAT"
    **Changelog:**


    - **2026-06-30:** Initial reset for the Consolidated Rules for 2026 Public Preview.




!!! quote ""
    Providers SHOULD configure agency tenants by default to use cryptographic services that use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when such modules are available.


    ---
    **Terms:** [Validation](../../../definitions/#validation){ data-preview }
