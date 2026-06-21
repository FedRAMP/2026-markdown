---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# System and Communications Protection (SC)

This page contains all **139** controls and control enhancements in the System and Communications Protection (SC) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## SC-01 (Policy and Procedures) { #sc-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business-process-level; system-level] system and communications protection policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the system and communications protection policy and the associated system and communications protection controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the system and communications protection policy and procedures; and
    - **c.** Review and update the current system and communications protection:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-1)

---

## SC-02 (Separation of System and User Functionality) { #sc-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Separate user functionality, including user interface services, from system management functionality.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-2)

---

## SC-02 (01) (Interfaces for Non-privileged Users) { #sc-02-01 }

!!! quote ""
    Prevent the presentation of system management functionality at interfaces to non-privileged users.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-2-1)

---

## SC-02 (02) (Disassociability) { #sc-02-02 }

!!! quote ""
    Store state information from applications and software separately.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-2-2)

---

## SC-03 (Security Function Isolation) { #sc-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Isolate security functions from nonsecurity functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3)

---

## SC-03 (01) (Hardware Separation) { #sc-03-01 }

!!! quote ""
    Employ hardware separation mechanisms to implement security function isolation.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3-1)

---

## SC-03 (02) (Access and Flow Control Functions) { #sc-03-02 }

!!! quote ""
    Isolate security functions enforcing access and information flow control from nonsecurity functions and from other security functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3-2)

---

## SC-03 (03) (Minimize Nonsecurity Functionality) { #sc-03-03 }

!!! quote ""
    Minimize the number of nonsecurity functions included within the isolation boundary containing security functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3-3)

---

## SC-03 (04) (Module Coupling and Cohesiveness) { #sc-03-04 }

!!! quote ""
    Implement security functions as largely independent modules that maximize internal cohesiveness within modules and minimize coupling between modules.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3-4)

---

## SC-03 (05) (Layered Structures) { #sc-03-05 }

!!! quote ""
    Implement security functions as a layered structure minimizing interactions between layers of the design and avoiding any dependence by lower layers on the functionality or correctness of higher layers.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-3-5)

---

## SC-04 (Information in Shared System Resources) { #sc-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent unauthorized and unintended information transfer via shared system resources.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-4)

---

## SC-04 (02) (Multilevel or Periods Processing) { #sc-04-02 }

!!! quote ""
    Prevent unauthorized information transfer via shared resources in accordance with [Assignment: organization-defined procedures] when system processing explicitly switches between different information classification levels or security categories.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-4-2)

---

## SC-05 (Denial-of-service Protection) { #sc-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** [Selection: one of: protect against; limit] the effects of the following types of denial-of-service events: [Assignment: organization-defined types of denial-of-service events]; and
    - **b.** Employ the following controls to achieve the denial-of-service objective: [Assignment: organization-defined controls by type of denial-of-service event].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-5)

---

## SC-05 (01) (Restrict Ability to Attack Other Systems) { #sc-05-01 }

!!! quote ""
    Restrict the ability of individuals to launch the following denial-of-service attacks against other systems: [Assignment: organization-defined denial-of-service attacks].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-5-1)

---

## SC-05 (02) (Capacity, Bandwidth, and Redundancy) { #sc-05-02 }

!!! quote ""
    Manage capacity, bandwidth, or other redundancy to limit the effects of information flooding denial-of-service attacks.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-5-2)

---

## SC-05 (03) (Detection and Monitoring) { #sc-05-03 }

!!! quote ""
    - **(a)** Employ the following monitoring tools to detect indicators of denial-of-service attacks against, or launched from, the system: [Assignment: organization-defined monitoring tools]; and
    - **(b)** Monitor the following system resources to determine if sufficient resources exist to prevent effective denial-of-service attacks: [Assignment: organization-defined system resources].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-5-3)

---

## SC-06 (Resource Availability) { #sc-06 }

!!! quote ""
    Protect the availability of resources by allocating [Assignment: organization-defined resources] by [Selection: one or more of: priority; quota].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-6)

---

