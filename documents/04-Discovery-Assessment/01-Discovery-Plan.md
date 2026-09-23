# 1. Purpose

The purpose of the discovery phase is to establish a reliable understanding of Heartland Integrated Health System's legacy, network-connected infusion-pump environment and document the evidence needed to assess its current state.

Discovery will examine the device population, locations, clinical workflows, connectivity, system integrations, cybersecurity considerations, vendor support, lifecycle status, operational dependencies, information flows, communication needs, and geographic distribution of affected devices.

The discovery process will use stakeholder interviews, technical reviews, available documentation, inventory analysis, workflow assessment, and other appropriate evidence-gathering activities. Findings will be validated with relevant subject matter experts and used to identify current-state risks, gaps, dependencies, communication needs, decision-readiness considerations, and areas requiring further investigation.

Discovery will not assume a specific technical solution or determine future-state implementation activities.

---

# 2. Discovery Objectives

The discovery objectives define the information and evidence needed to establish the current state of Heartland's legacy connected infusion-pump environment and support evidence-based assessment, decision-readiness, and identification of areas requiring further investigation.

### 2.1 Establish a Reliable Device Baseline

Determine which legacy infusion pumps are in service, including manufacturer, model, age, location, ownership, connectivity, and support status.

### 2.2 Understand Clinical Workflows

Determine how selected infusion pumps are used in clinical environments and identify workflow dependencies, information needs, communication points, usability concerns, and operational constraints.

### 2.3 Understand Connectivity and Integration

Determine how selected pumps connect to networks and clinical systems, what information is exchanged, and what integration dependencies exist.

### 2.4 Assess Cybersecurity Considerations

Identify relevant security characteristics, network exposure, access requirements, vulnerability considerations, and existing security controls or dependencies.

### 2.5 Assess Lifecycle and Vendor Support

Determine device support status, lifecycle position, end-of-life considerations, and vendor capabilities or limitations.

### 2.6 Identify and Prioritize Risks

Establish the factors needed to evaluate clinical, operational, cybersecurity, interoperability, and lifecycle risks across the selected device population.

### 2.7 Identify Decision-Readiness Considerations

Identify the requirements, constraints, dependencies, evidence gaps, and unresolved questions that should be understood before future decisions are made.

### 2.8 Identify Areas for Further Investigation

Identify information, technical conditions, stakeholder questions, dependencies, or risks that require additional assessment beyond the current discovery activities.
---

# 3. Key Discovery Questions
## Objective 1: Establish a Reliable Device Baseline

Discovery questions: 

- How many infusion pumps are currently in service?
- Which manufacturers and models are represented?
- Where is each device located?
- Which devices are network-connected?
- Who owns and maintains the inventory?
- How can Clinical Engineering records be reconciled with network records?
- Which devices are vendor-supported?


## Objective 2: Understand Clinical Workflows

Discovery questions:

- In which clinical areas are the infusion pumps used?
- Which types of patients and clinical workflows depend on the pumps?
- Who interacts with the pumps during a typical clinical workflow?
- How are pumps selected, configured, monitored, and maintained during use?
- What information must clinicians receive from or enter into the pump?
- Does pump connectivity support any part of the clinical workflow?
- What happens when a pump is unavailable, disconnected, or unable to communicate with another system?
- Are there differences in workflow between facilities or clinical departments?
- What workflow dependencies could affect clinical operations or continuity?
- What information is available to clinicians at the point where it is needed?
- Are there situations where staff must obtain information from multiple systems or people to complete the workflow?
- Where do communication handoffs occur between clinical, technical, and operational teams?
- Are there workflow steps that depend on information being transmitted between the pump and another system?
- What workflow issues, gaps, or uncertainties require further investigation?
  
## Objective 3: Understand Connectivity and Integration

Discovery questions:

- How are the infusion pumps connected to Heartland's network?
- Are the pumps connected through wired, wireless, or other connectivity methods?
- Which pumps are currently network-connected, and are there differences by model or facility?
- What clinical or enterprise systems communicate with the infusion pumps?
- What information is exchanged between the pumps and connected systems?
- What interfaces, protocols, or integration technologies support these exchanges?
- Are any vendor-specific interfaces or proprietary technologies involved?
- Where do the interfaces or integration points reside within the current architecture?
- What happens when a pump loses network connectivity or an interface becomes unavailable?
- How is connectivity or interface failure detected and communicated to clinical or technical staff?
- Are there differences in connectivity or integration between facilities?
- What dependencies exist between the pumps, network infrastructure, integration components, and connected systems?
- Does the information exchanged between systems arrive in a form that is useful to the people who need it?
- What information is lost, delayed, duplicated, or difficult to interpret across current interfaces?
- What connectivity, interface, or integration issues require further investigation?
  
## Objective 4: Assess Cybersecurity Considerations

Discovery questions:

