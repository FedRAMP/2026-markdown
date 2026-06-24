---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Access Control (AC)

This page contains all **131** controls and control enhancements in the Access Control (AC) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## AC-01 (Policy and Procedures) { #ac-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] access control policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the access control policy and the associated access controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the access control policy and procedures; and
    - **c.** Review and update the current access control:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-1)

---

## AC-02 (Account Management) { #ac-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Define and document the types of accounts allowed and specifically prohibited for use within the system;
    - **b.** Assign account managers;
    - **c.** Require [Assignment: organization-defined prerequisites and criteria] for group and role membership;
    - **d.** Specify:
        - **1.** Authorized users of the system;
        - **2.** Group and role membership; and
        - **3.** Access authorizations (i.e., privileges) and [Assignment: organization-defined attributes (as required)] for each account;
    - **e.** Require approvals by [Assignment: organization-defined personnel or roles] for requests to create accounts;
    - **f.** Create, enable, modify, disable, and remove accounts in accordance with [Assignment: organization-defined policy, procedures, prerequisites, and criteria];
    - **g.** Monitor the use of accounts;
    - **h.** Notify account managers and [Assignment: organization-defined personnel or roles] within:
        - **1.** [Assignment: organization-defined time period] when accounts are no longer required;
        - **2.** [Assignment: organization-defined time period] when users are terminated or transferred; and
        - **3.** [Assignment: organization-defined time period] when system usage or need-to-know changes for an individual;
    - **i.** Authorize access to the system based on:
        - **1.** A valid access authorization;
        - **2.** Intended system usage; and
        - **3.** [Assignment: organization-defined attributes (as required)];
    - **j.** Review accounts for compliance with account management requirements [Assignment: organization-defined frequency];
    - **k.** Establish and implement a process for changing shared or group account authenticators (if deployed) when individuals are removed from the group; and
    - **l.** Align account management processes with personnel termination and transfer processes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2)

---

## AC-02 (01) (Automated System Account Management) { #ac-02-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Support the management of system accounts using [Assignment: organization-defined automated mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-1)

---

## AC-02 (02) (Automated Temporary and Emergency Account Management) { #ac-02-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Automatically [Selection: one of: remove; disable] temporary and emergency accounts after [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-2)

---

## AC-02 (03) (Disable Accounts) { #ac-02-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Disable accounts within [Assignment: organization-defined time period] when the accounts:
    
    - **(a)** Have expired;
    - **(b)** Are no longer associated with a user or individual;
    - **(c)** Are in violation of organizational policy; or
    - **(d)** Have been inactive for [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-3)

---

## AC-02 (04) (Automated Audit Actions) { #ac-02-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Automatically audit account creation, modification, enabling, disabling, and removal actions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-4)

---

## AC-02 (05) (Inactivity Logout) { #ac-02-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require that users log out when [Assignment: organization-defined time period of expected inactivity or description of when to log out].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-5)

---

## AC-02 (06) (Dynamic Privilege Management) { #ac-02-06 }

!!! quote ""
    Implement [Assignment: organization-defined dynamic privilege management capabilities].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-6)

---

## AC-02 (07) (Privileged User Accounts) { #ac-02-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Establish and administer privileged user accounts in accordance with [Selection: one of: a role-based access scheme; an attribute-based access scheme];
    - **(b)** Monitor privileged role or attribute assignments;
    - **(c)** Monitor changes to roles or attributes; and
    - **(d)** Revoke access when privileged role or attribute assignments are no longer appropriate.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-7)

---

## AC-02 (08) (Dynamic Account Management) { #ac-02-08 }

!!! quote ""
    Create, activate, manage, and deactivate [Assignment: organization-defined system accounts] dynamically.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-8)

---

## AC-02 (09) (Restrictions on Use of Shared and Group Accounts) { #ac-02-09 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Only permit the use of shared and group accounts that meet [Assignment: organization-defined conditions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-9)

---

## AC-02 (11) (Usage Conditions) { #ac-02-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Enforce [Assignment: organization-defined circumstances and/or usage conditions] for [Assignment: organization-defined system accounts].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-11)

---

## AC-02 (12) (Account Monitoring for Atypical Usage) { #ac-02-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Monitor system accounts for [Assignment: organization-defined atypical usage]; and
    - **(b)** Report atypical usage of system accounts to [Assignment: organization-defined personnel or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-12)

---

## AC-02 (13) (Disable Accounts for High-risk Individuals) { #ac-02-13 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Disable accounts of individuals within [Assignment: organization-defined time period] of discovery of [Assignment: organization-defined significant risks].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-2-13)

---

## AC-03 (Access Enforcement) { #ac-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Enforce approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3)

---

## AC-03 (02) (Dual Authorization) { #ac-03-02 }

