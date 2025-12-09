## Pens and Printers Product Sales Analysis – Summary

Dashboard in Tableau: https://public.tableau.com/app/profile/anton.talizin/viz/SalesMethodEffectivenessforaB2BProductLaunch/Dashboard1

**Key findings**

- The combined **Email → Call** approach delivered the **highest average revenue per customer** and the strongest positive week‑to‑week revenue trend, making it the most effective sales method. 
- Pure **Email** outreach generated the largest total revenue volume but showed a sharp decline after launch, suggesting it is not sustainable as a standalone strategy. 
- **Call‑only** contacts required more effort and produced lower average revenue compared to Email → Call. 
- Revenue was **concentrated in four states** (CA, TX, NY, IL), indicating high‑value regions for targeted campaigns. 
- **Newer customers** and those with around **25 website visits** contributed disproportionately to revenue, highlighting promising segments for future targeting. 

***

## Project overview

This project is a practical DataCamp certification exam focused on a new product line’s sales performance. Using a transactional dataset (15,000 rows, 8 columns), the goal was to identify the most effective sales method and define metrics to monitor ongoing performance. 

***

## Workflow and technical skills

- **Data validation and cleaning**
    - Checked schema, data types, and completeness for all columns.
    - Standardized inconsistent `salesmethod` labels into three categories using pandas mapping.
    - Imputed missing `revenue` values with the median after inspecting the skewed distribution.
    - Corrected impossible `yearsascustomer` values based on maximum company age and verified zero remaining missing values. 
- **Exploratory data analysis**
    - Used `groupby` aggregations to compare customer counts and revenue across sales methods, weeks, states, tenure, and website visits.
    - Calculated average revenue per method and week‑to‑week revenue changes to assess trends over time. 
- **Visualization (pandas + matplotlib)**
    - Bar charts for customers and revenue by sales method and by state.
    - Histograms/boxplots to explore revenue distributions overall and per method.
    - Line plots for revenue over time by sales method.
    - Scatter plots for revenue vs. years as customer and revenue vs. website visits. 
- **Business metrics and recommendations**
    - Defined **total revenue by sales method** and **revenue over time by method** as key monitoring KPIs.
    - Recommended prioritizing the **Email → Call** sequence, focusing on top‑revenue states, newer customers, and mid‑engagement visitors (~25 site visits). 
***

## Tech stack

- Python, pandas, NumPy
- Matplotlib for visualizations
- Jupyter Notebook (.ipynb) for analysis and reporting

  


