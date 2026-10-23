# Sudan Displacement & Return Monitor

## Files

- [Open the Power BI dashboard](SudanPressureFingerprint.pbix) in Power BI Desktop.
- [Read the PDF analytical preview](Sudan_Displacement_Return_Monitor.pdf). This PDF summarises independently checked figures; it is not yet a page-for-page export of the PBIX. A matching PDF export is pending verification in Power BI Desktop.

The PBIX is the single-file dashboard. A data refresh may need network access to its saved source URLs.

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


## Source and limitations

Source: [IOM Displacement Tracking Matrix (DTM) Sudan](https://dtm.iom.int/sudan), *IDPs and Returnees Snapshot 007*, 30 June 2026.

DTM figures are operational estimates and may be revised as verification and access conditions change. This is a single-snapshot descriptive analysis; it does not measure historical trends, cross-border displacement, humanitarian severity, access constraints, or response capacity. IDPs and returned individuals are distinct operational categories.

## Technical features

- Power BI Desktop (`.pbix`) report and semantic model
- PBIR report definition and TMDL semantic model
- Power Query data preparation from a public, versioned CSV snapshot
- DAX measures and interactive state/locality filtering
- Dedicated methodology and source documentation

## Author

**Khalid SaadAldin Yahia**
Data Analyst | Power BI | Python | SQL | Excel