!!! quote ""
    Enforce dual authorization for [Assignment: organization-defined privileged commands and/or other actions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-2)

---

## AC-03 (03) (Mandatory Access Control) { #ac-03-03 }

!!! quote ""
    Enforce [Assignment: organization-defined mandatory access control policy] over the set of covered subjects and objects specified in the policy, and where the policy:
    
    - **(a)** Is uniformly enforced across the covered subjects and objects within the system;
    - **(b)** Specifies that a subject that has been granted access to information is constrained from doing any of the following;
        - **(1)** Passing the information to unauthorized subjects or objects;
        - **(2)** Granting its privileges to other subjects;
        - **(3)** Changing one or more security attributes (specified by the policy) on subjects, objects, the system, or system components;
        - **(4)** Choosing the security attributes and attribute values (specified by the policy) to be associated with newly created or modified objects; and
        - **(5)** Changing the rules governing access control; and
    - **(c)** Specifies that [Assignment: organization-defined subjects] may explicitly be granted [Assignment: organization-defined privileges] such that they are not limited by any defined subset (or all) of the above constraints.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-3)

---

## AC-03 (04) (Discretionary Access Control) { #ac-03-04 }

!!! quote ""
    Enforce [Assignment: organization-defined discretionary access control policy] over the set of covered subjects and objects specified in the policy, and where the policy specifies that a subject that has been granted access to information can do one or more of the following:
    
    - **(a)** Pass the information to any other subjects or objects;
    - **(b)** Grant its privileges to other subjects;
    - **(c)** Change security attributes on subjects, objects, the system, or the system’s components;
    - **(d)** Choose the security attributes to be associated with newly created or revised objects; or
    - **(e)** Change the rules governing access control.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-4)

---

## AC-03 (05) (Security-relevant Information) { #ac-03-05 }

!!! quote ""
    Prevent access to [Assignment: organization-defined security-relevant information] except during secure, non-operable system states.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-5)

---

## AC-03 (07) (Role-based Access Control) { #ac-03-07 }

!!! quote ""
    Enforce a role-based access control policy over defined subjects and objects and control access based upon [Assignment: organization-defined roles and users authorized to assume such roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-7)

---

## AC-03 (08) (Revocation of Access Authorizations) { #ac-03-08 }

!!! quote ""
    Enforce the revocation of access authorizations resulting from changes to the security attributes of subjects and objects based on [Assignment: organization-defined rules].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-8)

---

## AC-03 (09) (Controlled Release) { #ac-03-09 }

!!! quote ""
    Release information outside of the system only if:
    
    - **(a)** The receiving [Assignment: organization-defined system or system component] provides [Assignment: organization-defined controls]; and
    - **(b)** [Assignment: organization-defined controls] are used to validate the appropriateness of the information designated for release.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-9)

---

## AC-03 (10) (Audited Override of Access Control Mechanisms) { #ac-03-10 }

!!! quote ""
    Employ an audited override of automated access control mechanisms under [Assignment: organization-defined conditions] by [Assignment: organization-defined roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-10)

---

## AC-03 (11) (Restrict Access to Specific Information Types) { #ac-03-11 }

!!! quote ""
    Restrict access to data repositories containing [Assignment: organization-defined information types].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-11)

---

## AC-03 (12) (Assert and Enforce Application Access) { #ac-03-12 }

!!! quote ""
    - **(a)** Require applications to assert, as part of the installation process, the access needed to the following system applications and functions: [Assignment: organization-defined system applications and functions];
    - **(b)** Provide an enforcement mechanism to prevent unauthorized access; and
    - **(c)** Approve access changes after initial installation of the application.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-12)

---

## AC-03 (13) (Attribute-based Access Control) { #ac-03-13 }

!!! quote ""
    Enforce attribute-based access control policy over defined subjects and objects and control access based upon [Assignment: organization-defined attributes].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-13)

---

## AC-03 (14) (Individual Access) { #ac-03-14 }

!!! quote ""
    Provide [Assignment: organization-defined mechanisms] to enable individuals to have access to the following elements of their personally identifiable information: [Assignment: organization-defined elements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-14)

---

## AC-03 (15) (Discretionary and Mandatory Access Control) { #ac-03-15 }

!!! quote ""
    - **(a)** Enforce [Assignment: organization-defined mandatory access control policy] over the set of covered subjects and objects specified in the policy; and
    - **(b)** Enforce [Assignment: organization-defined discretionary access control policy] over the set of covered subjects and objects specified in the policy.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-3-15)

---

## AC-04 (Information Flow Enforcement) { #ac-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Enforce approved authorizations for controlling the flow of information within the system and between connected systems based on [Assignment: organization-defined information flow control policies].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4)

---

