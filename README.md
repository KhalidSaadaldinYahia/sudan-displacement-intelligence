# Sudan Displacement Intelligence

A four-page Power BI project examining **internal displacement and return movements across Sudan** using public data from the **IOM Displacement Tracking Matrix (DTM) Sudan**.

The dashboard is based on the **IOM DTM Sudan IDPs and Returnees Snapshot 007**, dated **30 June 2026**, and is designed to support geographic comparison of displacement and return caseloads across Sudan's states and localities.

---

## Project Purpose

This project provides a structured analytical view of the reported internal displacement and return situation in Sudan as of **30 June 2026**.

The dashboard focuses on:

- Internally displaced people (IDPs)
- IDP households
- Returned individuals
- Returnee households
- State-level displacement and return pressure
- Locality-level caseload distribution

The objective is to make the IOM DTM snapshot easier to explore and interpret through an interactive Power BI report.

---

## Analytical Questions

The dashboard is designed to answer questions such as:

- Which states report the largest internally displaced populations?
- Which states report the largest numbers of returned individuals?
- How do displacement and return caseloads compare across states?
- Which localities account for the largest reported IDP caseloads?
- Which localities report the largest return movements?
- Where is displacement pressure concentrated geographically?
- What does the 30 June 2026 snapshot show about the distribution of internal displacement and returns across Sudan?

---

## Dashboard Pages

### 1. National Overview

Provides a high-level summary of the Sudan displacement and return situation.

Key indicators include:

- Total internally displaced people
- Total IDP households
- Total returned individuals
- Total returnee households
- State coverage
- Locality coverage

The page provides a national-level view before moving into more detailed geographic analysis.

---

### 2. State-Level Analysis

Compares displacement and return caseloads across Sudan's states.

The page is designed to identify:

- States with the largest IDP populations
- States with the largest return movements
- Differences between displacement and return pressure
- Geographic concentration of reported caseloads

A key visual is the **State Pressure Matrix**, which uses a diverging layout:

- IDP caseloads extend in one direction
- Returned-individual caseloads extend in the opposite direction

This allows displacement and return pressure to be compared directly for each state without relying on overlapping bubbles.

IDP-household information is also available as supporting context.

---

### 3. Locality Explorer

Provides more detailed analysis at the locality level.

Users can explore:

- Locality-level IDP populations
- Locality-level return movements
- Ranked caseloads
- Geographic concentration within selected states

The page allows users to move from national and state-level analysis into more detailed local-level exploration.

---

### 4. Methodology & Sources

Documents:

- Data source
- Reporting date
- Geographic grain
- Metric definitions
- Analytical assumptions
- Limitations
- Interpretation guidance

The purpose of this page is to make the analytical process transparent and prevent the dashboard from being interpreted beyond what the source data supports.

---

## Data Structure and Methodology

### Data Source

**International Organization for Migration (IOM)**  
**Displacement Tracking Matrix (DTM) Sudan**

Dataset:

**IDPs and Returnees Snapshot 007**

Reporting date:

**30 June 2026**

Source:

https://dtm.iom.int/sudan

---

### Geographic Grain

The dashboard is structured geographically around:

- **State**
- **Locality**

It represents a **single operational snapshot dated 30 June 2026**.

The dataset is therefore not structured as an origin-by-year time series.

---

### Primary Indicators

The dashboard reports:

- **Internally Displaced People (IDPs)**
- **IDP Households**
- **Returned Individuals**
- **Returnee Households**

These are the primary population measures used throughout the report.

---

### Geographic Coverage

The source snapshot covers:

- **18 states**
- **185 localities**

---

## Data Snapshot

As reported in the IOM DTM Sudan snapshot dated 30 June 2026:

- **8,685,273 internally displaced people**
- **1,742,414 IDP households**
- **4,649,056 returned individuals**
- **928,168 returnee households**
- **18 states**
- **185 localities**

These values represent the operational estimates reported in the source snapshot.

---

## Analytical Approach

The dashboard uses descriptive analysis to compare the geographic distribution of displacement and return caseloads.

The analysis includes:

- National-level aggregation
- State-level comparison
- Locality-level ranking
- Displacement-versus-return comparison
- Geographic filtering
- Caseload concentration analysis

The dashboard does not attempt to estimate causal relationships or predict future displacement.

---

## Important Interpretation Note

This dashboard is an analysis of **internal displacement and return movements** recorded by IOM DTM Sudan.

It is **not a refugee-status dashboard**.

IOM's Displacement Tracking Matrix is used as a source of mobility and displacement information.

The dashboard does not treat IOM DTM data as refugee-status determinations and does not imply that IOM grants or recognizes refugee status.

Terms such as refugees, asylum-seekers, refugee recognition, origin-year observations, or cross-border refugee status are not used as analytical categories in this report.

---

## Combined Population Metric

Where a combined population figure is displayed, it is calculated as:

**Reported IDPs + Reported Returned Individuals**

This is a dashboard-level analytical sum intended to summarize the populations represented in the selected snapshot.

It should not be interpreted as:

- A historical cumulative displacement total
- A count of unique individuals over time
- A national population estimate
- A measure of all displacement-affected people in Sudan

---

## Data Quality and Limitations

IOM DTM figures are operational estimates and may be revised as:

- Field verification improves
- Access conditions change
- New information becomes available
- Previously reported figures are updated

Additional limitations include:

- The dashboard represents a **single snapshot**, not a historical time series.
- Reported figures should not be interpreted as permanent or final population counts.
- State and locality comparisons are descriptive and do not measure humanitarian severity.
- Larger caseloads do not automatically imply greater humanitarian need.
- The dashboard does not measure access constraints, protection risks, service availability, or response capacity.
- Geographic totals reflect the structure and definitions of the source dataset.

The dashboard should therefore be used as a descriptive analytical tool rather than as a substitute for formal humanitarian needs assessments.

---

## Quality Assurance

The project was reviewed to ensure consistency between:

- Dashboard visuals
- KPI values
- State-level totals
- Locality-level data
- Metric definitions
- Data-source documentation
- Methodology statements

The methodology was specifically aligned with the Sudan IOM DTM dataset so that the documentation accurately reflects the data used in the report.

---

## Technical Features

- Power BI Project (`.pbip`) format
- Power Query data preparation
- DAX measures
- Interactive state and locality filtering
- Geographic comparison
- State-level pressure analysis
- Ranked locality analysis
- Dedicated methodology and source documentation

---

## Open the Project

1. Download the Power BI project archive:

   [Sudan Displacement Power BI Project](Sudan_Displacement_30_June_2026_Power_BI_Project.rar)

2. Extract the archive.

3. Open the `.pbip` file using a recent version of **Power BI Desktop** with Power BI Project support.

4. If Power Query requests the data location, update the source path to the data file included in the extracted project folder.

---

## Dashboard Preview

You can view the completed dashboard here:

[Open the dashboard PDF](Sudan_Displacement_30_June_2026_Dashboard.pdf)

---

## Source

**IOM Displacement Tracking Matrix (DTM) Sudan**

*IDPs and Returnees Snapshot 007 — 30 June 2026*

https://dtm.iom.int/sudan

---

## Author

**Khalid SaadAldin Yahia**

Data Analyst | Power BI | Python | SQL | Excel

GitHub:  
https://github.com/KhalidSaadaldinYahia
