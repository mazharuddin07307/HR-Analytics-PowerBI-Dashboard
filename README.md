# HR Analytics Dashboard (Power BI)

## Project Overview
An interactive Power BI dashboard analyzing employee attrition across an organization. The dashboard tracks key HR metrics — attrition rate, demographics, salary bands, tenure, and job roles — across three departments (Human Resources, Research & Development, Sales) to help identify attrition patterns and support data-driven retention strategies.

## Data
- **Source:** HR employee records dataset (employee demographics, department, job role, salary, tenure, and attrition status)
- **File:** `HR_Analytics.pbix`
- **Total Employees Analyzed:** 967

## Dashboard Features

### Key Metrics (KPI Cards)
- **Count of Employees:** 967
- **Total Attrition:** 133 employees
- **Attrition Rate:** ~13.7%
- **Average Age:** ~37 years
- **Average Years at Company:** 6.86

### Key Visualizations
- **Attrition by Gender:** Breakdown of attrition across Male (88) vs Female (39) employees
- **Attrition by Education:** Donut chart showing attrition distribution across education fields — Medical (35%), Life Sciences (44%), Technical Degree (15%), Other (5%)
- **Attrition by Age Group:** Bar chart showing attrition concentrated in the 26–35 age group (67 cases), followed by 36–45 (25) and 18–25 (24)
- **Attrition by Job Role (Matrix):** Detailed breakdown of attrition by job role across 4 categories, highlighting Laboratory Technician (62) and Research Scientist (47) as highest-attrition roles
- **Attrition by Salary Slab:** Shows attrition heavily concentrated in the lowest salary band (Upto 5k: 110 cases), suggesting a strong link between compensation and attrition
- **Attrition by Year at Company:** Line chart revealing attrition peaks sharply at Year 2 (38 cases), indicating early-tenure employees are highest flight risk
- **Attrition by Job Role (Bar Chart):** Ranked view confirming Laboratory Technician and Research Scientist roles as top attrition contributors

### Interactive Features
- **Department Tabs:** Filter the entire dashboard by Human Resources, Research & Development, or Sales department
- Built using Power BI's data model with relationships across employee, department, and attrition tables

## Key Insights
- Attrition is heavily concentrated among **early-tenure employees** (peak at Year 2), suggesting onboarding/retention gaps in the first two years
- **Lower salary bands (Upto 5k)** show disproportionately high attrition, pointing to compensation as a major driver
- **Laboratory Technician and Research Scientist** roles have the highest attrition counts and warrant targeted retention efforts
- The **26–35 age group** shows the highest attrition volume, likely reflecting early/mid-career job mobility

## Power BI Skills Demonstrated
- Data modeling and relationship management
- DAX measures (Attrition Rate, Average Age, Average Years calculations)
- Multiple visual types (KPI cards, donut charts, bar charts, line charts, matrix tables)
- Page-level and tab-based filtering across departments
- Dashboard UX design for executive-level reporting

## How to View
Download `HR_Analytics.pbix` and open in Power BI Desktop to interact with filters and explore the full data model.
