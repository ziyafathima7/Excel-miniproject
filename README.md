## MedCare Clinic & Pharmacy — Patient Visit Data Analysis

A mini data-analysis project exploring 320 patient visit records from MedCare Clinic & Pharmacy (2023–2024). The goal was to clean real-world messy data and derive business insights using Excel formulas only — no Power Query, Pivot Tables, or VLOOKUP.

About the Project

MedCare Clinic wanted to understand its performance across departments, cities, doctors, and patient demographics. This project simulates that analysis end-to-end: from raw, inconsistent data to a polished summary report with actionable findings.

Repository Structure

| Sheet | Purpose |
|---|---|
| Raw Data | Original 320 records (untouched, 12 columns) |
| Working Sheet | Cleaned data with derived columns (standardized names, age groups, total cost) |
| Summary Sheet | Formula-driven answers to all five business questions |
| Changelog | Full log of every cleaning step and formula used |

Data Cleaning Process
• Converted raw data into an Excel Table for structured referencing
• Standardized patient names with TRIM + PROPER
• Normalized inconsistent gender entries (Male/Female → M/F) via Find & Replace
• Sorted records alphabetically for readability
• Added a Total Cost column (Consultation Fee + Medicine Cost)
• Added an Age Group column (Minor, Adult, Middle Age, Senior)

Full step-by-step reasoning for every change is documented in the Changelog sheet.

Key Findings
Department Performance

| Department | Patients | Revenue (₹) |
|---|---|---|
| Cardiology | 85 | 129,030 |
| General Medicine | 87 | 55,110 |
| Orthopedics | 51 | 61,820 |
| Dermatology | 54 | 56,350 |
| Pediatrics | 43 | 32,200 |

Cardiology generates the most revenue despite having fewer patients than General Medicine, which sees the highest patient volume — pointing to Cardiology's higher-cost treatments per visit.

City-Wise Outreach

Chennai leads on both fronts — 91 patients and ₹96,620 in revenue — making it the clear priority for outreach and expansion efforts. Coimbatore (66 patients, ₹63,050) is a strong secondary market.

Year-on-Year Growth (2023 → 2024)

| Metric | 2023 | 2024 | Change |
|---|---|---|---|
| Visits | 155 | 165 | +10 (6.45%) |
| Revenue (₹) | 162,670 | 171,840 | +9,170 (5.63%) |
| Avg. Bill (₹) | 1,049.48 | 1,041.45 | −8.03 (0.77%) |

The clinic grew in both volume and revenue, though the average bill per visit dipped slightly — suggesting growth came from more visits rather than higher-value ones.

Doctor Performance
• Busiest doctor: Dr. Vikram Nair — 34 patients
• Highest revenue generator: Dr. Priya Reddy — ₹49,900 (from 32 patients)

Dr. Priya Reddy earns more per patient on average than Dr. Vikram Nair, indicating she may handle higher-cost cases.

Age Group vs. Billing Pattern

| Age Group | Patients | Avg. Consultation Fee (₹) | Avg. Total Bill (₹) |
|---|---|---|---|
| Minor | 66 | 694.70 | 1,028.03 |
| Adult | 104 | 647.60 | 1,062.98 |
| Middle Age | 88 | 694.32 | 1,024.94 |
| Senior | 62 | 667.74 | 1,063.23 |

The clinic's assumption that older patients rack up higher bills is only partially supported — Seniors and Adults do have the highest average total bills, but the difference across all groups is small, and Middle Age patients actually have the lowest average bill despite not being the youngest group.

Tools Used
• Microsoft Excel (Tables, TRIM, PROPER, COUNTIF, SUMIF, AVERAGEIF, UNIQUE, Find & Replace)

Author

Ziya Fathima
GitHub: ziyafathima7