## SC-07 (Boundary Protection) { #sc-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Monitor and control communications at the external managed interfaces to the system and at key internal managed interfaces within the system;
    - **b.** Implement subnetworks for publicly accessible system components that are [Selection: one of: physically; logically] separated from internal organizational networks; and
    - **c.** Connect to external networks or systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security and privacy architecture.

    ---

    !!! info ""
        **FedRAMP Guidance**

        SC-7 (b) may be met by using any technical capability or complement of capabilities that ensures logical separation between publicly accessible components and internal networks by preventing traversal without inspection and authorization; traffic may not flow unrestricted from publicly accessible components to internal networks.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7)

---

## SC-07 (03) (Access Points) { #sc-07-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Limit the number of external network connections to the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-3)

---

## SC-07 (04) (External Telecommunications Services) { #sc-07-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Implement a managed interface for each external telecommunication service;
    - **(b)** Establish a traffic flow policy for each managed interface;
    - **(c)** Protect the confidentiality and integrity of the information being transmitted across each interface;
    - **(d)** Document each exception to the traffic flow policy with a supporting mission or business need and duration of that need;
    - **(e)** Review exceptions to the traffic flow policy [Assignment: organization-defined frequency] and remove exceptions that are no longer supported by an explicit mission or business need;
    - **(f)** Prevent unauthorized exchange of control plane traffic with external networks;
    - **(g)** Publish information to enable remote networks to detect unauthorized control plane traffic from internal networks; and
    - **(h)** Filter unauthorized control plane traffic from external networks.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-4)

---

## SC-07 (05) (Deny by Default — Allow by Exception) { #sc-07-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Deny network communications traffic by default and allow network communications traffic by exception [Selection: one or more of: at managed interfaces; for].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-5)

---

## SC-07 (07) (Split Tunneling for Remote Devices) { #sc-07-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent split tunneling for remote devices connecting to organizational systems unless the split tunnel is securely provisioned using [Assignment: organization-defined safeguards].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-7)

---

## SC-07 (08) (Route Traffic to Authenticated Proxy Servers) { #sc-07-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Route [Assignment: organization-defined internal communications traffic] to [Assignment: organization-defined external networks] through authenticated proxy servers at managed interfaces.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-8)

---

## SC-07 (09) (Restrict Threatening Outgoing Communications Traffic) { #sc-07-09 }

!!! quote ""
    - **(a)** Detect and deny outgoing communications traffic posing a threat to external systems; and
    - **(b)** Audit the identity of internal users associated with denied communications.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-9)

---

## SC-07 (10) (Prevent Exfiltration) { #sc-07-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Prevent the exfiltration of information; and
    - **(b)** Conduct exfiltration tests [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-10)

---

## SC-07 (11) (Restrict Incoming Communications Traffic) { #sc-07-11 }

!!! quote ""
    Only allow incoming communications from [Assignment: organization-defined authorized sources] to be routed to [Assignment: organization-defined authorized destinations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-11)

---

## SC-07 (12) (Host-based Protection) { #sc-07-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement [Assignment: organization-defined host-based boundary protection mechanisms] at [Assignment: organization-defined system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-12)

---

## SC-07 (13) (Isolation of Security Tools, Mechanisms, and Support Components) { #sc-07-13 }

!!! quote ""
    Isolate [Assignment: organization-defined information security tools, mechanisms, and support components] from other internal system components by implementing physically separate subnetworks with managed interfaces to other components of the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-13)

---

## SC-07 (14) (Protect Against Unauthorized Physical Connections) { #sc-07-14 }

!!! quote ""
    Protect against unauthorized physical connections at [Assignment: organization-defined managed interfaces].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-14)

---

## SC-07 (15) (Networked Privileged Accesses) { #sc-07-15 }

!!! quote ""
    Route networked, privileged accesses through a dedicated, managed interface for purposes of access control and auditing.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-15)

---

## SC-07 (16) (Prevent Discovery of System Components) { #sc-07-16 }

!!! quote ""
    Prevent the discovery of specific system components that represent a managed interface.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-16)

---

## SC-07 (17) (Automated Enforcement of Protocol Formats) { #sc-07-17 }

!!! quote ""
    Enforce adherence to protocol formats.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-17)

---

## SC-07 (18) (Fail Secure) { #sc-07-18 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent systems from entering unsecure states in the event of an operational failure of a boundary protection device.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-18)

---

## SC-07 (19) (Block Communication from Non-organizationally Configured Hosts) { #sc-07-19 }

