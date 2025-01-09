# COVID-19 Case Surveillance: Storytelling Using Tableau and Power BI  

**View the Tableau Dashboard**:  
[COVID-19 Case Surveillance Dashboard (Tableau)](https://public.tableau.com/app/profile/lokesh.velmurugan.sujatha/viz/COVID_19_Case_Surveillance/Dashboard1)  

**View the Power BI Dashboard**:  
[COVID-19 Case Surveillance Dashboard (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiZmM5NDE0OGEtNjFkMi00M2FjLTg4MTMtYTBiNmNjMWRjODQxIiwidCI6Ijk2NDY0YThhLWY4ZWQtNDBiMS05OWUyLTVmNmI1MGEyMDI1MCIsImMiOjN9&pageName=31dab1e5546d97341540)


## Project Overview  
This visualization project provides a comprehensive analysis of COVID-19 case surveillance data, focusing on infection rates, demographic patterns, hospitalization trends, and mortality statistics. By leveraging the capabilities of both Tableau and Power BI, this project supports decision-making by public health officials, researchers, and policymakers. The interactive dashboards created with these tools tell compelling stories and reveal actionable insights into the pandemic's impact across various population segments.  


## Data Preparation  

**Data Sources**  
- **COVID Case Surveillance Dataset**: A comprehensive dataset detailing infection rates, demographics, hospitalization, ICU admissions, and death counts, segmented by gender, age group, and race/ethnicity.  

**Data Cleaning and Transformation**  
1. **Error Correction**: Resolved inconsistencies in reported values for fields such as hospitalization and ICU admissions.  
2. **Handling Missing Values**: Applied filtering to exclude records with missing, unknown, or invalid values for critical columns like gender and race/ethnicity.  
3. **Normalization**: Standardized formats for date and categorical fields to ensure consistency.  
4. **Derived Metrics**: Created calculated fields and measures to analyze case-to-death ratios and demographic-based segmentation effectively.  


## Visualization and Insights  

**Tools Used**  
- **Tableau Desktop**: Designed interactive dashboards for detailed analysis.  
- **Tableau Public**: Published the Tableau dashboard for broader audience access.  
- **Power BI Desktop**: Developed engaging visuals and reports with advanced DAX calculations.  
- **Power BI Service**: Published Power BI reports for collaboration and accessibility.  

**Key Visualizations (in both Tableau and Power BI)**  

1. **Gender-Based Pie Charts**:  
   - **Story**: Highlights COVID-19 infection and death rates by gender.  
   - **Insights**: Infection rates are similar across genders, but mortality is higher in males.  
   - **Design Principles**: Utilized similarity in color schemes and clear labels for readability.  

2. **Monthly Trends (Line and Bar Charts)**:  
   - **Story**: Depicts the rise and fall of active cases and death counts over time.  
   - **Insights**: Spikes in cases and deaths are evident in April 2020, followed by fluctuations.  
   - **Design Principles**: Combined line and bar charts to display trends seamlessly.  

3. **Age and Gender Analysis (Stacked Bar Charts)**:  
   - **Story**: Examines confirmed and probable cases across age groups and genders.  
   - **Insights**: Cases peak in the 50–59 age group, with males showing slightly higher confirmed cases.  
   - **Design Principles**: Consistent color coding for categories with dynamic tooltips for deeper insights.  

4. **Hospitalization and ICU Admissions (Pie Charts)**:  
   - **Story**: Illustrates gender differences in hospitalization and ICU admissions.  
   - **Insights**: Females are less likely to require ICU care compared to males.  
   - **Design Principles**: Used contrasting colors and clean layouts for clarity.  

5. **Race/Ethnicity and Age Heatmaps**:  
   - **Story**: Explores infection and death rates across races and age groups.  
   - **Insights**:  
     - Highest infections: Age group 50–59, White Non-Hispanic.  
     - Highest deaths: Age group 80+, White Non-Hispanic.  
     - Native Hawaiian/Other Pacific Islander groups show lower infection and mortality rates, indicating higher immunity.  
   - **Design Principles**: Enhanced spacing and intensity gradients for better readability.  


## Dashboard Design  

The dashboards integrate these visualizations into an interactive, cohesive narrative:  
- **Purpose**: Highlight key COVID-19 trends, including case distribution, gender and age impacts, and demographic insights.  
- **Design Concepts**:  
  - **Interactive Filters**: Allow users to explore specific subgroups (e.g., gender, age, race).  
  - **Continuity**: Ensures a logical flow between visuals for an intuitive user experience.  
  - **Cross-Filtering and Slicers (Power BI)**: Enable dynamic interactivity and deeper analysis.  
  - **Consistent Color Schemes**: Enhance readability and visual appeal.  


## Process and Key Takeaways  

1. **Visual Development**:  
   - Analyzed the dataset to identify key variables and trends.  
   - Created calculated fields (Tableau) and DAX measures (Power BI) to address analytical questions.  
   - Tailored visuals to communicate insights effectively.  

2. **Challenges Encountered**:  
   - Managed missing and inconsistent data by applying conditional transformations.  
   - Optimized performance in Power BI by refining the data model and reducing report load times.  

3. **Insights Gained**:  
   - Gender, age, and race significantly influence COVID-19 outcomes.  
   - Temporal trends reveal spikes and declines in cases and mortality.  

4. **Audience Persona**:  
   - **Primary Audience**: Public health departments, for targeted interventions.  
   - **Secondary Audience**: General public, for awareness and preventive measures.  

## Conclusion  
This project transforms raw COVID-19 data into actionable insights using Tableau and Power BI. By simplifying complex datasets and presenting them through interactive dashboards, this project empowers stakeholders to make informed decisions to combat public health challenges effectively.  

