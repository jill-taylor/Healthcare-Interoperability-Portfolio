# 09 - Risk and Gap Assessment

## 1. Purpose

The purpose of this risk and gap assessment is to consolidate current-state risks, gaps, dependencies, and areas requiring further investigation identified during the Heartland Integrated Health System (HIHS) legacy infusion-pump assessment.

The assessment builds on information documented in:

- 02 - Device Inventory
- 03 - Interface Inventory
- 04 - Current-State Architecture
- 05 - Clinical Workflow Assessment
- 06 - Cybersecurity Assessment
- 07 - Current-State Findings
- 08 - Stakeholder Analysis

The risk and gap assessment supports:

- Identification of current-state risks and constraints
- Identification of gaps in information, visibility, ownership, monitoring, or validation
- Evaluation of potential clinical, operational, technical, integration, cybersecurity, and decision-readiness impacts
- Identification of dependencies requiring additional investigation
- Traceability between risks, gaps, and supporting assessment evidence
- Prioritization of areas requiring additional validation
- Preparation for subsequent decision-readiness activities

This artifact is part of the current-state discovery assessment and does not define future-state solutions, remediation plans, procurement recommendations, implementation activities, or production changes.

---

## 2. Risk and Gap Assessment Approach

The assessment distinguishes between:

- **Confirmed current-state conditions** supported by available assessment evidence
- **Stakeholder-reported information** requiring appropriate validation
- **Potential risks or impacts** identified from current-state conditions
- **Information or evidence gaps** that limit assessment confidence
- **Dependencies** requiring additional investigation
- **Assumptions** that have not yet been independently validated

Risk and gap identification considers the relationship between:

**Devices → Connectivity → Information Flow → Clinical Workflow → Lifecycle → Cybersecurity → Operations → Decision Readiness**

Risk and gap assessment should consider the potential effect of a condition rather than treating the existence of a technical limitation as an automatic risk.

Where available evidence is insufficient to determine the significance of a condition, the assessment identifies the item as requiring further investigation rather than assigning an unsupported risk level.

---

## 3. Assessment Inputs

The risk and gap assessment uses the following current-state assessment components as inputs:

| Assessment Component | Primary Risk / Gap Inputs |
|---|---|
| 02 - Device Inventory | Device population, lifecycle, support status, connectivity, integration status, facility variation, preliminary risk indicators |
| 03 - Interface Inventory | Interfaces, information flows, dependencies, ownership, monitoring, criticality, unresolved technical information |
| 04 - Current-State Architecture | System relationships, connectivity paths, integration components, supporting services, architecture dependencies |
| 05 - Clinical Workflow Assessment | Workflow dependencies, clinical criticality, usability, information needs, operational constraints, continuity considerations |
| 06 - Cybersecurity Assessment | Device exposure, lifecycle-related security concerns, access, monitoring, security dependencies, areas requiring investigation |
| 07 - Current-State Findings | Consolidated findings, evidence gaps, cross-cutting observations, further investigation areas |
| 08 - Stakeholder Analysis | Stakeholder responsibilities, validation needs, ownership considerations, stakeholder dependencies, information gaps |

The assessment should maintain traceability to the source artifact wherever practical.

---

## 4. Risk Categories

The following categories are used to organize current-state risks and potential impacts:

- **Clinical and Patient Safety**
- **Clinical Workflow and Usability**
- **Device Lifecycle and Support**
- **Connectivity and Infrastructure**
- **Integration and Information Flow**
- **Cybersecurity**
- **Monitoring and Visibility**
- **Operational Continuity**
- **Ownership and Governance**
- **Evidence and Validation**
- **Decision Readiness**

A single condition may affect more than one category.

---

## 5. Current-State Risk Register

The following register identifies representative risks arising from the current-state assessment.

Risk descriptions are intentionally framed according to the evidence available. Where additional validation is required, the item is not treated as a confirmed risk rating.

