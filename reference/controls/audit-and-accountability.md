---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Audit and Accountability (AU)

This page contains all **56** controls and control enhancements in the Audit and Accountability (AU) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## AU-01 (Policy and Procedures) { #au-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] audit and accountability policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the audit and accountability policy and the associated audit and accountability controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the audit and accountability policy and procedures; and
    - **c.** Review and update the current audit and accountability:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-1)

---

## AU-02 (Event Logging) { #au-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Identify the types of events that the system is capable of logging in support of the audit function: [Assignment: organization-defined event types];
    - **b.** Coordinate the event logging function with other organizational entities requiring audit-related information to guide and inform the selection criteria for events to be logged;
    - **c.** Specify the following event types for logging within the system: [Assignment: organization-defined event types (subset of the event types defined in AU-2a.) along with the frequency of (or situation requiring) logging for each identified event type];
    - **d.** Provide a rationale for why the event types selected for logging are deemed to be adequate to support after-the-fact investigations of incidents; and
    - **e.** Review and update the event types selected for logging [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-2)

---

## AU-03 (Content of Audit Records) { #au-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Ensure that audit records contain information that establishes the following:
    
    - **a.** What type of event occurred;
    - **b.** When the event occurred;
    - **c.** Where the event occurred;
    - **d.** Source of the event;
    - **e.** Outcome of the event; and
    - **f.** Identity of any individuals, subjects, or objects/entities associated with the event.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-3)

---

## AU-03 (01) (Additional Audit Information) { #au-03-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Generate audit records containing the following additional information: [Assignment: organization-defined additional information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-3-1)

---

## AU-03 (03) (Limit Personally Identifiable Information Elements) { #au-03-03 }

!!! quote ""
    Limit personally identifiable information contained in audit records to the following elements identified in the privacy risk assessment: [Assignment: organization-defined elements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-3-3)

---

## AU-04 (Audit Log Storage Capacity) { #au-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Allocate audit log storage capacity to accommodate [Assignment: organization-defined audit log retention requirements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-4)

---

## AU-04 (01) (Transfer to Alternate Storage) { #au-04-01 }

!!! quote ""
    Transfer audit logs [Assignment: organization-defined frequency] to a different system, system component, or media other than the system or system component conducting the logging.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-4-1)

---

## AU-05 (Response to Audit Logging Process Failures) { #au-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Alert [Assignment: organization-defined personnel or roles] within [Assignment: organization-defined time period] in the event of an audit logging process failure; and
    - **b.** Take the following additional actions: [Assignment: organization-defined additional actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5)

---

## AU-05 (01) (Storage Capacity Warning) { #au-05-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide a warning to [Assignment: organization-defined personnel, roles, and/or locations] within [Assignment: organization-defined time period] when allocated audit log storage volume reaches [Assignment: organization-defined percentage] of repository maximum audit log storage capacity.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5-1)

---

## AU-05 (02) (Real-time Alerts) { #au-05-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide an alert within [Assignment: organization-defined real-time period] to [Assignment: organization-defined personnel, roles, and/or locations] when the following audit failure events occur: [Assignment: organization-defined audit logging failure events requiring real-time alerts].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5-2)

---

## AU-05 (03) (Configurable Traffic Volume Thresholds) { #au-05-03 }

!!! quote ""
    Enforce configurable network communications traffic volume thresholds reflecting limits on audit log storage capacity and [Selection: one or more of: reject; delay] network traffic above those thresholds.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5-3)

---

## AU-05 (04) (Shutdown on Failure) { #au-05-04 }

!!! quote ""
    Invoke a [Selection: one or more of: full system shutdown; partial system shutdown; degraded operational mode with limited mission or business functionality available] in the event of [Assignment: organization-defined audit logging failures], unless an alternate audit logging capability exists.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5-4)

---

## AU-05 (05) (Alternate Audit Logging Capability) { #au-05-05 }

!!! quote ""
    Provide an alternate audit logging capability in the event of a failure in primary audit logging capability that implements [Assignment: organization-defined alternate audit logging functionality].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-5-5)

---

## AU-06 (Audit Record Review, Analysis, and Reporting) { #au-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Review and analyze system audit records [Assignment: organization-defined frequency] for indications of [Assignment: organization-defined inappropriate or unusual activity] and the potential impact of the inappropriate or unusual activity;
    - **b.** Report findings to [Assignment: organization-defined personnel or roles]; and
    - **c.** Adjust the level of audit record review, analysis, and reporting within the system when there is a change in risk based on law enforcement information, intelligence information, or other credible sources of information.

    ---

    !!! info ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6)

---

## AU-06 (01) (Automated Process Integration) { #au-06-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Integrate audit record review, analysis, and reporting processes using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-1)

---

## AU-06 (03) (Correlate Audit Record Repositories) { #au-06-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Analyze and correlate audit records across different repositories to gain organization-wide situational awareness.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-3)

---

## AU-06 (04) (Central Review and Analysis) { #au-06-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide and implement the capability to centrally review and analyze audit records from multiple components within the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-4)