!!! quote ""
    Block inbound and outbound communications traffic between [Assignment: organization-defined communication clients] that are independently configured by end users and external service providers.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-19)

---

## SC-07 (20) (Dynamic Isolation and Segregation) { #sc-07-20 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide the capability to dynamically isolate [Assignment: organization-defined system components] from other system components.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-20)

---

## SC-07 (21) (Isolation of System Components) { #sc-07-21 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ boundary protection mechanisms to isolate [Assignment: organization-defined system components] supporting [Assignment: organization-defined missions and/or business functions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-21)

---

## SC-07 (22) (Separate Subnets for Connecting to Different Security Domains) { #sc-07-22 }

!!! quote ""
    Implement separate network addresses to connect to systems in different security domains.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-22)

---

## SC-07 (23) (Disable Sender Feedback on Protocol Validation Failure) { #sc-07-23 }

!!! quote ""
    Disable feedback to senders on protocol format validation failure.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-23)

---

## SC-07 (24) (Personally Identifiable Information) { #sc-07-24 }

!!! quote ""
    For systems that process personally identifiable information:
    
    - **(a)** Apply the following processing rules to data elements of personally identifiable information: [Assignment: organization-defined processing rules];
    - **(b)** Monitor for permitted processing at the external interfaces to the system and at key internal boundaries within the system;
    - **(c)** Document each processing exception; and
    - **(d)** Review and remove exceptions that are no longer supported.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-24)

---

## SC-07 (25) (Unclassified National Security System Connections) { #sc-07-25 }

!!! quote ""
    Prohibit the direct connection of [Assignment: organization-defined unclassified national security system] to an external network without the use of [Assignment: organization-defined boundary protection device].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-25)

---

## SC-07 (26) (Classified National Security System Connections) { #sc-07-26 }

!!! quote ""
    Prohibit the direct connection of a classified national security system to an external network without the use of [Assignment: organization-defined boundary protection device].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-26)

---

## SC-07 (27) (Unclassified Non-national Security System Connections) { #sc-07-27 }

!!! quote ""
    Prohibit the direct connection of [Assignment: organization-defined unclassified, non-national security system] to an external network without the use of [Assignment: organization-defined boundary protection device].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-27)

---

## SC-07 (28) (Connections to Public Networks) { #sc-07-28 }

!!! quote ""
    Prohibit the direct connection of [Assignment: organization-defined system] to a public network.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-28)

---

## SC-07 (29) (Separate Subnets to Isolate Functions) { #sc-07-29 }

!!! quote ""
    Implement [Selection: one of: physically; logically] separate subnetworks to isolate the following critical system components and functions: [Assignment: organization-defined critical system components and functions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-7-29)

---

## SC-08 (Transmission Confidentiality and Integrity) { #sc-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Protect the [Selection: one or more of: confidentiality; integrity] of transmitted information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8)

---

## SC-08 (01) (Cryptographic Protection) { #sc-08-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to [Selection: one or more of: prevent unauthorized disclosure of information; detect changes to information] during transmission.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8-1)

---

## SC-08 (02) (Pre- and Post-transmission Handling) { #sc-08-02 }

!!! quote ""
    Maintain the [Selection: one or more of: confidentiality; integrity] of information during preparation for transmission and during reception.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8-2)

---

## SC-08 (03) (Cryptographic Protection for Message Externals) { #sc-08-03 }

!!! quote ""
    Implement cryptographic mechanisms to protect message externals unless otherwise protected by [Assignment: organization-defined alternative physical controls].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8-3)

---

## SC-08 (04) (Conceal or Randomize Communications) { #sc-08-04 }

!!! quote ""
    Implement cryptographic mechanisms to conceal or randomize communication patterns unless otherwise protected by [Assignment: organization-defined alternative physical controls].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8-4)

---

## SC-08 (05) (Protected Distribution System) { #sc-08-05 }

!!! quote ""
    Implement [Assignment: organization-defined protected distribution system] to [Selection: one or more of: prevent unauthorized disclosure of information; detect changes to information] during transmission.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-8-5)

---

## SC-10 (Network Disconnect) { #sc-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Terminate the network connection associated with a communications session at the end of the session or after [Assignment: organization-defined time period] of inactivity.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-10)

---

## SC-11 (Trusted Path) { #sc-11 }

