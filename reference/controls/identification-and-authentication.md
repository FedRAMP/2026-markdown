---
tags:
  - Rev5
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Identification and Authentication (IA)

This page contains all **59** controls and control enhancements in the Identification and Authentication (IA) family from the vendored NIST SP 800-53 Revision 5 OSCAL catalog.

!!! info "Official NIST OSCAL source"
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

## IA-01 (Policy and Procedures) { #ia-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Develop, document, and disseminate to [Assignment: organization-defined personnel or roles]:
        - **1.** [Selection: one or more of: organization-level; mission/business process-level; system-level] identification and authentication policy that:
            - **(a)** Addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
            - **(b)** Is consistent with applicable laws, executive orders, directives, regulations, policies, standards, and guidelines; and
        - **2.** Procedures to facilitate the implementation of the identification and authentication policy and the associated identification and authentication controls;
    - **b.** Designate an [Assignment: organization-defined official] to manage the development, documentation, and dissemination of the identification and authentication policy and procedures; and
    - **c.** Review and update the current identification and authentication:
        - **1.** Policy [Assignment: organization-defined frequency] and following [Assignment: organization-defined events]; and
        - **2.** Procedures [Assignment: organization-defined frequency] and following [Assignment: organization-defined events].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-1)

---

## IA-02 (Identification and Authentication (Organizational Users)) { #ia-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2)

---

## IA-02 (01) (Multi-factor Authentication to Privileged Accounts) { #ia-02-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement multi-factor authentication for access to privileged accounts.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-1)

---

## IA-02 (02) (Multi-factor Authentication to Non-privileged Accounts) { #ia-02-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement multi-factor authentication for access to non-privileged accounts.

    ---

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-2)

---

## IA-02 (05) (Individual Authentication with Group Authentication) { #ia-02-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    When shared accounts or authenticators are employed, require users to be individually authenticated before granting access to the shared accounts or resources.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-5)

---

## IA-02 (06) (Access to Accounts —separate Device) { #ia-02-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement multi-factor authentication for [Selection: one or more of: local; network; remote] access to [Selection: one or more of: privileged accounts; non-privileged accounts] such that:
    
    - **(a)** One of the factors is provided by a device separate from the system gaining access; and
    - **(b)** The device meets [Assignment: organization-defined strength of mechanism requirements].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.06_odp.01` | one or more of: local; network; remote | local, network and remote |
        | `ia-02.06_odp.02` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-6)

---

## IA-02 (08) (Access to Accounts — Replay Resistant) { #ia-02-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement replay-resistant authentication mechanisms for access to [Selection: one or more of: privileged accounts; non-privileged accounts].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.08_odp` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-8)

---

## IA-02 (10) (Single Sign-on) { #ia-02-10 }

!!! quote ""
    Provide a single sign-on capability for [Assignment: organization-defined system accounts and services].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-10)

---

## IA-02 (12) (Acceptance of PIV Credentials) { #ia-02-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Accept and electronically verify Personal Identity Verification-compliant credentials.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-12)

---

## IA-02 (13) (Out-of-band Authentication) { #ia-02-13 }

!!! quote ""
    Implement the following out-of-band authentication mechanisms under [Assignment: organization-defined conditions]: [Assignment: organization-defined out-of-band authentication].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-2-13)

---

## IA-03 (Device Identification and Authentication) { #ia-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Uniquely identify and authenticate [Assignment: organization-defined devices and/or types of devices] before establishing a [Selection: one or more of: local; remote; network] connection.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-3)

---

## IA-03 (01) (Cryptographic Bidirectional Authentication) { #ia-03-01 }

!!! quote ""
    Authenticate [Assignment: organization-defined devices and/or types of devices] before establishing [Selection: one or more of: local; remote; network] connection using bidirectional authentication that is cryptographically based.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-3-1)

---

## IA-03 (03) (Dynamic Address Allocation) { #ia-03-03 }

!!! quote ""
    - **(a)** Where addresses are allocated dynamically, standardize dynamic address allocation lease information and the lease duration assigned to devices in accordance with [Assignment: organization-defined lease information and lease duration]; and
    - **(b)** Audit lease information when assigned to a device.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-3-3)

---

## IA-03 (04) (Device Attestation) { #ia-03-04 }

!!! quote ""
    Handle device identification and authentication based on attestation by [Assignment: organization-defined configuration management process].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-3-4)

---

