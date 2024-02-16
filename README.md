# COVID-19 Dashboard: Tracking the Pandemic


## Introduction
In the battle against COVID-19, data plays a pivotal role in understanding the spread of the virus, assessing its impact, and guiding public health interventions. However, raw data often comes with inconsistencies, errors, and missing values that can hinder analysis. In this project, we employ SQL to clean and prepare COVID-19 data, followed by visualization in Tableau to create an interactive dashboard for insights and decision-making.

**Dataset**: https://ourworldindata.org/covid-deaths <br>
**Dashboard**: https://public.tableau.com/views/Covid19CasesAnalysisDashboard2019-2021/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

![Covid19 Case Analysis Dasboard Snap](https://github.com/Anannya1234/Covid-19-Dashboard--Tracking-the-Pandemic/assets/138116291/6270891e-11ce-40d7-90bf-00c514d379ac)

## Data Cleaning with SQL:
1. Data Exploration: Used SQL queries to inspect the dataset, identifying anomalies, duplicates, and missing values, ensuring data integrity.
2. Data Cleaning: Leveraging SQL's powerful data manipulation capabilities, we perform cleaning tasks such as:
    - Removing duplicate records to ensure data accuracy.
    - Handling missing values through imputation or deletion based on contextual relevance.
    - Standardizing data formats, such as date formats, to ensure consistency.
    - Correcting errors or inconsistencies in data entry, such as typos or invalid entries.
3. Data Transformation: We transform the cleaned data into a format suitable for analysis and visualization. This may involve aggregating data at different levels (e.g., daily, weekly, by region) and calculating derived metrics for deeper insights.

## Dashboard Creation in Tableau:
1. Data Connection: We connect Tableau to the cleaned COVID-19 dataset stored in a SQL database or a structured file format (e.g., CSV). Tableau's connectivity options enable seamless integration with various data sources.
2. Visualization Design: Using Tableau's intuitive drag-and-drop interface, we design visualizations tailored to our analysis goals. This includes:
    - Table containing Total no of cases, Total no of Deaths and Death percentage
    - Line chart representing avg. percentage of population infected vs months.
    - Bar graph representing Death count vs countries.
    - Map for geographical distribution visualization on Percentage Infected Per country
    - Filters and parameters for interactive exploration, allowing users to drill down into specific regions or time periods.
3. Dashboard Composition: We assemble the individual visualizations into a cohesive dashboard layout, organizing them logically for easy interpretation.
4. Dashboard Interactivity: We enhance the dashboard with interactive elements such as tooltips, hover effects, and dashboard actions. This enables users to dynamically explore the data and gain deeper insights by interacting with the visualizations.
5. Dashboard Publishing: Once the dashboard is complete, we publish it to Tableau Server or Tableau Public for wider dissemination and collaboration.

## Conclusion
Utilizing SQL for data cleaning and Tableau for visualization, we craft a strong COVID-19 data analysis solution. This enables actionable insights from complex datasets, aiding decision-makers in pandemic response efforts. Together, we leverage data-driven strategies to combat COVID-19 and protect public health.