## AC-04 (01) (Object Security and Privacy Attributes) { #ac-04-01 }

!!! quote ""
    Use [Assignment: organization-defined security and privacy attributes] associated with [Assignment: organization-defined information, source, and destination objects] to enforce [Assignment: organization-defined information flow control policies] as a basis for flow control decisions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-1)

---

## AC-04 (02) (Processing Domains) { #ac-04-02 }

!!! quote ""
    Use protected processing domains to enforce [Assignment: organization-defined information flow control policies] as a basis for flow control decisions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-2)

---

## AC-04 (03) (Dynamic Information Flow Control) { #ac-04-03 }

!!! quote ""
    Enforce [Assignment: organization-defined information flow control policies].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-3)

---

## AC-04 (04) (Flow Control of Encrypted Information) { #ac-04-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent encrypted information from bypassing [Assignment: organization-defined information flow control mechanisms] by [Selection: one or more of: decrypting the information; blocking the flow of the encrypted information; terminating communications sessions attempting to pass encrypted information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-4)

---

## AC-04 (05) (Embedded Data Types) { #ac-04-05 }

!!! quote ""
    Enforce [Assignment: organization-defined limitations] on embedding data types within other data types.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-5)

---

## AC-04 (06) (Metadata) { #ac-04-06 }

!!! quote ""
    Enforce information flow control based on [Assignment: organization-defined metadata].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-6)

---

## AC-04 (07) (One-way Flow Mechanisms) { #ac-04-07 }

!!! quote ""
    Enforce one-way information flows through hardware-based flow control mechanisms.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-7)

---

## AC-04 (08) (Security and Privacy Policy Filters) { #ac-04-08 }

!!! quote ""
    - **(a)** Enforce information flow control using [Assignment: organization-defined security or privacy policy filters] as a basis for flow control decisions for [Assignment: organization-defined information flows]; and
    - **(b)** [Selection: one or more of: block; strip; modify; quarantine] data after a filter processing failure in accordance with [Assignment: organization-defined security or privacy policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-8)

---

## AC-04 (09) (Human Reviews) { #ac-04-09 }

!!! quote ""
    Enforce the use of human reviews for [Assignment: organization-defined information flows] under the following conditions: [Assignment: organization-defined conditions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-9)

---

## AC-04 (10) (Enable and Disable Security or Privacy Policy Filters) { #ac-04-10 }

!!! quote ""
    Provide the capability for privileged administrators to enable and disable [Assignment: organization-defined security or privacy policy filters] under the following conditions: [Assignment: organization-defined conditions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-10)

---

## AC-04 (11) (Configuration of Security or Privacy Policy Filters) { #ac-04-11 }

!!! quote ""
    Provide the capability for privileged administrators to configure [Assignment: organization-defined security or privacy policy filters] to support different security or privacy policies.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-11)

---

## AC-04 (12) (Data Type Identifiers) { #ac-04-12 }

!!! quote ""
    When transferring information between different security domains, use [Assignment: organization-defined data type identifiers] to validate data essential for information flow decisions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-12)

---

## AC-04 (13) (Decomposition into Policy-relevant Subcomponents) { #ac-04-13 }

!!! quote ""
    When transferring information between different security domains, decompose information into [Assignment: organization-defined policy-relevant subcomponents] for submission to policy enforcement mechanisms.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-13)

---

## AC-04 (14) (Security or Privacy Policy Filter Constraints) { #ac-04-14 }

!!! quote ""
    When transferring information between different security domains, implement [Assignment: organization-defined security or privacy policy filters] requiring fully enumerated formats that restrict data structure and content.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-14)

---

## AC-04 (15) (Detection of Unsanctioned Information) { #ac-04-15 }

!!! quote ""
    When transferring information between different security domains, examine the information for the presence of [Assignment: organization-defined unsanctioned information] and prohibit the transfer of such information in accordance with the [Assignment: organization-defined security or privacy policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-15)

---

## AC-04 (17) (Domain Authentication) { #ac-04-17 }

!!! quote ""
    Uniquely identify and authenticate source and destination points by [Selection: one or more of: organization, system, application, service, individual] for information transfer.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-17)

---

## AC-04 (19) (Validation of Metadata) { #ac-04-19 }

!!! quote ""
    When transferring information between different security domains, implement [Assignment: organization-defined security or privacy policy filters] on metadata.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-19)

---

## AC-04 (20) (Approved Solutions) { #ac-04-20 }

!!! quote ""
    Employ [Assignment: organization-defined solutions in approved configurations] to control the flow of [Assignment: organization-defined information] across security domains.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-20)

---

## AC-04 (21) (Physical or Logical Separation of Information Flows) { #ac-04-21 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Separate information flows logically or physically using [Assignment: organization-defined mechanisms and/or techniques] to accomplish [Assignment: organization-defined required separations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-21)

