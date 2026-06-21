---
tags:
  - Rev5
---

<span class="picto">:lucide-computer:{ .machine title="This content is machine-generated from FedRAMP Machine-Readable Rules." } :lucide-book-open-check:{ .stable title="This content is relatively stable and only minor changes are expected." }</span>

# System and Information Integrity

### Flaw Remediation { #si-02-flaw-remediation }

??? abstract "SI-02"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-02`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Identify, report, and correct system flaws;
    - **b.** Test software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
    - **c.** Install security-relevant software and firmware updates within [Assignment: organization-defined time period] of the release of the updates; and
    - **d.** Incorporate flaw remediation into the organizational configuration management process.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Automated Flaw Remediation Status { #si-02-02-automated-flaw-remediation-status }

??? abstract "SI-02(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-02(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Determine if system components have applicable security-relevant software and firmware updates installed using [Assignment: organization-defined automated mechanisms] [Assignment: organization-defined frequency].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### System Monitoring { #si-04-system-monitoring }

??? abstract "SI-04"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

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

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response and Incident Communication Procedure guidance.

---

### System-wide Intrusion Detection System { #si-04-01-system-wide-intrusion-detection-system }

??? abstract "SI-04(01)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(01)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Connect and configure individual intrusion detection tools into a system-wide intrusion detection system.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Automated Tools and Mechanisms for Real-time Analysis { #si-04-02-automated-tools-and-mechanisms-for-real-time-analysis }

??? abstract "SI-04(02)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(02)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Employ automated tools and mechanisms to support near real-time analysis of events.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Inbound and Outbound Communications Traffic { #si-04-04-inbound-and-outbound-communications-traffic }

??? abstract "SI-04(04)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(04)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **(a)** Determine criteria for unusual or unauthorized activities or conditions for inbound and outbound communications traffic;
    - **(b)** Monitor inbound and outbound communications traffic [Assignment: organization-defined frequency] for [Assignment: organization-defined unusual or unauthorized activities or conditions].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### System-generated Alerts { #si-04-05-system-generated-alerts }

??? abstract "SI-04(05)"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-04(05)`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    Alert [Assignment: organization-defined personnel or roles] when the following system-generated indications of compromise or potential compromise occur: [Assignment: organization-defined compromise indicators].

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the Vulnerability and Detection Response guidance.

---

### Security Alerts, Advisories, and Directives { #si-05-security-alerts-advisories-and-directives }

??? abstract "SI-05"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-05`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Receive system security alerts, advisories, and directives from [Assignment: organization-defined external organizations] on an ongoing basis;
    - **b.** Generate internal security alerts, advisories, and directives as deemed necessary;
    - **c.** Disseminate security alerts, advisories, and directives to: [Assignment: si-05_odp.02]; and
    - **d.** Implement security directives in accordance with established time frames, or notify the issuing organization of the degree of noncompliance.

    !!! note ""
        **FedRAMP Guidance**

        Follow all applicable rules within the FedRAMP Secure Inbox (FSI) guidance.

---

### Spam Protection { #si-08-spam-protection }

??? abstract "SI-08"
    **NIST SP 800-53 Revision 5.2.0**

    - **Official NIST control ID:** `SI-08`
    - **Catalog version:** 5.2.0
    - **OSCAL version:** 1.2.2
    - **Catalog last modified:** May 11, 2026

!!! quote ""
    - **a.** Employ spam protection mechanisms at system entry and exit points to detect and act on unsolicited messages; and
    - **b.** Update spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.

    !!! note ""
        **FedRAMP Guidance**

        When CSO sends email on behalf of the government as part of the business offering, Control Description should include implementation of Domain-based Message Authentication, Reporting & Conformance (DMARC) on the sending domain for outgoing messages as described in DHS Binding Operational Directive (BOD) 18-01. [https://www.cisa.gov/news-events/directives](https://www.cisa.gov/news-events/directives)

        SI-8 Guidance: CSPs should confirm DMARC configuration (where appropriate) to ensure that policy=reject and the rua parameter includes reports@dmarc.cyber.dhs.gov.  DMARC compliance should be documented in the SI-08 control implementation solution description, and list the FROM: domain(s) when emails are sent on behalf of the government.

---
