# 1. Purpose

The purpose of this document is to establish the current-state baseline for legacy infusion pumps within the scope of the Heartland Integrated Health System (HIHS) modernization assessment.

The inventory identifies the devices in scope, their locations, technical characteristics, connectivity, integration status, lifecycle position, and vendor support status. This information will provide a common baseline for subsequent risk assessment, architecture analysis, modernization options, and implementation planning.

The inventory represents the fictional current-state environment established for this portfolio and is intended to demonstrate the types of information that would be collected and reconciled during an actual healthcare technology discovery effort.

---

# 2. Inventory Scope

The inventory includes infusion pumps operated within the selected HIHS facilities that may be affected by the modernization initiative.

The initial system-wide population is established at approximately 480 infusion pumps distributed across hospitals and selected community facilities.

The inventory will distinguish between:

- Network-connected and non-network-connected devices
- Supported and unsupported device models
- Devices with different lifecycle positions
- Devices with different integration characteristics
- Devices operating in different clinical environments
- Devices with different levels of modernization risk

Not every device in the inventory will necessarily require replacement or modernization. The purpose of the assessment is to identify the characteristics, dependencies, and risks that should inform subsequent decision-making.

---

# 3. Facility Distribution

| Facility | Facility Type | Infusion Pumps |
|---|---|---:|
| Heartland Regional Medical Center | Regional Medical Center | 280 |
| Heartland Community Hospital | Community Hospital | 100 |
| Heartland Rural Hospital North | Rural Hospital | 40 |
| Heartland Rural Hospital South | Rural Hospital | 30 |
| Heartland Community Clinic Network | Community Clinics | 30 |
| **Total** | | **480** |

---

# 4. Inventory Attributes

Each device record will capture the following information:

| Attribute | Description |
|---|---|
| Device ID | Unique identifier assigned to the device |
| Facility | Facility where the device is primarily assigned |
| Clinical Area | Department or clinical environment |
| Manufacturer | Device manufacturer |
| Model | Device model |
| Year | Approximate year placed in service |
| Network Status | Network-connected, non-connected, or unknown |
| Integration Status | Integrated, capable, non-integrated, or unknown |
| Support Status | Current, limited, or unsupported |
| Lifecycle Status | Current, aging, end-of-life, or end-of-support |
| Maintenance Status | Current maintenance/support condition |
| Risk Tier | Preliminary relative risk classification |
| Notes | Relevant dependencies, exceptions, or observations |


---
# 5. Device Inventory

The current-state inventory contains 480 fictional infusion pumps distributed across the selected Heartland facilities.

The detailed device-level inventory is maintained in the accompanying `heartland_infusion_pump_inventory.csv` dataset.

The inventory includes device identity, facility, clinical area, manufacturer, model, age, network connectivity, integration status, vendor support, lifecycle status, maintenance status, and preliminary risk tier.

The inventory will serve as the baseline for subsequent risk assessment, interface analysis, geographic visualization, and modernization planning.

## Device Inventory Summary

## Model Summary

| Model | Manufacturer | Devices | Avg Age (Years) | Network Connected | Integrated | Limited Support | Unsupported | High Risk |
|---|---|---:|---:|---:|---:|---:|---:|---:|
| HI-100 | Heartland Medical Technologies | 90 | 15.3 | 0 | 0 | 41 | 49 | 90 |
| HI-200 | Heartland Medical Technologies | 150 | 10.0 | 102 | 36 | 44 | 0 | 6 |
| HI-300 | Apex Clinical Devices | 170 | 5.9 | 170 | 140 | 0 | 0 | 0 |
| HI-400 | Apex Clinical Devices | 70 | 2.6 | 70 | 67 | 0 | 0 | 0 |
| **Total** | | **480** | | **342** | **243** | **85** | **49** | **96** |

## Facility Summary

| Facility | Devices | Fleet % | Network Connected | Integrated | Aging or Beyond | Aging or Beyond % | End-of-Life | End-of-Support | Limited Support | Unsupported | High Risk | High Risk % |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Heartland Community Clinic Network | 30 | 6.2% | 22 | 16 | 19 | 63.3% | 4 | 3 | 5 | 5 | 8 | 26.7% |
| Heartland Community Hospital | 100 | 20.8% | 75 | 56 | 47 | 47.0% | 11 | 7 | 16 | 9 | 19 | 19.0% |
| Heartland Regional Medical Center | 280 | 58.3% | 190 | 129 | 147 | 52.5% | 41 | 13 | 54 | 26 | 57 | 20.4% |
| Heartland Rural Hospital North | 40 | 8.3% | 31 | 25 | 23 | 57.5% | 4 | 3 | 6 | 6 | 8 | 20.0% |
| Heartland Rural Hospital South | 30 | 6.2% | 24 | 17 | 16 | 53.3% | 3 | 1 | 4 | 3 | 4 | 13.3% |

> **Note:** The inventory is fictional and represents the current-state baseline established for this portfolio. Counts and risk tiers are preliminary and should be treated as assessment inputs rather than validated clinical or operational findings.
