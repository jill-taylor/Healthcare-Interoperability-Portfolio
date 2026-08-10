# 1. Purpose

The purpose of this document is to establish a current-state baseline of the interfaces and integration dependencies associated with the Heartland Integrated Health System (HIHS) infusion-pump environment.

The inventory identifies the systems, devices, applications, and infrastructure components involved in exchanging information or supporting connectivity within the modernization scope.

The interface inventory provides a foundation for current-state architecture, cybersecurity, clinical workflow, risk assessment, and modernization planning.

---

# 2. Interface Scope

The inventory focuses on interfaces and integration dependencies that may affect the selected infusion-pump environment.

The assessment includes:

- Device-to-system connectivity
- Application-to-application interfaces
- Integration gateway dependencies
- Interface engine dependencies
- Network monitoring
- Asset and configuration data synchronization
- Vendor support dependencies
- Security and identity dependencies
- Interface monitoring and operational support

The inventory does not attempt to document every interface within HIHS. Interfaces are included when they may affect device connectivity, clinical information exchange, operational support, cybersecurity, or modernization decisions.


---

# 3. Interface Attributes

Each interface record will capture the following information:

| Attribute | Description |
|---|---|
| Interface ID | Unique identifier assigned to the interface |
| Source System | System or component originating the information |
| Target System | System or component receiving the information |
| Information Exchanged | General description of information exchanged |
| Interface Type | General integration or connectivity mechanism |
| Connectivity | Network or other connectivity dependency |
| Integration Status | Current integration condition |
| Primary Owner | Team responsible for the interface |
| Criticality | Preliminary operational importance |
| Failure Handling | Expected response when the interface is unavailable |
| Dependencies | Systems, infrastructure, vendors, or services required |
| Notes | Relevant assumptions, unknowns, or validation requirements |


---

# 4. Interface Inventory

The detailed interface inventory is maintained in the accompanying
[`heartland_interface_inventory.csv`](../../data/heartland_interface_inventory.csv)
dataset.

The current-state baseline contains 12 representative interfaces and integration dependencies.

| Category | Count |
|---|---|
| Active | 8 |
| Partial | 3 |
| Non-integrated | 1 |
| High Critically | 7 |
| Moderate Criticality | 5 |

---

# 5. Key Integration Dependencies

The preliminary interface inventory identifies several dependencies that require additional discovery and validation:

- Infusion integration gateway
- Enterprise interface engine
- EHR
- Network infrastructure
- Network monitoring
- Clinical Engineering and IT asset records
- Vendor support services
- Identity and access management
- Interface monitoring and alerting

---

# 6. Validation Requirements

The interface inventory is a working current-state baseline and requires validation with appropriate subject matter experts.

Validation should confirm:

- Actual source and target systems
- Data exchanged
- Interface protocols and message types
- Devices using each interface
- Interface ownership
- Failure and downtime procedures
- Monitoring coverage
- Security dependencies
- Vendor dependencies
- Facility-specific differences

Unknown or conflicting information should be documented rather than assumed.