---

## AU-06 (05) (Integrated Analysis of Audit Records) { #au-06-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Integrate analysis of audit records with analysis of [Selection: one or more of: vulnerability scanning information; performance data; system monitoring information] to further enhance the ability to identify inappropriate or unusual activity.

    ---

    !!! info ""
        **FedRAMP Guidance**

        This activity is considered vulnerability detection and is subject to the Vulnerability Detection and Response rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-5)

---

## AU-06 (06) (Correlation with Physical Monitoring) { #au-06-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Correlate information from audit records with information obtained from monitoring physical access to further enhance the ability to identify suspicious, inappropriate, unusual, or malevolent activity.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-6)

---

## AU-06 (07) (Permitted Actions) { #au-06-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Specify the permitted actions for each [Selection: one or more of: system process; role; user] associated with the review, analysis, and reporting of audit record information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-7)

---

## AU-06 (08) (Full Text Analysis of Privileged Commands) { #au-06-08 }

!!! quote ""
    Perform a full text analysis of logged privileged commands in a physically distinct component or subsystem of the system, or other system that is dedicated to that analysis.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-8)

---

## AU-06 (09) (Correlation with Information from Nontechnical Sources) { #au-06-09 }

!!! quote ""
    Correlate information from nontechnical sources with audit record information to enhance organization-wide situational awareness.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-6-9)

---

## AU-07 (Audit Record Reduction and Report Generation) { #au-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide and implement an audit record reduction and report generation capability that:
    
    - **a.** Supports on-demand audit record review, analysis, and reporting requirements and after-the-fact investigations of incidents; and
    - **b.** Does not alter the original content or time ordering of audit records.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-7)

---

## AU-07 (01) (Automatic Processing) { #au-07-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide and implement the capability to process, sort, and search audit records for events of interest based on the following content: [Assignment: organization-defined fields within audit records].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-7-1)

---

## AU-08 (Time Stamps) { #au-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Use internal system clocks to generate time stamps for audit records; and
    - **b.** Record time stamps for audit records that meet [Assignment: organization-defined granularity of time measurement] and that use Coordinated Universal Time, have a fixed local time offset from Coordinated Universal Time, or that include the local time offset as part of the time stamp.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-8)

---

## AU-09 (Protection of Audit Information) { #au-09 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Protect audit information and audit logging tools from unauthorized access, modification, and deletion; and
    - **b.** Alert [Assignment: organization-defined personnel or roles] upon detection of unauthorized access, modification, or deletion of audit information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9)

---

## AU-09 (01) (Hardware Write-once Media) { #au-09-01 }

!!! quote ""
    Write audit trails to hardware-enforced, write-once media.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-1)

---

## AU-09 (02) (Store on Separate Physical Systems or Components) { #au-09-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Store audit records [Assignment: organization-defined frequency] in a repository that is part of a physically different system or system component than the system or component being audited.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-2)

---

## AU-09 (03) (Cryptographic Protection) { #au-09-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to protect the integrity of audit information and audit tools.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-3)

---

## AU-09 (04) (Access by Subset of Privileged Users) { #au-09-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Authorize access to management of audit logging functionality to only [Assignment: organization-defined subset of privileged users or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-4)

---

## AU-09 (05) (Dual Authorization) { #au-09-05 }

!!! quote ""
    Enforce dual authorization for [Selection: one or more of: movement; deletion] of [Assignment: organization-defined audit information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-5)

---

## AU-09 (06) (Read-only Access) { #au-09-06 }

!!! quote ""
    Authorize read-only access to audit information to [Assignment: organization-defined subset of privileged users or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-6)

---

## AU-09 (07) (Store on Component with Different Operating System) { #au-09-07 }

!!! quote ""
    Store audit information on a component running a different operating system than the system or component being audited.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-9-7)

---

## AU-10 (Non-repudiation) { #au-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide irrefutable evidence that an individual (or process acting on behalf of an individual) has performed [Assignment: organization-defined actions].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-10_odp` | actions | at least actions including the addition, modification, deletion, approval, sending, or receiving of data |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-10)

---

## AU-10 (01) (Association of Identities) { #au-10-01 }

!!! quote ""
    - **(a)** Bind the identity of the information producer with the information to [Assignment: organization-defined strength of binding]; and
    - **(b)** Provide the means for authorized individuals to determine the identity of the producer of the information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-10-1)

---

## AU-10 (02) (Validate Binding of Information Producer Identity) { #au-10-02 }

!!! quote ""
    - **(a)** Validate the binding of the information producer identity to the information at [Assignment: organization-defined frequency]; and
    - **(b)** Perform [Assignment: organization-defined actions] in the event of a validation error.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-10-2)

---

## AU-10 (03) (Chain of Custody) { #au-10-03 }

!!! quote ""
    Maintain reviewer or releaser credentials within the established chain of custody for information reviewed or released.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-10-3)

---