!!! quote ""
    - **a.** Provide a [Selection: one of: physically; logically] isolated trusted communications path for communications between the user and the trusted components of the system; and
    - **b.** Permit users to invoke the trusted communications path for communications between the user and the following security functions of the system, including at a minimum, authentication and re-authentication: [Assignment: organization-defined security functions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-11)

---

## SC-11 (01) (Irrefutable Communications Path) { #sc-11-01 }

!!! quote ""
    - **(a)** Provide a trusted communications path that is irrefutably distinguishable from other communications paths; and
    - **(b)** Initiate the trusted communications path for communications between the [Assignment: organization-defined security functions] of the system and the user.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-11-1)

---

## SC-12 (Cryptographic Key Establishment and Management) { #sc-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Establish and manage cryptographic keys when cryptography is employed within the system in accordance with the following key management requirements: [Assignment: organization-defined requirements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-12)

---

## SC-12 (01) (Availability) { #sc-12-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Maintain availability of information in the event of the loss of cryptographic keys by users.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-12-1)

---

## SC-12 (02) (Symmetric Keys) { #sc-12-02 }

!!! quote ""
    Produce, control, and distribute symmetric cryptographic keys using [Selection: one of: NIST FIPS-validated; NSA-approved] key management technology and processes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-12-2)

---

## SC-12 (03) (Asymmetric Keys) { #sc-12-03 }

!!! quote ""
    Produce, control, and distribute asymmetric cryptographic keys using [Selection: one of: NSA-approved key management technology and processes; prepositioned keying material; DoD-approved or DoD-issued Medium Assurance PKI certificates; DoD-approved or DoD-issued Medium Hardware Assurance PKI certificates and hardware security tokens that protect the user’s private key; certificates issued in accordance with organization-defined requirements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-12-3)

---

## SC-12 (06) (Physical Control of Keys) { #sc-12-06 }

!!! quote ""
    Maintain physical control of cryptographic keys when stored information is encrypted by external service providers.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-12-6)

---

## SC-13 (Cryptographic Protection) { #sc-13 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Determine the [Assignment: organization-defined cryptographic uses]; and
    - **b.** Implement the following types of cryptography required for each specified cryptographic use: [Assignment: organization-defined types of cryptography].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Cryptographic Module Use rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-13)

---

## SC-15 (Collaborative Computing Devices and Applications) { #sc-15 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Prohibit remote activation of collaborative computing devices and applications with the following exceptions: [Assignment: organization-defined exceptions where remote activation is to be allowed]; and
    - **b.** Provide an explicit indication of use to users physically present at the devices.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-15)

---

## SC-15 (01) (Physical or Logical Disconnect) { #sc-15-01 }

!!! quote ""
    Provide [Selection: one or more of: physical; logical] disconnect of collaborative computing devices in a manner that supports ease of use.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-15-1)

---

## SC-15 (03) (Disabling and Removal in Secure Work Areas) { #sc-15-03 }

!!! quote ""
    Disable or remove collaborative computing devices and applications from [Assignment: organization-defined systems or system components] in [Assignment: organization-defined secure work areas].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-15-3)

---

## SC-15 (04) (Explicitly Indicate Current Participants) { #sc-15-04 }

!!! quote ""
    Provide an explicit indication of current participants in [Assignment: organization-defined online meetings and teleconferences].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-15-4)

---

## SC-16 (Transmission of Security and Privacy Attributes) { #sc-16 }

!!! quote ""
    Associate [Assignment: organization-defined security and privacy attributes] with information exchanged between systems and between system components.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-16)

---

## SC-16 (01) (Integrity Verification) { #sc-16-01 }

!!! quote ""
    Verify the integrity of transmitted security and privacy attributes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-16-1)

---

## SC-16 (02) (Anti-spoofing Mechanisms) { #sc-16-02 }

!!! quote ""
    Implement anti-spoofing mechanisms to prevent adversaries from falsifying the security attributes indicating the successful application of the security process.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-16-2)

---

## SC-16 (03) (Cryptographic Binding) { #sc-16-03 }

!!! quote ""
    Implement [Assignment: organization-defined mechanisms or techniques] to bind security and privacy attributes to transmitted information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-16-3)

---

## SC-17 (Public Key Infrastructure Certificates) { #sc-17 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Issue public key certificates under an [Assignment: organization-defined certificate policy] or obtain public key certificates from an approved service provider; and
    - **b.** Include only approved trust anchors in trust stores or certificate stores managed by the organization.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-17)

