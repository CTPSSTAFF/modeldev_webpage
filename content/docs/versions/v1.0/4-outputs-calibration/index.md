---
title: "4. Model Calibration & Outputs"
---

This chapter describes the adjustments made to calibrate the model to observed conditions and summarizes the final STOPS estimates.

### Calibration Adjustments
To calibrate the model to local conditions, several adjustments were made to STOPS parameters and input files, including:
- **Transfer Penalty:** Adjusted to 3.0 minutes to reflect the difficulty of transferring between routes.
- **Auto Time Adjustment:** Constants and factors were applied to normalize MPO travel times to observed congested highway travel times.
- **ACS Zone Splits:** Several large census zones were split to align more closely with the TAZ boundaries, adding approximately 900 zones.
![Example of ACS Zone Splits](/boston-region-stops/images/documentation/v1.0/3-inputs/acs-zone-splits.jpg "Example of ACS Zone Splits")
- **Fare File:** The value of time (VOT) was increased, and ferry/commuter rail fares were adjusted to reflect monthly pass rates.
- **Station Penalties:** Penalties were added at many park-and-ride (PNR) lots to reflect actual parking capacities.

### Calibration Results
The calibration results reflect ridership on an average weekday in September/October 2024. The model was compared against observed data from sources like the 2023 MBTA Passenger Survey. STOPS produces boarding estimates by mode (Heavy Rail, Light Rail, Bus, etc.) that closely match the observed values for the MBTA and other regional transit agencies.