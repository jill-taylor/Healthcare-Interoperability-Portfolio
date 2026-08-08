# Heartland Integrated Health System (HIHS)

## Legacy Medical Device Modernization & Secure Integration Project

### Project Charter

**Prepared for:** Executive Leadership Team

**Prepared by:** Jill Taylor, Technical Project Manager (Consulting)

**Version:** 2.0 – Focused Project Revision

**Status:** Discovery Phase

---

# Executive Summary

Heartland Integrated Health System (HIHS) has identified a need to assess and modernize a population of legacy, network-connected infusion pumps within its healthcare environment.

Heartland's continued growth through hospital and healthcare-service acquisitions has resulted in a diverse technology environment that includes medical devices of varying ages, manufacturers, connectivity capabilities, security controls, and vendor support levels. Some legacy devices may not align with current enterprise cybersecurity, interoperability, or infrastructure requirements.

Immediate replacement of the entire legacy device population is not considered practical because of cost, clinical dependencies, operational disruption, and device availability. At the same time, continued operation of aging connected devices may introduce cybersecurity, interoperability, support, and patient-safety risks that require structured evaluation.

The purpose of this project is to conduct a focused discovery and assessment of Heartland's legacy connected infusion-pump environment and develop a safe, practical, phased modernization strategy.

The project will examine the current device environment, clinical workflows, connectivity, integration requirements, cybersecurity considerations, vendor support, operational dependencies, and geographic distribution of the affected devices.

The project will not assume a specific technical solution. Discovery findings will be used to evaluate potential approaches, which may include device replacement, vendor-supported upgrades, network segmentation, controlled access, integration modernization, or a combination of strategies.

The resulting recommendation will provide Heartland leadership with a practical path for reducing risk while maintaining continuity of clinical operations.



---


# 1. Organization Background

Heartland Integrated Health System (HIHS) is a not-for-profit regional healthcare organization serving approximately 300,000 residents across four counties.

Originally established as a single community hospital, HIHS has expanded through strategic acquisitions designed to improve access to healthcare services throughout the region. Today, the organization serves both urban and rural communities through hospitals, primary care clinics, specialty care, urgent care, laboratory, imaging, and telehealth services.

HIHS currently consists of:

- **Heartland Regional Medical Center** (Flagship tertiary care hospital)
- **Heartland Community Hospital** (Community acute care hospital)
- Eight primary care clinics
- Three specialty care clinics
- Two urgent care centers
- One regional reference laboratory
- Two outpatient imaging centers
- A growing telehealth services program

The organization's continued growth has created a diverse technology environment in which clinical systems and medical devices have been acquired, implemented, and maintained at different points in time.

---


# 2. Business Problem

Heartland has identified a population of legacy, network-connected infusion pumps that may not fully align with current enterprise technology and security requirements.

The devices remain important to clinical operations and cannot simply be removed from service. However, their age, connectivity capabilities, vendor support status, integration limitations, and security characteristics may create operational and cybersecurity concerns.

Heartland currently lacks a consolidated assessment of:

- Which legacy infusion pumps are in service
- Where the devices are located
- Which devices are network-connected
- Which systems they communicate with
- What integration capabilities they support
- Which devices remain vendor-supported
- Which devices present the greatest operational or cybersecurity risk
- Which devices should be upgraded, isolated, replaced, or otherwise remediated

The organization therefore needs a structured discovery and decision-making process before committing to a modernization approach.

Core PM Question

How can Heartland safely manage its legacy connected infusion pumps while determining an appropriate path toward modernization without disrupting clinical operations?

---


# 3. Project Vision

Heartland seeks to establish a safe, sustainable approach for managing legacy connected infusion pumps while transitioning toward a modern medical-device environment.

The future state should:

- Support safe clinical operations
- Reduce cybersecurity exposure associated with legacy technology
- Maintain necessary clinical and system connectivity
- Improve visibility into the medical-device environment
- Establish clear device lifecycle and modernization priorities
- Provide a practical path for phased modernization
- Minimize disruption to patients and clinical staff

The project will use discovery findings and stakeholder input to determine the appropriate combination of technical, operational, and lifecycle strategies.

---

# 4. Project Objectives

The project will:

1. **Establish a Current-State Device Inventory**

Identify the relevant infusion pumps, manufacturers, models, locations, age, connectivity, ownership, and support status.

2. **Understand Clinical Workflows**

Document how infusion pumps are used within selected clinical environments and identify operational dependencies that could affect modernization.

3. **Assess Connectivity and Integration**

Determine how selected devices connect to Heartland's network and clinical systems and identify significant interoperability or integration dependencies.

4. **Assess Cybersecurity Considerations**

Identify security characteristics, vulnerabilities, access requirements, network exposure, and other risks associated with the legacy device environment.

