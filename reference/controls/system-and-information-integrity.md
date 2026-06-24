---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# System and Information Integrity (SI)

This page contains all **102** controls and control enhancements in the System and Information Integrity (SI) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## SI-01 (Policy and Procedures) { #si-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] system and information integrity policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the system and information integrity policy and the associated system and information integrity controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the system and information integrity policy and procedures; and
    - **c.** Review and update the current system and information integrity:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-1)

---

## SI-02 (Flaw Remediation) { #si-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Identify, report, and correct system flaws;
    - **b.** Test software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
    - **c.** Install security-relevant software and firmware updates within [Assignment: organization-defined time period] of the release of the updates; and
    - **d.** Incorporate flaw remediation into the organizational configuration management process.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2)

---

## SI-02 (02) (Automated Flaw Remediation Status) { #si-02-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Determine if system components have applicable security-relevant software and firmware updates installed using [Assignment: organization-defined automated mechanisms] [Assignment: organization-defined frequency].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-2)

---

## SI-02 (03) (Time to Remediate Flaws and Benchmarks for Corrective Actions) { #si-02-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Measure the time between flaw identification and flaw remediation; and
    - **(b)** Establish the following benchmarks for taking corrective actions: [Assignment: organization-defined benchmarks].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-3)

---

## SI-02 (04) (Automated Patch Management Tools) { #si-02-04 }

!!! quote ""
    Employ automated patch management tools to facilitate flaw remediation to the following system components: [Assignment: organization-defined components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-4)

---

## SI-02 (05) (Automatic Software and Firmware Updates) { #si-02-05 }

!!! quote ""
    Install [Assignment: organization-defined security-relevant software and firmware updates] automatically to [Assignment: organization-defined system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-5)

---

## SI-02 (06) (Removal of Previous Versions of Software and Firmware) { #si-02-06 }

!!! quote ""
    Remove previous versions of [Assignment: organization-defined software and firmware components] after updated versions have been installed.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-6)

---

## SI-02 (07) (Root Cause Analysis) { #si-02-07 }

!!! quote ""
    - **a.** Conduct root cause analysis to identify underlying causes of issues or failures.
    - **b.** Develop actions to address the root cause of the issue or failure.
    - **c.** Implement the actions and monitor the implementation for effectiveness.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-2-7)

---

## SI-03 (Malicious Code Protection) { #si-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Implement [Selection: one or more of: signature-based; non-signature-based] malicious code protection mechanisms at system entry and exit points to detect and eradicate malicious code;
    - **b.** Automatically update malicious code protection mechanisms as new releases are available in accordance with organizational configuration management policy and procedures;
    - **c.** Configure malicious code protection mechanisms to:
        - **1.** Perform periodic scans of the system [Assignment: organization-defined frequency] and real-time scans of files from external sources at [Selection: one or more of: endpoint; network entry and exit points] as the files are downloaded, opened, or executed in accordance with organizational policy; and
        - **2.** [Selection: one or more of: block malicious code; quarantine malicious code; take]; and send alert to [Assignment: organization-defined personnel or roles] in response to malicious code detection; and
    - **d.** Address the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-3)

---

## SI-03 (04) (Updates Only by Privileged Users) { #si-03-04 }

!!! quote ""
    Update malicious code protection mechanisms only when directed by a privileged user.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-3-4)

---

## SI-03 (06) (Testing and Verification) { #si-03-06 }

!!! quote ""
    - **(a)** Test malicious code protection mechanisms [Assignment: organization-defined frequency] by introducing known benign code into the system; and
    - **(b)** Verify that the detection of the code and the associated incident reporting occur.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-3-6)

---

## SI-03 (08) (Detect Unauthorized Commands) { #si-03-08 }

!!! quote ""
    - **(a)** Detect the following unauthorized operating system commands through the kernel application programming interface on [Assignment: organization-defined system hardware components]: [Assignment: organization-defined unauthorized operating system commands]; and
    - **(b)** [Selection: one or more of: issue a warning; audit the command execution; prevent the execution of the command].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-3-8)

---

## SI-03 (10) (Malicious Code Analysis) { #si-03-10 }

!!! quote ""
    - **(a)** Employ the following tools and techniques to analyze the characteristics and behavior of malicious code: [Assignment: organization-defined tools and techniques]; and
    - **(b)** Incorporate the results from malicious code analysis into organizational incident response and flaw remediation processes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-3-10)

---

