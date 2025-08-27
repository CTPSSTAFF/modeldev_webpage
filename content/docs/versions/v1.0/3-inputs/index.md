---
title: "3. Model Inputs"
---

This chapter describes the sources of the key input data used to develop the Boston Regional STOPS Model.

### Analysis Years
The model is configured for several analysis years to support both short-term and long-range planning:
* **Current Year:** 2024 (the calibration year)
* **10-Year Horizon:** 2045 (to align with FTA CIG project requirements)
* **20-Year Horizon:** 2050 (aligning with the region's Long-Range Transportation Plan)

### Key Data Sources

#### MPO Data
Data from the Boston Region MPO's regional travel demand model is a critical input. This includes:
* **Population and Employment:** TAZ-level data for 2019 (as a proxy for 2024) and 2050 is used to grow census-based trip data to the correct analysis years.
* **Auto Travel Times:** Zone-to-zone AM peak period auto travel times and distances (skims) for 2019 and 2050 are used.

#### Transit Network (GTFS)
The General Transit Feed Specification (GTFS) format represents the transit network. The model includes Fall 2024 GTFS data for five regional transit authorities:
* Massachusetts Bay Transportation Authority (MBTA)
* Brockton Area Transit Authority (BATA)
* Cape Ann Transportation Authority (CATA)
* Merrimack Valley Regional Transit Authority (MVRTA)
* MetroWest Regional Transit Authority (MWRTA)

A separate 2050 GTFS network was developed for the MBTA to reflect long-range plans, including a redesigned bus network.

#### Existing Ridership Data
The model calibration target for current year regional weekday unlinked transit trips is set at **887,322 boardings**. This figure is based on Fall 2024 data from the MBTA, the National Transit Database (NTD), and other regional sources.

#### Census Data
The model relies on the **2012-2016 American Community Survey (ACS)** and Census Transportation Planning Package (CTPP) Journey-to-Work datasets for base-year travel patterns.

### Other Key Input Files
* **Special Market File:** A file containing zone-to-zone transit trips for air passengers traveling to/from Logan Airport.
* **Station Shape File:** Includes locations and key attributes (like observed boardings) for every transit stop in the region.
* **Walk Links File:** A hybrid pedestrian network representing walk access to the transit system, with higher detail in transit-dense areas.
* **Fare Structure File:** A simplified representation of the region’s complex transit fare system.