| ID | Risk Area | Current-State Condition / Concern | Potential Impact | Supporting Evidence | Assessment Status |
|---|---|---|---|---|---|
| R-01 | Device Lifecycle and Support | Varying device lifecycle and vendor-support conditions exist across the assessed population | May affect device supportability, operational continuity, integration dependencies, and security considerations | 02 Device Inventory; 05 Clinical Workflow; 06 Cybersecurity | Requires further assessment |
| R-02 | Connectivity and Integration | Connected devices may have differing connectivity and integration characteristics | May increase interface dependencies and create variation in information flow or operational support | 02 Device Inventory; 03 Interface Inventory; 04 Architecture | Requires further assessment |
| R-03 | Integration and Information Flow | Some interface and information-flow characteristics remain vendor- or system-dependent | May limit confidence in current-state integration behavior and failure dependencies | 03 Interface Inventory; 04 Architecture | Requires validation |
| R-04 | Clinical Workflow | Clinical workflows depend on device availability, information access, connectivity, and operational processes | Connectivity, device, or information-flow limitations may affect workflow continuity | 05 Clinical Workflow Assessment | Requires further validation |
| R-05 | Cybersecurity | Security considerations are affected by device lifecycle, connectivity, access, and monitoring conditions | May create cybersecurity or operational concerns that require additional investigation | 06 Cybersecurity Assessment | Requires further investigation |
| R-06 | Monitoring and Visibility | Monitoring and visibility dependencies exist across device, network, interface, and operational components | Limited visibility may delay identification or investigation of device, connectivity, or interface conditions | 03 Interface Inventory; 04 Architecture; 06 Cybersecurity | Requires validation |
| R-07 | Facility Variation | Device, lifecycle, connectivity, support, and workflow conditions may vary by facility | A consolidated finding may not apply consistently across all assessed locations | 02 Device Inventory; 05 Clinical Workflow; 08 Stakeholder Analysis | Requires further assessment |
| R-08 | Ownership and Dependencies | Ownership of certain devices, interfaces, monitoring functions, or information flows may require additional clarification | Unclear ownership may affect support, escalation, monitoring, and decision-making | 03 Interface Inventory; 08 Stakeholder Analysis | Requires validation |
| R-09 | Evidence Quality | Some current-state technical, workflow, lifecycle, and cybersecurity information remains incomplete or requires validation | Limits confidence in certain findings and may affect decision readiness | 03 Interface Inventory; 05 Clinical Workflow; 06 Cybersecurity; 07 Findings | Requires further investigation |
| R-10 | Decision Readiness | Additional evidence and stakeholder validation may be required before subsequent modernization decisions can be supported | Decisions based on incomplete current-state information may carry additional uncertainty | 07 Current-State Findings; 08 Stakeholder Analysis | Requires further validation |

These risk statements represent assessment considerations rather than final enterprise risk ratings.

---

## 6. Gap Assessment

The following gaps represent areas where current-state information, visibility, ownership, validation, or supporting evidence may be incomplete.

| ID | Gap Area | Current-State Gap | Potential Effect | Supporting Evidence | Status |
|---|---|---|---|---|---|
| G-01 | Device Information | Additional validation may be required for selected device attributes, lifecycle conditions, and support information | May limit confidence in device-level assessment conclusions | 02 Device Inventory | Requires validation |
| G-02 | Interface Information | Certain interface protocols, transport characteristics, ownership, or technical details remain TBD | Limits confidence in detailed interface characterization | 03 Interface Inventory; 04 Architecture | Requires validation |
| G-03 | Information Flow | Additional confirmation may be required regarding information exchanged between selected systems and components | May limit understanding of operational and workflow dependencies | 03 Interface Inventory; 04 Architecture; 05 Clinical Workflow | Requires investigation |
| G-04 | Workflow Evidence | Some workflow observations and dependencies require stakeholder or clinical validation | May limit confidence in conclusions regarding usability, workarounds, or operational impact | 05 Clinical Workflow; 08 Stakeholder Analysis | Requires validation |
| G-05 | Cybersecurity Evidence | Additional evidence may be required regarding device security support, access, monitoring, and lifecycle-related security conditions | May limit confidence in cybersecurity risk characterization | 06 Cybersecurity Assessment | Requires investigation |
| G-06 | Monitoring Visibility | Current monitoring coverage and responsibilities may require additional validation | May limit visibility into device, network, or interface conditions | 03 Interface Inventory; 04 Architecture; 06 Cybersecurity | Requires validation |
| G-07 | Ownership | Ownership and support responsibilities for selected interfaces, systems, monitoring functions, or dependencies may require clarification | May create operational and escalation uncertainty | 03 Interface Inventory; 08 Stakeholder Analysis | Requires validation |
| G-08 | Facility Variation | Additional facility-level information may be required to determine whether conditions are consistent across the assessed population | May affect applicability of consolidated findings | 02 Device Inventory; 05 Clinical Workflow; 08 Stakeholder Analysis | Requires investigation |
| G-09 | Evidence Traceability | Some findings depend on information that is stakeholder-reported or requires additional validation | May affect assessment confidence and decision readiness | 07 Current-State Findings; 08 Stakeholder Analysis | Requires validation |
| G-10 | Decision Information | Additional evidence may be needed before subsequent modernization decisions can be appropriately evaluated | May limit decision readiness | 07 Current-State Findings | Requires further investigation |