- What security controls currently protect the infusion pumps and their supporting systems?
- Which infusion pumps are connected to the network, and what level of network access do they require?
- Are the pumps located within appropriate network segments or security zones?
- What network traffic is required for normal pump operation and system integration?
- How are users, devices, and administrative access authenticated and authorized?
- What remote-access capabilities exist for the pumps or supporting systems?
- How are security updates, patches, firmware, and configuration changes currently managed?
- Which devices or models have known vulnerabilities or unsupported security characteristics?
- How are vulnerabilities identified, tracked, prioritized, and communicated?
- What monitoring or logging exists for device and network activity?
- What happens when a device cannot support a required security control because of its age or technical limitations?
- Are compensating controls currently being used for legacy devices?
- What cybersecurity dependencies or constraints exist within the current environment?
- What cybersecurity risks, gaps, or uncertainties require further investigation?

## Objective 5: Assess Lifecycle and Vendor Support

Discovery questions:

- What is the age and expected service life of each infusion-pump model?
- Which manufacturers and models are currently supported by the vendor?
- Which devices are approaching or past their expected service life?
- Which devices are approaching or past vendor end-of-support or end-of-life dates?
- What maintenance and technical support is currently available for each device or model?
- Are replacement parts, firmware updates, security patches, and other vendor services still available?
- What limitations exist for devices that are no longer fully supported?
- Are there differences in lifecycle or support status between facilities?
- What vendor dependencies exist within the current environment?
- Are there contractual, licensing, or maintenance considerations that need to be understood?
- Which devices require further investigation because of lifecycle or support concerns?
- What information is available about devices that remain in service despite lifecycle or support limitations?
- What information is needed from vendors to clarify device capabilities, support limitations, lifecycle status, and available technical options?

## Objective 6: Identify and Prioritize Risks

Discovery questions:

- What characteristics make one infusion pump or device population higher risk than another?
- Which clinical, operational, cybersecurity, interoperability, and lifecycle factors should be considered when evaluating risk?
- Which devices or facilities have the greatest combination of risk factors?
- Are there devices with known vulnerabilities, unsupported software, or limited security capabilities?
- Which devices have the greatest dependency on network connectivity or system integration?
- Which devices or workflows would create the greatest operational impact if connectivity or device functionality were disrupted?
- Are there differences in risk between facilities, departments, device models, or device configurations?
- How should risk factors be documented and prioritized for this discovery assessment?
- Which risks require further investigation or additional evidence?
- What existing controls or mitigations are currently documented for the identified risks?
- Where are residual risks or evidence gaps present after existing controls are considered?
- Which risks or gaps should be carried forward into the current-state findings?
- Which stakeholders or subject matter experts should validate the identified risks and findings?

## Objective 7: Identify Decision-Readiness Considerations

Discovery questions:

- What clinical requirements are important to understanding the current environment?
- What cybersecurity requirements and dependencies are currently identified?
- What interoperability and integration requirements must be understood?
- What device capabilities or limitations affect current workflows and system dependencies?
- What operational constraints are currently documented?
- What lifecycle and vendor-support considerations require further investigation?
- What workflow dependencies or clinical continuity considerations should be understood before future decisions are made?
- What financial or resource information is available that may affect future analysis?
- What dependencies or evidence gaps could affect future decision-making?
- Which requirements or constraints are considered mandatory, and which are desirable?
- Which stakeholders should participate in defining and validating decision-readiness considerations?
- How should these requirements, constraints, dependencies, and evidence gaps be documented for future analysis?

## Objective 8: Identify Areas for Further Investigation

Discovery questions:

- Which devices, facilities, workflows, or interfaces require additional assessment based on current findings?
- What technical, clinical, operational, cybersecurity, interoperability, lifecycle, or vendor questions remain unresolved?
- What information gaps or conflicting information require additional validation?
- Which findings require confirmation from subject matter experts?
- What additional documentation or evidence is needed to clarify current-state conditions?
- What vendor information or participation may be needed to resolve outstanding questions?
- Which dependencies or assumptions should be validated before future decisions are made?
- Which risks or gaps require additional analysis to support decision-readiness?
- Which findings should be carried forward into subsequent phases of analysis?
- What areas remain outside the scope of the current discovery activities?

---

# 4. Stakeholders & Subject Matter Experts

Discovery will require input from clinical, technical, operational, cybersecurity, and vendor stakeholders. Each stakeholder group provides a different perspective on the current infusion-pump environment.

The Technical Project Manager will coordinate discovery activities, document findings, facilitate communication across stakeholder groups, and ensure that information is validated by the appropriate subject matter experts.

