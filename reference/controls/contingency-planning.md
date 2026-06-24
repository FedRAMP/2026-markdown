---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Contingency Planning (CP)

This page contains all **49** controls and control enhancements in the Contingency Planning (CP) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## CP-01 (Policy and Procedures) { #cp-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] contingency planning policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the contingency planning policy and the associated contingency planning controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the contingency planning policy and procedures; and
    - **c.** Review and update the current contingency planning:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-1)

---

## CP-02 (Contingency Plan) { #cp-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop a contingency plan for the system that:
        - **1.** Identifies essential mission and business functions and associated contingency requirements;
        - **2.** Provides recovery objectives, restoration priorities, and metrics;
        - **3.** Addresses contingency roles, responsibilities, assigned individuals with contact information;
        - **4.** Addresses maintaining essential mission and business functions despite a system disruption, compromise, or failure;
        - **5.** Addresses eventual, full system restoration without deterioration of the controls originally planned and implemented;
        - **6.** Addresses the sharing of contingency information; and
        - **7.** Is reviewed and approved by [Assignment: organization-defined personnel or roles];
    - **b.** Distribute copies of the contingency plan to [Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements];
    - **c.** Coordinate contingency planning activities with incident handling activities;
    - **d.** Review the contingency plan for the system [Assignment: organization-defined frequency];
    - **e.** Update the contingency plan to address changes to the organization, system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;
    - **f.** Communicate contingency plan changes to [Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements];
    - **g.** Incorporate lessons learned from contingency plan testing, training, or actual contingency activities into contingency testing and training; and
    - **h.** Protect the contingency plan from unauthorized disclosure and modification.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2)

---

## CP-02 (01) (Coordinate with Related Plans) { #cp-02-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Coordinate contingency plan development with organizational elements responsible for related plans.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-1)

---

## CP-02 (02) (Capacity Planning) { #cp-02-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Conduct capacity planning so that necessary capacity for information processing, telecommunications, and environmental support exists during contingency operations.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-2)

---

