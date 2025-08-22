---
title: "6. Example Application & Forecasts (v0.1)"
---

This chapter presents a test application of the Boston Regional STOPS model for a corridor and provides horizon year forecasts.

### Example: Corridor Calibration
Before applying the model to a specific corridor (e.g., Blue Hill Avenue), inputs and results must be reviewed to ensure consistency with local conditions. This can involve:
1.  Isolating specific routes (e.g., fare-free buses) in a new GTFS folder.
2.  Updating the STOPS parameter file and fare file to reflect the new GTFS.
3.  Updating district definitions and station groupings to provide more geographic detail.

### Sensitivity Tests
Tests were conducted to see how changes to service affect model outputs. Results confirmed that the calibrated model responds plausibly to service and operating changes, such as frequency reductions or travel time improvements.

### Horizon Year Forecasts
The model includes ridership forecasts for the years 2045 and 2050, accounting for projected changes in population, employment, and the transit network.
- **2045 Forecast:** Regional transit boardings are forecasted to increase by **38%** compared to 2024.
- **2050 Forecast:** Regional transit boardings are forecasted to increase by **43%** compared to 2024.