---

## AC-04 (22) (Access Only) { #ac-04-22 }

!!! quote ""
    Provide access from a single device to computing platforms, applications, or data residing in multiple different security domains, while preventing information flow between the different security domains.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-22)

---

## AC-04 (23) (Modify Non-releasable Information) { #ac-04-23 }

!!! quote ""
    When transferring information between different security domains, modify non-releasable information by implementing [Assignment: organization-defined modification action].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-23)

---

## AC-04 (24) (Internal Normalized Format) { #ac-04-24 }

!!! quote ""
    When transferring information between different security domains, parse incoming data into an internal normalized format and regenerate the data to be consistent with its intended specification.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-24)

---

## AC-04 (25) (Data Sanitization) { #ac-04-25 }

!!! quote ""
    When transferring information between different security domains, sanitize data to minimize [Selection: one or more of: delivery of malicious content, command and control of malicious code, malicious code augmentation, and steganography-encoded data; spillage of sensitive information] in accordance with [Assignment: organization-defined policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-25)

---

## AC-04 (26) (Audit Filtering Actions) { #ac-04-26 }

!!! quote ""
    When transferring information between different security domains, record and audit content filtering actions and results for the information being filtered.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-26)

---

## AC-04 (27) (Redundant/Independent Filtering Mechanisms) { #ac-04-27 }

!!! quote ""
    When transferring information between different security domains, implement content filtering solutions that provide redundant and independent filtering mechanisms for each data type.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-27)

---

## AC-04 (28) (Linear Filter Pipelines) { #ac-04-28 }

!!! quote ""
    When transferring information between different security domains, implement a linear content filter pipeline that is enforced with discretionary and mandatory access controls.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-28)

---

## AC-04 (29) (Filter Orchestration Engines) { #ac-04-29 }

!!! quote ""
    When transferring information between different security domains, employ content filter orchestration engines to ensure that:
    
    - **(a)** Content filtering mechanisms successfully complete execution without errors; and
    - **(b)** Content filtering actions occur in the correct order and comply with [Assignment: organization-defined policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-29)

---

## AC-04 (30) (Filter Mechanisms Using Multiple Processes) { #ac-04-30 }

!!! quote ""
    When transferring information between different security domains, implement content filtering mechanisms using multiple processes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-30)

---

## AC-04 (31) (Failed Content Transfer Prevention) { #ac-04-31 }

!!! quote ""
    When transferring information between different security domains, prevent the transfer of failed content to the receiving domain.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-31)

---

## AC-04 (32) (Process Requirements for Information Transfer) { #ac-04-32 }

!!! quote ""
    When transferring information between different security domains, the process that transfers information between filter pipelines:
    
    - **(a)** Does not filter message content;
    - **(b)** Validates filtering metadata;
    - **(c)** Ensures the content associated with the filtering metadata has successfully completed filtering; and
    - **(d)** Transfers the content to the destination filter pipeline.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-4-32)

---

## AC-05 (Separation of Duties) { #ac-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Identify and document [Assignment: organization-defined duties of individuals]; and
    - **b.** Define system access authorizations to support separation of duties.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-5)

---

## AC-06 (Least Privilege) { #ac-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) that are necessary to accomplish assigned organizational tasks.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6)

---

## AC-06 (01) (Authorize Access to Security Functions) { #ac-06-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Authorize access for [Assignment: organization-defined individuals and roles] to:
    
    - **(a)** [Assignment: organization-defined security functions (deployed in hardware, software, and firmware)]; and
    - **(b)** [Assignment: organization-defined security-relevant information].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.01_odp.02` | security functions (deployed in hardware) | all functions not publicly accessible |
        | `ac-06.01_odp.05` | security-relevant information | all security-relevant information not publicly available |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-1)

---

## AC-06 (02) (Non-privileged Access for Nonsecurity Functions) { #ac-06-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require that users of system accounts (or roles) with access to [Assignment: organization-defined security functions or security-relevant information] use non-privileged accounts or roles, when accessing nonsecurity functions.

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.02_odp` | security functions or security-relevant information | all security functions |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-2)

---

## AC-06 (03) (Network Access to Privileged Commands) { #ac-06-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Authorize network access to [Assignment: organization-defined privileged commands] only for [Assignment: organization-defined compelling operational needs] and document the rationale for such access in the security plan for the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-3)

---

## AC-06 (04) (Separate Processing Domains) { #ac-06-04 }

!!! quote ""
    Provide separate processing domains to enable finer-grained allocation of user privileges.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-4)

---

## AC-06 (05) (Privileged Accounts) { #ac-06-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Restrict privileged accounts on the system to [Assignment: organization-defined personnel or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-5)