## SI-04 (System Monitoring) { #si-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Monitor the system to detect:
        - **1.** Attacks and indicators of potential attacks in accordance with the following monitoring objectives: [Assignment: organization-defined monitoring objectives]; and
        - **2.** Unauthorized local, network, and remote connections;
    - **b.** Identify unauthorized use of the system through the following techniques and methods: [Assignment: organization-defined techniques and methods];
    - **c.** Invoke internal monitoring capabilities or deploy monitoring devices:
        - **1.** Strategically within the system to collect organization-determined essential information; and
        - **2.** At ad hoc locations within the system to track specific types of transactions of interest to the organization;
    - **d.** Analyze detected events and anomalies;
    - **e.** Adjust the level of system monitoring activity when there is a change in risk to organizational operations and assets, individuals, other organizations, or the Nation;
    - **f.** Obtain legal opinion regarding system monitoring activities; and
    - **g.** Provide [Assignment: organization-defined system monitoring information] to [Assignment: organization-defined personnel or roles] [Selection: one or more of: as needed].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response and Incident Communication Procedure guidance.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4)

---

## SI-04 (01) (System-wide Intrusion Detection System) { #si-04-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Connect and configure individual intrusion detection tools into a system-wide intrusion detection system.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-1)

---

## SI-04 (02) (Automated Tools and Mechanisms for Real-time Analysis) { #si-04-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ automated tools and mechanisms to support near real-time analysis of events.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-2)

---

## SI-04 (03) (Automated Tool and Mechanism Integration) { #si-04-03 }

!!! quote ""
    Employ automated tools and mechanisms to integrate intrusion detection tools and mechanisms into access control and flow control mechanisms.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-3)

---

## SI-04 (04) (Inbound and Outbound Communications Traffic) { #si-04-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Determine criteria for unusual or unauthorized activities or conditions for inbound and outbound communications traffic;
    - **(b)** Monitor inbound and outbound communications traffic [Assignment: organization-defined frequency] for [Assignment: organization-defined unusual or unauthorized activities or conditions].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-4)

---

## SI-04 (05) (System-generated Alerts) { #si-04-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Alert [Assignment: organization-defined personnel or roles] when the following system-generated indications of compromise or potential compromise occur: [Assignment: organization-defined compromise indicators].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Vulnerability Detection and Response and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-5)

---

## SI-04 (07) (Automated Response to Suspicious Events) { #si-04-07 }

!!! quote ""
    - **(a)** Notify [Assignment: organization-defined incident response personnel] of detected suspicious events; and
    - **(b)** Take the following actions upon detection: [Assignment: organization-defined least-disruptive actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-7)

---

## SI-04 (09) (Testing of Monitoring Tools and Mechanisms) { #si-04-09 }

!!! quote ""
    Test intrusion-monitoring tools and mechanisms [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-9)

---

## SI-04 (10) (Visibility of Encrypted Communications) { #si-04-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Make provisions so that [Assignment: organization-defined encrypted communications traffic] is visible to [Assignment: organization-defined system monitoring tools and mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-10)

---

## SI-04 (11) (Analyze Communications Traffic Anomalies) { #si-04-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Analyze outbound communications traffic at the external interfaces to the system and selected [Assignment: organization-defined interior points] to discover anomalies.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-11)

---

## SI-04 (12) (Automated Organization-generated Alerts) { #si-04-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Alert [Assignment: organization-defined personnel or roles] using [Assignment: organization-defined automated mechanisms] when the following indications of inappropriate or unusual activities with security or privacy implications occur: [Assignment: organization-defined activities that trigger alerts].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-12)

---

## SI-04 (13) (Analyze Traffic and Event Patterns) { #si-04-13 }

!!! quote ""
    - **(a)** Analyze communications traffic and event patterns for the system;
    - **(b)** Develop profiles representing common traffic and event patterns; and
    - **(c)** Use the traffic and event profiles in tuning system-monitoring devices.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-13)

---

## SI-04 (14) (Wireless Intrusion Detection) { #si-04-14 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ a wireless intrusion detection system to identify rogue wireless devices and to detect attack attempts and potential compromises or breaches to the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-14)

---

## SI-04 (15) (Wireless to Wireline Communications) { #si-04-15 }

!!! quote ""
    Employ an intrusion detection system to monitor wireless communications traffic as the traffic passes from wireless to wireline networks.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-15)

---

## SI-04 (16) (Correlate Monitoring Information) { #si-04-16 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Correlate information from monitoring tools and mechanisms employed throughout the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-16)

---

## SI-04 (17) (Integrated Situational Awareness) { #si-04-17 }

