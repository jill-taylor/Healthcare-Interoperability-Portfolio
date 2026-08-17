# Current-State Architecture

## 1. Purpose

The purpose of this document is to establish a current-state architectural view of the Heartland Integrated Health System (HIHS) legacy connected infusion-pump environment.

The architecture describes the major devices, systems, applications, infrastructure, integration components, and supporting services within the modernization scope. It also identifies the relationships and dependencies among these components and provides a foundation for understanding current-state information flows.

The architecture represents the fictional current-state environment established for this portfolio. It is intended to demonstrate how architectural information would be documented, validated, and analyzed during an actual healthcare technology modernization effort.

---

## 2. Architecture Scope

The current-state architecture focuses on the selected HIHS infusion-pump environment and the technical and operational dependencies that support it.

The architecture includes:

- Network-connected infusion pumps
- Network infrastructure
- Infusion integration gateway
- Enterprise interface engine
- EHR and relevant supporting clinical systems
- Interface monitoring and alerting
- Network monitoring
- Identity and access management
- Clinical Engineering and IT asset records
- Vendor support dependencies
- Relevant cybersecurity and operational boundaries
- Major information and integration flows

The architecture does not attempt to document the complete enterprise architecture of HIHS. Components are included when they directly support, connect to, monitor, secure, or otherwise affect the selected infusion-pump environment.

---

## 3. Architecture Components

The current-state environment includes several categories of components that work together to support connected infusion-pump operations.

| Component | Role in Current State | Primary Dependency |
|---|---|---|
| Infusion Pumps | Deliver and record infusion-related device activity | Network connectivity, device configuration, clinical workflow |
| Network Infrastructure | Provides connectivity between devices and supporting systems | Network availability, configuration, security controls |
| Infusion Integration Gateway | Provides device-specific integration capabilities | Network, device configuration, vendor support |
| Enterprise Interface Engine | Routes and manages information exchanged between systems | Integration gateway, EHR, interface configuration |
| EHR | Receives and/or provides relevant clinical information | Interface engine, network, identity/access |
| Network Monitoring | Monitors network availability and connectivity | Network infrastructure, monitoring platform |
| Interface Monitoring | Monitors interface availability and operational status | Interface engine, integration components |
| Identity and Access Management | Supports authentication and access controls for applicable systems | Directory and security infrastructure |
| Clinical Engineering / IT Asset Records | Maintains device and asset information | Device inventory, support processes |
| Vendor Support Services | Provides device, software, maintenance, and technical support | Vendor agreements, device lifecycle |
