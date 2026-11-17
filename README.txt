TASK-4 — Healthcare Analytics Decision Brief

FILES
- Executive_Decision_Brief.pdf: leadership-ready report.
- Supporting_Dashboard.html: self-contained dashboard; open in a browser.
- Leadership_Presentation_3min.pptx: five-slide presentation.
- 3_Minute_Presentation_Script.txt: speaker script.
- Source CSV files: supplied synthetic patient, pharmacy-sales and adverse-reaction samples.
- PNG charts: supporting chart images used in the report and slides.

OPERATIONAL QUESTION
How can healthcare leadership use de-identified patient, pharmacy-sales and adverse-reaction data to prioritize operational monitoring and improve future reporting quality?

VERIFIED INDICATORS
1. Patient readmission share = Readmitted Yes records / all patient records = 3/10 = 30.0%.
2. Pharmacy sales revenue = sum of TotalRevenueINR = INR 54,260 across 10 transactions.
3. Serious safety-report share = Severe or Life-Threatening reports / all reports = 3/8 = 37.5%.
4. Exploratory common drug-name overlap across all three datasets = 3 (atorvastatin, ibuprofen, metformin). This is not patient-level linkage.

DATA QUALITY
- Patient file: 10 rows, 0 missing cells, 0 duplicate full rows, 0 duplicate patient IDs.
- Pharmacy file: 10 rows, 0 missing cells, 0 duplicate full rows, 0 duplicate transaction IDs.
- Safety file: 8 rows, 0 missing cells, 0 duplicate full rows, 0 duplicate report IDs.
- Pharmacy revenue arithmetic matched units × unit price in 10/10 rows.

LIMITATIONS
All datasets are synthetic and small. The safety reports have no exposed-population denominator. There is no shared patient/event key. Results are descriptive and cannot establish causation, clinical risk, incidence, treatment effectiveness, profit or stock availability.

PRIVACY / SAFE USE
Use synthetic training data only. Do not add real patient information or attempt re-identification. Suppress or combine small groups in public reporting. Keep shared materials view-only where possible. Do not use for clinical decisions.

NEXT ACTION
Run a monthly aggregate review with the same definitions, add pharmacy purchase-cost and stock-on-hand fields, and route serious safety reports through the established qualified review process.

FOLLOW-UP MEASUREMENT
Recalculate the same three indicators in the next reporting period and compare only like-for-like periods and denominators. Track missingness and duplicate-ID checks.

IMPORTANT
This package is prepared from the supplied synthetic training data. Before submission, upload this folder to one public or view-only project page/repository and share that single link. The folder is not automatically published online by creating these files.