5. **Evaluate Device Lifecycle and Vendor Support**

Determine which devices are supported, approaching end of life, or otherwise candidates for remediation or replacement.

6. **Identify and Prioritize Risks**

Develop a risk-based view of the device population using clinical, operational, cybersecurity, interoperability, and lifecycle considerations.

7. **Evaluate Modernization Options**

Evaluate potential approaches such as:

- Device replacement
- Vendor-supported upgrades
- Network segmentation
- Controlled access
- Integration modernization
- Compensating security controls
- Phased combinations of these approaches

8. **Develop a Phased Modernization Strategy**
Recommend a practical sequence for addressing the highest-priority devices and environments while maintaining clinical operations.

---

# 5. Project Scope

## In Scope
- Selected legacy network-connected infusion pumps
- Device inventory and classification
- Device location and facility distribution
- Clinical workflow discovery
- Device connectivity and integration assessment
- Cybersecurity risk assessment
- Vendor and lifecycle assessment
- Stakeholder interviews and workshops
- Current-state architecture
- Risk prioritization
- Evaluation of modernization options
- Future-state concept architecture
- Phased modernization roadmap
- Change-management considerations
- Executive recommendation


## Out of Scope
- Replacement of all Heartland medical devices
- Production deployment of security technologies
- Production device configuration
- Development of medical-device software
- Development of production interfaces
- Procurement or contract negotiation
- Clinical validation of medication protocols
- Replacement of the EHR
- Enterprise-wide interoperability modernization
- Operational support following project completion

---

# 6. Success Criteria

The Legacy Medical Device Modernization & Secure Integration Project will be considered successful when the following outcomes have been achieved:


## Discovery
- A representative population of legacy infusion pumps has been inventoried.
- Device locations and relevant attributes have been documented.
- Key clinical, technical, cybersecurity, and operational dependencies have been identified.

## Assessment
- Current-state device connectivity and integration have been documented.
- Major risks have been identified and prioritized.
- Device lifecycle and vendor-support conditions have been assessed.

## Decision Support
- Multiple modernization options have been evaluated.
- Options have been compared using agreed-upon criteria.
- A recommended approach has been presented to leadership.

## Implementation Planning
- A phased modernization roadmap has been developed.
- High-priority facilities/devices have been identified.
- Major implementation risks and dependencies have been documented.
- Clinical continuity requirements have been incorporated into the plan.

## Executive Outcome
- Executive leadership has an evidence-based recommendation for managing and modernizing the legacy infusion-pump environment.

# 7. Key Stakeholders

The success of the Legacy Medical Device Modernization & Secure Integration Project depends on collaboration among executive leadership, clinical departments, operational teams, information technology, and the consulting team. The following stakeholders will provide strategic direction, subject matter expertise, governance, and decision-making throughout the project.

| Stakeholder | Role | Primary Responsibility |
|-------------|------|------------------------|
| Executive Leadership  | Executive Sponsor | Strategic direction, funding, major decisions |
| Chief Information Officer (CIO) | Technology Sponsor | Technology strategy and executive support |
| Chief Medical Information Officer (CMIO) | Clinical Sponsor | Physician and clinical workflow considerations |
| Chief Nursing Officer (CNO) | Clinical Sponsor | Nursing workflow and patient-care considerations |
| Clinical Engineering/Biomedical | Technical SME | Device inventory, maintenance, lifecycle, vendor support |
| Cybersecurity | Technical SME | Assesses device vulnerabilities, security controls, network exposure, authentication/access requirements, segmentation options, monitoring needs, and cybersecurity risks; recommends appropriate risk-mitigation controls. |
| Network Engineering | Technical SME | Connectivity, network architecture, segmentation |
| Integration/Interface Team | Technical SME | Device/system integration and data exchange |
| Nursing Leadership | Business Stakeholder | Clinical workflow and operational requirements |
| Pharmacy | Clinical Stakeholder | Medication-management dependencies |
| IT Operations | Technical Stakeholder | Infrastructure and operational support |
| Compliance/Privacy | Regulatory Stakeholder | Regulatory and organizational requirements |
| Medical Device Vendors | External Stakeholder | Device capabilities, support, upgrades, technical constraints |
| Technical Project Manager | Project Lead | Planning, discovery, coordination, risks, decisions, documentation |


# 8. Assumptions and Constraints

## Assumptions
- Executive sponsorship remains active.
- Clinical and technical SMEs will participate in discovery.
- Heartland can provide available device and system documentation.
- Device information can be validated through stakeholder interviews and technical review.
- The project will use fictionalized data for portfolio development.
- Clinical safety will remain the primary consideration for implementation decisions.