---

## SC-18 (Mobile Code) { #sc-18 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Define acceptable and unacceptable mobile code and mobile code technologies; and
    - **b.** Authorize, monitor, and control the use of mobile code within the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18)

---

## SC-18 (01) (Identify Unacceptable Code and Take Corrective Actions) { #sc-18-01 }

!!! quote ""
    Identify [Assignment: organization-defined unacceptable mobile code] and take [Assignment: organization-defined corrective actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18-1)

---

## SC-18 (02) (Acquisition, Development, and Use) { #sc-18-02 }

!!! quote ""
    Verify that the acquisition, development, and use of mobile code to be deployed in the system meets [Assignment: organization-defined mobile code requirements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18-2)

---

## SC-18 (03) (Prevent Downloading and Execution) { #sc-18-03 }

!!! quote ""
    Prevent the download and execution of [Assignment: organization-defined unacceptable mobile code].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18-3)

---

## SC-18 (04) (Prevent Automatic Execution) { #sc-18-04 }

!!! quote ""
    Prevent the automatic execution of mobile code in [Assignment: organization-defined software applications] and enforce [Assignment: organization-defined actions] prior to executing the code.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18-4)

---

## SC-18 (05) (Allow Execution Only in Confined Environments) { #sc-18-05 }

!!! quote ""
    Allow execution of permitted mobile code only in confined virtual machine environments.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-18-5)

---

## SC-20 (Secure Name/Address Resolution Service (Authoritative Source)) { #sc-20 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Provide additional data origin authentication and integrity verification artifacts along with the authoritative name resolution data the system returns in response to external name/address resolution queries; and
    - **b.** Provide the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-20)

---

## SC-20 (02) (Data Origin and Integrity) { #sc-20-02 }

!!! quote ""
    Provide data origin and integrity protection artifacts for internal name/address resolution queries.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-20-2)

---

## SC-21 (Secure Name/Address Resolution Service (Recursive or Caching Resolver)) { #sc-21 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Request and perform data origin authentication and data integrity verification on the name/address resolution responses the system receives from authoritative sources.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-21)

---

## SC-22 (Architecture and Provisioning for Name/Address Resolution Service) { #sc-22 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Ensure the systems that collectively provide name/address resolution service for an organization are fault-tolerant and implement internal and external role separation.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-22)

---

## SC-23 (Session Authenticity) { #sc-23 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Protect the authenticity of communications sessions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-23)

---

## SC-23 (01) (Invalidate Session Identifiers at Logout) { #sc-23-01 }

!!! quote ""
    Invalidate session identifiers upon user logout or other session termination.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-23-1)

---

## SC-23 (03) (Unique System-generated Session Identifiers) { #sc-23-03 }

!!! quote ""
    Generate a unique session identifier for each session with [Assignment: organization-defined randomness requirements] and recognize only session identifiers that are system-generated.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-23-3)

---

## SC-23 (05) (Allowed Certificate Authorities) { #sc-23-05 }

!!! quote ""
    Only allow the use of [Assignment: organization-defined certificated authorities] for verification of the establishment of protected sessions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-23-5)

---

## SC-24 (Fail in Known State) { #sc-24 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Fail to a [Assignment: organization-defined known system state] for the following failures on the indicated components while preserving [Assignment: organization-defined system state information] in failure: [Assignment: organization-defined types of system failures on system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-24)

---

## SC-25 (Thin Nodes) { #sc-25 }

!!! quote ""
    Employ minimal functionality and information storage on the following system components: [Assignment: organization-defined system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-25)

---

## SC-26 (Decoys) { #sc-26 }

!!! quote ""
    Include components within organizational systems specifically designed to be the target of malicious attacks for detecting, deflecting, and analyzing such attacks.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-26)

---

## SC-27 (Platform-independent Applications) { #sc-27 }

!!! quote ""
    Include within organizational systems the following platform independent applications: [Assignment: organization-defined platform-independent applications].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-27)

---

## SC-28 (Protection of Information at Rest) { #sc-28 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Protect the [Selection: one or more of: confidentiality; integrity] of the following information at rest: [Assignment: organization-defined information at rest].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-28)

---

