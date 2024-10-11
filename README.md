# module3-sparcs-descriptive-2022
Module 3 Homework Assignment:  Explore healthcare trends, patient demographics, and hospital performance metrics in 2022 SPARCS (Statewide Planning and Research Cooperative System) de-identified data

## Objective
This project involves loading a portion of the 2022 SPARCS (Statewide Planning and Research Cooperative System) de-identified data and performing basic descriptive statistics and visualizations. The goal is to explore healthcare trends, patient demographics, and hospital performance metrics.

By the end of this assignment, the analysis will be uploaded to a GitHub repository named **sparcs_descriptive_2022**.

## Data Source
The dataset used in this analysis is from [Hospital Inpatient Discharges - SPARCS De-Identified 2022](https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/5dtw-tffi). The analysis focuses on a subset of this dataset with the following key fields:

- Age Group
- Gender
- Length of Stay
- Type of Admission
- Total Charges
- Total Costs
- Discharge Year
- Ethnicity
- Race

## Instructions

### 1. Setup GitHub Repository
Create a GitHub repository named **sparcs_descriptive_2022**. Ensure that the repository includes this `README.md` file explaining the analysis.

### 2. Loading the Data
Use the dataset from the link provided or download the file and load it into your Python environment using Pandas. Filtered data down to only include Suffolk and Nassau counties. Ensure that the dataset includes the following fields:
- Age Group
- Gender
- Length of Stay
- Total Charges
- Total Costs
- Type of Admission

### 3. Basic Descriptive Statistics
Perform basic descriptive statistics on key numeric fields:
- Length of Stay
- Total Charges
- Total Costs

Calculate the following statistics:
- Mean
- Median
- Standard Deviation
- Min/Max
- Percentiles (25th, 50th, 75th)
- Quartiles

### 4. Exploring Categorical Variables
Count and explore the distribution of categorical variables:
- Age Group
- Gender
- Type of Admission

Create bar plots to visualize the counts of each category.

### 5. Visualizations
Generate the following visualizations to summarize the dataset:
1. **Histogram** of `Length of Stay` to show its distribution.
2. **Boxplot** for `Total Charges` to identify outliers.
3. **Bar Plot** for `Type of Admission` to analyze admission trends (e.g., Emergency, Elective, Trauma).

### 6. Handling Missing Data
Check for missing data in the selected fields and handle it appropriately by:
- Dropping rows with missing data, or
- Filling missing data with the mean/median as needed.

### 7. Summary Report
- What is the average length of stay?
- How does the total cost vary by age group or type of admission?
- Are there any noticeable trends in admissions or charges?

---

## Technologies Used
- **Python**: The core language used for data analysis.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **Seaborn**: For advanced visualizations.
  
## Setup Instructions
1. Clone the repository.
2. Install the necessary dependencies using the following:
   ```bash
   pip install pandas matplotlib seaborn

