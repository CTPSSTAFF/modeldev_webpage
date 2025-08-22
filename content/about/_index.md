---
title: "About the Project"
---

### What is FTA STOPS?

The **Simplified-Trips-on-Project Software (STOPS)** is a stand-alone computer program developed by the Federal Transit Administration (FTA) that applies a set of travel models to predict detailed transit travel patterns for user-specified scenarios.

Since its original release in 2013, STOPS has been used for a wide range of applications, including transit alternative analysis, service planning, long-range transportation planning, and for predicting measures for FTA Capital Investment Grant (CIG) projects.

STOPS has four main approaches for developing an application:

* **Synthetic:** Relies on Census Transportation Planning Package (CTPP) data and demographic data from a regional travel model to estimate transit trips. This approach is mainly used when very sparse or no data regarding actual transit travel patterns is available.
* **Incremental:** Relies on data from a comprehensive transit origin-destination on-board survey as the basis for developing person trips and calibrating the model.
* **Synthetic with Special Markets:** Uses the "Synthetic" approach but supplements it with data for distinct travel patterns not captured by CTPP data, such as large airports, universities, or tourist areas.
* **Synthetic + Incremental:** Combines both approaches, suitable for when a transit survey exists but the modeling area needs to be larger to cover a full project service area.

---

### Boston Region Implementation

The Boston Region STOPS model was developed, calibrated, and tested using STOPS version 2.53. It was prepared for the Boston Region Metropolitan Planning Organization (MPO) to support regional transportation planning and analysis.

#### Modeling Approach
This model uses the **“Synthetic with Special Markets”** STOPS approach. Due to the absence of a recent, detailed origin-destination on-board survey covering all routes, the "Synthetic" method was selected. This was supplemented with a special market trip table for air passengers traveling to and from Boston Logan International Airport. The model reflects average weekday ridership in the fall of 2024.

#### Modeling Area
The geographic coverage of the model includes the states of Massachusetts (MA), Rhode Island (RI), and New Hampshire (NH), generally aligning with the latest regional travel demand model. Within STOPS, trip movements are configured to include flows within Massachusetts and inter-state flows between MA and NH, and MA and RI. Trip movements entirely within RI and NH are excluded from the analysis.

STOPS only analyzes zones whose centroids fall within 25 miles of an active transit stop, which means the western portion of Massachusetts and the northern portion of New Hampshire are not included in the active modeling area.