---

## 7. Cross-Cutting Risk and Gap Observations

Several conditions span multiple assessment domains rather than belonging to a single technical or operational category.

### 7.1 Lifecycle and Support

Differences in device lifecycle position, vendor support, and device characteristics may affect:

- Device supportability
- Maintenance dependencies
- Integration conditions
- Security considerations
- Operational continuity
- Future decision readiness

The assessment does not assume that lifecycle status alone establishes a specific clinical or cybersecurity risk. Additional validation may be required to determine the significance of individual conditions.

### 7.2 Connectivity and Integration

The assessed environment contains dependencies among infusion pumps, network infrastructure, integration components, clinical systems, monitoring functions, and supporting services.

Variation in connectivity or integration characteristics may increase the complexity of understanding:

- Information flows
- Interface dependencies
- Monitoring
- Operational support
- Failure dependencies
- Workflow impacts

Where technical interface characteristics remain TBD, they should remain identified as validation items rather than being replaced with assumed protocols or technologies.

### 7.3 Clinical Workflow

Clinical workflow considerations connect device availability and information flow with operational use.

Potential areas requiring validation include:

- Device availability
- Information access
- Workflow dependencies
- Usability
- Workarounds
- Connectivity-related workflow effects
- Clinical continuity

Workflow impacts should be validated with appropriate clinical stakeholders before being treated as confirmed findings.

### 7.4 Cybersecurity

Cybersecurity considerations are closely related to:

- Device lifecycle
- Connectivity
- Access
- Monitoring
- Security support
- Vendor dependencies
- Operational processes

The assessment identifies these relationships for further investigation rather than defining future-state cybersecurity controls or remediation activities.

### 7.5 Monitoring and Visibility

Monitoring dependencies exist across multiple components of the current environment.

Additional validation may be required to determine:

- What is monitored
- How monitoring is performed
- Who owns monitoring
- What alerts are generated
- How conditions are escalated
- Whether monitoring differs by facility or system

### 7.6 Evidence and Validation

Evidence quality is itself an assessment consideration.

Where information is incomplete, stakeholder-reported, vendor-provided, or otherwise unvalidated, the assessment should preserve that distinction.

Unresolved evidence gaps should not be converted into confirmed findings solely to create a complete risk register.

---

## 8. Risk and Gap Prioritization Considerations

The assessment uses the following considerations when determining which risks and gaps require additional attention:

- Clinical criticality
- Patient safety and clinical continuity
- Device lifecycle and support conditions
- Connectivity and exposure
- Integration and information-flow dependencies
- Security support and update considerations
- Monitoring and visibility
- Clinical workflow impact
- Operational continuity
- Ownership and escalation dependencies
- Evidence quality
- Degree of uncertainty
- Potential effect on decision readiness

These considerations are used to guide additional investigation and validation.

They are not intended to establish a formal enterprise risk score unless sufficient evidence and an approved risk methodology are available.

### Priority Interpretation

| Priority Consideration | Interpretation |
|---|---|
| Higher attention required | Condition may have significant clinical, operational, technical, cybersecurity, or decision-readiness implications and warrants additional investigation |
| Moderate attention required | Condition may affect assessment confidence or operational dependencies and should be validated |
| Evidence gap | Insufficient information exists to determine the significance of the condition |
| Validation required | Existing information should be confirmed with an appropriate stakeholder or evidence source |
| Further investigation required | Additional discovery is necessary before the condition can be characterized confidently |

