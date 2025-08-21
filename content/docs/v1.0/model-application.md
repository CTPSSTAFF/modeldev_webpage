---
title: "3. Model Application"
weight: 13
---

This chapter describes the key model files that should be reviewed and updated when applying the model to a transit project.

### 3.1 Regional vs. Corridor Calibration
While the model has been calibrated at a regional level, users should carefully review outputs for their specific corridor of interest before developing ridership forecasts.

### 3.2 Define Forecast Years & MPO Data
In Step 4, users can define additional forecast years. This requires adding new population and employment fields to the `MPO0000TAZPopEmp.shp` file and updating highway travel time skims.

### 3.3 Transit Network (GTFS)
The transit system is represented by GTFS data for the MBTA, BATA, CATA, MVRTA, and MWRTA. The "Existing" scenario represents service as of September/October 2024.

### 3.4 Park and Rides
STOPS uses an additional file, `pnr.txt`, located within each GTFS folder to define park-and-ride locations, capacities, and costs.