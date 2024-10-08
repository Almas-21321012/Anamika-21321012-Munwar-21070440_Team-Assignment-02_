# cardiohealth : Cardiovascular Health Analysis 
# Project Overview
This project aims to analyze a cardiovascular health dataset to uncover insights into how demographic, clinical, and lifestyle factors contribute to cardiovascular disease (CVD). The analysis is divided into two deliverables: the Business Report Notebook, which presents the analysis and key findings, and the Development Notebook, which details the technical steps, algorithms, and pseudocode used to perform the analysis.

# Dataset Information
The dataset consists of the following columns:
- Demographic Factors: Age (in days), Gender
- Clinical Factors: Systolic Blood Pressure, Diastolic Blood Pressure, Cholesterol Levels, Glucose Levels
- Lifestyle Factors: Smoking Status, Alcohol Consumption, Physical Activity
- Target Variable: Cardiovascular Disease (0: No, 1: Yes)

# 1. Business Report Notebook
# Purpose:
The Business Report Notebook focuses on presenting the results of the data analysis. It includes data cleaning, exploration, and visualizations, along with key insights and recommendations based on the findings.

# Key Sections:
- Problem Definition: Investigates cardiovascular disease risk factors using combinations of demographic, clinical, and lifestyle data.
- Data Exploration: Includes summary statistics, visualizations (bar charts, stacked charts), and trend analysis to uncover patterns in the dataset.
- Analysis of Factor Combinations:
Demographic + Lifestyle (e.g., Gender + Smoking)
Demographic + Clinical (e.g., Age + Cholesterol)
Demographic, Clinical, and Lifestyle (e.g., Age, Blood Pressure, and Physical Activity)
- Insights and Recommendations: Discusses key findings such as the impact of cholesterol, age, and blood pressure on cardiovascular disease risk, and suggests public health interventions.

# How to Run:
- Ensure the SQLite database (cardiohealth.db) is uploaded.
- Run all cells sequentially in Google Colab to reproduce the analysis and visualizations.

# 2. Development Notebook
# Purpose:
The Development Notebook provides a detailed breakdown of the technical aspects of the analysis. It contains pseudocode, algorithms, and code implementation, along with explanations of the testing process and challenges encountered.

# Key Sections:
1. Pseudocode and Algorithms: Step-by-step explanation of the approach taken to analyze various combinations of demographic, clinical, and lifestyle factors.
2. Data Cleaning and Preprocessing: Explanation of how missing or inconsistent data was handled.
3. Code Implementation: Python code for data extraction, analysis, and visualization, with proper use of libraries like Pandas and Matplotlib.
4. Testing and Debugging: Includes how the data was validated, handling of outliers, and testing the visualizations for accuracy.
5. Challenges and Resolutions: Discusses challenges like handling outliers, ambiguous data, and visualization complexity, along with the solutions applied.

# How to Run:
- Ensure the cardiohealth.db database is uploaded.
- Run all cells sequentially in Google Colab to reproduce the data processing steps and algorithms.

# Tools and Technologies Used:
- Python: For data processing, analysis, and visualization.
- Pandas: For data manipulation and handling.
- Matplotlib: For creating visualizations.
- SQLite: For database querying and data extraction.
- Google Colab: For running the Jupyter Notebooks and executing Python code.

# How to Use the Gen AI Tools:
In both notebooks, Gen AI tools like ChatGPT and GitHub Copilot were used for generating SQL queries, resolving coding challenges, and improving code efficiency. The interaction with AI tools is documented using the 4-step framework, showcasing how the tools helped or required modifications.
