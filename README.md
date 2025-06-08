# Climate-Health-Analysis
An analysis of the links between climate change, societal resilience, and global health outcomes using World Bank and WHO data
# Analyzing the Links Between Climate, Resilience, and Global Health

**Author:** [Wil Watkins]
**Date:** June 7, 2025

## 1. Project Objective
This project, developed as part of a professional data analytics portfolio, aims to explore the complex relationships between climate change, societal resilience, and critical public health outcomes. Using a multi-source dataset, the analysis investigates how factors like rising temperatures and access to basic services correlate with health burdens such as malaria and diarrheal diseases, with a focus on how these impacts differ across various socio-economic contexts.

## 2. The Analytical Journey: From Global Noise to Specific Stories
The initial phase of this project involved a global-level correlation analysis. However, this approach revealed a crucial insight: on a global scale, the correlations were surprisingly weak. This discovery was not a failure, but a finding in itself—proving that the impacts of climate change are not uniform and are heavily mediated by local factors.

This led to a strategic pivot. Instead of a broad and noisy global analysis, the project's focus shifted to a more powerful "Case Study" approach. By creating dashboard-style time-series charts for individual, highly vulnerable nations, we were able to uncover much clearer and more compelling narratives.

## 3. Data Sources & Preparation
A robust dataset was constructed by sourcing, cleaning, and merging data from five distinct sources:

**Climate Data:** Temperature Anomalies (FAOSTAT / Our World in Data)
**Resilience Data:** Access to Basic Water Services (WHO / Our World in Data)
**Socio-economic Data:** Historical Income Group Classifications (World Bank)
**Health Data:** Global Burden of Disease (IHME / Kaggle) & Malaria Estimated Cases (WHO / Kaggle)
The data preparation was a significant part of the project, involving handling missing values, standardizing country names, and merging multiple tables to create a final, analysis-ready dataset.

## 4. Key Findings & Visualizations
The final analysis, focusing on case studies of climate-vulnerable nations, produced several key insights.

### Finding 1: The "Threat Multiplier" Effect in Vulnerable Nations
In countries like Mali, which face significant climate stress, there is a visible relationship between temperature spikes and public health crises. The charts show that years with higher temperature anomalies often correspond with higher burdens from climate-sensitive diseases like malaria and water-borne illnesses like diarrhea. This highlights how climate change acts as a "threat multiplier" in nations with lower resilience.

[image](https://github.com/user-attachments/assets/940e1499-ed87-47e6-85c3-958ce9040c99)

### Finding 2: The Challenge of Scale in Population Giants
The analysis of countries like Brazil and Pakistan tells a different but equally important story. While these nations may have higher average resilience metrics, their immense populations mean that even small climate-related disruptions can affect a massive number of people. Their charts often show high and volatile absolute numbers for disease cases, illustrating the unique challenge of protecting large populations.

[image](https://github.com/user-attachments/assets/3a6f6977-e650-42d7-984e-9c96495d7f08)

## 5. Tools Used

**Python:** Pandas for data manipulation and analysis.
**Matplotlib:** For creating custom, multi-axis time-series visualizations.
**Jupyter/Google Colab:** As the primary development environment.
## 6. How to Use This Repository

The complete, commented code and analysis can be found in the Jupyter Notebook file: **Untitled0.ipynb**
The clean, merged dataset used for the analysis and for building the Tableau dashboard is available here: **project2_health_climate_data.csv**
An interactive version of this analysis can be explored on my **[Tableau Public Dashboard] (https://public.tableau.com/app/profile/william.watkins5080/vizzes)**.
A narrative summary of this project is also available as a **[LinkedIn Article](link-to-your-linkedin-article)**.
