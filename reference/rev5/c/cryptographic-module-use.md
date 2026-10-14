---
search:
  exclude: true
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Cryptographic Module Use

The Cryptographic Module Use rules clarify how providers should select and use cryptographic modules. These rules allow risk-based decisions for some services while still encouraging validated cryptographic modules whenever they are technically feasible and reasonable.

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption Allowed:** 2026-07-04
    - **Obtaining Initial Certification:** 2027-01-01
    - **Maintaining Ongoing Certification:** 2027-01-01
    - **Grace Period Ends:** 2027-06-01



---


## Cloud Service Provider Responsibilities {#cloud-service-provider-responsibilities}

These rules apply to providers for FedRAMP Certifications.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Cryptographic Module Documentation

??? abstract "CMU-CSO-CMD"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added au-9.3, cm-3.6, ia-7, sc-28.1, sc-8.1.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Providers [MUST](../../../definitions/#must){ data-preview } document the cryptographic modules used in each service (or groups of services that use the same modules) where cryptographic services are used to protect federal customer data, including whether these modules are validated under the NIST Cryptographic Module Validation Program or are update streams of such modules.



    **Related SP 800-53 Controls:** [AU-09 (03)](../../controls/audit-and-accountability.md#au-09-03){ data-preview }, [CM-03 (06)](../../controls/configuration-management.md#cm-03-06){ data-preview }, [IA-07](../../controls/identification-and-authentication.md#ia-07){ data-preview }, [SC-28 (01)](../../controls/system-and-communications-protection.md#sc-28-01){ data-preview }, [SC-08 (01)](../../controls/system-and-communications-protection.md#sc-08-01){ data-preview }

    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Using Validated Cryptographic Modules

??? abstract "CMU-CSO-UVM"
    **Changelog:**
    { data-search-exclude }


    - **2026-10-13:** Updated control mappings: added ac-18, au-9.3, ia-7, sc-28.1, sc-8.1.
    { data-search-exclude }


    - **2026-10-05:** Added a note clarifying that new algorithms in update streams of modules are not included in the scope of updates to  validated cryptographic modules.
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    === "Class C"
        Providers with Class C Certifications [SHOULD](../../../definitions/#should){ data-preview } use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.


    ---

    _**Note:** Cryptographic modules include specific algorithms by definition; if an update stream of a cryptographic module adds new algorithms that were not previously validated then those algorithms can not be considered within the scope of update stream usage under these rules as they are new algorithms within the module that have never been validated._


    **Related SP 800-53 Controls:** [AC-18](../../controls/access-control.md#ac-18){ data-preview }, [AU-09 (03)](../../controls/audit-and-accountability.md#au-09-03){ data-preview }, [IA-07](../../controls/identification-and-authentication.md#ia-07){ data-preview }, [SC-28 (01)](../../controls/system-and-communications-protection.md#sc-28-01){ data-preview }, [SC-08 (01)](../../controls/system-and-communications-protection.md#sc-08-01){ data-preview }

    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
### Configuration of Agency Tenants

??? abstract "CMU-CSO-CAT"
    **Changelog:**
    { data-search-exclude }


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.
    { data-search-exclude }




!!! quote ""
    Providers [SHOULD](../../../definitions/#should){ data-preview } configure agency tenants by default to use cryptographic services that use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when such modules are available.


    ---
    **Terms:** [Validation](../../../definitions/#validation){ data-preview }
