# 📄 Prompt Journey: The Evolution of a Data Analysis

This document details the sequence of prompts used throughout this chat to perform a data analysis on sales figures. The progression of these prompts demonstrates a realistic workflow that evolved from a broad business question to specific technical refinements, resulting in a robust and well-documented data product.

---

### Phase 1: The Initial Business Question

In this phase, the goal was broad: to extract value from raw data.

* **Main Prompt:**
    > "Consolidate all third-party datasets to perform an analysis. Transform sales data into relevant insights for the manufacturer. What are the most popular products in each country? How can we optimize the transportation and logistics process up to the point of sale?"

* **The Goal:** To obtain a 360° view of the business from multiple data sources, focusing on product and logistics insights.

* **The AI's Action:**
    1.  Consolidated data from 3 spreadsheets.
    2.  Analyzed product popularity by country.
    3.  Analyzed sales volume by country to suggest optimizations.

* **Evolution:** This initial prompt defined the project's scope and generated the first strategic insights.

---

### Phase 2: Refinement and Data Quality

After the initial analysis, the focus shifted to data quality and readability.

* **Sequential Prompts:**
    > 1. "change the date format to the US standard"
    > 2. "transform the birth date as well"
    > 3. "show the average age for each country"

* **The Goal:** To standardize the data for the local context (US) and to extract new demographic information from the already cleaned data.

* **The AI's Action:**
    1.  Formatted the date columns to the `MM/DD/YYYY` standard.
    2.  Calculated the age of each buyer and presented the average per country.

* **Evolution:** The project evolved from a purely sales-focused analysis to include customer demographics. Data quality became a priority.

---

### Phase 3: Documentation and Project Structuring

With the analysis complete, the need shifted to documenting the process professionally.

* **Main Prompts:**
    > 1. "Challenge Description... This project aims to explore the use of prompts..."
    > 2. "base it on this repository format" (with an image of a GitHub repository)
    > 3. "create a detailed `README.md` file"