| Stakeholder/SME | Discovery Role | Information Needed |
|---|---|---|
| Executive Sponsor | Executive decision-maker | Project priorities, constraints, decision authority |
| Clinical Engineering/Biomedical | Primary device SME | Device inventory, models, maintenance, lifecycle, connectivity, vendor support |
| Nursing Leadership | Clinical workflow SME | Clinical workflows, operational dependencies, workflow risks, staff impact |
| Clinical Staff | End-user perspective | Actual pump usage, workflow challenges, downtime procedures, operational concerns |
| Cybersecurity | Security SME | Vulnerabilities, security controls, network exposure, access, monitoring, compensating controls |
| Network Engineering | Network SME | Network connectivity, segmentation, traffic, network architecture, device dependencies |
| Integration/Interface Team | Integration SME | Interfaces, protocols, data exchanges, integration dependencies, failure handling |
| IT Operations | Infrastructure SME | Infrastructure support, monitoring, operational procedures, incident response |
| Pharmacy | Clinical stakeholder | Medication-management dependencies and workflow considerations |
| Compliance/Privacy | Regulatory stakeholder | Applicable organizational, regulatory, and privacy requirements |
| Medical Device Vendors | External technical SME | Device capabilities, support status, upgrades, limitations, lifecycle information |
| Technical Project Manager | Discovery lead | Coordinates interviews, evidence collection, findings, risks, decision-readiness considerations, and documentation |

---

# 5. Discovery Activities

Discovery activities will be conducted using a combination of stakeholder interviews, technical reviews, data and inventory analysis, workflow assessment, workshops, and evidence validation.

Activities will be coordinated according to the discovery objectives and targeted to the stakeholders and subject matter experts with relevant knowledge. Findings will be documented and validated before being incorporated into the current-state assessment, risk and gap analysis, and decision-readiness findings.

### 5.1 Stakeholder Interviews

Understand organizational priorities, clinical workflows, operational concerns, decision constraints, and stakeholder perspectives.

### 5.2 Device Inventory & Data Reconciliation

Compare Clinical Engineering, IT, network, and other available records to establish a reliable device baseline.

### 5.3 Clinical Workflow Assessment

Examine how infusion pumps are used in selected clinical environments and identify workflow dependencies, variations, information needs, usability concerns, communication points, and operational constraints.

### 5.4 Connectivity & Integration Review

Review network connectivity, system interfaces, data exchange, integration dependencies, and failure-handling processes.

### 5.5 Cybersecurity & Technical Review

Review relevant security characteristics, network exposure, access controls, monitoring, vulnerabilities, and existing compensating controls.

### 5.6 Lifecycle & Vendor Assessment

Review device age, support status, end-of-life considerations, maintenance history, current device capabilities and limitations, and vendor dependencies.

### 5.7 Cross-Functional Findings Validation

Bring relevant SMEs together to validate findings, resolve discrepancies, identify gaps, and confirm risks, dependencies, communication needs, and decision-readiness considerations.

---

# 6. Evidence & Data Sources

Discovery will use available technical, operational, clinical, and organizational evidence to establish the current state of the selected infusion-pump environment.

Evidence will be collected from multiple sources where practical and reconciled when discrepancies are identified. The objective is to develop a reliable evidence base for identifying current-state risks, gaps, dependencies, decision-readiness considerations, and areas requiring further investigation.

Potential evidence and data sources include:

### 6.1 Device & Inventory Data
- Clinical Engineering device inventories
- Asset management records
- Device manufacturer and model information
- Device age and lifecycle records
- Maintenance records
- Device location records

### 6.2 Network & Integration Data
- Network diagrams
- Network inventory records
- Device connectivity records
- Interface documentation
- Integration architecture diagrams
- Relevant interface specifications
- System dependency information

### 6.3 Clinical & Operational Evidence
- Workflow documentation
- Clinical procedures
- Standard operating procedures
- Downtime procedures
- Workflow observation notes
- Stakeholder and SME interview findings

### 6.4 Cybersecurity Evidence
- Applicable security policies
- Network segmentation documentation
- Access-control information
- Vulnerability information
- Security assessment findings, where available
- Monitoring and logging information
- Existing compensating controls

### 6.5 Vendor & Lifecycle Evidence
- Vendor documentation
- Product specifications
- Support status
- End-of-life/end-of-support information
- Upgrade or firmware documentation
- Maintenance agreements
- Vendor responses to discovery questions

### 6.6 Organizational & Project Evidence
- Existing architecture documentation
- Previous assessment reports
- Project or modernization plans
- Organizational policies
- Applicable requirements and standards
- Existing risk or issue records

### 6.7 Communication & Organizational Evidence
- Stakeholder communication records
- Escalation procedures
- Incident communication procedures
- Change-management materials, where available
- Training materials
- User feedback or issue records
- Meeting notes documenting operational or workflow concerns

### 6.8 Validation Evidence
Findings will be reviewed with appropriate subject matter experts to confirm accuracy, resolve discrepancies, identify information gaps, and establish confidence in the current-state assessment.


---






