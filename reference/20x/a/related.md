---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# 20x Class A Related Rules

These rules are referenced by this ruleset reference but are not otherwise included in this generated class-specific ruleset.



---


## Addressing FedRAMP Communication (AFC) {#addressing-fedramp-communication-afc}

The Addressing FedRAMP Communication rules (formerly FedRAMP Security Inbox) ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.

### Complete Required Actions

??? abstract "AFC-CSO-CRA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST complete the required actions in Emergency or Emergency Test designated messages sent by FedRAMP within the timeframe included in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }
### Maintain a FedRAMP Security Inbox

??? abstract "AFC-CSO-INB"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST establish and maintain an email address to receive messages from FedRAMP; this inbox is a FedRAMP Security Inbox (FSI).

    ---

    !!! danger "Be careful using a personal email tied to an individual for this inbox due to the significant risk to future communications after a change in personnel!"

    ---

    _**Notes:**_

    - _Unless otherwise notified, FedRAMP will use the listed Security Email on the Marketplace for these notifications._
    - _If a provider establishes a new inbox in reaction to this guidance that is different from the Security Email then they must follow the [AFC-CSO-NOC (Notification of Changes)](../../../providers/20x/rules/addressing-fedramp-communication.md#notification-of-changes){ data-preview } rules to notify FedRAMP._
    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Receive Email Without Disruption

??? abstract "AFC-CSO-RCV"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST receive and react to email messages from FedRAMP without disruption and without requiring additional actions from FedRAMP.


    ---

    _**Note:** This requirement is intended to prevent cloud service providers from requiring FedRAMP to complete a CAPTCHA, log into a customer portal, or otherwise take service-specific actions that might prevent the security team from receiving the message._

## Certification Data Sharing (CDS) {#certification-data-sharing-cds}

The Certification Data Sharing rules allow providers to store and share FedRAMP certification information through the platform they choose as long as it follows FedRAMP rules for access, accuracy, and transparency. This helps customers and the public review consistent, current security and compliance information while recognizing that the information usually remains the provider's intellectual property and is not federal information.

### Availability Reporting

??? abstract "CDS-CSO-AVR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service SHOULD be available even if the primary cloud service offering is unavailable.

        ---

        _**Note:** This service may be separate from the trust center._


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Machine-Readable](../../../definitions/#machine-readable){ data-preview }
### Per-Service Certification Materials

??? abstract "CDS-CSO-PSM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY supply per-service FedRAMP Certification materials.


    ---

    _**Notes:**_

    - _Providers determine what they consider to be separate services, based on maximizing the customer experience for agencies who may only adopt some services and not others._
    - _Providers are encouraged to provide a single comprehensive set of materials for all shared aspects of the service offering and only provide separate materials for unique aspects of each service to minimize the burden on providers and agencies._
### Public Information

??? abstract "CDS-CSO-PUB"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Public Marketplace Information Schema](https://fedramp.gov/schemas/fedramp-public-marketplace-information-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    Providers MUST publicly share up-to-date information about the cloud service offering in both human-readable and JSON formats, including at least the following information that is available and applicable:

    1. Direct link to the FedRAMP Marketplace for the offering
    1. Service Model
    1. Deployment Model
    1. Business Category
    1. UEI Number
    1. Sales Contact Information
    1. Security Contact Information
    1. Product Website Link
    1. Link to Product Logo
    1. Overall Service Description
    1. Detailed list of specific services and their security categories (see [CDS-CSO-SVC (Public Service List)](../../../providers/20x/rules/certification-data-sharing.md#public-service-list){ data-preview } (Service List))
    1. Link to Secure Configuration Guidance
    1. Overview of documentation supplied by the provider for the cloud service offering
    1. Link to Trust Center landing page that includes instructions on accessing information in the trust center
    1. Next Ongoing Certification Report date (see [CCM-OCR-NRD (Next Report Date)](#next-report-date){ data-preview })
    1. Current FedRAMP Recognized Independent Assessment Service


    ---

    _**Note:** Generally, this information should be available on a public webpage or publicly shared in a FedRAMP-compatible trust center._

    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certification Report](../../../definitions/#fedramp-certification-report){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Security Category](../../../definitions/#security-category){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Use Trust Centers

??? abstract "CDS-CSO-UTC"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST use a FedRAMP-compatible trust center to store and share FedRAMP Certification Data with all necessary parties.


    ---

    _**Note:** Rules for FedRAMP-Compatible Trust Centers are explained in the Certification Data Sharing Rules under the FedRAMP-Compatible Trust Centers section (id: CDS-TRC)._

    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Trust Center](../../../definitions/#trust-center){ data-preview }
### Agency Access Denial

??? abstract "CDS-UTC-AAD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by form using https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51829826617243.


!!! quote ""
    Providers MUST notify FedRAMP within 5 business days of denying an agency access request for FedRAMP Certification Data.

    **Timeframe:** 5 business days


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }
## Certification Package Overview (CPO) {#certification-package-overview-cpo}

The Certification Package Overview rules outline the expectations for a simple overview of the cloud service offering that must be included within a FedRAMP Certification Package. This overview replaces the historically required base System Security Plan for FedRAMP Rev5 and is intended to provide a clear, concise, and consistent summary of the offering and the information included in the package to help customers understand the offering at a high level.

### Certification Package Maintenance for Rev5

??? abstract "CPO-CSF-CPM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Rev5 Class A Certifications SHOULD persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every year.

        **Timeframe:** 1 years


    ---

    _**Notes:**_

    - _This maximum timeframe for Rev5 is the absolutely poorest worst case for horrible customer experience and is based on legacy FedRAMP Rev5 allowing providers to leave their packages unmaintained for up to a year. Rev5 providers should maintain their packages far more frequently than this requirement to ensure potential customers have access to up-to-date information, updating it at least after every transformative significant change._
    - _FedRAMP 20x Certifications expect providers to maintain their FedRAMP Certification Packages as changes occur to ensure they are never out of date._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Significant Change](../../../definitions/#significant-change){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }
## Collaborative Continuous Monitoring (CCM) {#collaborative-continuous-monitoring-ccm}

The Collaborative Continuous Monitoring rules help agencies use shared, current authorization information from providers as part of each agency's own Information Security Continuous Monitoring strategy. These rules reduce unnecessary manual burden by encouraging automated monitoring and review while allowing each agency to make its own risk-based decisions about ongoing authorization.

### Report Availability

??? abstract "CCM-OCR-AVL"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply an Ongoing Certification Report to all necessary parties every 3 months, covering the entire period since the previous summary, in a consistent format that is human readable; this report MUST include high-level summaries of at least the following information:

    1. Changes to FedRAMP Certification Data
    1. Planned changes to FedRAMP Certification Data during at least the next 3 months
    1. Accepted vulnerabilities
    1. Transformative changes
    1. Updated recommendations or best practices for security, configuration, usage, or similar aspects of the cloud service offering
    1. A list of all agencies that are directly using the product
    1. FedRAMP Reportable Incidents or an attestation that no such incidents occurred
    1. Lessons learned and changes planned or made as a result of FedRAMP Reportable Incidents (if such occurred)


    ---
    **Terms:** [Accepted Vulnerability](../../../definitions/#accepted-vulnerability){ data-preview }, [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Certification Data](../../../definitions/#certification-data){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Certification Report](../../../definitions/#fedramp-certification-report){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }, [Transformative Change](../../../definitions/#transformative-change){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
### Next Report Date

??? abstract "CCM-OCR-NRD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST supply the target date for their next Ongoing Certification Report with other public FedRAMP Certification Data.


    ---
    **Terms:** [Certification Data](../../../definitions/#certification-data){ data-preview }, [FedRAMP Certification Report](../../../definitions/#fedramp-certification-report){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Ongoing Certification Report (OCR)](../../../definitions/#ongoing-certification-report-ocr){ data-preview }
### Quarterly Review Meeting

??? abstract "CCM-QTR-MTG"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY host a synchronous Quarterly Review every 3 months, open to all necessary parties, to review aspects of the most recent Ongoing Certification Reports that the provider determines are of the most relevance to agencies.

        **Timeframe:** 3 months


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Ongoing Certification](../../../definitions/#ongoing-certification){ data-preview }, [Quarterly Review](../../../definitions/#quarterly-review){ data-preview }
## Cryptographic Module Use (CMU) {#cryptographic-module-use-cmu}

The Cryptographic Module Use rules clarify how providers should select and use cryptographic modules. These rules allow risk-based decisions for some services while still encouraging validated cryptographic modules whenever they are technically feasible and reasonable.

### Using Validated Cryptographic Modules

??? abstract "CMU-CSO-UVM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.


    ---
    **Terms:** [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }
## Incident Evaluation and Communication (IEC) {#incident-evaluation-and-communication-iec}

The Incident Evaluation and Communication rules explain how providers must communicate incident information to FedRAMP and government customers when they are affected by an incident or likely to be affected by an incident.

### Evaluate FedRAMP Reportability

??? abstract "IEC-CSO-EFR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST promptly evaluate incidents to determine if they affect confidentiality or integrity of federal customer data or are likely to affect confidentiality or integrity of federal customer data; such incidents are FedRAMP Reportable Incidents and must be reported following the FedRAMP Incident Communications Procedures.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
### Final Incident Report

??? abstract "IEC-CSO-FIR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by varies using varies by agency.
    - Notify All Necessary Parties by update using trust center.


!!! quote ""
    === "Class A"
        Providers with Class A Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Final Incident Report |
        |--------------------------|---|
        | PAIN-5 | 3 business days |
        | PAIN-4 | 3 business days |
        | PAIN-3 | 3 business days |
        | PAIN-2 | 3 business days |
        | PAIN-1 | 3 business days |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [Final Incident Report (FIR)](../../../definitions/#final-incident-report-fir){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Initial Incident Report

??? abstract "IEC-CSO-IIR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by varies using varies by agency.
    - Notify All Necessary Parties by update using trust center.


!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting and/or the current relevant status for each item:

        1. Contact information for the federal incident response coordinator
        1. Provider's internally assigned tracking identifier
        1. Description of the incident
        1. Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider
        1. Historically and currently estimated Potential Agency Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in [IEC-CSO-EFI (Estimate Federal Impact)](../../../providers/20x/rules/incident-evaluation-and-communication.md#estimate-federal-impact){ data-preview } (if applicable)
        1. Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)
        1. Estimated recovery plan, milestones, and timelines
        1. List of likely affected customer agencies


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Initial Incident Report |
        |--------------------------|---|
        | PAIN-5 | 6 hours |
        | PAIN-4 | 6 hours |
        | PAIN-3 | 6 hours |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Initial Incident Report (IIR)](../../../definitions/#initial-incident-report-iir){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }
### Ongoing Incident Reports

??? abstract "IEC-CSO-OIR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using fedramp_security@fedramp.gov.
    - Notify Agency Customers by varies using varies by agency.
    - Notify All Necessary Parties by update using trust center.


!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available and/or the current relevant status for each item:

        1. Observed incident activity
        1. Indicators of compromise
        1. Related Common Vulnerabilities and Exposures (CVE) identifier (if applicable)
        1. Root cause
        1. Response and recovery activities


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | Ongoing Incident Report |
        |--------------------------|---|
        | PAIN-5 | 1 business day |
        | PAIN-4 | 1 business day |
        | PAIN-3 | 1 business day |
        | PAIN-2 | 1 business day |
        | PAIN-1 | 1 business day |


    ---
    **Terms:** [All Affected Parties](../../../definitions/#all-affected-parties){ data-preview }, [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Responsibly](../../../definitions/#responsibly){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
## Independent Verification and Validation (IVV) {#independent-verification-and-validation-ivv}

This ruleset explains the expectations for independent verification and validation assessments.

### Annual Independent Assessments for Rev5

??? abstract "IVV-CSF-AIA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""

    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }
### FedRAMP Independent Assessments

??? abstract "IVV-CSO-FIA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY persistently complete an independent verification and validation assessment of all applicable FedRAMP Rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

        **Timeframe:** 1 years


    ---

    _**Notes:**_

    - _The first such completed assessment is typically called an "initial assessment" while following assessments are called "annual assessments."_
    - _The specific requirements for independent verification and validation assessments are documented by the FedRAMP Certification Class and Type._
    - _The option for assessment by FedRAMP directly is limited to cloud services that are explicitly prioritized by FedRAMP, in consultation with the FedRAMP Board and the federal Chief Information Officers Council; this is _extremely_ rare._
    - _FedRAMP Recognized independent assessment services are listed on the FedRAMP Marketplace._
    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }, [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [FedRAMP Recognized](../../../definitions/#fedramp-recognized){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Annual Independent Assessments for 20x

??? abstract "IVV-CSX-AIA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with 20x Class A Certifications MUST meet the expectations of their underlying alternative security framework as part of their persistent independent verification and validation assessment.


    ---
    **Terms:** [FedRAMP Independent Assessment](../../../definitions/#fedramp-independent-assessment){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
## Marketplace Listing (MKT) {#marketplace-listing-mkt}

The Marketplace Listing rules define how FedRAMP decides which cloud service offerings, assessors, and advisors may be listed in the FedRAMP Marketplace. These rules help agencies and other customers rely on the Marketplace as a consistent source of eligible services and supporting organizations, while requiring listed organizations to supply accurate, accessible, and machine-readable information.

### Agency Use Cases

??? abstract "MKT-IIP-AGU"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST demonstrate that a cloud service offering is intended for one of the following use cases:

    1. Direct Use: The product will be used directly by agency customers for integration into a federal information system that falls within the scope of 44 USC § 3506 and will receive an agency Authorization to Operate.
    1. Indirect Use: The product will be included as a third-party information resource in other cloud service offerings that are directly used by agency customers.


    ---

    _**Notes:**_

    - _FedRAMP will not list products or services that are outside the explicit statutory scope of FedRAMP; See [MKT-FRP-SOF (Scope of FedRAMP)](marketplace-listing.md#scope-of-fedramp){ data-preview }._
    - _Services used by private companies to meet other compliance requirements (such as CMMC) that do not also meet one of the above use cases are outside the scope of FedRAMP._
    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Third-Party Information Resource](../../../definitions/#third-party-information-resource){ data-preview }
### Demonstrating Continuous Progress

??? abstract "MKT-IIP-DCP"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST demonstrate continuous progress towards a FedRAMP Certification, documented in their Trust Center or website and updated at least quarterly; progress is measured by the provider against documented goals and milestones.


    ---

    _**Note:** This is an opportunity for a business to showcase its goals and progress, and should be seen as a marketing and customer experience challenge instead of a compliance challenge._

    ---
    **Terms:** [Trust Center](../../../definitions/#trust-center){ data-preview }
## Minimum Assessment Scope (MAS) {#minimum-assessment-scope-mas}

The Minimum Assessment Scope rules help providers define assessment boundaries narrowly enough to avoid unnecessary review of components that do not affect the offering's security. These rules still ensure the assessment includes the resources and connections needed to understand the offering's confidentiality, integrity, and availability.

### Identify Information Resources

??? abstract "MAS-CSO-IIR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST identify a set of information resources to assess for FedRAMP Certification that includes all information resources that are likely to handle federal customer data or likely to impact the confidentiality, integrity, or availability of federal customer data handled by the cloud service offering; this set of information resources is the cloud service offering.


    ---

    _**Notes:**_

    - _Certain categories of cloud computing products and services are specified as entirely outside the scope of FedRAMP by the Director of the Office of Management and Budget. All such products and services are therefore not included in the cloud service offering for FedRAMP. For more, see https://fedramp.gov/scope._
    - _Software produced by cloud service providers that is delivered separately for installation on agency systems and not operated in a shared responsibility model (typically including agents, application clients, mobile applications, etc. that are not fully managed by the cloud service provider) is not a cloud computing product or service and is entirely outside the scope of FedRAMP under the FedRAMP Certification Act. All such software is therefore not included in the cloud service offering for FedRAMP. For more, see fedramp.gov/scope._
    - _All aspects of the cloud service offering are determined and maintained by the cloud service provider in accordance with related FedRAMP Certification rules and documented by the cloud service provider in their FedRAMP Certification Package._
    ---
    **Terms:** [Certification Package](../../../definitions/#certification-package){ data-preview }, [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [Federal Customer Data](../../../definitions/#federal-customer-data){ data-preview }, [Handle](../../../definitions/#handle){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }
## Security Decision Record (SDR) {#security-decision-record-sdr}

The Security Decision Record replaced a traditional System Security Plan with a persistently maintained, verified, and validated record of the security decisions made by the cloud service provider over the lifecycle of their cloud service offering.

### Key Security Indicator Metrics

??? abstract "SDR-CSX-KMT"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Security Decision Record Schema](https://fedramp.gov/schemas/fedramp-security-decision-record-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    === "Class A"
        Providers with 20x Class A Certifications MAY also include historical metrics in their Security Decision Record.


    ---
    **Terms:** [Security Decision Record (SDR)](../../../definitions/#security-decision-record-sdr){ data-preview }
## Vulnerability Detection and Response (VDR) {#vulnerability-detection-and-response-vdr}

The Vulnerability Detection and Response rules require providers to continuously identify, analyze, prioritize, mitigate, and remediate vulnerabilities and related exposures through automated systems. These rules give providers flexibility in implementation while ensuring agencies receive the information needed to support ongoing authorization decisions.

### Vulnerability Detection

??? abstract "VDR-CSO-DET"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST systematically, persistently, and promptly discover and identify vulnerabilities within their cloud service offering using appropriate techniques such as assessment, scanning, threat intelligence, vulnerability disclosure mechanisms, bug bounties, penetration testing, incident response, automated control testing, supply chain monitoring, and other relevant capabilities; this process is called vulnerability detection. Vulnerability detection includes persistently verifying and validating that information resources and processes are operating as intended and documented for FedRAMP Practices.

    ---

    !!! danger "Vulnerability Detection and Response includes all efforts to identify weaknesses in a system and is NOT limited to traditional vulnerability scanning or testing. An out-of-date control statement in the Security Decision Record is a vulnerability that must be detected and remediated just like any other vulnerability."

    ---

    _**Notes:**_

    - _FedRAMP's vulnerability detection (and response) rules are intended to set modern expectations for maintaining the security of a cloud service. Historical FedRAMP guidance on vulnerability scanning or continuous monitoring generally focused only on CVE-type vulnerabilities while leaving other types of vulnerabilities and exposures unaddressed._
    - _Providers are encouraged to leverage their existing holistic security review, architecture review, and similar processes to meet these requirements. FedRAMP strongly discourages providers from implementing separate vulnerability detection and response processes for FedRAMP reporting that are operated by independent compliance branches unless these processes are consuming data directly from the areas of the cloud service that actively maintain it._
    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Practices](../../../definitions/#fedramp-practices){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Persistent Machine Verification and Validation for 20x

??? abstract "VDR-TFR-MVX"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers of FedRAMP 20x Class A offerings SHOULD verify and validate the status of machine-based information resources at least once every month.

        **Timeframe:** 1 month


    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Validation](../../../definitions/#validation){ data-preview }, [Verification](../../../definitions/#verification){ data-preview }
### Persistently Complete Detection

??? abstract "VDR-TFR-PCD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD persistently perform vulnerability detection on all information resources that are NOT likely to drift, at least once every 6 months.

        **Timeframe:** 6 months


    ---
    **Terms:** [Drift](../../../definitions/#drift){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }
### Persistent Drift Detection

??? abstract "VDR-TFR-PDD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD persistently perform vulnerability detection on all information resources that are likely to drift, at least once every 3 months.

        **Timeframe:** 3 months


    ---
    **Terms:** [Drift](../../../definitions/#drift){ data-preview }, [Information Resource](../../../definitions/#information-resource){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }
### Persistent Sample Detection

??? abstract "VDR-TFR-PSD"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD persistently perform vulnerability detection on representative samples of similar machine-based information resources, at least once every 14 days.

        **Timeframe:** 14 days


    ---
    **Terms:** [Information Resource](../../../definitions/#information-resource){ data-preview }, [Machine-Based (Information Resources)](../../../definitions/#machine-based-information-resources){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }
### Mitigation and Remediation Expectations

??? abstract "VDR-TFR-PVR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD partially mitigate vulnerabilities, fully mitigate vulnerabilities, or remediate vulnerabilities to a lower potential agency impact within the timeframes from evaluation shown below, factoring for the current Potential Agency Impact N-rating, internet reachability, and likely exploitability.


        ---

        **Potential Agency Impact N-rating (PAIN) Timeframes:**

        | PAIN Rating | LEV + IRV | LEV + NIRV | NLEV |
        |--------------------------|---|---|---|
        | PAIN-5 | 4 days | 8 days | 32 days |
        | PAIN-4 | 8 days | 32 days | 64 days |
        | PAIN-3 | 32 days | 64 days | 192 days |
        | PAIN-2 | 96 days | 160 days | 192 days |


    ---
    **Terms:** [Fully Mitigated Vulnerability](../../../definitions/#fully-mitigated-vulnerability){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Partially Mitigated Vulnerability](../../../definitions/#partially-mitigated-vulnerability){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Remediated Vulnerability](../../../definitions/#remediated-vulnerability){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
## Vulnerability Evaluation and Reporting (VER) {#vulnerability-evaluation-and-reporting-ver}

The Vulnerability Evaluation and Reporting rules require cloud service providers to determine when vulnerabilities are likely to impact federal customers and report the status of such vulnerabilities to all necessary parties.

### Evaluate Vulnerabilities Quickly

??? abstract "VER-TFR-EVU"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications SHOULD evaluate ALL vulnerabilities as required by VER-EVA (Evaluation) within 14 days of detection.

        **Timeframe:** 14 days


    ---
    **Terms:** [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }
### Internet-Reachable Incidents

??? abstract "VER-TFR-IRI"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY treat internet-reachable likely exploitable vulnerabilities where Potential Agency Impact N-rating > 3 as a FedRAMP Reportable Incident until they are partially mitigated vulnerabilities at N3 or below.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Likely Exploitable Vulnerability (LEV)](../../../definitions/#likely-exploitable-vulnerability-lev){ data-preview }, [Partially Mitigated Vulnerability](../../../definitions/#partially-mitigated-vulnerability){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
### Historical Activity

??? abstract "VER-TFR-MRH"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.



!!! schema "Related JSON Schema: [FedRAMP Historical VDR Activity Schema](https://fedramp.gov/schemas/fedramp-historical-VER-activity-schema-v2026.06.06.01.json)"

    _Note: This is a placeholder, the URL will not work yet._


!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY make all recent historical vulnerability detection and response activity available in JSON format for automated retrieval by all necessary parties (e.g. using an API service or similar); this information MAY be updated persistently, at least once every month.

        **Timeframe:** 1 month


    ---
    **Terms:** [All Necessary Parties](../../../definitions/#all-necessary-parties){ data-preview }, [Persistently](../../../definitions/#persistently){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }, [Vulnerability Detection](../../../definitions/#vulnerability-detection){ data-preview }, [Vulnerability Response](../../../definitions/#vulnerability-response){ data-preview }
### Non-Internet-Reachable Incidents

??? abstract "VER-TFR-NRI"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    === "Class A"
        Providers with Class A Certifications MAY treat likely exploitable vulnerabilities that are NOT internet-reachable where Potential Agency Impact N-rating = 5 as a FedRAMP Reportable Incident until they are partially mitigated vulnerabilities at N4 or below.


    ---
    **Terms:** [FedRAMP Reportable Incident](../../../definitions/#fedramp-reportable-incident){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }, [Likely](../../../definitions/#likely){ data-preview }, [Likely Exploitable Vulnerability (LEV)](../../../definitions/#likely-exploitable-vulnerability-lev){ data-preview }, [Partially Mitigated Vulnerability](../../../definitions/#partially-mitigated-vulnerability){ data-preview }, [Potential Agency Impact](../../../definitions/#potential-agency-impact){ data-preview }, [Vulnerability](../../../definitions/#vulnerability){ data-preview }