## SC-28 (01) (Cryptographic Protection) { #sc-28-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of the following information at rest on [Assignment: organization-defined system components or media]: [Assignment: organization-defined information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-28-1)

---

## SC-28 (02) (Offline Storage) { #sc-28-02 }

!!! quote ""
    Remove the following information from online storage and store offline in a secure location: [Assignment: organization-defined information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-28-2)

---

## SC-28 (03) (Cryptographic Keys) { #sc-28-03 }

!!! quote ""
    Provide protected storage for cryptographic keys [Selection: one of: hardware-protected key store].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-28-3)

---

## SC-29 (Heterogeneity) { #sc-29 }

!!! quote ""
    Employ a diverse set of information technologies for the following system components in the implementation of the system: [Assignment: organization-defined system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-29)

---

## SC-29 (01) (Virtualization Techniques) { #sc-29-01 }

!!! quote ""
    Employ virtualization techniques to support the deployment of a diversity of operating systems and applications that are changed [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-29-1)

---

## SC-30 (Concealment and Misdirection) { #sc-30 }

!!! quote ""
    Employ the following concealment and misdirection techniques for [Assignment: organization-defined systems] at [Assignment: organization-defined time periods] to confuse and mislead adversaries: [Assignment: organization-defined concealment and misdirection techniques].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-30)

---

## SC-30 (02) (Randomness) { #sc-30-02 }

!!! quote ""
    Employ [Assignment: organization-defined techniques] to introduce randomness into organizational operations and assets.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-30-2)

---

## SC-30 (03) (Change Processing and Storage Locations) { #sc-30-03 }

!!! quote ""
    Change the location of [Assignment: organization-defined processing and/or storage] [Selection: one of: random time intervals]].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-30-3)

---

## SC-30 (04) (Misleading Information) { #sc-30-04 }

!!! quote ""
    Employ realistic, but misleading information in [Assignment: organization-defined system components] about its security state or posture.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-30-4)

---

## SC-30 (05) (Concealment of System Components) { #sc-30-05 }

!!! quote ""
    Employ the following techniques to hide or conceal [Assignment: organization-defined system components]: [Assignment: organization-defined techniques].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-30-5)

---

## SC-31 (Covert Channel Analysis) { #sc-31 }

!!! quote ""
    - **a.** Perform a covert channel analysis to identify those aspects of communications within the system that are potential avenues for covert [Selection: one or more of: storage; timing] channels; and
    - **b.** Estimate the maximum bandwidth of those channels.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-31)

---

## SC-31 (01) (Test Covert Channels for Exploitability) { #sc-31-01 }

!!! quote ""
    Test a subset of the identified covert channels to determine the channels that are exploitable.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-31-1)

---

## SC-31 (02) (Maximum Bandwidth) { #sc-31-02 }

!!! quote ""
    Reduce the maximum bandwidth for identified covert [Selection: one or more of: storage; timing] channels to [Assignment: organization-defined values].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-31-2)

---

## SC-31 (03) (Measure Bandwidth in Operational Environments) { #sc-31-03 }

!!! quote ""
    Measure the bandwidth of [Assignment: organization-defined subset of identified covert channels] in the operational environment of the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-31-3)

---

## SC-32 (System Partitioning) { #sc-32 }

!!! quote ""
    Partition the system into [Assignment: organization-defined system components] residing in separate [Selection: one of: physical; logical] domains or environments based on [Assignment: organization-defined circumstances for the physical or logical separation of components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-32)

---

## SC-32 (01) (Separate Physical Domains for Privileged Functions) { #sc-32-01 }

!!! quote ""
    Partition privileged functions into separate physical domains.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-32-1)

---

## SC-34 (Non-modifiable Executable Programs) { #sc-34 }

!!! quote ""
    For [Assignment: organization-defined system components], load and execute:
    
    - **a.** The operating environment from hardware-enforced, read-only media; and
    - **b.** The following applications from hardware-enforced, read-only media: [Assignment: organization-defined applications].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-34)

---

## SC-34 (01) (No Writable Storage) { #sc-34-01 }

!!! quote ""
    Employ [Assignment: organization-defined system components] with no writeable storage that is persistent across component restart or power on/off.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-34-1)

---

## SC-34 (02) (Integrity Protection on Read-only Media) { #sc-34-02 }

!!! quote ""
    Protect the integrity of information prior to storage on read-only media and control the media after such information has been recorded onto the media.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-34-2)

