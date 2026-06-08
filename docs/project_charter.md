# Project Charter

# Urban Mobility Shock Absorber

## 1. Project Overview

Urban transportation systems are highly dependent on centralized public transit infrastructure. When major disruptions occur, such as transit strikes or network failures, commuters must rapidly adapt and seek alternative means of transportation.

This project aims to quantify the role of micro-mobility systems as urban "shock absorbers" during such disruptions. Specifically, the project will investigate how London's bike-sharing network responds to London Underground strike events and measure the extent to which bike-sharing absorbs displaced transit demand.

The study will use historical transportation datasets to identify behavioral shifts in mobility patterns during disruption events and evaluate the resilience of decentralized transportation alternatives.

---

## 2. Problem Statement

Public transit disruptions create immediate mobility challenges for large urban populations. While it is generally assumed that commuters switch to alternative transportation modes during these events, there is limited quantitative evidence measuring:

* The magnitude of this behavioral shift
* The speed and scale of demand redistribution
* The geographic concentration of alternative mobility usage
* The effectiveness of alternative transportation systems in absorbing disrupted demand

This project seeks to address these gaps through data-driven analysis.

---

## 3. Research Question

To what extent does bike-sharing usage increase during London Underground strike events, and how effectively does the Santander Cycles network absorb mobility demand displaced by transit disruptions?

---

## 4. Project Objectives

### Primary Objective

Measure the relationship between London Underground disruption events and changes in bike-sharing usage.

### Secondary Objectives

* Quantify increases in bike-sharing demand during strike events.
* Identify geographic hotspots of mobility redistribution.
* Estimate the proportion of disrupted transit demand absorbed by bike-sharing.
* Analyze spatial patterns of mobility adaptation.
* Evaluate the role of bike-sharing as an urban resilience mechanism.

---

## 5. Project Scope

### Geographic Scope

London, United Kingdom.

### Transit System

London Underground.

### Alternative Mobility System

Santander Cycles bike-sharing network.

### Disruption Definition

London Underground strike events.

### Analysis Period

2020–2025.

### Geographic Focus

Areas served by both London Underground stations and Santander Cycles infrastructure.

---

## 6. Data Sources

### Santander Cycles Trip Data

Contents:

* Trip start station
* Trip end station
* Trip timestamp
* Trip duration

Coverage:
2014–2025

Purpose:
Primary source for measuring bike-sharing demand.

---

### London Underground Station Entry and Exit Counts

Contents:

* Station-level passenger counts
* Weekday and weekend breakdowns

Coverage:
2017–2025

Purpose:
Transit demand context and station importance analysis.

---

### London Underground Strike Event Records

Contents:

* Strike dates
* Strike duration
* Service disruption information

Purpose:
Identification of disruption events for event-based analysis.

---

### Geographic Data

Contents:

* Station coordinates
* Network locations
* Spatial reference information

Purpose:
Spatial analysis and mapping.

---

## 7. Key Performance Indicators (KPIs)

### KPI 1: Bike Usage Surge Percentage

Measures the relative increase in bike-sharing usage during strike events compared to baseline demand.

---

### KPI 2: Additional Trips Generated

Measures the absolute increase in bike-sharing trips during disruption periods.

---

### KPI 3: Station Impact Score

Measures which geographic areas experience the largest increases in bike-sharing demand.

---

### KPI 4: Absorption Capacity

Measures the proportion of disrupted transit demand absorbed by the bike-sharing network.

---

### KPI 5: Spatial Impact Radius

Measures how far disruption-induced demand shifts spread geographically.

---

## 8. Methodology

### Step 1

Identify and catalog London Underground strike events.

### Step 2

Collect and prepare Santander Cycles trip records.

### Step 3

Establish baseline bike-sharing demand using the previous four matching weekdays.

### Step 4

Measure bike-sharing activity during strike periods.

### Step 5

Calculate demand deltas between baseline and disruption periods.

### Step 6

Perform spatial analysis using station and geographic data.

### Step 7

Estimate bike-sharing absorption capacity.

### Step 8

Aggregate findings across multiple disruption events.

---

## 9. Assumptions

* Strike events represent meaningful transit disruptions.
* Santander Cycles usage serves as a measurable indicator of micro-mobility adoption.
* The previous four matching weekdays provide an appropriate baseline for expected demand.
* Observed demand increases are partially attributable to transit disruption effects.

---

## 10. Limitations

* Analysis focuses only on Santander Cycles and excludes other mobility services.
* Informal transportation modes are not included.
* Traffic and road network effects are not directly modeled.
* Causal relationships may be influenced by external factors such as weather or public events.

---

## 11. Success Criteria

The project will be considered successful if it:

* Quantifies bike-sharing demand changes during transit disruptions.
* Produces measurable estimates of absorption capacity.
* Identifies geographic patterns of mobility redistribution.
* Demonstrates a repeatable methodology for analyzing transportation resilience.
* Generates findings supported by historical transportation data.

---

## 12. Expected Deliverables

* Cleaned analytical datasets
* Exploratory data analysis notebooks
* Spatial mobility visualizations
* KPI calculations and dashboards
* Final analytical report
* Public GitHub repository documenting the project
