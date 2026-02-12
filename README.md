# Federal Cybersecurity Standards: A Comprehensive Guide

## Introduction
This repository serves as a centralized resource for cybersecurity compliance experts specializing in U.S. Federal government requirements. It details the major standards, frameworks, and governing bodies that define the federal cybersecurity landscape.

## Governance Bodies & Key Standards

### 1. National Institute of Standards and Technology (NIST)
*   **Role**: Non-regulatory federal agency within the U.S. Department of Commerce. Develops cybersecurity standards, guidelines, best practices, and other resources to meet the needs of U.S. industry, federal agencies, and the broader public.
*   **Key Publications**:
    *   **FIPS (Federal Information Processing Standards)**: Mandatory standards for federal agencies.
    *   **SP 800-Series (Special Publications)**: Guidelines and recommendations.

#### key Standards Managed:
*   **NIST Risk Management Framework (RMF)** - *SP 800-37 Rev. 2*
    *   **Purpose**: Provides a disciplined, structured, and flexible process for managing security and privacy risk.
    *   **Applicability**: Mandatory for Federal Agencies.
*   **Security and Privacy Controls** - *SP 800-53 Rev. 5*
    *   **Purpose**: Catalog of security and privacy controls for federal information systems and organizations.
    *   **Applicability**: Mandatory for Federal Agencies; widely adopted by private sector.
*   **Protecting CUI** - *SP 800-171 Rev. 2* & *SP 800-172*
    *   **Purpose**: Protecting Controlled Unclassified Information (CUI) in Non-Federal Systems and Organizations.
    *   **Applicability**: Mandatory for Federal Contractors processing CUI (via DFARS).
*   **NIST Cybersecurity Framework (CSF) 2.0**
    *   **Purpose**: High-level framework to help organizations of all sizes manage and reduce cybersecurity risk.
    *   **Applicability**: Voluntary (but highly recommended); impactful for federal agencies.

---

### 2. Office of Management and Budget (OMB)
*   **Role**: Oversees the implementation of the President's vision across the Executive Branch.
*   **Key Outputs**: Memoranda (M-series) that set deadlines and requirements for agency cybersecurity implementation (e.g., M-22-09 regarding Zero Trust).
*   **Key Standard**:
    *   **FISMA (Federal Information Security Modernization Act of 2014)**
        *   **Purpose**: Codifies the authority of DHS to administer the implementation of information security policies for non-national security federal Executive Branch systems.
        *   **Applicability**: Mandatory for all Federal Agencies.

---

### 3. Department of Homeland Security (DHS) / CISA
*   **Role**: The Cybersecurity and Infrastructure Security Agency (CISA) leads the national effort to understand, manage, and reduce risk to cyber and physical infrastructure.
*   **Key Outputs**: Binding Operational Directives (BODs) and Emergency Directives (EDs).
*   **Key Program**:
    *   **FedRAMP (Federal Risk and Authorization Management Program)**
        *   **Purpose**: Standardized approach to security assessment, authorization, and continuous monitoring for cloud products and services.
        *   **Applicability**: Mandatory for Federal Agencies adopting cloud services.

---

### 4. Department of Defense (DoD)
*   **Role**: Protects national security systems and the Defense Industrial Base (DIB).
*   **Key Program**:
    *   **CMMC (Cybersecurity Maturity Model Certification) 2.0**
        *   **Purpose**: Validates the cybersecurity maturity of companies in the DIB to protect FCI and CUI.
        *   **Applicability**: Mandatory for DoD Contractors (phased rollout).

---

## Detailed Standards Overview

### FIPS 199 & 200
*   **Governing Body**: NIST
*   **Name**:
    *   *FIPS 199*: Standards for Security Categorization of Federal Information and Information Systems.
    *   *FIPS 200*: Minimum Security Requirements for Federal Information and Information Systems.
*   **Purpose**: FIPS 199 defines the "high water mark" (Low, Moderate, High) for confidentiality, integrity, and availability. FIPS 200 specifies the minimum security requirements based on that categorization.
*   **Applicability**: Mandatory for Federal Agencies.

### NIST SP 800-53 Rev. 5
*   **Governing Body**: NIST
*   **Name**: Security and Privacy Controls for Information Systems and Organizations.
*   **Purpose**: A comprehensive catalog of controls (e.g., Access Control, Incident Response) selected based on the FIPS 199 impact level. Rev. 5 integrates privacy controls into the main catalog.
*   **Applicability**: Mandatory for Federal Agencies.

### NIST SP 800-171 & 172
*   **Governing Body**: NIST
*   **Name**:
    *   *SP 800-171*: Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations.
    *   *SP 800-172*: Enhanced Security Requirements for Protecting CUI.
*   **Purpose**: 800-171 provides a subset of 800-53 controls tailored for non-federal systems to protect CUI. 800-172 is for high-value assets/critical programs where the threat of Advanced Persistent Threats (APTs) is higher.
*   **Applicability**: DoD Contractors (DFARS 7012 clause) and other federal contractors handling CUI.

### FedRAMP
*   **Governing Body**: FedRAMP PMO (GSA/DHS)
*   **Name**: Federal Risk and Authorization Management Program.
*   **Purpose**: "Do Once, Use Many Times" framework for cloud security assessments.
*   **Applicability**: Mandatory for any Cloud Service Provider (CSP) wanting to sell to the federal government.

### CMMC 2.0
*   **Governing Body**: DoD
*   **Name**: Cybersecurity Maturity Model Certification.
*   **Purpose**: Verification mechanism to ensure DIB contractors have implemented the required security controls (primarily NIST SP 800-171).
*   **Applicability**: Mandatory for DIB contractors; 3 Levels (Foundational, Advanced, Expert).

### NIST Cybersecurity Framework (CSF) 2.0
*   **Governing Body**: NIST
*   **Name**: Framework for Improving Critical Infrastructure Cybersecurity.
*   **Purpose**: Provides a common language for understanding, managing, and expressing cybersecurity risk. Core Functions: Govern, Identify, Protect, Detect, Respond, Recover.
*   **Applicability**: Voluntary for private sector; used by federal agencies to align with executive orders.

### NIST RMF (SP 800-37 Rev. 2)
*   **Governing Body**: NIST
*   **Name**: Risk Management Framework for Information Systems and Organizations.
*   **Purpose**: A 7-step process (Prepare, Categorize, Select, Implement, Assess, Authorize, Monitor) to integrate security and risk management into the system development life cycle.
*   **Applicability**: Mandatory for Federal Agencies.

---

## Summary Mapping Table

| Governing Body | Primary Standards / Programs | Focus Area |
| :--- | :--- | :--- |
| **NIST** | FIPS 199/200, SP 800-53, SP 800-37 (RMF), CSF 2.0 | Standards, Controls, Risk Frameworks |
| **OMB** | FISMA, Memoranda (e.g., M-22-09) | Oversight, Policy, Compliance Deadlines |
| **DHS/CISA** | FedRAMP, BODs, Emergency Directives | Cloud Security, Operational Security |
| **DoD** | CMMC 2.0, STIGs (DISA) | Defense Industrial Base Security |
| **NSA** | CSfC, CNSS Policies | National Security Systems (Classified) |