---

## AC-06 (06) (Privileged Access by Non-organizational Users) { #ac-06-06 }

!!! quote ""
    Prohibit privileged access to the system by non-organizational users.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-6)

---

## AC-06 (07) (Review of User Privileges) { #ac-06-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Review [Assignment: organization-defined frequency] the privileges assigned to [Assignment: organization-defined roles and classes] to validate the need for such privileges; and
    - **(b)** Reassign or remove privileges, if necessary, to correctly reflect organizational mission and business needs.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-7)

---

## AC-06 (08) (Privilege Levels for Code Execution) { #ac-06-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent the following software from executing at higher privilege levels than users executing the software: [Assignment: organization-defined software].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ac-06.08_odp` | software | any software except software explicitly documented |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-8)

---

## AC-06 (09) (Log Use of Privileged Functions) { #ac-06-09 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Log the execution of privileged functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-9)

---

## AC-06 (10) (Prohibit Non-privileged Users from Executing Privileged Functions) { #ac-06-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prevent non-privileged users from executing privileged functions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-6-10)

---

## AC-07 (Unsuccessful Logon Attempts) { #ac-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Enforce a limit of [Assignment: organization-defined number] consecutive invalid logon attempts by a user during a [Assignment: organization-defined time period]; and
    - **b.** Automatically [Selection: one or more of: lock the account or node for; lock the account or node until released by an administrator; delay next logon prompt per; notify system administrator; take other] when the maximum number of unsuccessful attempts is exceeded.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-7)

---

## AC-07 (02) (Purge or Wipe Mobile Device) { #ac-07-02 }

!!! quote ""
    Purge or wipe information from [Assignment: organization-defined mobile devices] based on [Assignment: organization-defined purging or wiping requirements and techniques] after [Assignment: organization-defined number] consecutive, unsuccessful device logon attempts.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-7-2)

---

## AC-07 (03) (Biometric Attempt Limiting) { #ac-07-03 }

!!! quote ""
    Limit the number of unsuccessful biometric logon attempts to [Assignment: organization-defined number].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-7-3)

---

## AC-07 (04) (Use of Alternate Authentication Factor) { #ac-07-04 }

!!! quote ""
    - **(a)** Allow the use of [Assignment: organization-defined authentication factors] that are different from the primary authentication factors after the number of organization-defined consecutive invalid logon attempts have been exceeded; and
    - **(b)** Enforce a limit of [Assignment: organization-defined number] consecutive invalid logon attempts through use of the alternative factors by a user during a [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-7-4)

---

## AC-08 (System Use Notification) { #ac-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Display [Assignment: organization-defined system use notification] to users before granting access to the system that provides privacy and security notices consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines and state that:
        - **1.** Users are accessing a U.S. Government system;
        - **2.** System usage may be monitored, recorded, and subject to audit;
        - **3.** Unauthorized use of the system is prohibited and subject to criminal and civil penalties; and
        - **4.** Use of the system indicates consent to monitoring and recording;
    - **b.** Retain the notification message or banner on the screen until users acknowledge the usage conditions and take explicit actions to log on to or further access the system; and
    - **c.** For publicly accessible systems:
        - **1.** Display system use information [Assignment: organization-defined conditions], before granting further access to the publicly accessible system;
        - **2.** Display references, if any, to monitoring, recording, or auditing that are consistent with privacy accommodations for such systems that generally prohibit those activities; and
        - **3.** Include a description of the authorized uses of the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-8)

---

## AC-09 (Previous Logon Notification) { #ac-09 }

!!! quote ""
    Notify the user, upon successful logon to the system, of the date and time of the last logon.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-9)

---

## AC-09 (01) (Unsuccessful Logons) { #ac-09-01 }

!!! quote ""
    Notify the user, upon successful logon, of the number of unsuccessful logon attempts since the last successful logon.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-9-1)

---

## AC-09 (02) (Successful and Unsuccessful Logons) { #ac-09-02 }

!!! quote ""
    Notify the user, upon successful logon, of the number of [Selection: one of: successful logons; unsuccessful logon attempts; both] during [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-9-2)

---

## AC-09 (03) (Notification of Account Changes) { #ac-09-03 }

!!! quote ""
    Notify the user, upon successful logon, of changes to [Assignment: organization-defined security-related characteristics or parameters] during [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-9-3)

---

## AC-09 (04) (Additional Logon Information) { #ac-09-04 }

!!! quote ""
    Notify the user, upon successful logon, of the following additional information: [Assignment: organization-defined additional information].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-9-4)

---

## AC-10 (Concurrent Session Control) { #ac-10 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Limit the number of concurrent sessions for each [Assignment: organization-defined account and/or account types] to [Assignment: organization-defined number].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-10)