## IA-04 (Identifier Management) { #ia-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Manage system identifiers by:
    
    - **a.** Receiving authorization from [Assignment: organization-defined personnel or roles] to assign an individual, group, role, service, or device identifier;
    - **b.** Selecting an identifier that identifies an individual, group, role, service, or device;
    - **c.** Assigning the identifier to the intended individual, group, role, service, or device; and
    - **d.** Preventing reuse of identifiers for [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4)

---

## IA-04 (01) (Prohibit Account Identifiers as Public Identifiers) { #ia-04-01 }

!!! quote ""
    Prohibit the use of system account identifiers that are the same as public identifiers for individual accounts.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-1)

---

## IA-04 (04) (Identify User Status) { #ia-04-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Manage individual identifiers by uniquely identifying each individual as [Assignment: organization-defined characteristics].

    ---

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-04.04_odp` | characteristics | contractors; foreign nationals |

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-4)

---

## IA-04 (05) (Dynamic Management) { #ia-04-05 }

!!! quote ""
    Manage individual identifiers dynamically in accordance with [Assignment: organization-defined dynamic identifier policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-5)

---

## IA-04 (06) (Cross-organization Management) { #ia-04-06 }

!!! quote ""
    Coordinate with the following external organizations for cross-organization management of identifiers: [Assignment: organization-defined external organizations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-6)

---

## IA-04 (08) (Pairwise Pseudonymous Identifiers) { #ia-04-08 }

!!! quote ""
    Generate pairwise pseudonymous identifiers.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-8)

---

## IA-04 (09) (Attribute Maintenance and Protection) { #ia-04-09 }

!!! quote ""
    Maintain the attributes for each uniquely identified individual, device, or service in [Assignment: organization-defined protected central storage].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-4-9)

---

## IA-05 (Authenticator Management) { #ia-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Manage system authenticators by:
    
    - **a.** Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, service, or device receiving the authenticator;
    - **b.** Establishing initial authenticator content for any authenticators issued by the organization;
    - **c.** Ensuring that authenticators have sufficient strength of mechanism for their intended use;
    - **d.** Establishing and implementing administrative procedures for initial authenticator distribution, for lost or compromised or damaged authenticators, and for revoking authenticators;
    - **e.** Changing default authenticators prior to first use;
    - **f.** Changing or refreshing authenticators [Assignment: organization-defined time period by authenticator type] or when [Assignment: organization-defined events] occur;
    - **g.** Protecting authenticator content from unauthorized disclosure and modification;
    - **h.** Requiring individuals to take, and having devices implement, specific controls to protect authenticators; and
    - **i.** Changing authenticators for group or role accounts when membership to those accounts changes.

    ---

    !!! info ""
        === "Class B"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 1. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

        === "Class C"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 2. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

        === "Class D"
            Authenticators must be compliant with NIST SP 800-63-3 Digital Identity Guidelines IAL, AAL, FAL level 3. Link [https://pages.nist.gov/800-63-3](https://pages.nist.gov/800-63-3)

            IA-5 Guidance: SP 800-63C Section 6.2.3 Encrypted Assertion requires that authentication assertions be encrypted when passed through third parties, such as a browser. For example, a SAML assertion can be encrypted using XML-Encryption, or an OpenID Connect ID Token can be encrypted using JSON Web Encryption (JWE).

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5)

---

## IA-05 (01) (Password-based Authentication) { #ia-05-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    For password-based authentication:
    
    - **(a)** Maintain a list of commonly-used, expected, or compromised passwords and update the list [Assignment: organization-defined frequency] and when organizational passwords are suspected to have been compromised directly or indirectly;
    - **(b)** Verify, when users create or update passwords, that the passwords are not found on the list of commonly-used, expected, or compromised passwords in IA-5(1)(a);
    - **(c)** Transmit passwords only over cryptographically-protected channels;
    - **(d)** Store passwords using an approved salted key derivation function, preferably using a keyed hash;
    - **(e)** Require immediate selection of a new password upon account recovery;
    - **(f)** Allow user selection of long passwords and passphrases, including spaces and all printable characters;
    - **(g)** Employ automated tools to assist the user in selecting strong password authenticators; and
    - **(h)** Enforce the following composition and complexity rules: [Assignment: organization-defined composition and complexity rules].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-1)

---

## IA-05 (02) (Public Key-based Authentication) { #ia-05-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** For public key-based authentication:
        - **(1)** Enforce authorized access to the corresponding private key; and
        - **(2)** Map the authenticated identity to the account of the individual or group; and
    - **(b)** When public key infrastructure (PKI) is used:
        - **(1)** Validate certificates by constructing and verifying a certification path to an accepted trust anchor, including checking certificate status information; and
        - **(2)** Implement a local cache of revocation data to support path discovery and validation.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-2)

---

## IA-05 (05) (Change Authenticators Prior to Delivery) { #ia-05-05 }

!!! quote ""
    Require developers and installers of system components to provide unique authenticators or change default authenticators prior to delivery and installation.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-5)

---

## IA-05 (06) (Protection of Authenticators) { #ia-05-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Protect authenticators commensurate with the security category of the information to which use of the authenticator permits access.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-6)

---

## IA-05 (07) (No Embedded Unencrypted Static Authenticators) { #ia-05-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Ensure that unencrypted static authenticators are not embedded in applications or other forms of static storage.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-7)

---

## IA-05 (08) (Multiple System Accounts) { #ia-05-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement [Assignment: organization-defined security controls] to manage the risk of compromise due to individuals having accounts on multiple systems.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-8)

---

## IA-05 (09) (Federated Credential Management) { #ia-05-09 }

!!! quote ""
    Use the following external organizations to federate credentials: [Assignment: organization-defined external organizations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-9)

---

## IA-05 (10) (Dynamic Credential Binding) { #ia-05-10 }

!!! quote ""
    Bind identities and authenticators dynamically using the following rules: [Assignment: organization-defined binding rules].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-10)

---

## IA-05 (12) (Biometric Authentication Performance) { #ia-05-12 }

!!! quote ""
    For biometric-based authentication, employ mechanisms that satisfy the following biometric quality requirements [Assignment: organization-defined biometric quality requirements].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-12)

---

## IA-05 (13) (Expiration of Cached Authenticators) { #ia-05-13 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Prohibit the use of cached authenticators after [Assignment: organization-defined time period].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-13)

---

## IA-05 (14) (Managing Content of PKI Trust Stores) { #ia-05-14 }

!!! quote ""
    For PKI-based authentication, employ an organization-wide methodology for managing the content of PKI trust stores installed across all platforms, including networks, operating systems, browsers, and applications.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-14)

---

## IA-05 (15) (GSA-approved Products and Services) { #ia-05-15 }

!!! quote ""
    Use only General Services Administration-approved products and services for identity, credential, and access management.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-15)

---

## IA-05 (16) (In-person or Trusted External Party Authenticator Issuance) { #ia-05-16 }

!!! quote ""
    Require that the issuance of [Assignment: organization-defined types of and/or specific authenticators] be conducted [Selection: one of: in person; by a trusted external party] before [Assignment: organization-defined registration authority] with authorization by [Assignment: organization-defined personnel or roles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-16)

---

## IA-05 (17) (Presentation Attack Detection for Biometric Authenticators) { #ia-05-17 }

!!! quote ""
    Employ presentation attack detection mechanisms for biometric-based authentication.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-17)

---

## IA-05 (18) (Password Managers) { #ia-05-18 }

!!! quote ""
    - **(a)** Employ [Assignment: organization-defined password managers] to generate and manage passwords; and
    - **(b)** Protect the passwords using [Assignment: organization-defined controls].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-5-18)

---

## IA-06 (Authentication Feedback) { #ia-06 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Obscure feedback of authentication information during the authentication process to protect the information from possible exploitation and use by unauthorized individuals.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-6)

---

## IA-07 (Cryptographic Module Authentication) { #ia-07 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Implement mechanisms for authentication to a cryptographic module that meet the requirements of applicable laws, executive orders, directives, policies, regulations, standards, and guidelines for such authentication.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-7)

---

## IA-08 (Identification and Authentication (Non-organizational Users)) { #ia-08 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Uniquely identify and authenticate non-organizational users or processes acting on behalf of non-organizational users.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8)

---

## IA-08 (01) (Acceptance of PIV Credentials from Other Agencies) { #ia-08-01 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Accept and electronically verify Personal Identity Verification-compliant credentials from other federal agencies.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8-1)

---

## IA-08 (02) (Acceptance of External Authenticators) { #ia-08-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **(a)** Accept only external authenticators that are NIST-compliant; and
    - **(b)** Document and maintain a list of accepted external authenticators.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8-2)

---

## IA-08 (04) (Use of Defined Profiles) { #ia-08-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Conform to the following profiles for identity management [Assignment: organization-defined identity management profiles].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8-4)

---

## IA-08 (05) (Acceptance of PIV-I Credentials) { #ia-08-05 }

!!! quote ""
    Accept and verify federated or PKI credentials that meet [Assignment: organization-defined policy].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8-5)

---

## IA-08 (06) (Disassociability) { #ia-08-06 }

!!! quote ""
    Implement the following measures to disassociate user attributes or identifier assertion relationships among individuals, credential service providers, and relying parties: [Assignment: organization-defined measures].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-8-6)

---

## IA-09 (Service Identification and Authentication) { #ia-09 }

!!! quote ""
    Uniquely identify and authenticate [Assignment: organization-defined system services and applications] before establishing communications with devices, users, or other services or applications.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-9)

---

## IA-10 (Adaptive Authentication) { #ia-10 }

!!! quote ""
    Require individuals accessing the system to employ [Assignment: organization-defined supplemental authentication techniques or mechanisms] under specific [Assignment: organization-defined circumstances or situations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-10)

---

## IA-11 (Re-authentication) { #ia-11 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class B</span><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require users to re-authenticate when [Assignment: organization-defined circumstances or situations].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-11)

---

## IA-12 (Identity Proofing) { #ia-12 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    - **a.** Identity proof users that require accounts for logical access to systems based on appropriate identity assurance level requirements as specified in applicable standards and guidelines;
    - **b.** Resolve user identities to a unique individual; and
    - **c.** Collect, validate, and verify identity evidence.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12)

---

## IA-12 (01) (Supervisor Authorization) { #ia-12-01 }

!!! quote ""
    Require that the registration process to receive an account for logical access includes supervisor or sponsor authorization.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-1)

---

## IA-12 (02) (Identity Evidence) { #ia-12-02 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require evidence of individual identification be presented to the registration authority.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-2)

---

## IA-12 (03) (Identity Evidence Validation and Verification) { #ia-12-03 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require that the presented identity evidence be validated and verified through [Assignment: organization-defined methods of validation and verification].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-3)

---

## IA-12 (04) (In-person Validation and Verification) { #ia-12-04 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require that the validation and verification of identity evidence be conducted in person before a designated registration authority.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-4)

---

## IA-12 (05) (Address Confirmation) { #ia-12-05 }

<div class="subset-applicability full-control-baselines" role="group" aria-label="FedRAMP Rev5 baseline applicability">
<span class="subset-applicability__group subset-applicability__group--classes"><span class="subset-applicability__label">FedRAMP Rev5 Baselines:</span> <span class="subset-applicability__values"><span class="subset-applicability__tag">Class C</span><span class="subset-applicability__tag">Class D</span></span></span>
</div>

!!! quote ""
    Require that a [Selection: one of: registration code; notice of proofing] be delivered through an out-of-band channel to verify the users address (physical or digital) of record.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-5)

---

## IA-12 (06) (Accept Externally-proofed Identities) { #ia-12-06 }

!!! quote ""
    Accept externally-proofed identities at [Assignment: organization-defined identity assurance level].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-12-6)

---

## IA-13 (Identity Providers and Authorization Servers) { #ia-13 }

!!! quote ""
    Employ identity providers and authorization servers to manage user, device, and non-person entity (NPE) identities, attributes, and access rights supporting authentication and authorization decisions in accordance with [Assignment: organization-defined policy] using [Assignment: organization-defined mechanisms].

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-13)

---

## IA-13 (01) (Protection of Cryptographic Keys) { #ia-13-01 }

!!! quote ""
    Cryptographic keys that protect access tokens are generated, managed, and protected from disclosure and misuse.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-13-1)

---

## IA-13 (02) (Verification of Identity Assertions and Access Tokens) { #ia-13-02 }

!!! quote ""
    The source and integrity of identity assertions and access tokens are verified before granting access to system and information resources.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-13-2)

---

## IA-13 (03) (Token Management) { #ia-13-03 }

!!! quote ""
    In accordance with [Assignment: organization-defined policy], assertions and access tokens are:
    
    - **(a)** generated;
    - **(b)** issued;
    - **(c)** refreshed;
    - **(d)** revoked;
    - **(e)** time-restricted; and
    - **(f)** audience-restricted.

    ---

    _This control does not have additional FedRAMP guidance or FedRAMP-assigned parameter values._

    ---

    **External Link for Additional Information:** [myctrl.tools](https://myctrl.tools/frameworks/nist-800-53-r5/ia-13-3)

---