!!! quote ""
    Correlate information from monitoring physical, cyber, and supply chain activities to achieve integrated, organization-wide situational awareness.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-17)

---

## SI-04 (18) (Analyze Traffic and Covert Exfiltration) { #si-04-18 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Analyze outbound communications traffic at external interfaces to the system and at the following interior points to detect covert exfiltration of information: [Assignment: organization-defined interior points].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-18)

---

## SI-04 (19) (Risk for Individuals) { #si-04-19 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement [Assignment: organization-defined additional monitoring] of individuals who have been identified by [Assignment: organization-defined sources] as posing an increased level of risk.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-19)

---

## SI-04 (20) (Privileged Users) { #si-04-20 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement the following additional monitoring of privileged users: [Assignment: organization-defined additional monitoring].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-20)

---

## SI-04 (21) (Probationary Periods) { #si-04-21 }

!!! quote ""
    Implement the following additional monitoring of individuals during [Assignment: organization-defined probationary period]: [Assignment: organization-defined additional monitoring].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-21)

---

## SI-04 (22) (Unauthorized Network Services) { #si-04-22 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Detect network services that have not been authorized or approved by [Assignment: organization-defined authorization or approval processes]; and
    - **(b)** [Selection: one or more of: audit; alert] when detected.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-22)

---

## SI-04 (23) (Host-based Devices) { #si-04-23 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement the following host-based monitoring mechanisms at [Assignment: organization-defined system components]: [Assignment: organization-defined host-based monitoring mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-23)

---

## SI-04 (24) (Indicators of Compromise) { #si-04-24 }

!!! quote ""
    Discover, collect, and distribute to [Assignment: organization-defined personnel or roles], indicators of compromise provided by [Assignment: organization-defined sources].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-24)

---

## SI-04 (25) (Optimize Network Traffic Analysis) { #si-04-25 }

!!! quote ""
    Provide visibility into network traffic at external and key internal system interfaces to optimize the effectiveness of monitoring devices.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-4-25)

---

## SI-05 (Security Alerts, Advisories, and Directives) { #si-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Receive system security alerts, advisories, and directives from [Assignment: organization-defined external organizations] on an ongoing basis;
    - **b.** Generate internal security alerts, advisories, and directives as deemed necessary;
    - **c.** Disseminate security alerts, advisories, and directives to: [Assignment: si-05_odp.02]; and
    - **d.** Implement security directives in accordance with established time frames, or notify the issuing organization of the degree of noncompliance.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Addressing FedRAMP Communication rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-5)

---

## SI-05 (01) (Automated Alerts and Advisories) { #si-05-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Broadcast security alert and advisory information throughout the organization using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-5-1)

---

## SI-06 (Security and Privacy Function Verification) { #si-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Verify the correct operation of [Assignment: organization-defined security and privacy functions];
    - **b.** Perform the verification of the functions specified in SI-6a [Selection: one or more of: upon command by user with appropriate privilege];
    - **c.** Alert [Assignment: organization-defined personnel or roles] to failed security and privacy verification tests; and
    - **d.** [Selection: one or more of: shut the system down; restart the system] when anomalies are discovered.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-6)

---

## SI-06 (02) (Automation Support for Distributed Testing) { #si-06-02 }

!!! quote ""
    Implement automated mechanisms to support the management of distributed security and privacy function testing.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-6-2)

---

## SI-06 (03) (Report Verification Results) { #si-06-03 }

!!! quote ""
    Report the results of security and privacy function verification to [Assignment: organization-defined personnel or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-6-3)

---

## SI-07 (Software, Firmware, and Information Integrity) { #si-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Employ integrity verification tools to detect unauthorized changes to the following software, firmware, and information: [Assignment: organization-defined software, firmware, and information]; and
    - **b.** Take the following actions when unauthorized changes to the software, firmware, and information are detected: [Assignment: organization-defined actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7)

---

## SI-07 (01) (Integrity Checks) { #si-07-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Perform an integrity check of [Assignment: organization-defined software, firmware, and information] [Selection: one or more of: at startup; at].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-1)

---

## SI-07 (02) (Automated Notifications of Integrity Violations) { #si-07-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ automated tools that provide notification to [Assignment: organization-defined personnel or roles] upon discovering discrepancies during integrity verification.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-2)

---

## SI-07 (03) (Centrally Managed Integrity Tools) { #si-07-03 }

!!! quote ""
    Employ centrally managed integrity verification tools.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-3)

---

