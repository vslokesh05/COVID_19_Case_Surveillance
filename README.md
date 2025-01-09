# COVID-19 Case Surveillance  Using Tableau

**View the dashboard on Tableau Public**:  
[COVID-19 Case Surveillance Dashboard](https://public.tableau.com/app/profile/lokesh.velmurugan.sujatha/viz/COVID_19_Case_Surveillance/Dashboard1)

## Project Overview  
This Tableau visualization project provides a comprehensive analysis of COVID-19 case surveillance data, focusing on infection rates, demographic patterns, hospitalization trends, and mortality statistics. The project is designed to support decision-making by public health officials, researchers, and policymakers through visually compelling and actionable insights. Each visualization tells a unique story, offering a detailed understanding of the pandemic's impact across various population segments.


## Data Preparation  

**Data Sources**  
- **COVID Case Surveillance Dataset**: A comprehensive dataset detailing infection rates, demographics, hospitalization, ICU admissions, and death counts, segmented by gender, age group, and race/ethnicity.  

**Data Cleaning and Transformation**  
1. **Error Correction**: Resolved inconsistencies in reported values for fields such as hospitalization and ICU admissions.  
2. **Handling Missing Values**: Applied filtering to exclude records with missing, unknown, or invalid values for critical columns like gender and race/ethnicity.  
3. **Normalization**: Standardized formats for date and categorical fields to ensure consistency.  
4. **Derived Metrics**: Created calculated fields for advanced analysis, such as case-to-death ratios and demographic-based segmentation.  


## Visualization and Insights  

**Tools Used**  
- **Tableau Desktop**: Designed interactive visualizations and dashboards for granular analysis.  
- **Tableau Public**: Published the project for easy access by a broader audience.  

**Key Visualizations**  
1. **Gender-Based Pie Charts**:  
   - **Story**: Highlights COVID-19 infection and death rates by gender.  
   - **Insights**: Infection rates are similar across genders, but mortality is higher in males.  
   - **Design Principles**: Utilized the Gestalt principle of similarity with consistent color schemes for gender representation.  

2. **Monthly Trends (Line and Bar Charts)**:  
   - **Story**: Depicts the rise and fall of active cases and death counts over time.  
   - **Insights**: Spikes in cases and deaths are evident in April 2020, followed by fluctuations.  
   - **Design Principles**: Applied the principle of continuity for seamless trend visualization.  

3. **Age and Gender Analysis (Bar Charts)**:  
   - **Story**: Examines confirmed and probable cases across age groups and genders.  
   - **Insights**: Cases peak in the 50–59 age group, with males showing slightly higher confirmed cases.  
   - **Design Principles**: Leveraged similarity in color coding for confirmed and probable cases.  

4. **Hospitalization and ICU Admissions (Pie Charts)**:  
   - **Story**: Illustrates gender differences in hospitalization and ICU admissions.  
   - **Insights**: Females are less likely to require ICU care compared to males.  
   - **Design Principles**: Used contrasting colors for better differentiation and clarity.  

5. **Race/Ethnicity and Age Heatmaps**:  
   - **Story**: Explores infection and death rates across races and age groups.  
   - **Insights**:  
     - Highest infections: Age group 50–59, White Non-Hispanic.  
     - Highest deaths: Age group 80+, White Non-Hispanic.  
     - Native Hawaiian/Other Pacific Islander groups show lower infection and mortality rates, indicating higher immunity.  
   - **Design Principles**: Improved spacing (proximity) and intensity gradients for readability and emphasis.  


## Dashboard Design  
The dashboard integrates these visualizations to provide an interactive, cohesive narrative:  
- **Purpose**: Highlight key COVID-19 trends, including case distribution, gender and age impacts, and demographic insights.  
- **Design Concepts**:  
  - Interactive filters allow users to explore specific subgroups (e.g., gender, age, race).  
  - Continuity ensures a logical flow between visuals.  
  - Consistent color schemes and layout enhance readability and user engagement.  

## Process and Key Takeaways  

1. **Visual Development**:  
   - Analyzed the dataset to understand key variables and trends.  
   - Generated questions to guide visualization creation (e.g., which demographics are most affected?).  
   - Created calculated fields and tailored visuals to address these questions effectively.  

2. **Challenges Encountered**:  
   - Managed a high volume of missing and unknown data by applying filters.  
   - Resolved inconsistencies in hospitalization and ICU admission records.  

3. **Insights Gained**:  
   - Gender, age, and race significantly influence COVID-19 outcomes.  
   - Seasonal trends show patterns of spikes and declines in case counts and mortality.  

4. **Audience Persona**:  
   - **Primary Audience**: Public health departments, to design targeted interventions.  
   - **Secondary Audience**: General public, to raise awareness and encourage preventive measures.  


## Conclusion  
This project transforms raw COVID-19 data into a powerful storytelling tool, revealing critical patterns and offering actionable insights. By visualizing complex datasets in an accessible format, the project empowers stakeholders to make informed decisions in managing public health challenges.  
