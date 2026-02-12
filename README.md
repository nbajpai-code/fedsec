# Federal Cybersecurity Standards: A Comprehensive Guide

## Introduction
This repository serves as a centralized resource for cybersecurity compliance experts specializing in U.S. Federal government requirements. It details the major standards, frameworks, and governing bodies that define the federal cybersecurity landscape.

## Foundational Laws

### FISMA (Federal Information Security Modernization Act of 2014)
*   **Overview**: The cornerstone legislation for federal cybersecurity. It replaced the Federal Information Security Management Act of 2002.
*   **Key Shift**: Moved the federal government from a "paper-based" compliance checklist approach to a "continuous monitoring" approach (real-time security).
*   **Requirements**:
    *   Mandates that each agency develop, document, and implement an agency-wide program to provide information security.
    *   Codifies the authority of the **Department of Homeland Security (DHS)** to administer the implementation of information security policies for non-national security federal systems.
    *   Requires annual reporting to **OMB** and **Congress**.
*   **Applicability**: Mandatory for all Federal Agencies and their contractors.

---

## Governance Bodies & Key Standards

### 1. National Institute of Standards and Technology (NIST)
*   **Role**: Non-regulatory federal agency. Develops the standards (FIPS) and guidelines (SP 800-series) required by FISMA.
*   **Key Publications**:
    *   **FIPS (Federal Information Processing Standards)**: Mandatory standards.
    *   **SP 800-Series (Special Publications)**: Best practice guidelines.

#### Key Standards Managed:

##### Risk Management & General Controls
*   **NIST Risk Management Framework (RMF)** - *SP 800-37 Rev. 2*
    *   **Purpose**: A 7-step lifecycle for managing security and privacy risk (Prepare, Categorize, Select, Implement, Assess, Authorize, Monitor).
    *   **Applicability**: Mandatory for Federal Agencies.
*   **Security and Privacy Controls** - *SP 800-53 Rev. 5*
    *   **Purpose**: The "catalog" of security/privacy controls selected during the RMF process.
    *   **Applicability**: Mandatory by FISMA.

##### Categorization & Planning (The "Missing Links")
*   **Security Categorization** - *FIPS 199* & *SP 800-60 Vol. 1 & 2*
    *   **Purpose**: Mapping information types to security categories (Low, Mod, High) based on CIA triad impact.
    *   **Applicability**: Mandatory step in RMF.
*   **Guide for Conducting Risk Assessments** - *SP 800-30 Rev. 1*
    *   **Purpose**: Methodology for identifying threats, vulnerabilities, and impacts to determine risk.
    *   **Applicability**: Critical for determining the need for controls tailored to specific risks.
*   **System Security Plans (SSP)** - *SP 800-18 Rev. 1*
    *   **Purpose**: Guide for developing System Security Plans, the primary document describing a system's security boundary and controls.
    *   **Applicability**: Required for every FISMA system.

##### Continuous Monitoring
*   **Information Security Continuous Monitoring (ISCM)** - *SP 800-137*
    *   **Purpose**: Guidelines for ongoing awareness of information security, vulnerabilities, and threats to support organizational risk management decisions.
    *   **Applicability**: The operational realization of FISMA 2014's goals.

##### Contractor & Private Sector Specific
*   **Protecting CUI** - *SP 800-171 Rev. 2* & *SP 800-172*
    *   **Purpose**: Protecting Controlled Unclassified Information (CUI) in non-federal systems.
    *   **Applicability**: Mandatory for Federal Contractors (via DFARS).
*   **NIST Cybersecurity Framework (CSF) 2.0**
    *   **Purpose**: High-level framework (Govern, Identify, Protect, Detect, Respond, Recover) for reducing cyber risk.
    *   **Applicability**: Voluntary (but impactful).

---

### 2. Office of Management and Budget (OMB)
*   **Role**: Oversees FISMA implementation/compliance.
*   **Key Outputs**: Memoranda (M-series) like **M-22-09** (Zero Trust Strategy).

### 3. Department of Homeland Security (DHS) / CISA
*   **Role**: Operational lead for federal cybersecurity.
*   **Key Programs**:
    *   **FedRAMP**: Cloud security authorization.
    *   **CDM (Continuous Diagnostics and Mitigation)**: Tooling for agencies.
    *   **Binding Operational Directives (BODs)**: Compulsory actions for agencies (e.g., patching known exploited vulnerabilities).

### 4. Department of Defense (DoD)
*   **Role**: National Security Systems and Defense Industrial Base.
*   **Key Program**: **CMMC 2.0** (Certification for contractors).

---

## Summary Mapping Table

| Governing Body | Primary Standards / Programs | Focus Area |
| :--- | :--- | :--- |
| **Congress** | **FISMA 2014** | **The Law** requiring all of this. |
| **NIST** | FIPS 199/200, SP 800-53, SP 800-37, SP 800-171 | **The Standards** (How to comply). |
| **OMB** | Memoranda (M-Series) | **Oversight** & Policy Direction. |
| **DHS/CISA** | FedRAMP, BODs, CDM | **Operations** & Cloud Security. |
| **DoD** | CMMC 2.0, STIGs | **Defense** Sector Compliance. |