---

## AC-11 (Device Lock) { #ac-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Prevent further access to the system by [Selection: one or more of: initiating a device lock after of inactivity; requiring the user to initiate a device lock before leaving the system unattended]; and
    - **b.** Retain the device lock until the user reestablishes access using established identification and authentication procedures.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-11)

---

## AC-11 (01) (Pattern-hiding Displays) { #ac-11-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Conceal, via the device lock, information previously visible on the display with a publicly viewable image.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-11-1)

---

## AC-12 (Session Termination) { #ac-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Automatically terminate a user session after [Assignment: organization-defined conditions or trigger events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-12)

---

## AC-12 (01) (User-initiated Logouts) { #ac-12-01 }

!!! quote ""
    Provide a logout capability for user-initiated communications sessions whenever authentication is used to gain access to [Assignment: organization-defined information resources].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-12-1)

---

## AC-12 (02) (Termination Message) { #ac-12-02 }

!!! quote ""
    Display an explicit logout message to users indicating the termination of authenticated communications sessions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-12-2)

---

## AC-12 (03) (Timeout Warning Message) { #ac-12-03 }

!!! quote ""
    Display an explicit message to users indicating that the session will end in [Assignment: organization-defined time].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-12-3)

---

## AC-14 (Permitted Actions Without Identification or Authentication) { #ac-14 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Identify [Assignment: organization-defined user actions] that can be performed on the system without identification or authentication consistent with organizational mission and business functions; and
    - **b.** Document and provide supporting rationale in the security plan for the system, user actions not requiring identification or authentication.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-14)

---

## AC-16 (Security and Privacy Attributes) { #ac-16 }

!!! quote ""
    - **a.** Provide the means to associate [Assignment: organization-defined types of security and privacy attributes] with [Assignment: organization-defined security and privacy attribute values] for information in storage, in process, and/or in transmission;
    - **b.** Ensure that the attribute associations are made and retained with the information;
    - **c.** Establish the following permitted security and privacy attributes from the attributes defined in AC-16a for [Assignment: organization-defined systems]: [Assignment: organization-defined security and privacy attributes];
    - **d.** Determine the following permitted attribute values or ranges for each of the established attributes: [Assignment: organization-defined attribute values or ranges];
    - **e.** Audit changes to attributes; and
    - **f.** Review [Assignment: organization-defined security and privacy attributes] for applicability [Assignment: organization-defined frequency].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16)

---

## AC-16 (01) (Dynamic Attribute Association) { #ac-16-01 }

!!! quote ""
    Dynamically associate security and privacy attributes with [Assignment: organization-defined subjects and objects] in accordance with the following security and privacy policies as information is created and combined: [Assignment: organization-defined security and privacy policies].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-1)

---

## AC-16 (02) (Attribute Value Changes by Authorized Individuals) { #ac-16-02 }

!!! quote ""
    Provide authorized individuals (or processes acting on behalf of individuals) the capability to define or change the value of associated security and privacy attributes.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-2)

---

## AC-16 (03) (Maintenance of Attribute Associations by System) { #ac-16-03 }

!!! quote ""
    Maintain the association and integrity of [Assignment: organization-defined security and privacy attributes] to [Assignment: organization-defined subjects and objects].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-3)

---

## AC-16 (04) (Association of Attributes by Authorized Individuals) { #ac-16-04 }

!!! quote ""
    Provide the capability to associate [Assignment: organization-defined security and privacy attributes] with [Assignment: organization-defined subjects and objects] by authorized individuals (or processes acting on behalf of individuals).

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-4)

---

## AC-16 (05) (Attribute Displays on Objects to Be Output) { #ac-16-05 }

!!! quote ""
    Display security and privacy attributes in human-readable form on each object that the system transmits to output devices to identify [Assignment: organization-defined instructions] using [Assignment: organization-defined naming conventions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-5)

---

## AC-16 (06) (Maintenance of Attribute Association) { #ac-16-06 }

!!! quote ""
    Require personnel to associate and maintain the association of [Assignment: organization-defined security and privacy attributes] with [Assignment: organization-defined subjects and objects] in accordance with [Assignment: organization-defined security and privacy policies].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-6)

---

## AC-16 (07) (Consistent Attribute Interpretation) { #ac-16-07 }

!!! quote ""
    Provide a consistent interpretation of security and privacy attributes transmitted between distributed system components.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-7)

---

## AC-16 (08) (Association Techniques and Technologies) { #ac-16-08 }

!!! quote ""
    Implement [Assignment: organization-defined techniques and technologies] in associating security and privacy attributes to information.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-8)

---

## AC-16 (09) (Attribute Reassignment — Regrading Mechanisms) { #ac-16-09 }

