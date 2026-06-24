---
tags:
  - Rev5
  - Cloud Service Providers
  - Controls
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." }</span>

# Identification and Authentication

### Identification and Authentication (Organizational Users) { #ia-02-identification-and-authentication-organizational-users }

??? abstract "IA-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Uniquely identify and authenticate organizational users and associate that unique identification with processes acting on behalf of those users.

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Multi-factor Authentication to Privileged Accounts { #ia-02-01-multi-factor-authentication-to-privileged-accounts }

??? abstract "IA-02(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for access to privileged accounts.

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Multi-factor Authentication to Non-privileged Accounts { #ia-02-02-multi-factor-authentication-to-non-privileged-accounts }

??? abstract "IA-02(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for access to non-privileged accounts.

    !!! info ""
        **FedRAMP Guidance**

        Multi-factor authentication must be phishing-resistant. In accordance with current CISA Guidance. Current CISA guidance can be found here: [https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf](https://www.cisa.gov/sites/default/files/publications/fact-sheet-implementing-phishing-resistant-mfa-508c.pdf)

---

### Access to Accounts —separate Device { #ia-02-06-access-to-accounts-separate-device }

??? abstract "IA-02(06)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(06)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement multi-factor authentication for [Selection: one or more of: local; network; remote] access to [Selection: one or more of: privileged accounts; non-privileged accounts] such that:
    
    - **(a)** One of the factors is provided by a device separate from the system gaining access; and
    - **(b)** The device meets [Assignment: organization-defined strength of mechanism requirements].

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.06_odp.01` | one or more of: local; network; remote | local, network and remote |
        | `ia-02.06_odp.02` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

---

### Access to Accounts — Replay Resistant { #ia-02-08-access-to-accounts--replay-resistant }

??? abstract "IA-02(08)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-02(08)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Implement replay-resistant authentication mechanisms for access to [Selection: one or more of: privileged accounts; non-privileged accounts].

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-02.08_odp` | one or more of: privileged accounts; non-privileged accounts | privileged accounts; non-privileged accounts |

---

### Identify User Status { #ia-04-04-identify-user-status }

??? abstract "IA-04(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-04(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Manage individual identifiers by uniquely identifying each individual as [Assignment: organization-defined characteristics].

    !!! info ""
        **FedRAMP Parameters**

        | Parameter ID | NIST assignment | FedRAMP value |
        | --- | --- | --- |
        | `ia-04.04_odp` | characteristics | contractors; foreign nationals |

---

### Authenticator Management { #ia-05-authenticator-management }

??? abstract "IA-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `IA-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

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
