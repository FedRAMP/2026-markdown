---
tags:
  - 20x
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# FedRAMP Security Inbox

The FedRAMP Security Inbox rules ensure FedRAMP can reliably contact the security and compliance staff responsible for every FedRAMP-authorized cloud service offering. These rules also set expectations for urgent communications, response time testing, and routing important messages separately from general support or customer service channels.


---


## FedRAMP Responsibilities {#fedramp-responsibilities}

These rules apply to FedRAMP when communicating with cloud service providers.

### Verified Emails

??? abstract "FSI-FRP-VRE"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST send messages to cloud service providers using an official @fedramp.gov or @gsa.gov email address with properly configured Sender Policy Framework (SPF), DomainKeys Identified Mail (DKIM), and Domain-based Message Authentication Reporting and Conformance (DMARC) email authentication.


    ---

    _**Note:** Anyone at GSA can send email from @fedramp.gov or @gsa.gov - FedRAMP team members will typically have "FedRAMP" or "Q20B" in their name but this is not universal or enforceable. The nature of government enterprise IT services makes it difficult for FedRAMP to isolate FedRAMP-specific team members with enforceable identifiers._

### Criticality Designators

??? abstract "FSI-FRP-CDS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST convey the criticality of the message in the subject line, IF the message requires an elevated reaction, using one of the following designators:

    1. **Emergency:** There is a potential incident or crisis such that FedRAMP requires an extremely urgent reaction; emergency messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Emergency Test:** FedRAMP requires an extremely urgent reaction to confirm the functionality and effectiveness of the FedRAMP Security Inbox; emergency test messages will contain aggressive timeframes for reaction and failure to meet these timeframes will result in corrective action.
    1. **Important:** There is an important issue that FedRAMP requires the cloud service provider to address; important messages will contain reasonable timeframes for reaction and failure to meet these timeframes may result in corrective action.


    ---

    _**Note:** Messages sent by FedRAMP without one of these designators are considered general communications and do not require an elevated reaction; these may be resolved in the normal course of business by the cloud service provider._

    ---
    **Terms:** [FedRAMP Security Inbox](../definitions/#fedramp-security-inbox){ data-preview }, [Incident](../definitions/#incident){ data-preview }
### Use FedRAMP_Security Email in Emergencies

??? abstract "FSI-FRP-UFS"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST send Emergency and Emergency Test designated messages from fedramp_security@gsa.gov OR fedramp_security@fedramp.gov.


### Public Notice of Emergency Tests

??? abstract "FSI-FRP-PNT"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.


!!! warning "This FRR includes a notification requirement!"
    - Notify public by web using fedramp.gov.

!!! quote ""
    FedRAMP MUST post a public notice at least 10 business days in advance of sending an Emergency Test message; such notices MUST include explanation of the likely expected actions and timeframes for the Emergency Test message.

    **Timeframe:** 10 business days


    ---

    _**Notes:**_

    - _Public notice may include blog posts, social media posts, announcements during Community Updates, or e-blasts._
    - _As this process matures, additional confirmed options may become available._
    ---
    **Terms:** [Likely](../definitions/#likely){ data-preview }
### Required Actions

??? abstract "FSI-FRP-RQA"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the required actions in the body of messages that require an elevated reaction.


### Elevated Reaction Timeframes

??? abstract "FSI-FRP-ERT"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the expected timeframe for completing required actions in the body of messages that require an elevated reaction; timeframes for actions will vary depending on the situation but the default timeframes to provide an estimated resolution time for Emergency and Emergency Test designated messages will be as follows:

    1. **Class D:** within 12 hours
    1. **Class C:** by 3:00 p.m. Eastern Time on the 2nd business day
    1. **Class B:** by 3:00 p.m. Eastern Time on the 3rd business day
    1. **Class A:** by 3:00 p.m. Eastern Time on the 5th business day


    ---

    _**Note:** FedRAMP Class D Certified cloud service providers are expected to address Emergency messages (including tests) from FedRAMP with a reaction time appropriate to operating a service where failure to react rapidly might have a severe or catastrophic adverse effect on the U.S. Government; some Emergency messages may require faster reaction and all such messages should be addressed as quickly as possible._

    ---
    **Terms:** [Catastrophic Adverse Effect](../definitions/#catastrophic-adverse-effect){ data-preview }, [FedRAMP Certified](../definitions/#fedramp-certified){ data-preview }
### Explain Corrective Actions

??? abstract "FSI-FRP-COR"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MUST clearly specify the corrective actions that will result from failure to complete the required actions in the body of messages that require an elevated reaction; such actions may vary from negative ratings in the FedRAMP Marketplace to suspension of FedRAMP Certification depending on the severity of the event.


### Reaction Metrics

??? abstract "FSI-FRP-RPM"
    **Changelog:**


    - **2026-05-04:** Initial reset for the Consolidated Rules for 2026 Public Preview.



!!! quote ""
    FedRAMP MAY track and publicly share the time required by cloud service providers to take the actions specified in messages that require an elevated reaction.