## SI-07 (05) (Automated Response to Integrity Violations) { #si-07-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Automatically [Selection: one or more of: shut down the system; restart the system; implement] when integrity violations are discovered.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-5)

---

## SI-07 (06) (Cryptographic Protection) { #si-07-06 }

!!! quote ""
    Implement cryptographic mechanisms to detect unauthorized changes to software, firmware, and information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-6)

---

## SI-07 (07) (Integration of Detection and Response) { #si-07-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Incorporate the detection of the following unauthorized changes into the organizational incident response capability: [Assignment: organization-defined changes].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-7)

---

## SI-07 (08) (Auditing Capability for Significant Events) { #si-07-08 }

!!! quote ""
    Upon detection of a potential integrity violation, provide the capability to audit the event and initiate the following actions: [Selection: one or more of: generate an audit record; alert current user; alert].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-8)

---

## SI-07 (09) (Verify Boot Process) { #si-07-09 }

!!! quote ""
    Verify the integrity of the boot process of the following system components: [Assignment: organization-defined system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-9)

---

## SI-07 (10) (Protection of Boot Firmware) { #si-07-10 }

!!! quote ""
    Implement the following mechanisms to protect the integrity of boot firmware in [Assignment: organization-defined system components]: [Assignment: organization-defined mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-10)

---

## SI-07 (12) (Integrity Verification) { #si-07-12 }

!!! quote ""
    Require that the integrity of the following user-installed software be verified prior to execution: [Assignment: organization-defined user-installed software].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-12)

---

## SI-07 (15) (Code Authentication) { #si-07-15 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to authenticate the following software or firmware components prior to installation: [Assignment: organization-defined software or firmware components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-15)

---

## SI-07 (16) (Time Limit on Process Execution Without Supervision) { #si-07-16 }

!!! quote ""
    Prohibit processes from executing without supervision for more than [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-16)

---

## SI-07 (17) (Runtime Application Self-protection) { #si-07-17 }

!!! quote ""
    Implement [Assignment: organization-defined controls] for application self-protection at runtime.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-7-17)

---

## SI-08 (Spam Protection) { #si-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Employ spam protection mechanisms at system entry and exit points to detect and act on unsolicited messages; and
    - **b.** Update spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.

    ---

    !!! info ""
        **FedRAMP Guidance**

        When CSO sends email on behalf of the government as part of the business offering, Control Description should include implementation of Domain-based Message Authentication, Reporting & Conformance (DMARC) on the sending domain for outgoing messages as described in DHS Binding Operational Directive (BOD) 18-01. [https://www.cisa.gov/news-events/directives](https://www.cisa.gov/news-events/directives)

        SI-8 Guidance: CSPs should confirm DMARC configuration (where appropriate) to ensure that policy=reject and the rua parameter includes reports@dmarc.cyber.dhs.gov.  DMARC compliance should be documented in the SI-08 control implementation solution description, and list the FROM: domain(s) when emails are sent on behalf of the government.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-8)

---

## SI-08 (02) (Automatic Updates) { #si-08-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Automatically update spam protection mechanisms [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-8-2)

---

## SI-08 (03) (Continuous Learning Capability) { #si-08-03 }

!!! quote ""
    Implement spam protection mechanisms with a learning capability to more effectively identify legitimate communications traffic.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-8-3)

---

## SI-10 (Information Input Validation) { #si-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Check the validity of the following information inputs: [Assignment: organization-defined information inputs].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10)

---

## SI-10 (01) (Manual Override Capability) { #si-10-01 }

!!! quote ""
    - **(a)** Provide a manual override capability for input validation of the following information inputs: [Assignment: organization-defined information inputs];
    - **(b)** Restrict the use of the manual override capability to only [Assignment: organization-defined authorized individuals]; and
    - **(c)** Audit the use of the manual override capability.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-1)

---

## SI-10 (02) (Review and Resolve Errors) { #si-10-02 }

!!! quote ""
    Review and resolve input validation errors within [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-2)

---

## SI-10 (03) (Predictable Behavior) { #si-10-03 }

!!! quote ""
    Verify that the system behaves in a predictable and documented manner when invalid inputs are received.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-3)

---

## SI-10 (04) (Timing Interactions) { #si-10-04 }

!!! quote ""
    Account for timing interactions among system components in determining appropriate responses for invalid inputs.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-4)

---

## SI-10 (05) (Restrict Inputs to Trusted Sources and Approved Formats) { #si-10-05 }

