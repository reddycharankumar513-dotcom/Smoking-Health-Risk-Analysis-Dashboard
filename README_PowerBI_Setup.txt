SAPPHIRE IQ | SMOKING AND HEALTH ANALYSIS
POWER BI HANDOFF PACKAGE

CONTENTS
1. Smoking_Health_Analysis.csv - original source data (10,000 rows, 15 columns)
2. Sapphire_IQ_PowerBI_DAX.txt - calculated columns, measures and field mappings
3. Sapphire_IQ_PowerBI_Theme.json - importable report theme
4. Smoking_Health_Analysis_Completed_Report.pdf - analysis report, findings and charts

BUILD IN POWER BI DESKTOP
1. Open Power BI Desktop.
2. Home > Get data > Text/CSV > select Smoking_Health_Analysis.csv.
3. Select Transform Data. Set Diagnosis_Date to Date; Patient_ID and text fields to Text;
   integer measures to Whole Number; BMI to Decimal Number.
4. Close & Apply. In Model view, rename the imported table to Patients.
5. Open Sapphire_IQ_PowerBI_DAX.txt. Create the calculated columns and measures in order.
6. Select View > Themes > Browse for themes, then import Sapphire_IQ_PowerBI_Theme.json.
7. Create a report page named "Smoking & Health Analysis".
8. Add four KPI cards: Total Patients, Current Smokers, Patients with Recorded Organ,
   Patients with Health Conditions.
9. Add visuals using the field mappings in the DAX file.
10. Add slicers for Gender, Region, Age Group, Smoking_Status and Diagnosis_Date.
11. Sort Age Group by Age Group Sort and Smoking Exposure Duration by Smoking Exposure Sort.
12. Save as Smoking_Health_Analysis.pbix.

IMPORTANT
This package contains the data, DAX, theme and report specification. It is not itself a
native .pbix file. A native .pbix must be generated and saved by Power BI Desktop.
The BP groupings are project-specific analytical labels, not clinical classifications.
The dataset supports descriptive analysis only, not causal claims.
