---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Addressing FedRAMP Communication

The Addressing FedRAMP Communication rules (formerly FedRAMP Security Inbox) ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.

**Subsets**

- [FedRAMP Responsibilities](#fedramp-responsibilities)
- [General Provider Responsibilities](#general-provider-responsibilities)

!!! info "Effective Date(s) & Overall Applicability for Rev5"
    - **Required** (Consolidated Rules for 2026)
    - **Obtain:** 2026-01-05
    - **Maintain:** 2026-01-05
    - **Grace Ends:** 2026-07-01



---


## FedRAMP Responsibilities {#fedramp-responsibilities}

These rules apply to FedRAMP when communicating with cloud service providers.

### Verified Emails

??? abstract "AFC-FRP-VRE"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST send messages to cloud service providers using an official @fedramp.gov or @gsa.gov email address with properly configured Sender Policy Framework (SPF), DomainKeys Identified Mail (DKIM), and Domain-based Message Authentication Reporting and Conformance (DMARC) email authentication.


    ---

    _**Note:** Anyone at GSA can send email from @fedramp.gov or @gsa.gov - FedRAMP team members will typically have "FedRAMP" or "F20B" in their name but this is not universal or enforceable. The nature of government enterprise IT services makes it difficult for FedRAMP to isolate FedRAMP-specific team members with enforceable identifiers._

### Criticality Designators

??? abstract "AFC-FRP-CDS"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST convey the criticality of the message in the subject line, IF the message requires an elevated reaction, using one of the following designators:

    1. **Emergency:** There is a potential incident or crisis such that FedRAMP requires an extremely urgent reaction; emergency messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Emergency Test:** FedRAMP requires an extremely urgent reaction to confirm the functionality and effectiveness of the FedRAMP Security Inbox; emergency test messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Important:** There is an important issue that FedRAMP requires the cloud service provider to address; important messages will contain reasonable timeframes for reaction and failure to meet these timeframes may result in corrective action.


    ---

    _**Note:** Messages sent by FedRAMP without one of these designators are considered general communications and do not require an elevated reaction; these may be resolved in the normal course of business by the cloud service provider._

    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../../../definitions/#incident){ data-preview }
### Use FedRAMP_Security Email in Emergencies

??? abstract "AFC-FRP-UFS"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST send Emergency and Emergency Test designated messages from fedramp_security@gsa.gov OR fedramp_security@fedramp.gov.


### Public Notice of Emergency Tests

??? abstract "AFC-FRP-PNT"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify Everyone by web using https://www.fedramp.gov/notices.


!!! quote ""
    FedRAMP MUST post a public notice at least 10 business days in advance of sending an Emergency Test message; such notices MUST include explanation of the likely expected actions and timeframes for the Emergency Test message.

    **Timeframe:** 10 business days


    ---

    _**Notes:**_

    - _Public notice may include blog posts, social media posts, announcements during Community Updates, or e-blasts._
    - _As this process matures, additional confirmed options may become available._
    ---
    **Terms:** [Likely](../../../definitions/#likely){ data-preview }
### Required Actions

??? abstract "AFC-FRP-RQA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST clearly specify the required actions in the body of messages that require an elevated reaction.


### Elevated Reaction Timeframes

??? abstract "AFC-FRP-ERT"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST clearly specify the expected timeframe for completing required actions in the body of messages that require an elevated reaction; timeframes for actions will vary depending on the situation but the default timeframes to provide an estimated resolution time for Emergency and Emergency Test designated messages will be as follows:

    1. **Class D:** within 12 hours
    1. **Class C:** by 3:00 p.m. Eastern Time on the 2nd business day
    1. **Class B:** by 3:00 p.m. Eastern Time on the 3rd business day
    1. **Class A:** by 3:00 p.m. Eastern Time on the 5th business day


    ---

    _**Note:** FedRAMP Class D Certified cloud service providers are expected to address Emergency messages (including tests) from FedRAMP with a reaction time appropriate to operating a service where failure to react rapidly might have a severe or debilitating customer effect on the U.S. Government; some Emergency messages may require faster reaction and all such messages should be addressed as quickly as possible._

    ---
    **Terms:** [Debilitating Customer Effect](../../../definitions/#debilitating-customer-effect){ data-preview }, [FedRAMP Certified](../../../definitions/#fedramp-certified){ data-preview }
### Explain Corrective Actions

??? abstract "AFC-FRP-COR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MUST clearly specify the corrective actions that will result from failure to complete the required actions in the body of messages that require an elevated reaction; such actions may vary from negative ratings in the FedRAMP Marketplace to suspension of FedRAMP Certification depending on the severity of the event.


### Reaction Metrics

??? abstract "AFC-FRP-RPM"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    FedRAMP MAY track and publicly share the time required by cloud service providers to take the actions specified in messages that require an elevated reaction.


## General Provider Responsibilities {#general-provider-responsibilities}

These rules apply to providers with any type of FedRAMP Certification.

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
    - _If a provider establishes a new inbox in reaction to this guidance that is different from the Security Email then they must follow the [AFC-CSO-NOC (Notification of Changes)](#notification-of-changes){ data-preview } rules to notify FedRAMP._
    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Notification of Changes

??? abstract "AFC-CSO-NOC"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.


!!! warning "This FRR includes a notification requirement!"
    - Notify FedRAMP by form using https://help.fedramp.gov/hc/en-us/requests/new?ticket_form_id=51829466938011.


!!! quote ""
    Providers MUST immediately notify FedRAMP of any changes to the email address for their FedRAMP Security Inbox.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }
### Trust @fedramp.gov and @gsa.gov

??? abstract "AFC-CSO-TFG"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST treat any email originating from an @fedramp.gov or @gsa.gov email address as if it was sent from FedRAMP by default; if such a message is confirmed to originate from someone other than FedRAMP then the FedRAMP Security Inbox rules no longer apply.


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
### Emergency Message Routing

??? abstract "AFC-CSO-EMR"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers MUST route Emergency designated messages sent by FedRAMP to a senior security official for their awareness.


    ---

    _**Note:** Senior security officials are determined by the provider._

### Important Message Actions

??? abstract "AFC-CSO-IMA"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD complete the required actions in Important designated messages sent by FedRAMP within the timeframe specified in the message.


    ---

    _**Note:** Timeframes may vary by FedRAMP Certification class._

    ---
    **Terms:** [Certification Class](../../../definitions/#certification-class){ data-preview }
### Acknowledge Receipt

??? abstract "AFC-CSO-ACK"
    **Changelog:**


    - **2026-06-23:** Official launch of the FedRAMP Consolidated Rules for 2026.




!!! quote ""
    Providers SHOULD promptly and automatically acknowledge the receipt of messages received from FedRAMP in their FedRAMP Security Inbox.


    ---
    **Terms:** [FedRAMP Security Inbox](../../../definitions/#fedramp-security-inbox){ data-preview }, [Promptly](../../../definitions/#promptly){ data-preview }