!!! quote ""
    Change security and privacy attributes associated with information only via regrading mechanisms validated using [Assignment: organization-defined techniques or procedures].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-9)

---

## AC-16 (10) (Attribute Configuration by Authorized Individuals) { #ac-16-10 }

!!! quote ""
    Provide authorized individuals the capability to define or change the type and value of security and privacy attributes available for association with subjects and objects.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-16-10)

---

## AC-17 (Remote Access) { #ac-17 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Establish and document usage restrictions, configuration/connection requirements, and implementation guidance for each type of remote access allowed; and
    - **b.** Authorize each type of remote access to the system prior to allowing such connections.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17)

---

## AC-17 (01) (Monitoring and Control) { #ac-17-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ automated mechanisms to monitor and control remote access methods.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-1)

---

## AC-17 (02) (Protection of Confidentiality and Integrity Using Encryption) { #ac-17-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement cryptographic mechanisms to protect the confidentiality and integrity of remote access sessions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-2)

---

## AC-17 (03) (Managed Access Control Points) { #ac-17-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Route remote accesses through authorized and managed network access control points.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-3)

---

## AC-17 (04) (Privileged Commands and Access) { #ac-17-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Authorize the execution of privileged commands and access to security-relevant information via remote access only in a format that provides assessable evidence and for the following needs: [Assignment: organization-defined needs]; and
    - **(b)** Document the rationale for remote access in the security plan for the system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-4)

---

## AC-17 (06) (Protection of Mechanism Information) { #ac-17-06 }

!!! quote ""
    Protect information about remote access mechanisms from unauthorized use and disclosure.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-6)

---

## AC-17 (09) (Disconnect or Disable Access) { #ac-17-09 }

!!! quote ""
    Provide the capability to disconnect or disable remote access to the system within [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-9)

---

## AC-17 (10) (Authenticate Remote Commands) { #ac-17-10 }

!!! quote ""
    Implement [Assignment: organization-defined mechanisms] to authenticate [Assignment: organization-defined remote commands].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-17-10)

---

## AC-18 (Wireless Access) { #ac-18 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Establish configuration requirements, connection requirements, and implementation guidance for each type of wireless access; and
    - **b.** Authorize each type of wireless access to the system prior to allowing such connections.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-18)

---

## AC-18 (01) (Authentication and Encryption) { #ac-18-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Protect wireless access to the system using authentication of [Selection: one or more of: users; devices] and encryption.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-18-1)

---

## AC-18 (03) (Disable Wireless Networking) { #ac-18-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Disable, when not intended for use, wireless networking capabilities embedded within system components prior to issuance and deployment.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-18-3)

---

## AC-18 (04) (Restrict Configurations by Users) { #ac-18-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Identify and explicitly authorize users allowed to independently configure wireless networking capabilities.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-18-4)

---

## AC-18 (05) (Antennas and Transmission Power Levels) { #ac-18-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Select radio antennas and calibrate transmission power levels to reduce the probability that signals from wireless access points can be received outside of organization-controlled boundaries.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-18-5)

---

## AC-19 (Access Control for Mobile Devices) { #ac-19 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Establish configuration requirements, connection requirements, and implementation guidance for organization-controlled mobile devices, to include when such devices are outside of controlled areas; and
    - **b.** Authorize the connection of mobile devices to organizational systems.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-19)

---

## AC-19 (04) (Restrictions for Classified Information) { #ac-19-04 }

!!! quote ""
    - **(a)** Prohibit the use of unclassified mobile devices in facilities containing systems processing, storing, or transmitting classified information unless specifically permitted by the authorizing official; and
    - **(b)** Enforce the following restrictions on individuals permitted by the authorizing official to use unclassified mobile devices in facilities containing systems processing, storing, or transmitting classified information:
        - **(1)** Connection of unclassified mobile devices to classified systems is prohibited;
        - **(2)** Connection of unclassified mobile devices to unclassified systems requires approval from the authorizing official;
        - **(3)** Use of internal or external modems or wireless interfaces within the unclassified mobile devices is prohibited; and
        - **(4)** Unclassified mobile devices and the information stored on those devices are subject to random reviews and inspections by [Assignment: organization-defined security officials], and if classified information is found, the incident handling policy is followed.
    - **(c)** Restrict the connection of classified mobile devices to classified systems in accordance with [Assignment: organization-defined security policies].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-19-4)

---

## AC-19 (05) (Full Device or Container-based Encryption) { #ac-19-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Employ [Selection: one of: full-device encryption; container-based encryption] to protect the confidentiality and integrity of information on [Assignment: organization-defined mobile devices].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-19-5)

---