---

## SC-35 (External Malicious Code Identification) { #sc-35 }

!!! quote ""
    Include system components that proactively seek to identify network-based malicious code or malicious websites.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-35)

---

## SC-36 (Distributed Processing and Storage) { #sc-36 }

!!! quote ""
    Distribute the following processing and storage components across multiple [Selection: one of: physical locations; logical domains]: [Assignment: organization-defined processing and storage components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-36)

---

## SC-36 (01) (Polling Techniques) { #sc-36-01 }

!!! quote ""
    - **(a)** Employ polling techniques to identify potential faults, errors, or compromises to the following processing and storage components: [Assignment: organization-defined distributed processing and storage components]; and
    - **(b)** Take the following actions in response to identified faults, errors, or compromises: [Assignment: organization-defined actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-36-1)

---

## SC-36 (02) (Synchronization) { #sc-36-02 }

!!! quote ""
    Synchronize the following duplicate systems or system components: [Assignment: organization-defined duplicate systems or system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-36-2)

---

## SC-37 (Out-of-band Channels) { #sc-37 }

!!! quote ""
    Employ the following out-of-band channels for the physical delivery or electronic transmission of [Assignment: organization-defined information, system components, or devices] to [Assignment: organization-defined individuals or systems]: [Assignment: organization-defined out-of-band channels].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-37)

---

## SC-37 (01) (Ensure Delivery and Transmission) { #sc-37-01 }

!!! quote ""
    Employ [Assignment: organization-defined controls] to ensure that only [Assignment: organization-defined individuals or systems] receive the following information, system components, or devices: [Assignment: organization-defined information, system components, or devices].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-37-1)

---

## SC-38 (Operations Security) { #sc-38 }

!!! quote ""
    Employ the following operations security controls to protect key organizational information throughout the system development life cycle: [Assignment: organization-defined operations security controls].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-38)

---

## SC-39 (Process Isolation) { #sc-39 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Maintain a separate execution domain for each executing system process.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-39)

---

## SC-39 (01) (Hardware Separation) { #sc-39-01 }

!!! quote ""
    Implement hardware separation mechanisms to facilitate process isolation.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-39-1)

---

## SC-39 (02) (Separate Execution Domain Per Thread) { #sc-39-02 }

!!! quote ""
    Maintain a separate execution domain for each thread in [Assignment: organization-defined multi-threaded processing].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-39-2)

---

## SC-40 (Wireless Link Protection) { #sc-40 }

!!! quote ""
    Protect external and internal [Assignment: organization-defined wireless links] from the following signal parameter attacks: [Assignment: organization-defined types of signal parameter attacks or references to sources for such attacks].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-40)

---

## SC-40 (01) (Electromagnetic Interference) { #sc-40-01 }

!!! quote ""
    Implement cryptographic mechanisms that achieve [Assignment: organization-defined level of protection] against the effects of intentional electromagnetic interference.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-40-1)

---

## SC-40 (02) (Reduce Detection Potential) { #sc-40-02 }

!!! quote ""
    Implement cryptographic mechanisms to reduce the detection potential of wireless links to [Assignment: organization-defined level of reduction].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-40-2)

---

## SC-40 (03) (Imitative or Manipulative Communications Deception) { #sc-40-03 }

!!! quote ""
    Implement cryptographic mechanisms to identify and reject wireless transmissions that are deliberate attempts to achieve imitative or manipulative communications deception based on signal parameters.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-40-3)

---

## SC-40 (04) (Signal Parameter Identification) { #sc-40-04 }

!!! quote ""
    Implement cryptographic mechanisms to prevent the identification of [Assignment: organization-defined wireless transmitters] by using the transmitter signal parameters.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-40-4)

---

## SC-41 (Port and I/O Device Access) { #sc-41 }

!!! quote ""
    [Selection: one of: physically; logically] disable or remove [Assignment: organization-defined connection ports or input/output devices] on the following systems or system components: [Assignment: organization-defined systems or system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-41)

---

## SC-42 (Sensor Capability and Data) { #sc-42 }

!!! quote ""
    - **a.** Prohibit [Selection: one or more of: the use of devices possessing in; the remote activation of environmental sensing capabilities on organizational systems or system components with the following exceptions:]; and
    - **b.** Provide an explicit indication of sensor use to [Assignment: organization-defined group of users].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-42)

