---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Secure Configuration Guide

The Secure Configuration Guide rules help agencies and other customers understand how to configure a cloud service offering securely. These rules require providers to clearly explain the security impact of common settings so customers can make informed configuration choices.

**Subsets**

- [General Provider Responsibilities](#general-provider-responsibilities)
- [Enhanced Capabilities](#enhanced-capabilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Obtain:** 2026-03-01
    - **Maintain:** 2026-03-01
    - **Grace Ends:** 2026-07-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Recommended Secure Configuration

??? abstract "SCG-CSO-RSC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Certification Overview Package (FRC-CSO-PKG)](https://fedramp.gov/schemas/fedramp-certification-overview-package-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST create, maintain, and make available recommendations for securely configuring their cloud services (the Secure Configuration Guide) that includes at least the following information:

    1. Required: Instructions on how to securely access, configure, operate, and decommission top-level administrative accounts that control enterprise access to the entire cloud service offering.
    1. Required: Explanations of security-related settings that can be operated only by top-level administrative accounts and their security implications.
    1. Recommended: Explanations of security-related settings that can be operated only by privileged accounts and their security implications.


    ---

    _**Notes:**_

    - _These rules refer to this guidance as a Secure Configuration Guide but cloud service providers may make this guidance available in various appropriate forms that provide the best customer experience._
    - _This guidance should explain how top-level administrative accounts and privileged accounts are named and referred to in the cloud service offering._
    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
### Use Instructions

??? abstract "SCG-CSO-AUP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST include instructions in the FedRAMP Certification Package that explain how to obtain and use the Secure Configuration Guide.


    ---

    _**Note:** These instructions may appear in a variety of ways; it is up to the provider to do so in the most appropriate and effective ways for their specific customer needs._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
### Public Secure Configuration Guidance

??? abstract "SCG-CSO-PUB"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD make the Secure Configuration Guide available publicly.


### Secure Defaults

??? abstract "SCG-CSO-SDF"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD set all settings to their recommended secure defaults for top-level administrative accounts and privileged accounts when initially provisioned.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
## Enhanced Capabilities {#enhanced-capabilities}

These recommendations apply to providers with FedRAMP Certifications of any type.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Comparison Capability

??? abstract "SCG-ENH-CMP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD offer the capability to compare all current settings for top-level administrative accounts and privileged accounts to the recommended secure defaults.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
### Export Capability

??? abstract "SCG-ENH-EXP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD offer the capability to export all security settings in a machine-readable format.


    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### API Capability

??? abstract "SCG-ENH-API"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD offer the capability to view and adjust security settings via an API or similar capability.


### Machine-Readable Guidance

??? abstract "SCG-ENH-MRG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD also provide the Secure Configuration Guide in a machine-readable format that can be used by customers or third-party tools to compare against current settings.


    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### Versioning and Release History

??? abstract "SCG-ENH-VRH"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD provide versioning and a release history for recommended secure default settings for top-level administrative accounts and privileged accounts as they are adjusted over time.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
