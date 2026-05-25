---
tags:
  - 20x
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# FedRAMP Security Inbox

The FedRAMP Security Inbox rules ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.



---


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with any type of FedRAMP Certification.

### Maintain a FedRAMP Security Inbox

??? abstract "FSI-CSO-INB"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST establish and maintain an email address to receive messages from FedRAMP; this inbox is a FedRAMP Security Inbox (FSI).

    ---

    !!! danger "Be careful using a personal email tied to an individual for this inbox due to the significant risk to future communications after a change in personnel!"

    ---

    _**Notes:**_

    - _Unless otherwise notified, FedRAMP will use the listed Security Email on the Marketplace for these notifications._
    - _If a provider establishes a new inbox in reaction to this guidance that is different from the Security Email then they must follow the [FSI-CSO-NOC (Notification of Changes)](#notification-of-changes){ data-preview } rules to notify FedRAMP._
    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Notification of Changes

??? abstract "FSI-CSO-NOC"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by email using info@fedramp.gov.

!!! quote ""
    Providers MUST immediately notify FedRAMP of any changes in addressing for their FedRAMP Security Inbox by emailing info@fedramp.gov with the name and FedRAMP ID of the cloud service offering and the updated email address.


    ---
    **Terms:** [Cloud Service Offering](../../../definitions/#cloud-service-offering){ data-preview }, [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Trust @fedramp.gov and @gsa.gov

??? abstract "FSI-CSO-TFG"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST treat any email originating from an @fedramp.gov or @gsa.gov email address as if it was sent from FedRAMP by default; if such a message is confirmed to originate from someone other than FedRAMP then the FedRAMP Security Inbox rules no longer apply.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Receive Email Without Disruption

??? abstract "FSI-CSO-RCV"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST receive and react to email messages from FedRAMP without disruption and without requiring additional actions from FedRAMP.


    ---

    _**Note:** This requirement is intended to prevent cloud service providers from requiring FedRAMP to complete a CAPTCHA, log into a customer portal, or otherwise take service-specific actions that might prevent the security team from receiving the message._

### Complete Required Actions

??? abstract "FSI-CSO-CRA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST complete the required actions in Emergency or Emergency Test designated messages sent by FedRAMP within the timeframe included in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

### Emergency Message Routing

??? abstract "FSI-CSO-EMR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers MUST route Emergency designated messages sent by FedRAMP to a senior security official for their awareness.


    ---

    _**Note:** Senior security officials are determined by the provider._

### Important Message Actions

??? abstract "FSI-CSO-IMA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD complete the required actions in Important designated messages sent by FedRAMP within the timeframe specified in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

### Acknowledge Receipt

??? abstract "FSI-CSO-ACK"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    Providers SHOULD promptly and automatically acknowledge the receipt of messages received from FedRAMP in their FedRAMP Security Inbox.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
