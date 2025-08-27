---
title: "2. Model Configuration"
---

This chapter describes the specific configuration of the Boston Regional STOPS model, which was developed and calibrated using **STOPS version 2.53**.

### Modeling Area
The geographic coverage of the model includes the states of **Massachusetts (MA)**, **Rhode Island (RI)**, and **New Hampshire (NH)**, generally aligning with the latest regional travel demand model.

While input files cover all three states, STOPS only actively analyzes zones whose centroids fall within 25 miles of a transit stop. This means the western portion of Massachusetts and the northern part of New Hampshire are not included in the active modeling area. Additionally, trip movements entirely within Rhode Island or New Hampshire are excluded from the analysis.

![STOPS Modeling Area Map](/boston-region-stops/images/documentation/v1.0/1-introduction/model-area.jpg "STOPS Modeling Area")

### Modeling Approach
The model uses the **“Synthetic with Special Markets”** approach. This method was chosen due to the absence of a recent, comprehensive origin-destination on-board survey. The "Synthetic" method, which uses census data, was supplemented with a special market trip table for travelers using **Boston Logan International Airport**. The model is calibrated to reflect average weekday ridership in fall 2024.

### District System
STOPS uses districts to group Traffic Analysis Zones (TAZs) for scaling trip data and for reporting outputs. The districts in this model are defined to align with the boundaries used in the regional travel demand model, with a total of **35 districts**.

![Map of the 35 districts in the STOPS model](/boston-region-stops/images/documentation/v1.0/2-configuration/model-districts.jpg "Regional View of STOPS Districts")
*Regional View*

![Map of the urban area districts with rail and ferry stations](/boston-region-stops/images/documentation/v1.0/2-configuration/urban-area-view-with-rail-and-ferry-stations.jpg "Urban Area View of STOPS Districts")
*Urban Area View with Rail and Ferry Stations*

### Fixed Guideway Settings (FGS)
FGS values approximate the perceived benefits of fixed-guideway transit (like rail) compared to regular bus service.
* **Full FGS** is applied to all existing heavy rail, light rail, commuter rail, and ferry services.
* **Partial FGS** can be applied to services like Bus Rapid Transit (BRT), but no routes are currently assigned a Partial FGS in this model.