---

## 9. Risk, Gap, and Evidence Traceability

Risk and gap assessment should remain traceable to the underlying current-state artifacts.

The following relationships provide the primary traceability structure:

| Assessment Area | Primary Supporting Artifacts |
|---|---|
| Device population and lifecycle | 02 Device Inventory |
| Interfaces and information flows | 03 Interface Inventory |
| System and infrastructure relationships | 04 Current-State Architecture |
| Clinical workflow and usability | 05 Clinical Workflow Assessment |
| Cybersecurity considerations | 06 Cybersecurity Assessment |
| Consolidated findings | 07 Current-State Findings |
| Stakeholder ownership and validation | 08 Stakeholder Analysis |
| Risk and gap characterization | 09 Risk and Gap Assessment |

Where a risk or gap depends on multiple domains, supporting artifacts should be identified rather than attributing the condition to a single source.

---

## 10. Areas Requiring Further Investigation

The following areas remain appropriate for additional discovery or validation:

- Confirm device lifecycle and vendor-support conditions where information remains incomplete
- Validate selected device connectivity and integration characteristics
- Confirm interface ownership and technical characteristics
- Validate information flows and operational dependencies
- Confirm workflow and usability observations with appropriate clinical stakeholders
- Validate monitoring coverage and operational ownership
- Clarify cybersecurity visibility, access, lifecycle, and monitoring conditions
- Confirm facility-specific differences where they may affect consolidated findings
- Resolve ownership questions involving devices, interfaces, monitoring, or supporting services
- Validate stakeholder-reported information before treating it as confirmed evidence
- Determine whether remaining evidence gaps materially affect decision readiness

These items remain within current-state discovery and do not constitute future-state requirements or remediation activities.

---

## 11. Decision-Readiness Considerations

The purpose of the risk and gap assessment is not to determine whether modernization should proceed.

Instead, it helps identify whether sufficient current-state information exists to support subsequent analysis and decision-making.

Decision-readiness considerations include:

- Whether the assessed device population is sufficiently understood
- Whether lifecycle and support conditions are sufficiently characterized
- Whether important interfaces and information flows are understood
- Whether clinical workflow dependencies have been appropriately validated
- Whether cybersecurity considerations have sufficient supporting evidence
- Whether monitoring and ownership dependencies are understood
- Whether significant facility variation has been identified
- Whether material evidence gaps remain unresolved
- Whether stakeholder perspectives have been appropriately validated
- Whether remaining uncertainty is clearly documented

A condition may be considered decision-relevant without representing a recommendation or requirement.

Where material evidence gaps remain, the appropriate outcome may be to identify additional discovery or validation rather than proceed directly to solution definition.

---

## 12. Assessment Outcome

The risk and gap assessment consolidates current-state risks, gaps, dependencies, evidence limitations, and areas requiring further investigation across the Heartland legacy infusion-pump environment.

The assessment establishes:

- A structured view of current-state risk areas
- A structured view of information and evidence gaps
- Potential clinical, operational, technical, integration, and cybersecurity impacts
- Dependencies requiring additional validation
- Traceability to supporting assessment artifacts
- Prioritization considerations for further investigation
- Decision-readiness considerations

The assessment supports the principle of **understand before recommending** by identifying where current-state evidence is sufficient and where additional discovery is required.

---

## 13. Scope and Limitations

This risk and gap assessment is part of a fictional, discovery-only current-state assessment for Heartland Integrated Health System.

The assessment does not constitute:

- A formal enterprise risk assessment
- A regulatory compliance assessment
- A cybersecurity certification
- A clinical safety determination
- A future-state architecture
- A modernization recommendation
- A procurement recommendation
- A remediation plan
- An implementation plan
- A production risk acceptance decision

Risk and gap statements are based on the current assessment artifacts and available information.

Where evidence is incomplete, stakeholder-reported, vendor-provided, or otherwise unvalidated, the assessment identifies the condition as requiring validation or further investigation rather than treating it as confirmed.

Risk and gap priorities may change as additional evidence, stakeholder input, technical validation, or facility-specific information becomes available.

This artifact should be updated if subsequent discovery materially changes the current-state understanding, evidence quality, risk characterization, or decision-readiness assessment.
