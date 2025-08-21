---
title: "Boston Region Implementation"
weight: 2
---

The Boston Region STOPS model was developed, calibrated, and tested using STOPS version 2.53. It was prepared for the Boston Region Metropolitan Planning Organization (MPO) to support regional transportation planning and analysis.

### Modeling Approach
This model uses the **“Synthetic with Special Markets”** STOPS approach. Due to the absence of a recent, detailed origin-destination on-board survey covering all routes, the "Synthetic" method was selected. This was supplemented with a special market trip table for air passengers traveling to and from Boston Logan International Airport. The model reflects average weekday ridership in the fall of 2024.

### Modeling Area
The geographic coverage of the model includes the states of Massachusetts (MA), Rhode Island (RI), and New Hampshire (NH), generally aligning with the latest regional travel demand model. Within STOPS, trip movements are configured to include flows within Massachusetts and inter-state flows between MA and NH, and MA and RI. Trip movements entirely within RI and NH are excluded from the analysis.



STOPS only analyzes zones whose centroids fall within 25 miles of an active transit stop, which means the western portion of Massachusetts and the northern portion of New Hampshire are not included in the active modeling area.