!!! quote ""
    Restrict the use of information inputs to [Assignment: organization-defined trusted sources] and/or [Assignment: organization-defined formats].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-5)

---

## SI-10 (06) (Injection Prevention) { #si-10-06 }

!!! quote ""
    Prevent untrusted data injections.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-10-6)

---

## SI-11 (Error Handling) { #si-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Generate error messages that provide information necessary for corrective actions without revealing information that could be exploited; and
    - **b.** Reveal error messages only to [Assignment: organization-defined personnel or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-11)

---

## SI-12 (Information Management and Retention) { #si-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Manage and retain information within the system and information output from the system in accordance with applicable laws, executive orders, directives, regulations, policies, standards, guidelines and operational requirements.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-12)

---

## SI-12 (01) (Limit Personally Identifiable Information Elements) { #si-12-01 }

!!! quote ""
    Limit personally identifiable information being processed in the information life cycle to the following elements of personally identifiable information: [Assignment: organization-defined elements of personally identifiable information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-12-1)

---

## SI-12 (02) (Minimize Personally Identifiable Information in Testing, Training, and Research) { #si-12-02 }

!!! quote ""
    Use the following techniques to minimize the use of personally identifiable information for research, testing, or training: [Assignment: organization-defined techniques].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-12-2)

---

## SI-12 (03) (Information Disposal) { #si-12-03 }

!!! quote ""
    Use the following techniques to dispose of, destroy, or erase information following the retention period: [Assignment: organization-defined techniques].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-12-3)

---

## SI-13 (Predictable Failure Prevention) { #si-13 }

!!! quote ""
    - **a.** Determine mean time to failure (MTTF) for the following system components in specific environments of operation: [Assignment: organization-defined system components]; and
    - **b.** Provide substitute system components and a means to exchange active and standby components in accordance with the following criteria: [Assignment: organization-defined mean time to failure (MTTF) substitution criteria].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-13)

---

## SI-13 (01) (Transferring Component Responsibilities) { #si-13-01 }

!!! quote ""
    Take system components out of service by transferring component responsibilities to substitute components no later than [Assignment: organization-defined fraction or percentage] of mean time to failure.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-13-1)

---

## SI-13 (03) (Manual Transfer Between Components) { #si-13-03 }

!!! quote ""
    Manually initiate transfers between active and standby system components when the use of the active component reaches [Assignment: organization-defined percentage] of the mean time to failure.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-13-3)

---

## SI-13 (04) (Standby Component Installation and Notification) { #si-13-04 }

!!! quote ""
    If system component failures are detected:
    
    - **(a)** Ensure that the standby components are successfully and transparently installed within [Assignment: organization-defined time period]; and
    - **(b)** [Selection: one or more of: activate; automatically shut down the system].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-13-4)

---

## SI-13 (05) (Failover Capability) { #si-13-05 }

!!! quote ""
    Provide [Selection: one of: real-time; near real-time] [Assignment: organization-defined failover capability] for the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-13-5)

---

## SI-14 (Non-persistence) { #si-14 }

!!! quote ""
    Implement non-persistent [Assignment: organization-defined system components and services] that are initiated in a known state and terminated [Selection: one or more of: upon end of session of use].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-14)

---

## SI-14 (01) (Refresh from Trusted Sources) { #si-14-01 }

!!! quote ""
    Obtain software and data employed during system component and service refreshes from the following trusted sources: [Assignment: organization-defined trusted sources].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-14-1)

---

## SI-14 (02) (Non-persistent Information) { #si-14-02 }

!!! quote ""
    - **(a)** [Selection: one of: refresh; generate on demand]; and
    - **(b)** Delete information when no longer needed.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-14-2)

---

## SI-14 (03) (Non-persistent Connectivity) { #si-14-03 }

!!! quote ""
    Establish connections to the system on demand and terminate connections after [Selection: one of: completion of a request; a period of non-use].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-14-3)

---

## SI-15 (Information Output Filtering) { #si-15 }

!!! quote ""
    Validate information output from the following software programs and/or applications to ensure that the information is consistent with the expected content: [Assignment: organization-defined software programs and/or applications].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-15)

---

## SI-16 (Memory Protection) { #si-16 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement the following controls to protect the system memory from unauthorized code execution: [Assignment: organization-defined controls].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-16)

---

## SI-17 (Fail-safe Procedures) { #si-17 }

!!! quote ""
    Implement the indicated fail-safe procedures when the indicated failures occur: [Assignment: organization-defined list of failure conditions and associated fail-safe procedures].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-17)

---

