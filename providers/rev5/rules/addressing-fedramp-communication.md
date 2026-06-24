---
tags:
  - Rev5
  - Cloud Service Providers
  - Rules
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Addressing FedRAMP Communication

The Addressing FedRAMP Communication rules (formerly FedRAMP Security Inbox) ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Obtain:** 2026-01-05
    - **Maintain:** 2026-01-05
    - **Grace Ends:** 2026-07-01



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with any type of FedRAMP Certification.

<div class="subset-applicability" role="group" aria-label="Applicability">
<span class="subset-applicability__group subset-applicability__group--types"><span class="subset-applicability__label">Type:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Rev5</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--paths"><span class="subset-applicability__label">Path:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Program</span><span class="subset-applicability__tag">Agency</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">Class:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span><br>
<span class="subset-applicability__group subset-applicability__group--affects"><span class="subset-applicability__label">Audience:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Providers</span></span></span>
</div>

### Maintain a FedRAMP Security Inbox

??? abstract "AFC-CSO-INB"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST establish and maintain an email address to receive messages from FedRAMP; this inbox is a FedRAMP Security Inbox (FSI).

    ---

    !!! danger "Be careful using a personal email tied to an individual for this inbox due to the significant risk to future communications after a change in personnel!"

    ---

    _**Notes:**_

    - _Unless otherwise notified, FedRAMP will use the listed Security Email on the Marketplace for these notifications._
    - _If a provider establishes a new inbox in reaction to this guidance that is different from the Security Email then they must follow the [AFC-CSO-NOC (Notification of Changes)](#notification-of-changes){ data-preview } rules to notify FedRAMP._
    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Notification of Changes

??? abstract "AFC-CSO-NOC"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP via form: [\[CSP\] Notification of Changes](https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51829466938011).


!!! quote ""
    Providers MUST immediately notify FedRAMP of any changes to the email address for their FedRAMP Security Inbox.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Trust @fedramp.gov and @gsa.gov

??? abstract "AFC-CSO-TFG"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST treat any email originating from an @fedramp.gov or @gsa.gov email address as if it was sent from FedRAMP by default; if such a message is confirmed to originate from someone other than FedRAMP then the FedRAMP Security Inbox rules no longer apply.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Receive Email Without Disruption

??? abstract "AFC-CSO-RCV"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST receive and react to email messages from FedRAMP without disruption and without requiring additional actions from FedRAMP.


    ---

    _**Note:** This requirement is intended to prevent cloud service providers from requiring FedRAMP to complete a CAPTCHA, log into a customer portal, or otherwise take service-specific actions that might prevent the security team from receiving the message._

### Complete Required Actions

??? abstract "AFC-CSO-CRA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST complete the required actions in Emergency or Emergency Test designated messages sent by FedRAMP within the timeframe included in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }
### Emergency Message Routing

??? abstract "AFC-CSO-EMR"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST route Emergency designated messages sent by FedRAMP to a senior security official for their awareness.


    ---

    _**Note:** Senior security officials are determined by the provider._

### Important Message Actions

??? abstract "AFC-CSO-IMA"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD complete the required actions in Important designated messages sent by FedRAMP within the timeframe specified in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }
### Acknowledge Receipt

??? abstract "AFC-CSO-ACK"
    **Changelog:**


    - **2026-06-24:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD promptly and automatically acknowledge the receipt of messages received from FedRAMP in their FedRAMP Security Inbox.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
