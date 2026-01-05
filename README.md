# NYC Jobs Dashboard (Excel)

An interactive Excel dashboard analyzing NYC government job postings to identify hiring demand, compensation trends, and employment stability across job categories.

This project demonstrates an end-to-end analytical workflow, including data cleaning, transformation, aggregation, and visualization using advanced Excel features.

---

## Project Objectives

This analysis answers three key questions:

1. **Job Market Demand**  
   Which NYC agencies and job roles account for the highest volume of position openings?

2. **Compensation Trends**  
   How do salaries vary by job category and career level?

3. **Employment Type & Stability**  
   Which job categories are primarily full-time versus part-time, indicating long-term employment stability?

---

## Data Preparation & Cleaning

The raw dataset required significant preprocessing before analysis. Key steps included:

- Cleaning and standardizing job category labels to eliminate duplicates and inconsistencies  
- Creating derived fields, including:
  - Average salary (calculated from minimum and maximum salary ranges)
  - Clean job category classifications
- Removing unnecessary columns and isolating analysis-ready fields
- Validating numeric fields to ensure accurate aggregation

All data cleaning and transformation steps were performed using **Power Query**, allowing for reproducible and scalable data preparation.

---

## Analysis & Modeling

Analysis was conducted using **PivotTables** to:

- Aggregate total **position openings** (rather than posting counts)
- Summarize salary metrics by job category and career level
- Compare full-time versus part-time employment distributions
- Enable dynamic filtering through slicers

Care was taken to select appropriate aggregation methods (sum, average, percentage) to ensure each analysis accurately reflected the underlying question.

---

## Dashboard & Visualization

The final dashboard was built entirely in Excel and includes:

- Bar charts highlighting top agencies by hiring demand
- Salary ranking charts by job category
- Salary range comparisons using minimum, average, and maximum values
- 100% stacked column charts showing employment stability (full-time vs part-time)
- Interactive slicers for agency, job category, and career level
- A locked layout to prevent accidental edits while preserving interactivity

Each visualization is paired with a concise written insight summarizing the key takeaway.

---

## Key Insights

- Hiring demand is highly concentrated within a small number of NYC agencies and specific job titles  
- Technology, Legal, and Engineering roles command the highest average salaries  
- Most job categories are dominated by full-time positions, while Health roles show a higher reliance on part-time employment  

---

## Tools & Techniques Used

- Microsoft Excel  
- Power Query (data cleaning and transformation)  
- PivotTables and PivotCharts  
- Slicers for interactive filtering  
- Dashboard layout design and sheet protection  

---

## Files Included

- `NYC_Jobs_Dashboard.xlsx` — Interactive Excel dashboard  
- `NYC_Jobs_Dashboard.pdf` — Static export for quick viewing  
- `dashboard_preview.png` — Dashboard preview image  

---

## Data Source

NYC Open Data — NYC Government Job Postings dataset  
(Data cleaned and transformed for analysis)

---

## Why This Project

This project demonstrates practical data analysis skills in Excel, including data cleaning, aggregation, visualization, and storytelling, mirroring real-world analyst workflows.
