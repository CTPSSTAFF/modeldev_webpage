---
title: "3. Model Inputs"
---

This chapter describes the sources of the key input data used to develop the Boston Regional STOPS Model using STOPS version 2.53.

### Analysis Years
The model is configured for several analysis years:
- **Current Year:** 2024 (the calibration year)
- **10-Year Horizon:** 2045 (to align with FTA CIG project requirements)
- **20-Year Horizon:** 2050 (aligning with the region's Long-Range Transportation Plan)

### MPO Data
STOPS requires TAZ-level population and employment data and zone-to-zone auto travel times and distances as inputs. These are obtained from the Boston Region MPO's regional travel demand model for the years 2019 (as a proxy for 2024) and 2050.

### Transit Network (GTFS)
The General Transit Feed Specification (GTFS) format represents the transit network. The model includes Fall 2024 GTFS data for:
- Massachusetts Bay Transportation Authority (MBTA)
- Brockton Area Transit Authority (BATA)
- Cape Ann Transportation Authority (CATA)
- Merrimack Valley Regional Transit Authority (MVRTA)
- MetroWest Regional Transit Authority (MWRTA)

### Existing Ridership Data
The model calibration target for current year regional weekday unlinked transit trips is set at **887,322 boardings**, based on Fall 2024 data from the MBTA, National Transit Database (NTD), and other sources.

### Other Key Input Files
- **Special Market File:** A file containing zone-to-zone transit trips for air passengers traveling to/from Logan Airport.
- **Station Shape File:** Includes locations and attributes for every transit stop in the region.
- **Walk Links File:** A hybrid pedestrian network representing walk access to the transit system.
- **Fare Structure File:** A simplified representation of the region’s transit fare system.