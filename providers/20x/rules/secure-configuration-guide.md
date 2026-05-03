---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Secure Configuration Guide


---


## General Provider Responsibilities

These rules apply to providers with FedRAMP Certifications of any type.

### Recommended Secure Configuration

??? abstract "SCG-CSO-RSC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST create, maintain, and make available recommendations for securely configuring their cloud services (the Secure Configuration Guide) that includes at least the following information:

    1. Required: Instructions on how to securely access, configure, operate, and decommission top-level administrative accounts that control enterprise access to the entire cloud service offering.
    1. Required: Explanations of security-related settings that can be operated only by top-level administrative accounts and their security implications.
    1. Recommended: Explanations of security-related settings that can be operated only by privileged accounts and their security implications.


    ---

    _**Notes:**_

    - _These rules refer to this guidance as a Secure Configuration Guide but cloud service providers may make this guidance available in various appropriate forms that provide the best customer experience._
    - _This guidance should explain how top-level administrative accounts are named and referred to in the cloud service offering._
    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
### Use Instructions

??? abstract "SCG-CSO-AUP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST include instructions in the FedRAMP Certification package that explain how to obtain and use the Secure Configuration Guide.


    ---

    _**Note:** These instructions may appear in a variety of ways; it is up to the provider to do so in the most appropriate and effective ways for their specific customer needs._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }
### Public Guidance

??? abstract "SCG-CSO-PUB"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD make the Secure Configuration Guide available publicly.


### Secure Defaults

??? abstract "SCG-CSO-SDF"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD set all settings to their recommended secure defaults for top-level administrative accounts and privileged accounts when initially provisioned.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
## Enhanced Capabilities

These recommendations apply to providers with FedRAMP Certifications of any type.

### Comparison Capability

??? abstract "SCG-ENH-CMP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD offer the capability to compare all current settings for top-level administrative accounts and privileged accounts to the recommended secure defaults.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
### Export Capability

??? abstract "SCG-ENH-EXP"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD offer the capability to export all security settings in a machine-readable format.


    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### API Capability

??? abstract "SCG-ENH-API"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD offer the capability to view and adjust security settings via an API or similar capability.


### Machine-Readable Guidance

??? abstract "SCG-ENH-MRG"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD also provide the Secure Configuration Guide in a machine-readable format that can be used by customers or third-party tools to compare against current settings.


    ---
    **Terms:** [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### Versioning and Release History

??? abstract "SCG-ENH-VRH"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD provide versioning and a release history for recommended secure default settings for top-level administrative accounts and privileged accounts as they are adjusted over time.


    ---
    **Terms:** [Privileged Account](../../../definitions/#privileged-account){ data-preview }, [Top-Level Administrative Account](../../../definitions/#top-level-administrative-account){ data-preview }
