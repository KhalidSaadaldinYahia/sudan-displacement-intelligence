# Sudan Displacement & Return Monitor — local review changes

- Retained only the correct IOM DTM Snapshot 007 project as the canonical review version; the duplicate PDF with copied UNHCR methodology is excluded.
- Renamed inherited refugee/origin/region semantic fields end to end: locality, locality code, state, IDPs, IDP households, returned individuals, and people represented.
- Corrected the return-series label, locality/state table labels, and the copied `region, and year` subtitle fragment.
- Replaced the copied Displacement Pulse QA summary and fixed the validation metadata to 18 states and 185 localities.
- Replaced the obsolete local CSV path with a `DataFolder` Power Query parameter.
- Removed the unrelated UNHCR `displacement_by_origin.csv` file from this corrected project copy.
- Renamed the calculated measure to `Selected Snapshot Year` so it no longer conflicts with the `Snapshot Year` source column when Power BI Desktop loads the model.
- Corrected the state slicer's stale native query label from `Snapshot Year` to `State`.

Reconciled source totals: 8,685,273 IDPs, 1,742,414 IDP households, 4,649,056 returned individuals, and 13,334,329 people represented as of 30 June 2026. A native PDF re-export still requires Power BI Desktop.
