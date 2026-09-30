# Heartland Integrated Health System (HIHS)

## Legacy Medical Device Modernization & Clinical Workflow Integration Project

This repository documents a fictional healthcare technology discovery and current-state assessment developed as a professional portfolio project in healthcare interoperability and technical project management.

Heartland Integrated Health System (HIHS) and the project scenario are fictional. The methodologies, project artifacts, healthcare technology concepts, and technical approaches presented throughout this repository are based on real-world healthcare technology and project management practices.

---

## Project Focus

HIHS has identified a population of legacy infusion pumps that may present operational, cybersecurity, lifecycle, workflow, and interoperability considerations.

The project uses a structured discovery and current-state assessment process to understand the device population, clinical workflows, information and communication flows, connectivity, integration dependencies, cybersecurity considerations, lifecycle and vendor-support conditions, risks, gaps, and areas requiring further investigation.

The project does not select, design, or implement a modernization solution. Findings are organized to support decision-readiness and inform potential future modernization analysis.

---

## Guiding Principle

**Discovery before solution.**

Successful healthcare technology projects require alignment among people, processes, clinical workflows, governance, cybersecurity, and technology.

This portfolio demonstrates how a Technical Project Manager can lead a focused healthcare technology discovery initiative by establishing the current state, engaging stakeholders, coordinating subject matter experts, assessing risks and dependencies, and using evidence to support future decision-making.

---

## Portfolio Focus

- Healthcare interoperability
- Technical project management
- Medical device modernization
- Clinical workflows
- Cybersecurity and risk
- Device connectivity and integration
- Current-state assessment
- Stakeholder management
- Lifecycle and vendor-support assessment
- Healthcare technology discovery
- QGIS and geographic visualization

---

## Project Approach

The project follows a structured discovery progression:

**Project Charter → Device Inventory → Interface Inventory → Current-State Architecture → Clinical Workflow Assessment → Cybersecurity Assessment → Current-State Findings**

The repository demonstrates how a healthcare technology project can move from project definition and evidence collection through current-state assessment and findings development while maintaining a clear boundary between discovery and future implementation.

### Discovery Boundary

This project is intentionally limited to the current-state discovery and assessment phase.

The project does **not** include:

- Future-state solution design
- Production implementation
- Production deployment
- Device configuration
- Production interface development
- Procurement
- Modernization roadmap development
- Post-project operational support

Future modernization options may be considered in a subsequent phase using the findings produced through discovery.

---

## Project Artifacts

### Project definition
- [Project Charter](documents/01-Project-Charter/Project-Charter.md)

### Current-state assessment
- [Heartland Environment](documents/02-Current-State-Assessment/01-Heartland-Environment.md)
- [Device Inventory](documents/02-Current-State-Assessment/02-Device-Inventory.md)
- [Interface Inventory](documents/02-Current-State-Assessment/03-Interface-Inventory.md)
- [Current-State Architecture (editable draw.io file)](documents/02-Current-State-Assessment/04-Current-State-Architecture.drawio)
- [Current-State Architecture (description)](documents/02-Current-State-Assessment/04-Current-State-Architecture.md)
- [Clinical Workflow Assessment](documents/02-Current-State-Assessment/05-Clinical-Workflow-Assessment.md)
- [Cybersecurity Assessment](documents/02-Current-State-Assessment/06-Cybersecurity-Assessment.md)
- [Current-State Findings](documents/02-Current-State-Assessment/07-Current-State-Findings.md)

### Discovery planning
- [Discovery Plan](documents/04-Discovery-Assessment/01-Discovery-Plan.md)

### Data
- [Infusion Pump Inventory (CSV)](data/heartland_infusion_pump_inventory.csv)
- [Interface Inventory (CSV)](data/heartland_interface_inventory.csv)
- [Device Summary by Facility](data/heartland_device_facility_summary.csv)
- [Device Summary by Model](data/heartland_device_model_summary.csv)

---

## Working with the Architecture Diagram

The editable draw.io source is stored at `documents/02-Current-State-Assessment/04-Current-State-Architecture.drawio`. Open it with [diagrams.net](https://app.diagrams.net/) using **File → Open From → Device**. After editing, save the `.drawio` file and commit the updated version to this same repository path.

The diagram is a source artifact; GitHub may not render it as an image in the README. Use diagrams.net to view and edit it.
