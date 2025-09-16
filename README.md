Pharma Sales Data Cleaning & Analysis
Executive Summary

The pharmaceutical industry generates vast amounts of data, from prescriptions and product sales to city-level distribution. However, the raw data often comes in messy formats, making analysis nearly impossible.

This project focused on transforming a messy pharmaceutical dataset (Messy_pharma.csv) into a cleaned, structured format (cleaned_large_pharma.csv). The cleaned dataset was then made suitable for dashboarding and further analysis.

The outcome is a reliable dataset that can now be used for:

      Revenue tracking by product, brand, or city

      Profit/loss evaluation

      Identifying high-performing regions

      Business strategy alignment

Business Problem
    
The original dataset suffered from several issues that made it difficult to use for business decision-making:

    Data Quality Issues: Missing values, duplicated entries, and inconsistent naming conventions for drugs and cities.

    Formatting Problems: Misaligned rows/columns and unstandardized date formats.

    Scalability Concerns: Data could not be fed directly into BI tools (like Power BI or Tableau) without transformation.

    Decision-Making Gap: Executives lacked a single source of truth for performance insights.

Without cleaning, the dataset was not actionable for either analysts or stakeholders.

Methodology
1. Data Cleaning & Transformation

    Removed duplicate rows and corrected column misalignments.

    Standardized city and product/brand names to ensure consistency.

    Replaced or flagged missing/null values.

    Reformatted dates into a standard time-series format.

    Validated revenue and profit calculations to eliminate negative or unrealistic values.

2. Dataset Structuring

   Exported cleaned data as cleaned_large_pharma.csv.

   Prepared dataset for dashboarding (Power BI/Excel).

    Ensured compatibility for future integration into advanced analytics (forecasting, segmentation).

Pipeline (Textual)

Messy Pharma Dataset (CSV)
        |
        v
Data Cleaning (duplicates removed, missing handled, names standardized)
        |
        v
Cleaned Dataset (Structured CSV)
        |
        v
Business Insights (Dashboards / Analysis)


Skills Applied

    Data Wrangling: Python (Pandas), Excel

    Data Quality Checks: Handling missing values, duplicates, and inconsistencies

    Data Structuring: Normalization, standardization, and schema alignment

    Business Analysis: Preparing dataset for KPIs like sales, revenue, profit

    Documentation: Clear, reproducible project structure for GitHub

Results

The cleaned dataset unlocked the ability to derive the following insights:

    Revenue by Product/Drug: Identifying the top-selling drugs.

    Brand-Level Performance: Comparing competing pharma brands.

    Profitability Trends: Distinguishing between high-revenue but low-margin drugs vs. sustainable performers.
  
    City-Wise Distribution: Highlighting regional strengths and weaknesses.

With the cleaned dataset, dashboards can now present KPIs such as total sales, revenue, profit/loss, and city-level performance without inconsistencies.

Next Steps

Visualization

    Build an interactive Power BI dashboard on top of cleaned_large_pharma.csv.

    Include KPIs such as revenue by brand, profit by region, and monthly trends.

Predictive Analytics

    Forecast demand for specific drugs/brands across different cities.

Segmentation

    Group cities and products into high-value vs. low-value categories.

Automation

    Develop a pipeline that automatically cleans new pharma datasets using Python.
