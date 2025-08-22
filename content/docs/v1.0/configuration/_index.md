---
title: "2. Boston Region Configuration (v0.1)"
---

The Boston Regional STOPS model has a specific configuration tailored to the region's geography and transit systems.

### Modeling Area
The geographic coverage of the model includes the states of **Massachusetts (MA)**, **Rhode Island (RI)**, and **New Hampshire (NH)**, generally aligning with the latest regional travel demand model. STOPS only analyzes zones whose centroids fall within 25 miles of an active transit stop.

### Modeling Approach
The model uses the **“Synthetic with Special Markets”** approach. This method was chosen due to the absence of a recent, comprehensive origin-destination on-board survey. The "Synthetic" method, which uses census data, was supplemented with a special market trip table for travelers using Boston Logan International Airport. The model reflects average weekday ridership in fall 2024.

### District System
STOPS uses districts to group Traffic Analysis Zones (TAZs) for scaling trip data and for reporting outputs. The districts in this model are defined to align with the boundaries used in the regional travel demand model, with a total of **35 districts**.

### Fixed Guideway Settings (FGS)
FGS values approximate the perceived benefits of fixed-guideway transit (like rail) compared to regular bus service.
- **Full FGS** is applied to all existing heavy rail, light rail, commuter rail, and ferry services.
- **Partial FGS** applies to services like Bus Rapid Transit (BRT). No routes are currently assigned a Partial FGS in this model.