# Hospital Emergency Room Dashboard

An Excel-based interactive dashboard analyzing emergency room patient data, covering patient demographics, wait times, satisfaction, admission status, and department referrals.

## Overview

This project turns raw ER patient records into a clean dataset, a set of KPI pivot tables, and an interactive dashboard — surfacing patterns in patient flow, delays, and satisfaction to help understand where an ER's operations could improve.

## Workbook Structure

The file `Hospital_Emergency_Room_Dashboard-1.xlsx` contains four sheets:

| Sheet | Description |
|---|---|
| `Hospital Emergency Room Data` | Raw, unprocessed source data (~9,216 records) |
| `Cleaned HRE Data` | Cleaned dataset ready for analysis |
| `KPI's` | Pivot tables summarizing key operational metrics |
| `Dashboard` | Interactive visual dashboard combining charts and slicers |

## Dataset Fields

Patient ID, Patient Admission Date, Patient Admission Time, Month, Year, Patient Name, Patient Gender, Patient Age, Age Group, Patient Race, Department Referral, Patient Admission Flag, Patient Satisfaction Score, Patient Wait time, Patient On Time/Delay Status.

> Note: This appears to be a synthetic/sample dataset (patient IDs and names follow a generic pattern typical of demo healthcare datasets) rather than real patient records.

## Key Metrics & Insights

- **Total Patients:** 9,216
- **Average Wait Time:** ~35.3 minutes
- **Average Patient Satisfaction Score:** ~4.99 (out of 10)
- **Gender Split:** ~51.3% Male, ~48.7% Female
- **On-Time vs. Delay:** ~59.3% of patients experienced a delay vs. ~40.7% on time
- **Admission Status:** Nearly even split — ~50.0% Admitted vs. ~50.0% Not Admitted
- **Age Group Distribution:** Fairly even across all age brackets (0–9 through 70–79), each accounting for roughly 1,000–1,200 patients
- **Department Referrals:** General Practice (1,840) and Orthopedics (995) are the top named departments; a large share of records (5,400) have no department referral recorded

## Tech Stack

- Microsoft Excel (PivotTables, PivotCharts, Slicers)

## How to Use

1. Download `Hospital_Emergency_Room_Dashboard-1.xlsx`
2. Open in Excel (or Google Sheets/LibreOffice Calc, though PivotTable interactivity is best in Excel)
3. Go to the `Dashboard` sheet to interact with the slicers and view the visual summary
4. Refer to the `KPI's` sheet for the underlying pivot tables and calculations
5. `Cleaned HRE Data` is the analysis-ready source; `Hospital Emergency Room Data` is the original raw export

## Project Structure

```
.
├── Hospital_Emergency_Room_Dashboard-1.xlsx   # Workbook: raw data, cleaned data, KPIs, dashboard
└── README.md
```

## Future Improvements

- Investigate the large volume of missing department referrals to see if it's a data quality issue
- Analyze whether wait time or delay status correlates with patient satisfaction score
- Break down admission rate and wait times by age group, race, or department
- Rebuild the dashboard in Power BI or Tableau for richer interactivity and easier sharing

## License

Feel free to use this project for learning purposes.
