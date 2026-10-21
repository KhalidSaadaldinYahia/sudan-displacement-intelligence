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


## Source and limitations

Source: [IOM Displacement Tracking Matrix (DTM) Sudan](https://dtm.iom.int/sudan), *IDPs and Returnees Snapshot 007*, 30 June 2026.

DTM figures are operational estimates and may be revised as verification and access conditions change. This is a single-snapshot descriptive analysis; it does not measure historical trends, cross-border displacement, humanitarian severity, access constraints, or response capacity. IDPs and returned individuals are distinct operational categories.

## Technical features

- Power BI Project (`.pbip`) format
- PBIR report definition and TMDL semantic model
- Power Query data preparation from a public, versioned CSV snapshot
- DAX measures and interactive state/locality filtering
- Dedicated methodology and source documentation

## Author

**Khalid SaadAldin Yahia**
Data Analyst | Power BI | Python | SQL | Excel

## Open and inspect the report

- [Preview the dashboard PDF](Sudan_Displacement_Return_Monitor.pdf). A PDF is a static export; the `.pbip` project contains the interactive report.
- [Browse the Power BI project](project/) or [download this repository as a ZIP](https://github.com/KhalidSaadaldinYahia/sudan-displacement-intelligence/archive/refs/heads/main.zip). Keep the `project` folder intact after extracting.
- Open [`SudanPressureFingerprint.pbip`](project/SudanPressureFingerprint.pbip) from the extracted `project` folder in a recent Power BI Desktop. The `.pbip` file references its sibling `.Report` and `.SemanticModel` folders; it cannot open by itself after downloading only that file.
- On refresh, choose **Anonymous** access if Power BI requests credentials for `raw.githubusercontent.com`. The project reads the included CSV snapshot from this repository's public `main` branch. For offline refresh, replace each table query's `Web.Contents(...)` CSV source with `File.Contents(...)` pointing to its included local `project/data` CSV.

The CSV data snapshots are included under [`project/data`](project/data/). A `.pbix` was not generated because the PBIP source cannot be converted faithfully without opening and saving it in Power BI Desktop.