## Constraints
- Clinical operations cannot be disrupted.
- Legacy devices may have limited technical capabilities.
- Device replacement budgets are limited.
- Vendor support may vary by device and model.
- Some device information may be incomplete.
- Modernization must occur while existing clinical services continue.

# 9. Project Risks and Mitigation Strategies

| Risk | Potential Impact | Mitigation Strategy |
|------|------------------|---------------------|
| Incomplete device inventory | High-risk devices may be missed | Validate inventory with Clinical Engineering/Biomedical, IT, and clinical teams |
| Unsupported devices | Increased operational and cybersecurity risk | Prioritize lifecycle assessment and remediation |
| Clinical workflow disruption | Patient-care impact | Include clinical stakeholders throughout discovery and planning |
| Legacy integration limitations | Modernization options may be constrained | Document interfaces and vendor capabilities early |
| Cybersecurity vulnerabilities | Potential patient-safety and operational risk | Conduct security assessment and evaluate compensating controls |
| Vendor dependency | Delays or limited modernization options | Engage vendors during discovery |
| Resource availability | Delayed discovery and validation | Prioritize critical stakeholders and facilities |
| Scope expansion | Schedule and complexity increase | Maintain focused device population and formal change control |
| Inaccurate assumptions | Poor recommendations | Validate findings through multiple stakeholder groups |


# 10. Project Deliverables

| Deliverable | Description |
|--------------|-------------|
| **Project Charter** | Defines the project problem, objectives, scope, stakeholders, risks, and success criteria. |
| **Discovery Plan** | Defines discovery questions, activities, stakeholders, evidence, and outputs. |
| **Device Inventory** | Documents the selected infusion-pump population and relevant attributes. |
| **Stakeholder Analysis** | Identifies stakeholders, responsibilities, influence, and engagement needs. |
| **Clinical Workflow Map** | Illustrates how infusion pumps are used within selected clinical workflows. |
| **Current-State Architecture** | Shows device connectivity, systems, interfaces, and relevant network boundaries. |
| **Cybersecurity Assessment** | Summarizes identified security concerns and risk considerations. |
| **Risk Assessment** | Prioritizes devices/facilities based on defined criteria. |
| **QGIS Visualizations** | Maps facility and device distribution to support prioritization and implementation planning. |
| **Gap Analysis** | Identifies gaps between the current environment and desired future state. |
| **Solution Options Analysis** | Compares potential modernization approaches. |
| **Interface Inventory** | Documents existing interfaces, data exchange methods, integration technologies, and information flows associated with the selected infusion-pump environment. |
| **Future-State Concept Architecture** | Illustrates the recommended target environment at an appropriate level of detail. |
| **Modernization Roadmap** | Defines phased implementation priorities and dependencies. |
| **Executive Presentation** | Summarizes findings, recommended approach, risks, and next steps. |

# 11. Governance

| Governance Role | Responsibilities |
|--------------|-------------|
| Executive Sponsor | Provides strategic direction and resolves major organizational issues. |
| CIO/Technology Sponsor | Provides technology oversight and decision support |
| Clinical Sponsors | Validate clinical priorities and workflow requirements |
| Technical SMEs | Provide subject-matter expertise and validate findings |
| Technical Project Manager | Leads planning, discovery, schedule, risks, communications, decisions, and deliverables |
| Project Team | Performs discovery, analysis, documentation, and solution evaluation |
| Steering Committee | Reviews major findings, risks, options, and recommendations |

The Technical Project Manager will coordinate the project but will not act as the technical authority for clinical engineering, cybersecurity, networking, or medical-device engineering decisions.


# 12. High-Level Timeline

| Phase | Description |
|--------------|-------------|
| Project Initiation | Charter approval, kickoff, governance, scope confirmation |
| Discovery Planning | Define discovery questions, stakeholders, evidence, and activities |
| Discovery | Device inventory, interviews, workflows, connectivity, cybersecurity, vendor assessment |
| Current-State Assessment | Consolidate findings and document the current environment |
| Risk & Gap Analysis | Identify and prioritize risks and modernization gaps |
| Options Evaluation | Evaluate replacement, upgrade, segmentation, controlled-access, and other approaches |
| Future-State Recommendation | Develop recommended approach and concept architecture |
| Roadmap Development | Define phases, priorities, dependencies, risks, and implementation considerations |
| Executive Review & Closeout | Present findings, recommendation, and roadmap |


# 13. Project Guiding Principle

Discovery before solution.

The project will not assume that device replacement, Zero Trust, network segmentation, secure browser technology, interoperability modernization, or any other technical approach is the appropriate solution.

The project team will first establish the current state, understand clinical and technical requirements, identify risks, and evaluate available options.

The recommended solution will be based on evidence gathered during discovery.


---




Version 2.0 – Focused Project Revision