## AU-10 (04) (Validate Binding of Information Reviewer Identity) { #au-10-04 }

!!! quote ""
    - **(a)** Validate the binding of the information reviewer identity to the information at the transfer or release points prior to release or transfer between [Assignment: organization-defined security domains]; and
    - **(b)** Perform [Assignment: organization-defined actions] in the event of a validation error.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-10-4)

---

## AU-11 (Audit Record Retention) { #au-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Retain audit records for [Assignment: organization-defined time period] to provide support for after-the-fact investigations of incidents and to meet regulatory and organizational information retention requirements.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-11)

---

## AU-11 (01) (Long-term Retrieval Capability) { #au-11-01 }

!!! quote ""
    Employ [Assignment: organization-defined measures] to ensure that long-term audit records generated by the system can be retrieved.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-11-1)

---

## AU-12 (Audit Record Generation) { #au-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Provide audit record generation capability for the event types the system is capable of auditing as defined in AU-2a on [Assignment: organization-defined system components];
    - **b.** Allow [Assignment: organization-defined personnel or roles] to select the event types that are to be logged by specific components of the system; and
    - **c.** Generate audit records for the event types defined in AU-2c that include the audit record content defined in AU-3.

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `au-12_odp.01` | system components | at least all information system and network components where audit capability is deployed/available |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-12)

---

## AU-12 (01) (System-wide and Time-correlated Audit Trail) { #au-12-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Compile audit records from [Assignment: organization-defined system components] into a system-wide (logical or physical) audit trail that is time-correlated to within [Assignment: organization-defined level of tolerance].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-12-1)

---

## AU-12 (02) (Standardized Formats) { #au-12-02 }

!!! quote ""
    Produce a system-wide (logical or physical) audit trail composed of audit records in a standardized format.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-12-2)

---

## AU-12 (03) (Changes by Authorized Individuals) { #au-12-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide and implement the capability for [Assignment: organization-defined individuals or roles] to change the logging to be performed on [Assignment: organization-defined system components] based on [Assignment: organization-defined selectable event criteria] within [Assignment: organization-defined time thresholds].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-12-3)

---

## AU-12 (04) (Query Parameter Audits of Personally Identifiable Information) { #au-12-04 }

!!! quote ""
    Provide and implement the capability for auditing the parameters of user query events for data sets containing personally identifiable information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-12-4)

---

## AU-13 (Monitoring for Information Disclosure) { #au-13 }

!!! quote ""
    - **a.** Monitor [Assignment: organization-defined open-source information and/or information sites] [Assignment: organization-defined frequency] for evidence of unauthorized disclosure of organizational information; and
    - **b.** If an information disclosure is discovered:
        - **1.** Notify [Assignment: organization-defined personnel or roles]; and
        - **2.** Take the following additional actions: [Assignment: organization-defined additional actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-13)

---

## AU-13 (01) (Use of Automated Tools) { #au-13-01 }

!!! quote ""
    Monitor open-source information and information sites using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-13-1)

---

## AU-13 (02) (Review of Monitored Sites) { #au-13-02 }

!!! quote ""
    Review the list of open-source information sites being monitored [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-13-2)

---

## AU-13 (03) (Unauthorized Replication of Information) { #au-13-03 }

!!! quote ""
    Employ discovery techniques, processes, and tools to determine if external entities are replicating organizational information in an unauthorized manner.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-13-3)

---

## AU-14 (Session Audit) { #au-14 }

!!! quote ""
    - **a.** Provide and implement the capability for [Assignment: organization-defined users or roles] to [Selection: one or more of: record; view; hear; log] the content of a user session under [Assignment: organization-defined circumstances]; and
    - **b.** Develop, integrate, and use session auditing activities in consultation with legal counsel and in accordance with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-14)

---

## AU-14 (01) (System Start-up) { #au-14-01 }

!!! quote ""
    Initiate session audits automatically at system start-up.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-14-1)

---

## AU-14 (03) (Remote Viewing and Listening) { #au-14-03 }

!!! quote ""
    Provide and implement the capability for authorized users to remotely view and hear content related to an established user session in real time.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-14-3)

---

## AU-16 (Cross-organizational Audit Logging) { #au-16 }

!!! quote ""
    Employ [Assignment: organization-defined methods] for coordinating [Assignment: organization-defined audit information] among external organizations when audit information is transmitted across organizational boundaries.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-16)

---

## AU-16 (01) (Identity Preservation) { #au-16-01 }

!!! quote ""
    Preserve the identity of individuals in cross-organizational audit trails.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-16-1)

---

## AU-16 (02) (Sharing of Audit Information) { #au-16-02 }

!!! quote ""
    Provide cross-organizational audit information to [Assignment: organization-defined organizations] based on [Assignment: organization-defined cross-organizational sharing agreements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-16-2)

---

## AU-16 (03) (Disassociability) { #au-16-03 }

!!! quote ""
    Implement [Assignment: organization-defined measures] to disassociate individuals from audit information transmitted across organizational boundaries.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/au-16-3)

---
