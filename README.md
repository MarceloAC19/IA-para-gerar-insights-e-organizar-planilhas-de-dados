# AI-for-generating-insights-and-organizing-data-spreadsheets

# 🚀 Sales Analysis with AI | Project Challenge

This repository documents the complete solution to a project challenge where an Artificial Intelligence (Gemini) was used to execute a data analysis pipeline, from cleaning and consolidating raw sources to extracting strategic insights for the fictional company "Meganium".

## 💻 About the Project

The goal was to simulate a real-world data analysis scenario, where interaction with an AI tool transformed raw, decentralized sales data into a cohesive and actionable knowledge base. The project demonstrates an iterative workflow in which requirements were refined, and the data processing pipeline was enhanced to ensure maximum quality and accuracy in the results.

### 🛠️ Technologies Used

* **Programming Language:** Python
* **Libraries:** Pandas
* **AI Tool:** Google Gemini
* **Platform:** GitHub

### 📊 Analysis Process: Step-by-Step

The analysis was conducted through a series of prompts, evolving from a simple request to a more robust and detailed data processing pipeline.

#### Step 1: Initial Request and First Analysis
* **Prompt:** "Consolidate all third-party datasets to perform an analysis. Transform sales data into relevant insights for the manufacturer. What are the most popular products in each country? How can we optimize the transportation and logistics process up to the point of sale?"
* **AI's Action:** The AI merged the three CSV files and performed a preliminary analysis.

#### Step 2: Process Improvement and Refinement
* **Prompts:** "change the date format to the US standard", "transform the birth date as well".
* **Process Evolution:** The workflow was revised to create a more complete and robust cleaning pipeline.

#### Step 3: Deep Cleaning and Formatting Pipeline (Final Version)
* **Prompts:** "for the three csv files I sent you, also correct the dates to the US format, then integrate them into the last command I gave you" and "format the csv files so they are all organized, in case there are any formatting errors".
* **AI's Action (Refined Workflow):**
    1.  **Cleaning at the Source:** The AI processed each of the three raw data files individually.
    2.  **Comprehensive Formatting:** In each file, the following corrections were applied: standardization of column names, formatting dates to `MM/DD/YYYY`, removing whitespace, and ensuring correct numeric data types.
    3.  **Final Consolidation:** After individual cleaning, the three processed files were merged into the `Consolidated_Sales_Data_Final.csv` file.

#### Step 4: Demographic Analysis
* **Prompt:** "show the average age for each country".
* **AI's Action:** Using the clean, consolidated file, the AI calculated the age of each buyer and grouped the data by country to extract the average.

### ✨ Strategic Recommendations

1.  **Logistics Optimization:** The highest sales volumes are concentrated in **Canada** and **France**. It is recommended to prioritize logistics optimization in these regions.
2.  **Targeted Marketing:** Campaigns should be segmented by country, considering product popularity and the demographic profile (age) of customers.
3.  **Intelligent Inventory Management:** Product inventory should be allocated geographically based on popularity data to optimize inventory levels.

### 🚀 How to Use This Project

1.  **Clone the repository.**
2.  **Explore the data:** The raw and processed data are in the `/data` folder.
3.  **(Optional) Run the analysis:** If a notebook is included, install the dependencies (`pandas`, `jupyter`) and run it.
