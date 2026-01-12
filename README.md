# Flight Delay Analysis – AOCC Operations Project

## Overview
This project analyzes flight departure delays using real-world AOCC-style data.
The objective is to classify delays, identify SLA breaches, and understand
operational impact on airline performance.

The analysis focuses on delay minutes, delay reasons, aircraft types,
and SLA compliance to support better decision-making in airport operations.

## Dataset Details
The dataset includes the following fields:
- Flight Number
- Destination
- STD (Scheduled Time of Departure)
- ATD (Actual Time of Departure)
- Aircraft Type
- Delay Reason
- Delay Minutes
- Delay Category
- SLA Status

## Delay Classification Logic
Delays are categorized based on delay minutes:
- On Time: 0–5 minutes
- Minor Delay: 6–15 minutes
- Major Delay: More than 15 minutes

SLA status is identified as:
- Within SLA
- Breach

## Tools Used
- Microsoft Excel
- Excel formulas (IF conditions)
- Conditional Formatting
- Manual data validation

## Key Insights
- Identified flights breaching SLA due to major delays
- Analyzed frequent delay reasons such as weather and late incoming aircraft
- Classified operational impact using delay categories
- Highlighted high-risk flights using color-coded SLA status

## Business Impact
This analysis helps AOCC and operations teams to:
- Monitor SLA compliance
- Quickly identify critical delays
- Improve coordination during irregular operations
- Support data-driven operational decisions

## Files Included
- Flight_Delay_Analysis.xlsx

## Author
Amlin Shaffi
