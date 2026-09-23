# 1. Purpose

The purpose of this assessment is to evaluate how the legacy connected infusion-pump environment supports current clinical workflows and to identify workflow, information, connectivity, lifecycle, and operational dependencies within the assessed environment.

The assessment focuses on the relationship between infusion pumps, clinical users, connected systems, information flows, device lifecycle, and workflow dependencies. It is intended to support current-state discovery, assessment, and identification of areas requiring further investigation.

# 2. Workflow Assessment Approach

The assessment considers the following sequence:

**Device Identification → Clinical Criticality → Connectivity → Information Flow → Lifecycle → Vendor Status → Workflow Dependencies → Risks & Constraints → Current-State Findings**

Each stage provides information needed to understand how the current infusion-pump environment supports clinical operations and where dependencies, gaps, risks, or questions may require further investigation.

# 3. Device Identification and Criticality

For each selected infusion pump, the assessment should establish:

- Device model and relevant attributes
- Physical location and facility
- Current lifecycle status
- Clinical function
- Degree of dependency within the clinical workflow
- Operational criticality
- Availability of alternative devices or processes

Device criticality should be considered in the context of the workflow that depends on the device and the potential operational impact if the device becomes unavailable.

The assessment should document available evidence, stakeholder input, and identified assumptions or unknowns rather than assume device capabilities or operational conditions that have not been validated.

# 4. Connectivity and Information Flow

The assessment should determine:

- Whether the device is network-connected
- How the device connects to the network environment
- Which systems or integration components it communicates with
- What information is exchanged
- How information moves through the integration environment
- What dependencies exist between the device, network, integration gateway, interface engine, and EHR or supporting systems

The current-state architecture identifies the infusion pump, network infrastructure, infusion integration gateway, enterprise interface engine, and EHR as major components within the assessed environment.

Connectivity and information-flow details should be validated where possible through available documentation and appropriate technical subject matter experts. Unknown or conflicting information should be documented rather than assumed.

# 5. Vendor and Lifecycle Assessment

The assessment should determine:

- Whether the device remains vendor-supported
- Whether software or firmware updates remain available
- Whether vendor-supported upgrades are available
- Whether the device has reached or exceeded its supported lifecycle
- Whether technical limitations affect the device's ability to meet identified operational or integration requirements
- Whether vendor documentation or support information is incomplete or unavailable

Devices that are no longer supported, have reached the end of their supported lifecycle, or have significant technical limitations should be identified as areas requiring further investigation.

The assessment should document vendor dependencies, lifecycle constraints, and known technical limitations without assuming a specific replacement, upgrade, isolation, or remediation approach.

# 6. Clinical Workflow Impact

The assessment should consider how the current infusion-pump environment supports clinical work and where technology, information, or connectivity dependencies may affect workflow.

The assessment should consider:

- Whether infusion pumps support the required clinical functions
- Whether relevant information is available at the appropriate point in the workflow
- Whether information flows support clinical and operational activities
- Whether manual steps or workarounds are required
- Whether users experience workflow interruptions or additional operational burden
- Whether workflow dependencies exist between infusion pumps and connected systems
- Whether device, connectivity, or integration limitations affect clinical operations
- Whether clinical continuity depends on specific devices, systems, interfaces, or support resources

The assessment should document observed or reported workflow dependencies, gaps, and constraints without assuming that a specific technology or modernization approach is required.

A key consideration is to identify where current technology supports the workflow and where limitations or dependencies may require further investigation.

# 7. Workflow Dependencies and Information Needs

The assessment should identify the people, systems, information, and operational dependencies associated with the current infusion-pump workflows.

The assessment should consider:

- Stakeholders involved in the workflow
- Information required at key workflow points
- Handoffs between clinical and technical teams
- Dependencies on connected systems or interfaces
- Dependencies on device support and maintenance resources
- Communication requirements associated with device operation and support
- Manual workarounds or information gaps
- Areas where ownership or responsibility may be unclear
- Workflow dependencies that may require additional investigation

The assessment should document current-state workflow dependencies and information needs without defining training, transition, deployment, or change-management activities.

# 8. Current-State Validation

The assessment should validate available information about devices, workflows, connectivity, information flows, lifecycle status, and operational dependencies with appropriate subject matter experts.

Validation activities should consider:

- Confirming device and workflow information
- Confirming connectivity and system relationships
- Confirming information exchanged between systems
- Confirming identified workflow dependencies
- Confirming lifecycle and vendor-support information
- Identifying conflicting or incomplete information
- Documenting assumptions and unresolved questions
- Identifying areas requiring additional technical, clinical, operational, or vendor investigation

Validation during discovery is intended to improve the accuracy and completeness of the current-state assessment. It does not constitute production testing, implementation testing, deployment, or operational validation.

# 9. Clinical Continuity Considerations

The assessment should consider how dependence on infusion pumps, connected systems, interfaces, and supporting resources may affect clinical continuity within the current environment.

The assessment should consider:

- Dependence on infusion pumps for clinical operations
- Availability of alternative devices or processes
- Dependencies on network, integration, and supporting systems
- Dependencies on clinical, technical, and vendor support resources
- Operational constraints that could affect continuity
- Communication requirements associated with device or system issues
- Known single points of dependency or limited alternatives
- Areas where additional investigation may be needed to understand continuity risks

Clinical continuity considerations identified during discovery should be documented as current-state dependencies, risks, constraints, or questions requiring further investigation.

This assessment does not define deployment schedules, rollback procedures, contingency plans, or other implementation activities.

# 10. Assessment Outcome

The Clinical Workflow Assessment will provide HIHS with a structured understanding of how legacy infusion pumps support current clinical operations and how workflow, information, connectivity, lifecycle, and operational dependencies affect the assessed environment.

The assessment will consolidate documented workflow dependencies, information needs, connectivity relationships, lifecycle considerations, risks, constraints, assumptions, and unresolved questions.

The findings will support subsequent current-state findings, risk and gap analysis, decision-readiness activities, and identification of areas requiring further investigation.