## CP-02 (03) (Resume Mission and Business Functions) { #cp-02-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Plan for the resumption of [Selection: one of: all; essential] mission and business functions within [Assignment: organization-defined time period] of contingency plan activation.

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cp-02.03_odp.02` | time period | time period defined in service provider and organization Service Level Agreements |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-3)

---

## CP-02 (05) (Continue Mission and Business Functions) { #cp-02-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Plan for the continuance of [Selection: one of: all; essential] mission and business functions with minimal or no loss of operational continuity and sustains that continuity until full system restoration at primary processing and/or storage sites.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-5)

---

## CP-02 (06) (Alternate Processing and Storage Sites) { #cp-02-06 }

!!! quote ""
    Plan for the transfer of [Selection: one of: all; essential] mission and business functions to alternate processing and/or storage sites with minimal or no loss of operational continuity and sustain that continuity through system restoration to primary processing and/or storage sites.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-6)

---

## CP-02 (07) (Coordinate with External Service Providers) { #cp-02-07 }

!!! quote ""
    Coordinate the contingency plan with the contingency plans of external service providers to ensure that contingency requirements can be satisfied.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-7)

---

## CP-02 (08) (Identify Critical Assets) { #cp-02-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify critical system assets supporting [Selection: one of: all; essential] mission and business functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-2-8)

---

## CP-03 (Contingency Training) { #cp-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Provide contingency training to system users consistent with assigned roles and responsibilities:
        - **1.** Within [Assignment: organization-defined time period] of assuming a contingency role or responsibility;
        - **2.** When required by system changes; and
        - **3.** [Assignment: organization-defined frequency] thereafter; and
    - **b.** Review and update contingency training content [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-3)

---

## CP-03 (01) (Simulated Events) { #cp-03-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Incorporate simulated events into contingency training to facilitate effective response by personnel in crisis situations.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-3-1)

---

## CP-03 (02) (Mechanisms Used in Training Environments) { #cp-03-02 }

!!! quote ""
    Employ mechanisms used in operations to provide a more thorough and realistic contingency training environment.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-3-2)

---

## CP-04 (Contingency Plan Testing) { #cp-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Test the contingency plan for the system [Assignment: organization-defined frequency] using the following tests to determine the effectiveness of the plan and the readiness to execute the plan: [Assignment: organization-defined tests].
    - **b.** Review the contingency plan test results; and
    - **c.** Initiate corrective actions, if needed.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4)

---

## CP-04 (01) (Coordinate with Related Plans) { #cp-04-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Coordinate contingency plan testing with organizational elements responsible for related plans.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4-1)

---

## CP-04 (02) (Alternate Processing Site) { #cp-04-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Test the contingency plan at the alternate processing site:
    
    - **(a)** To familiarize contingency personnel with the facility and available resources; and
    - **(b)** To evaluate the capabilities of the alternate processing site to support contingency operations.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4-2)

---

## CP-04 (03) (Automated Testing) { #cp-04-03 }

!!! quote ""
    Test the contingency plan using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4-3)

---

## CP-04 (04) (Full Recovery and Reconstitution) { #cp-04-04 }

!!! quote ""
    Include a full recovery and reconstitution of the system to a known state as part of contingency plan testing.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4-4)

---

## CP-04 (05) (Self-challenge) { #cp-04-05 }

!!! quote ""
    Employ [Assignment: organization-defined mechanisms] to [Assignment: organization-defined system or system component] to disrupt and adversely affect the system or system component.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-4-5)

---

## CP-06 (Alternate Storage Site) { #cp-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Establish an alternate storage site, including necessary agreements to permit the storage and retrieval of system backup information; and
    - **b.** Ensure that the alternate storage site provides controls equivalent to that of the primary site.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-6)

---

## CP-06 (01) (Separation from Primary Site) { #cp-06-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify an alternate storage site that is sufficiently separated from the primary storage site to reduce susceptibility to the same threats.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-6-1)

---

## CP-06 (02) (Recovery Time and Recovery Point Objectives) { #cp-06-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Configure the alternate storage site to facilitate recovery operations in accordance with recovery time and recovery point objectives.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-6-2)

---

## CP-06 (03) (Accessibility) { #cp-06-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify potential accessibility problems to the alternate storage site in the event of an area-wide disruption or disaster and outline explicit mitigation actions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-6-3)

---

## CP-07 (Alternate Processing Site) { #cp-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Establish an alternate processing site, including necessary agreements to permit the transfer and resumption of [Assignment: organization-defined system operations] for essential mission and business functions within [Assignment: organization-defined time period] when the primary processing capabilities are unavailable;
    - **b.** Make available at the alternate processing site, the equipment and supplies required to transfer and resume operations or put contracts in place to support delivery to the site within the organization-defined time period for transfer and resumption; and
    - **c.** Provide controls at the alternate processing site that are equivalent to those at the primary site.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7)

---

## CP-07 (01) (Separation from Primary Site) { #cp-07-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify an alternate processing site that is sufficiently separated from the primary processing site to reduce susceptibility to the same threats.

    ---

    !!! info ""
        **FedRAMP Guidance**

        The service provider may determine what is considered a sufficient degree of separation between the primary and alternate processing sites, based on the types of threats that are of concern. For one particular type of threat (i.e., hostile cyber attack), the degree of separation between sites will be less relevant.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7-1)

---

## CP-07 (02) (Accessibility) { #cp-07-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify potential accessibility problems to alternate processing sites in the event of an area-wide disruption or disaster and outlines explicit mitigation actions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7-2)

---

## CP-07 (03) (Priority of Service) { #cp-07-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Develop alternate processing site agreements that contain priority-of-service provisions in accordance with availability requirements (including recovery time objectives).

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7-3)

---

## CP-07 (04) (Preparation for Use) { #cp-07-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prepare the alternate processing site so that the site can serve as the operational site supporting essential mission and business functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7-4)

---

## CP-07 (06) (Inability to Return to Primary Site) { #cp-07-06 }

!!! quote ""
    Plan and prepare for circumstances that preclude returning to the primary processing site.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-7-6)

---

## CP-08 (Telecommunications Services) { #cp-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Establish alternate telecommunications services, including necessary agreements to permit the resumption of [Assignment: organization-defined system operations] for essential mission and business functions within [Assignment: organization-defined time period] when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8)

---

## CP-08 (01) (Priority of Service Provisions) { #cp-08-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Develop primary and alternate telecommunications service agreements that contain priority-of-service provisions in accordance with availability requirements (including recovery time objectives); and
    - **(b)** Request Telecommunications Service Priority for all telecommunications services used for national security emergency preparedness if the primary and/or alternate telecommunications services are provided by a common carrier.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8-1)

---

## CP-08 (02) (Single Points of Failure) { #cp-08-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Obtain alternate telecommunications services to reduce the likelihood of sharing a single point of failure with primary telecommunications services.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8-2)

---

## CP-08 (03) (Separation of Primary and Alternate Providers) { #cp-08-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Obtain alternate telecommunications services from providers that are separated from primary service providers to reduce susceptibility to the same threats.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8-3)

---

## CP-08 (04) (Provider Contingency Plan) { #cp-08-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Require primary and alternate telecommunications service providers to have contingency plans;
    - **(b)** Review provider contingency plans to ensure that the plans meet organizational contingency requirements; and
    - **(c)** Obtain evidence of contingency testing and training by providers [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8-4)

---

## CP-08 (05) (Alternate Telecommunication Service Testing) { #cp-08-05 }

!!! quote ""
    Test alternate telecommunication services [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-8-5)

---

## CP-09 (System Backup) { #cp-09 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Conduct backups of user-level information contained in [Assignment: organization-defined system components] [Assignment: organization-defined frequency];
    - **b.** Conduct backups of system-level information contained in the system [Assignment: organization-defined frequency];
    - **c.** Conduct backups of system documentation, including security- and privacy-related documentation [Assignment: organization-defined frequency]; and
    - **d.** Protect the confidentiality, integrity, and availability of backup information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9)

---

## CP-09 (01) (Testing for Reliability and Integrity) { #cp-09-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Test backup information [Assignment: organization-defined frequency] to verify media reliability and information integrity.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-1)

---

## CP-09 (02) (Test Restoration Using Sampling) { #cp-09-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Use a sample of backup information in the restoration of selected system functions as part of contingency plan testing.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-2)

---

## CP-09 (03) (Separate Storage for Critical Information) { #cp-09-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Store backup copies of [Assignment: organization-defined critical system software and other security-related information] in a separate facility or in a fire rated container that is not collocated with the operational system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-3)

---

## CP-09 (05) (Transfer to Alternate Storage Site) { #cp-09-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Transfer system backup information to the alternate storage site [Assignment: organization-defined time period and transfer rate consistent with the recovery time and recovery point objectives].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-5)

---

## CP-09 (06) (Redundant Secondary System) { #cp-09-06 }

!!! quote ""
    Conduct system backup by maintaining a redundant secondary system that is not collocated with the primary system and that can be activated without loss of information or disruption to operations.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-6)

---

## CP-09 (07) (Dual Authorization for Deletion or Destruction) { #cp-09-07 }

!!! quote ""
    Enforce dual authorization for the deletion or destruction of [Assignment: organization-defined backup information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-7)

---

## CP-09 (08) (Cryptographic Protection) { #cp-09-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to prevent unauthorized disclosure and modification of [Assignment: organization-defined backup information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-9-8)

---

## CP-10 (System Recovery and Reconstitution) { #cp-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide for the recovery and reconstitution of the system to a known state within [Assignment: organization-defined time period consistent with recovery time and recovery point objectives] after a disruption, compromise, or failure.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-10)

---

## CP-10 (02) (Transaction Recovery) { #cp-10-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement transaction recovery for systems that are transaction-based.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-10-2)

---

## CP-10 (04) (Restore Within Time Period) { #cp-10-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Provide the capability to restore system components within [Assignment: organization-defined restoration time periods] from configuration-controlled and integrity-protected information representing a known, operational state for the components.

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `cp-10.04_odp` | restoration time periods | time period consistent with the restoration time-periods defined in the service provider and organization Service Level Agreements |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-10-4)

---

## CP-10 (06) (Component Protection) { #cp-10-06 }

!!! quote ""
    Protect system components used for recovery and reconstitution.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-10-6)

---

## CP-11 (Alternate Communications Protocols) { #cp-11 }

!!! quote ""
    Provide the capability to employ [Assignment: organization-defined alternative communications protocols] in support of maintaining continuity of operations.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-11)

---

## CP-12 (Safe Mode) { #cp-12 }

!!! quote ""
    When [Assignment: organization-defined conditions] are detected, enter a safe mode of operation with [Assignment: organization-defined restrictions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-12)

---

## CP-13 (Alternative Security Mechanisms) { #cp-13 }

!!! quote ""
    Employ [Assignment: organization-defined alternative or supplemental security mechanisms] for satisfying [Assignment: organization-defined security functions] when the primary means of implementing the security function is unavailable or compromised.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/cp-13)

---
