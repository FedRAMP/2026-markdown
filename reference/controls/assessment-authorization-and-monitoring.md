---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# Assessment, Authorization, and Monitoring (CA)

This page contains all **25** controls and control enhancements in the Assessment, Authorization, and Monitoring (CA) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## CA-01 (Policy and Procedures) { #ca-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] assessment, authorization, and monitoring policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the assessment, authorization, and monitoring policy and the associated assessment, authorization, and monitoring controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the assessment, authorization, and monitoring policy and procedures; and
    - **c.** Review and update the current assessment, authorization, and monitoring:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-1)

---

## CA-02 (Control Assessments) { #ca-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Select the appropriate assessor or assessment team for the type of assessment to be conducted;
    - **b.** Develop a control assessment plan that describes the scope of the assessment including:
        - **1.** Controls and control enhancements under assessment;
        - **2.** Assessment procedures to be used to determine control effectiveness; and
        - **3.** Assessment environment, assessment team, and assessment roles and responsibilities;
    - **c.** Ensure the control assessment plan is reviewed and approved by the authorizing official or designated representative prior to conducting the assessment;
    - **d.** Assess the controls in the system and its environment of operation [Assignment: organization-defined assessment frequency] to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security and privacy requirements;
    - **e.** Produce a control assessment report that document the results of the assessment; and
    - **f.** Provide the results of the control assessment to [Assignment: organization-defined individuals or roles].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ca-02_odp.02` | individuals or roles | individuals or roles to include FedRAMP and agency customers |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-2)

---

## CA-02 (01) (Independent Assessors) { #ca-02-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ independent assessors or assessment teams to conduct control assessments.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-2-1)

---

## CA-02 (02) (Specialized Assessments) { #ca-02-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Include as part of control assessments, [Assignment: organization-defined specialized assessment frequency], [Selection: one of: announced; unannounced], [Selection: one or more of: in-depth monitoring; security instrumentation; automated security test cases; vulnerability scanning; malicious user testing; insider threat assessment; performance and load testing; data leakage or data loss assessment].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-2-2)

---

## CA-02 (03) (Leveraging Results from External Organizations) { #ca-02-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Leverage the results of control assessments performed by [Assignment: organization-defined external organization(s)] on [Assignment: organization-defined system] when the assessment meets [Assignment: organization-defined requirements].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ca-02.03_odp.01` | external organization(s) | any FedRAMP Recognized independent assessment service |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-2-3)

---

## CA-03 (Information Exchange) { #ca-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Approve and manage the exchange of information between the system and other systems using [Selection: one or more of: interconnection security agreements; information exchange security agreements; memoranda of understanding or agreement; service level agreements; user agreements; non-disclosure agreements];
    - **b.** Document, as part of each exchange agreement, the interface characteristics, security and privacy requirements, controls, and responsibilities for each system, and the impact level of the information communicated; and
    - **c.** Review and update the agreements [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-3)

---

## CA-03 (06) (Transfer Authorizations) { #ca-03-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Verify that individuals or systems transferring data between interconnecting systems have the requisite authorizations (i.e., write permissions or privileges) prior to accepting such data.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-3-6)

---

## CA-03 (07) (Transitive Information Exchanges) { #ca-03-07 }

!!! quote ""
    - **(a)** Identify transitive (downstream) information exchanges with other systems through the systems identified in CA-3a; and
    - **(b)** Take measures to ensure that transitive (downstream) information exchanges cease when the controls on identified transitive (downstream) systems cannot be verified or validated.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-3-7)

---

## CA-05 (Plan of Action and Milestones) { #ca-05 }

!!! quote ""
    - **a.** Develop a plan of action and milestones for the system to document the planned remediation actions of the organization to correct weaknesses or deficiencies noted during the assessment of the controls and to reduce or eliminate known vulnerabilities in the system; and
    - **b.** Update existing plan of action and milestones [Assignment: organization-defined frequency] based on the findings from control assessments, independent audits or reviews, and continuous monitoring activities.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-5)

---

## CA-05 (01) (Automation Support for Accuracy and Currency) { #ca-05-01 }

!!! quote ""
    Ensure the accuracy, currency, and availability of the plan of action and milestones for the system using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-5-1)

---

## CA-06 (Authorization) { #ca-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Assign a senior official as the authorizing official for the system;
    - **b.** Assign a senior official as the authorizing official for common controls available for inheritance by organizational systems;
    - **c.** Ensure that the authorizing official for the system, before commencing operations:
        - **1.** Accepts the use of common controls inherited by the system; and
        - **2.** Authorizes the system to operate;
    - **d.** Ensure that the authorizing official for common controls authorizes the use of those controls for inheritance by organizational systems;
    - **e.** Update the authorizations [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-6)