## AC-20 (Use of External Systems) { #ac-20 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** [Selection: one or more of: establish; identify], consistent with the trust relationships established with other organizations owning, operating, and/or maintaining external systems, allowing authorized individuals to:
        - **1.** Access the system from external systems; and
        - **2.** Process, store, or transmit organization-controlled information using external systems; or
    - **b.** Prohibit the use of [Assignment: organization-defined prohibited types of external systems].

    ---

    !!! info ""
        **FedRAMP Guidance**

        The interrelated controls of AC-20, CA-3, and SA-9 should be differentiated as follows:

        AC-20 describes system access to and from external systems.

        CA-3 describes documentation of an agreement between the respective system owners when data is exchanged between the CSO and an external system.

        SA-9 describes the responsibilities of external system owners. These responsibilities would typically be captured in the agreement required by CA-3.

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20)

---

## AC-20 (01) (Limits on Authorized Use) { #ac-20-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Permit authorized individuals to use an external system to access the system or to process, store, or transmit organization-controlled information only after:
    
    - **(a)** Verification of the implementation of controls on the external system as specified in the organization’s security and privacy policies and security and privacy plans; or
    - **(b)** Retention of approved system connection or processing agreements with the organizational entity hosting the external system.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20-1)

---

## AC-20 (02) (Portable Storage Devices — Restricted Use) { #ac-20-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Restrict the use of organization-controlled portable storage devices by authorized individuals on external systems using [Assignment: organization-defined restrictions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20-2)

---

## AC-20 (03) (Non-organizationally Owned Systems — Restricted Use) { #ac-20-03 }

!!! quote ""
    Restrict the use of non-organizationally owned systems or system components to process, store, or transmit organizational information using [Assignment: organization-defined restrictions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20-3)

---

## AC-20 (04) (Network Accessible Storage Devices — Prohibited Use) { #ac-20-04 }

!!! quote ""
    Prohibit the use of [Assignment: organization-defined network-accessible storage devices] in external systems.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20-4)

---

## AC-20 (05) (Portable Storage Devices — Prohibited Use) { #ac-20-05 }

!!! quote ""
    Prohibit the use of organization-controlled portable storage devices by authorized individuals on external systems.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-20-5)

---

## AC-21 (Information Sharing) { #ac-21 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Enable authorized users to determine whether access authorizations assigned to a sharing partner match the information’s access and use restrictions for [Assignment: organization-defined information-sharing circumstances]; and
    - **b.** Employ [Assignment: organization-defined automated mechanisms] to assist users in making information sharing and collaboration decisions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-21)

---

## AC-21 (01) (Automated Decision Support) { #ac-21-01 }

!!! quote ""
    Employ [Assignment: organization-defined automated mechanisms] to enforce information-sharing decisions by authorized users based on access authorizations of sharing partners and access restrictions on information to be shared.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-21-1)

---

## AC-21 (02) (Information Search and Retrieval) { #ac-21-02 }

!!! quote ""
    Implement information search and retrieval services that enforce [Assignment: organization-defined information-sharing restrictions].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-21-2)

---

## AC-22 (Publicly Accessible Content) { #ac-22 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Designate individuals authorized to make information publicly accessible;
    - **b.** Train authorized individuals to ensure that publicly accessible information does not contain nonpublic information;
    - **c.** Review the proposed content of information prior to posting onto the publicly accessible system to ensure that nonpublic information is not included; and
    - **d.** Review the content on the publicly accessible system for nonpublic information [Assignment: organization-defined frequency] and remove such information, if discovered.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-22)

---

## AC-23 (Data Mining Protection) { #ac-23 }

!!! quote ""
    Employ [Assignment: organization-defined techniques] for [Assignment: organization-defined data storage objects] to detect and protect against unauthorized data mining.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-23)

---

## AC-24 (Access Control Decisions) { #ac-24 }

!!! quote ""
    [Selection: one or more of: establish procedures; implement mechanisms] to ensure [Assignment: organization-defined access control decisions] are applied to each access request prior to access enforcement.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-24)

---

## AC-24 (01) (Transmit Access Authorization Information) { #ac-24-01 }

!!! quote ""
    Transmit [Assignment: organization-defined access authorization information] using [Assignment: organization-defined controls] to [Assignment: organization-defined systems] that enforce access control decisions.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-24-1)

---

## AC-24 (02) (No User or Process Identity) { #ac-24-02 }

!!! quote ""
    Enforce access control decisions based on [Assignment: organization-defined security or privacy attributes] that do not include the identity of the user or process acting on behalf of the user.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-24-2)

---

## AC-25 (Reference Monitor) { #ac-25 }

!!! quote ""
    Implement a reference monitor for [Assignment: organization-defined access control policies] that is tamperproof, always invoked, and small enough to be subject to analysis and testing, the completeness of which can be assured.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ac-25)

---
