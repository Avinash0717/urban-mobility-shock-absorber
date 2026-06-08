# Research Log

## Project Title

Urban Mobility Shock Absorber

---

## Project Overview

This project aims to quantify the "shock absorber" effect of micro-mobility systems during major public transit disruptions. The central hypothesis is that when a large-scale transit network experiences service interruptions, commuters shift to decentralized transportation alternatives such as bike-sharing systems. By analyzing historical transit and bike-share data, the project seeks to measure the scale, speed, and spatial distribution of this behavioral shift.

---

## Initial Problem Statement

Modern metropolitan areas depend heavily on centralized public transportation systems. When these systems experience sudden disruptions such as strikes, line closures, or signal failures, large numbers of commuters are affected simultaneously.

While it is commonly assumed that travelers switch to alternative transportation modes during these events, there is limited quantitative evidence showing:

* How quickly commuters change travel behavior
* How much demand shifts to micro-mobility systems
* Which areas experience the largest changes
* How effectively alternative networks absorb disrupted transit demand

The objective of this project is to measure these effects using historical open transportation datasets.

---

## City Evaluation

### Candidate 1: Delhi

Delhi was initially considered due to my familiarity with its transportation ecosystem and commuter behavior patterns.

#### Advantages

* Large population and commuter volume
* Extensive public transportation network
* Strong last-mile transportation culture
* High practical relevance

#### Limitations

* Fragmented open-data ecosystem
* Limited availability of historical disruption records
* Inconsistent accessibility of micro-mobility datasets
* Greater effort required for data collection and validation

Due to concerns regarding data availability and project feasibility, alternative cities were evaluated.

---

## Selected City: London

London was selected as the primary study area because of its mature open-data ecosystem and extensive transportation infrastructure.

### Selection Rationale

* Large metropolitan population
* High public transit dependency
* Established bike-sharing network
* Rich historical datasets
* Strong support for spatial analysis
* Well-documented transit disruptions

London provides a suitable environment for studying mobility behavior during transportation disruptions while maintaining strong analytical rigor.

---

## Dataset Assessment

### Santander Cycles Trip Data

Status: Approved

Strengths:

* Trip-level records
* Start and end stations
* Timestamps
* Duration information
* Historical coverage from 2014–2025

Assessment:
This dataset provides the primary measure of micro-mobility usage and will serve as the core analytical dataset.

---

### Station Entry and Exit Counts

Status: Approved

Strengths:

* Station-level passenger counts
* Weekday and weekend breakdowns
* Historical coverage from 2017–2025

Assessment:
This dataset provides context regarding station importance and commuter demand.

---

### Transit Disruption Data

Status: Approved with Scope Adjustment

Findings:
Historical disruption records are not consistently available through current TfL APIs.

Decision:
Tube strike events will initially be used as disruption events because they provide clear and well-documented instances of large-scale transit service interruption.

Future expansion may include:

* Major line closures
* Severe service suspensions
* Other documented network disruptions

---

### Traffic Spillover Data

Status: Optional

Findings:
Historical coverage is limited and incomplete.

Decision:
Traffic data will not be considered a critical dependency for the first phase of analysis.

---

### Geographic Data

Status: Approved

Strengths:

* Station coordinates
* Multiple geospatial formats
* Full network coverage

Assessment:
This dataset enables mapping, spatial clustering, and proximity analysis.

---

## Initial Research Design

### Working Hypothesis

Major transit disruptions result in measurable increases in bike-share usage near affected transit corridors.

### Initial Event Definition

The first phase of analysis will focus on documented London Underground strike events.

### Initial Micro-Mobility Definition

The first phase of analysis will focus exclusively on Santander Cycles.

Additional transportation modes may be incorporated in later project phases if suitable data becomes available.

### Planned Analytical Approach

1. Identify major disruption events.
2. Establish pre-event baseline mobility behavior.
3. Measure bike-share activity during disruption periods.
4. Calculate changes relative to baseline.
5. Analyze geographic distribution of demand shifts.
6. Estimate the extent to which bike-share systems absorb disrupted transit demand.

---

## Current Status

### Phase 1: Project Charter and Planning
Status: Completed ✅

Completed:

- Problem definition
- City selection
- Dataset feasibility assessment
- Scope definition
- KPI definition
- Methodology design
- Project charter development

### Next Phase

Phase 2: Data Acquisition and Exploration

Planned Activities:

- Acquire required datasets
- Inspect dataset schemas
- Assess data quality
- Evaluate dataset compatibility
- Identify data cleaning requirements

### Lessons Learned

- Early dataset validation significantly reduced project risk.
- Data availability should influence city selection decisions.
- Narrow project scope improves feasibility and analytical clarity.
- Well-defined KPIs simplify methodology design.