---

## SC-42 (01) (Reporting to Authorized Individuals or Roles) { #sc-42-01 }

!!! quote ""
    Verify that the system is configured so that data or information collected by the [Assignment: organization-defined sensors] is only reported to authorized individuals or roles.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-42-1)

---

## SC-42 (02) (Authorized Use) { #sc-42-02 }

!!! quote ""
    Employ the following measures so that data or information collected by [Assignment: organization-defined sensors] is only used for authorized purposes: [Assignment: organization-defined measures].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-42-2)

---

## SC-42 (04) (Notice of Collection) { #sc-42-04 }

!!! quote ""
    Employ the following measures to facilitate an individual’s awareness that personally identifiable information is being collected by [Assignment: organization-defined sensors]: [Assignment: organization-defined measures].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-42-4)

---

## SC-42 (05) (Collection Minimization) { #sc-42-05 }

!!! quote ""
    Employ [Assignment: organization-defined sensors] that are configured to minimize the collection of information about individuals that is not needed.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-42-5)

---

## SC-43 (Usage Restrictions) { #sc-43 }

!!! quote ""
    - **a.** Establish usage restrictions and implementation guidelines for the following system components: [Assignment: organization-defined components]; and
    - **b.** Authorize, monitor, and control the use of such components within the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-43)

---

## SC-44 (Detonation Chambers) { #sc-44 }

!!! quote ""
    Employ a detonation chamber capability within [Assignment: organization-defined system, system component, or location].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-44)

---

## SC-45 (System Time Synchronization) { #sc-45 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Synchronize system clocks within and between systems and system components.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-45)

---

## SC-45 (01) (Synchronization with Authoritative Time Source) { #sc-45-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Compare the internal system clocks [Assignment: organization-defined frequency] with [Assignment: organization-defined authoritative time source]; and
    - **(b)** Synchronize the internal system clocks to the authoritative time source when the time difference is greater than [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-45-1)

---

## SC-45 (02) (Secondary Authoritative Time Source) { #sc-45-02 }

!!! quote ""
    - **(a)** Identify a secondary authoritative time source that is in a different geographic region than the primary authoritative time source; and
    - **(b)** Synchronize the internal system clocks to the secondary authoritative time source if the primary authoritative time source is unavailable.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-45-2)

---

## SC-46 (Cross Domain Policy Enforcement) { #sc-46 }

!!! quote ""
    Implement a policy enforcement mechanism [Selection: one of: physically; logically] between the physical and/or network interfaces for the connecting security domains.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-46)

---

## SC-47 (Alternate Communications Paths) { #sc-47 }

!!! quote ""
    Establish [Assignment: organization-defined alternate communication paths] for system operations organizational command and control.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-47)

---

## SC-48 (Sensor Relocation) { #sc-48 }

!!! quote ""
    Relocate [Assignment: organization-defined sensors and monitoring capabilities] to [Assignment: organization-defined locations] under the following conditions or circumstances: [Assignment: organization-defined conditions or circumstances].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-48)

---

## SC-48 (01) (Dynamic Relocation of Sensors or Monitoring Capabilities) { #sc-48-01 }

!!! quote ""
    Dynamically relocate [Assignment: organization-defined sensors and monitoring capabilities] to [Assignment: organization-defined locations] under the following conditions or circumstances: [Assignment: organization-defined conditions or circumstances].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-48-1)

---

## SC-49 (Hardware-enforced Separation and Policy Enforcement) { #sc-49 }

!!! quote ""
    Implement hardware-enforced separation and policy enforcement mechanisms between [Assignment: organization-defined security domains].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-49)

---

## SC-50 (Software-enforced Separation and Policy Enforcement) { #sc-50 }

!!! quote ""
    Implement software-enforced separation and policy enforcement mechanisms between [Assignment: organization-defined security domains].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-50)

---

## SC-51 (Hardware-based Protection) { #sc-51 }

!!! quote ""
    - **a.** Employ hardware-based, write-protect for [Assignment: organization-defined system firmware components]; and
    - **b.** Implement specific procedures for [Assignment: organization-defined authorized individuals] to manually disable hardware write-protect for firmware modifications and re-enable the write-protect prior to returning to operational mode.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/sc-51)

---
