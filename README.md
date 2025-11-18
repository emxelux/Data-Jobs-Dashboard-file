# Data Jobs Dashboard
![Dashboard Page1](/images/Dashboard_homepage.png)
[View interaction dashboard here on the PowerBI service](https://app.powerbi.com/links/REC6RJQZMB?ctid=ff9602ba-14ce-4683-828a-fcc17702b7d0&pbi_source=linkShare)

## Introduction
This dashboard was created for **Jobs seekers, Job Transitioners, and Job Swappers** to solve a common problem: Information about the data job market is scattered and hard to grasp. Using real-world dataset of 2024 data science job postings (including titles, salaries, and locations), this project provides a single, easy-to-use interface to explore market trends and compensation.

---

## Skills Showcase
- **🧿Data Transformation (ETL) with Power Query:**
Cleaned, shaped and prepared the raw data for analysis by handling blanks, changing data types, and creating necessary columns.
- **📊 Core Charts:**
Utilized **Column, Bar, Line and Area Charts** to visualize the global data job market.
- **📈 Advanced DAX Measures & Calculations:**
Engineered complex Data Analysis Expressions (DAX) to calculate and present key metrics, including:
    * **Average Salary** by job title and location.
    * **Market Concentration Index** to show the distribution of job postings.
    * **Year-over-Year (YoY) Growth** trends for posting volume (if applicable to the 2024 data).
- **🗺️ Interactive Geospatial Analysis:**
Used a **Map Visual** to display job density and average salary across different geographical locations, providing a clear regional market view.
- **⚙️ Dynamic Filtering & Interactivity:**
Implemented **Slicers and Filters** (e.g., Job Title, Location, Salary Range) to allow users to drill down and customize their data exploration experience.

# Dashboard Overview
### Page1 High-Level Market View
![Dashboard Page1](/images/Dashboard_homepage.png)
This is your mission control for data job market. It showcases key KPIs like total job count, median Salaries, and top job titles to give you a quick Understanding of what's happening in the job market at a glance

### Page2 Job Title Drill
![Dashboard Page1](/images/Drill_through_Page.png)

This is the deep-dive page. Form the main dashboard, you can drill through to this view to get specific detailsfor a single job title. inclusing salary ranges, work-from-home stats, top hiring platforms, and a global map of jobs location

---

## Key Insights & Features 💡

This dashboard helps answer critical questions for anyone navigating the data job market:

* **Top Job Roles:** Which data science roles (**Data Scientist, Data Analyst, ML Engineer**) have the highest demand and offer the best compensation?
* **Geographic Hotspots:** Where are the highest-paying and most abundant job opportunities located globally? 
* **Compensation Benchmarks:** What is the average salary range for a specific role and location, enabling better salary negotiation?
* **Market Trends:** How has the volume of job postings changed over time (e.g., monthly or quarterly trends)?

---

## Technical Details (Power BI)

* **Source:** Real-world dataset of 2024 Data Science Job Postings (Specify source if non-sensitive, e.g., Kaggle, or keep it general as done here).
* **Tool:** Microsoft Power BI Desktop.
* **Modeling:** Established a well-structured **Star Schema** (if applicable) or a simplified data model for efficient calculation and visualization performance.
* **Theme:** Used a clean, professional theme for maximum readability and user experience.

---

## How to Use the Dashboard

1.  **Select a Job Title:** Use the **Job Title Slicer** to focus on roles like 'Data Analyst' or 'Machine Learning Engineer'.
2.  **Filter by Location:** Utilize the **Map** or **Location Filter** to see regional data.
3.  **Analyze Compensation:** Review the **Average Salary Card** and **Salary Distribution Charts** to understand the market rate for your selected criteria.

---

## Conclusion

The **Data Jobs Dashboard** transforms raw, scattered job market data into clear, actionable insights, empowering job seekers to make informed decisions and secure their next career move.