## SI-18 (Personally Identifiable Information Quality Operations) { #si-18 }

!!! quote ""
    - **a.** Check the accuracy, relevance, timeliness, and completeness of personally identifiable information across the information life cycle [Assignment: organization-defined frequency]; and
    - **b.** Correct or delete inaccurate or outdated personally identifiable information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18)

---

## SI-18 (01) (Automation Support) { #si-18-01 }

!!! quote ""
    Correct or delete personally identifiable information that is inaccurate or outdated, incorrectly determined regarding impact, or incorrectly de-identified using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18-1)

---

## SI-18 (02) (Data Tags) { #si-18-02 }

!!! quote ""
    Employ data tags to automate the correction or deletion of personally identifiable information across the information life cycle within organizational systems.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18-2)

---

## SI-18 (03) (Collection) { #si-18-03 }

!!! quote ""
    Collect personally identifiable information directly from the individual.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18-3)

---

## SI-18 (04) (Individual Requests) { #si-18-04 }

!!! quote ""
    Correct or delete personally identifiable information upon request by individuals or their designated representatives.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18-4)

---

## SI-18 (05) (Notice of Correction or Deletion) { #si-18-05 }

!!! quote ""
    Notify [Assignment: organization-defined recipients] and individuals that the personally identifiable information has been corrected or deleted.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-18-5)

---

## SI-19 (De-identification) { #si-19 }

!!! quote ""
    - **a.** Remove the following elements of personally identifiable information from datasets: [Assignment: organization-defined elements]; and
    - **b.** Evaluate [Assignment: organization-defined frequency] for effectiveness of de-identification.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19)

---

## SI-19 (01) (Collection) { #si-19-01 }

!!! quote ""
    De-identify the dataset upon collection by not collecting personally identifiable information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-1)

---

## SI-19 (02) (Archiving) { #si-19-02 }

!!! quote ""
    Prohibit archiving of personally identifiable information elements if those elements in a dataset will not be needed after the dataset is archived.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-2)

---

## SI-19 (03) (Release) { #si-19-03 }

!!! quote ""
    Remove personally identifiable information elements from a dataset prior to its release if those elements in the dataset do not need to be part of the data release.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-3)

---

## SI-19 (04) (Removal, Masking, Encryption, Hashing, or Replacement of Direct Identifiers) { #si-19-04 }

!!! quote ""
    Remove, mask, encrypt, hash, or replace direct identifiers in a dataset.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-4)

---

## SI-19 (05) (Statistical Disclosure Control) { #si-19-05 }

!!! quote ""
    Manipulate numerical data, contingency tables, and statistical findings so that no individual or organization is identifiable in the results of the analysis.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-5)

---

## SI-19 (06) (Differential Privacy) { #si-19-06 }

!!! quote ""
    Prevent disclosure of personally identifiable information by adding non-deterministic noise to the results of mathematical operations before the results are reported.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-6)

---

## SI-19 (07) (Validated Algorithms and Software) { #si-19-07 }

!!! quote ""
    Perform de-identification using validated algorithms and software that is validated to implement the algorithms.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-7)

---

## SI-19 (08) (Motivated Intruder) { #si-19-08 }

!!! quote ""
    Perform a motivated intruder test on the de-identified dataset to determine if the identified data remains or if the de-identified data can be re-identified.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-19-8)

---

## SI-20 (Tainting) { #si-20 }

!!! quote ""
    Embed data or capabilities in the following systems or system components to determine if organizational data has been exfiltrated or improperly removed from the organization: [Assignment: organization-defined systems or system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-20)

---

## SI-21 (Information Refresh) { #si-21 }

!!! quote ""
    Refresh [Assignment: organization-defined information] at [Assignment: organization-defined frequencies] or generate the information on demand and delete the information when no longer needed.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-21)

---

## SI-22 (Information Diversity) { #si-22 }

!!! quote ""
    - **a.** Identify the following alternative sources of information for [Assignment: organization-defined essential functions and services]: [Assignment: organization-defined alternative information sources]; and
    - **b.** Use an alternative information source for the execution of essential functions or services on [Assignment: organization-defined systems or system components] when the primary source of information is corrupted or unavailable.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-22)

---

## SI-23 (Information Fragmentation) { #si-23 }

!!! quote ""
    Based on [Assignment: organization-defined circumstances]:
    
    - **a.** Fragment the following information: [Assignment: organization-defined information]; and
    - **b.** Distribute the fragmented information across the following systems or system components: [Assignment: organization-defined systems or system components].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/si-23)

---