---

## CA-06 (01) (Joint Authorization — Intra-organization) { #ca-06-01 }

!!! quote ""
    Employ a joint authorization process for the system that includes multiple authorizing officials from the same organization conducting the authorization.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-6-1)

---

## CA-06 (02) (Joint Authorization — Inter-organization) { #ca-06-02 }

!!! quote ""
    Employ a joint authorization process for the system that includes multiple authorizing officials with at least one authorizing official from an organization external to the organization conducting the authorization.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-6-2)

---

## CA-07 (Continuous Monitoring) { #ca-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Develop a system-level continuous monitoring strategy and implement continuous monitoring in accordance with the organization-level continuous monitoring strategy that includes:
    
    - **a.** Establishing the following system-level metrics to be monitored: [Assignment: organization-defined system-level metrics];
    - **b.** Establishing [Assignment: organization-defined frequencies] for monitoring and [Assignment: organization-defined frequencies] for assessment of control effectiveness;
    - **c.** Ongoing control assessments in accordance with the continuous monitoring strategy;
    - **d.** Ongoing monitoring of system and organization-defined metrics in accordance with the continuous monitoring strategy;
    - **e.** Correlation and analysis of information generated by control assessments and monitoring;
    - **f.** Response actions to address results of the analysis of control assessment and monitoring information; and
    - **g.** Reporting the security and privacy status of the system to [Assignment: organization-defined personnel or roles] [Assignment: organization-defined frequency].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Follow the FedRAMP Continuous Collaborative Monitoring, Significant Change Notification, Vulnerability Detection and Response, and Vulnerability Evaluation and Reporting rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7)

---

## CA-07 (01) (Independent Assessment) { #ca-07-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ independent assessors or assessment teams to monitor the controls in the system on an ongoing basis.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7-1)

---

## CA-07 (03) (Trend Analyses) { #ca-07-03 }

!!! quote ""
    Employ trend analyses to determine if control implementations, the frequency of continuous monitoring activities, and the types of activities used in the continuous monitoring process need to be modified based on empirical data.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7-3)

---

## CA-07 (04) (Risk Monitoring) { #ca-07-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Ensure risk monitoring is an integral part of the continuous monitoring strategy that includes the following:
    
    - **(a)** Effectiveness monitoring;
    - **(b)** Compliance monitoring; and
    - **(c)** Change monitoring.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7-4)

---

## CA-07 (05) (Consistency Analysis) { #ca-07-05 }

!!! quote ""
    Employ the following actions to validate that policies are established and implemented controls are operating in a consistent manner: [Assignment: organization-defined actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7-5)

---

## CA-07 (06) (Automation Support for Monitoring) { #ca-07-06 }

!!! quote ""
    Ensure the accuracy, currency, and availability of monitoring results for the system using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-7-6)

---

## CA-08 (Penetration Testing) { #ca-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Conduct penetration testing [Assignment: organization-defined frequency] on [Assignment: organization-defined system(s) or system components].

    ---

    !!! info ""
        **FedRAMP Guidance**

        Penetration testing is part of vulnerability detection and is subject to the Vulnerability Detection and Response rules.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-8)

---

## CA-08 (01) (Independent Penetration Testing Agent or Team) { #ca-08-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ an independent penetration testing agent or team to perform penetration testing on the system or system components.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-8-1)

---

## CA-08 (02) (Red Team Exercises) { #ca-08-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ the following red-team exercises to simulate attempts by adversaries to compromise organizational systems in accordance with applicable rules of engagement: [Assignment: organization-defined red team exercises].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-8-2)

---

## CA-08 (03) (Facility Penetration Testing) { #ca-08-03 }

!!! quote ""
    Employ a penetration testing process that includes [Assignment: organization-defined frequency] [Selection: one or more of: announced; unannounced] attempts to bypass or circumvent controls associated with physical access points to the facility.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-8-3)

---

## CA-09 (Internal System Connections) { #ca-09 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Authorize internal connections of [Assignment: organization-defined system components] to the system;
    - **b.** Document, for each internal connection, the interface characteristics, security and privacy requirements, and the nature of the information communicated;
    - **c.** Terminate internal system connections after [Assignment: organization-defined conditions]; and
    - **d.** Review [Assignment: organization-defined frequency] the continued need for each internal connection.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-9)

---

## CA-09 (01) (Compliance Checks) { #ca-09-01 }

!!! quote ""
    Perform security and privacy compliance checks on constituent system components prior to the establishment of the internal connection.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ca-9-1)

---
