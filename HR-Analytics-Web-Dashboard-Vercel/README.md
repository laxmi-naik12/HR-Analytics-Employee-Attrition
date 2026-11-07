# HR Analytics Web Dashboard

A static, interactive HR attrition dashboard built with HTML, CSS, JavaScript and Chart.js.

## Deploy on Vercel
1. Add `index.html` to the root of your `HR-Analytics-Employee-Attrition` GitHub repository (or upload this folder's contents to a new repository).
2. In Vercel, import that repository.
3. Framework Preset: **Other**.
4. Build Command: leave empty.
5. Output Directory: leave empty (or `.` if Vercel requires a value).
6. Deploy.

The dashboard loads Chart.js from jsDelivr, so visitors need an internet connection.

## Included analysis
KPIs: total employees, active employees, attrition count, attrition rate and average monthly income.
Charts: attrition by department, age group, job role, overtime, job satisfaction and business travel.
Filters: gender, department, job role and age group.

## Data notice
This dashboard embeds the uploaded cleaned dataset in `index.html`. Anyone who can access the deployed site can inspect the data in the page source. Only deploy if you have the right to publish this dataset and it contains no confidential or personal employee information.
