---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Minimum Assessment Scope

The Minimum Assessment Scope rules help providers define assessment boundaries narrowly enough to avoid unnecessary review of components that do not affect the offering's security. These rules still ensure the assessment includes the resources and connections needed to understand the offering's confidentiality, integrity, and availability.

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Optional Adoption:** 2026-07-04
    - **Obtain:** 2027-01-01
    - **Maintain:** 2027-01-01
    - **Grace Ends:** On the first FedRAMP independent assessment started after 2027-01-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers for any type of FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Identify Information Resources

??? abstract "MAS-CSO-IIR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST identify a set of information resources to assess for FedRAMP Certification that includes all information resources that are likely to handle federal customer data or likely to impact the confidentiality, integrity, or availability of federal customer data handled by the cloud service offering; this set of information resources is the cloud service offering.


    ---

    _**Notes:**_

    - _Certain categories of cloud computing products and services are specified as entirely outside the scope of FedRAMP by the Director of the Office of Management and Budget. All such products and services are therefore not included in the cloud service offering for FedRAMP. For more, see https://fedramp.gov/scope._
    - _Software produced by cloud service providers that is delivered separately for installation on agency systems and not operated in a shared responsibility model (typically including agents, application clients, mobile applications, etc. that are not fully managed by the cloud service provider) is not a cloud computing product or service and is entirely outside the scope of FedRAMP under the FedRAMP Certification Act. All such software is therefore not included in the cloud service offering for FedRAMP. For more, see https://fedramp.gov/scope._
    - _All aspects of the cloud service offering are determined and maintained by the cloud service provider in accordance with related FedRAMP Certification rules and documented by the cloud service provider in their FedRAMP Certification Package._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Handle](../../../definitions/#handle){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }
### Information Flows and Security Categories

??? abstract "MAS-CSO-FLO"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST clearly identify, document, and explain information flows and security categories for ALL information resources or sets of information resources in the cloud service offering.


    ---

    _**Note:** Information resources (including third-party information resources) MAY vary by security category as appropriate to the type of information handled by or impacted by the information resource._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Handle](../../../definitions/#handle){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }, [Third-Party Information Resource](../../../definitions/#third-party-information-resource){ data-preview }
### Third-Party Information Resources

??? abstract "MAS-CSO-TPR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Certification Overview Package (FRC-CSO-PKG)](https://fedramp.gov/schemas/fedramp-certification-package-overview-schema-2026-06-24.json)"


!!! quote ""
    Providers MUST address the potential impact to federal customer data from third-party information resources used by the cloud service offering, ONLY IF [MAS-CSO-IIR (Identify Information Resources)](#identify-information-resources){ data-preview } APPLIES, by documenting the following information about each applicable third-party information resource:

    1. General usage and configuration
    1. Explanation or justification for use
    1. Mitigation measures in place to reduce the potential impact to federal customer data
    1. Compensating controls in place to reduce the potential impact to federal customer data


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Third-Party Information Resource](../../../definitions/#third-party-information-resource){ data-preview }
### Metadata Inclusion

??? abstract "MAS-CSO-MDI"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST include metadata (including metadata about federal customer data) in the Minimum Assessment Scope ONLY IF [MAS-CSO-IIR (Identify Information Resources)](#identify-information-resources){ data-preview } APPLIES.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }
### Supplemental Information

??? abstract "MAS-CSO-SUP"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MAY include additional materials about other information resources that are not part of the cloud service offering in a FedRAMP Certification Package supplement; these resources will not be FedRAMP Certified and MUST be clearly marked and separated from the cloud service offering.


    ---

    _**Note:** This is intended to allow inclusion of things like security materials for apps, supplemental marketing collateral, and other information that is not part of the cloud service offering but may be useful to agencies._

    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certified](../../../definitions/#fedramp-certified){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }
