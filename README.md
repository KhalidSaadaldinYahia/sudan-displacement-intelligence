# Sudan Displacement & Return Monitor

A four-page Power BI project examining internal displacement and return movements across Sudan using the public **IOM Displacement Tracking Matrix (DTM) Sudan IDPs and Returnees Snapshot 007**, dated **30 June 2026**.

## Analytical questions

- Which states carry the largest reported IDP and returnee caseloads?
- Where do return movements exceed or lag current displacement pressure?
- Which localities have the largest reported concentrations?
- How are IDPs and returned individuals distributed across 18 states and 185 localities?

## Dashboard pages

1. **National Overview** — national totals, state ranking, and leading localities.
2. **State-Level Analysis** — a diverging pressure fingerprint comparing IDPs with returned individuals.
3. **State & Locality Lens** — locality rankings and an interactive state/locality benchmark.
4. **Methodology & Sources** — definitions, source coverage, limitations, and interpretation guidance.

## Data snapshot

- **8,685,273** internally displaced people
- **1,742,414** IDP households
- **4,649,056** returned individuals
- **13,334,329** people represented by the dashboard's IDP-plus-returned-individuals measure
- **18 states** and **185 localities**

The combined people-represented metric is the sum of reported IDPs and returned individuals. It is not a historical cumulative total or a count of unique people over time.

## Open the project

1. [Download the Power BI project archive](Sudan_Displacement_Return_Monitor_Power_BI_Project.zip) and extract it.
2. Open `SudanPressureFingerprint.pbip` in a recent version of Power BI Desktop.
3. If prompted, set the `DataFolder` parameter to the extracted project's `data` folder and refresh.

Preview the completed dashboard: [open the PDF](Sudan_Displacement_Return_Monitor.pdf).

## Source and limitations

Source: [IOM Displacement Tracking Matrix (DTM) Sudan](https://dtm.iom.int/sudan), *IDPs and Returnees Snapshot 007*, 30 June 2026.

DTM figures are operational estimates and may be revised as verification and access conditions change. This is a single-snapshot descriptive analysis; it does not measure historical trends, cross-border displacement, humanitarian severity, access constraints, or response capacity. IDPs and returned individuals are distinct operational categories.

## Technical features

- Power BI Project (`.pbip`) format
- PBIR report definition and TMDL semantic model
- Power Query data preparation with a reusable `DataFolder` parameter
- DAX measures and interactive state/locality filtering
- Dedicated methodology and source documentation

## Author

**Khalid SaadAldin Yahia**
Data Analyst | Power BI | Python | SQL | Excel
