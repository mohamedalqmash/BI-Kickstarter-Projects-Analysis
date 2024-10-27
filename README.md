# Power BI Project: Kickstarter Projects Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools-used)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Results/Findings](#resultsfindings)
- [Recommendations](#recommendations)
- [Challenges Faced](#challenges-faced)
- [Future Work](#future-work)
- [Conclusion](#conclusion)
  
## Project Overview
This project offers a deep analysis of Kickstarter projects from 2016 to 2018. The analysis explores factors affecting project success, geographical trends, and category distributions using Power BI for data transformation and visualization. Insights include project success rates, state distribution, and pledged goals.

## Data Sources
- **Kickstarter Projects Data:** CSV files from 2016 and 2018.

- **Source:** [Kaggle - Kickstarter Projects](https://www.kaggle.com/kemical/kickstarter-projects)

## Tools Used
- **Power BI:** For data extraction, transformation, and interactive visualizations.

## Data Cleaning/Preparation
During data preparation in Power BI, the following transformations were applied:

- **Data Loading and Inspection:** CSV files for 2016 and 2018 were imported and inspected.
- **Appending Files:** The two datasets were combined into a unified table using Power Query's Union function.
- **Column Customization:** Created a new column identifying the file year to distinguish data.
- **Hierarchical Modeling:** Created a project hierarchy by main category, category, and project name.
- **Measure Creation:** Calculated measures like Total Projects, Total Backers, Total Pledged, and Total Goal.

## Exploratory Data Analysis (EDA)
Some key questions explored include:

**1-What is the total number of projects in each category?**

**2-Which states have the highest number of successful projects?**

**3-What is the trend of projects launched over the years?**

**4-How much funding was pledged by country?**

## Results/Findings
- **Total Projects Analyzed:** 379K
- **Key Insights:**
    - **Top Countries by Project Count:** USA, GB, and CA.
    - **Success Rate:** ~35% of projects were successful, with 52% failing.
    - **Top Categories:** Film & Video, Publishing, and Games were among the highest categories by project count.
  
## Recommendations
Based on the analysis, the following recommendations were made:

- **Target Successful Categories:** Emphasize categories with higher success rates.
- **Country-Specific Campaigns:** Focus on countries with high project counts and backers.
- **Pledge Goals:** Set realistic pledge goals aligned with successful projects.
  
## Challenges Faced
- **Data Transformation:** Merging datasets from different years required handling inconsistent formats.
- **Categorization Complexity:** Some categories had subcategories that needed normalization for accurate analysis.
  
## Future Work
- **Expand Analysis Period:** Incorporate data from other years to assess long-term trends.
- **Add More Variables:** Explore additional attributes such as project duration, project updates, and communication with backers.
  
## Conclusion
- This project provided valuable insights into Kickstarter project trends, highlighting successful categories, the impact of geographical location, and the potential for targeted strategies based on historical data.
