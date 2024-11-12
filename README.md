# Impact of Ozempic on Obese and Hypertensive Patients

## Overview
This project examines the effects of Ozempic on obese and hypertensive patients aged 40-75, with a focus on estimating treatment effects accurately. By leveraging advanced statistical methods and handling endogeneity, this analysis aims to provide insights into the causal relationships within the dataset. The assignment involves exploratory data analysis, data merging, causal modeling, and generating insights using various external resources.

## Project Structure
1. **Exploratory Data Analysis (EDA)**  
   - Conducts a thorough exploration of medical claims and prescription datasets, analyzing data structure, missing values, and variable distributions.
   - Visualizes relationships and identifies patterns, outliers, and anomalies to better understand the dataset.

2. **Data Preprocessing and Merging**  
   - Handles missing data and encodes categorical variables.
   - Merges Medical and Prescription datasets to create a cohesive structure for analysis.

3. **Causal Analysis Setup**  
   - Discusses potential endogeneity issues in estimating Ozempic’s treatment effects.
   - Outlines strategies to address causality and treatment effect estimation.

4. **Model Development**  
   - Implements Double-Lasso/Treatment Effect Lasso techniques to estimate the treatment effect, carefully selecting variables.
   - Provides rationale for the inclusion of variables to enhance the reliability of causal estimates.

5. **Model Evaluation and Interpretation**  
   - Evaluates model performance and interprets the treatment effects of Ozempic on the patient population.
   - Discusses implications of findings and provides insights into the model’s output.

6. **Additional Insights**  
   - Incorporates demographic factors from census data and additional Ozempic-related information to enrich the analysis.
   - Explores patterns related to treatment effects based on demographics and ZIP code regions.

## Data Sources
- This is a subset of the exclusive dataset of actual patients procured for research purposes.
- **Medical Claims Data**: Includes medical claims data for the specified patient group.
- **Prescription Data**: Contains prescription information for a subset of patients in the Medical Claims dataset.
- **Data Dictionary**: Explains dataset fields and relevant codes.
- **Census and Demographics**: Additional data from census records for ZIP code prefixes and other demographic resources.

## Methodology
- **Double-Lasso / Treatment Effect Lasso**: Applied to handle endogeneity and estimate treatment effects.
- **Endogeneity Handling**: Strategic variable selection to mitigate bias in causal estimates.
- **Statistical Analysis and Visualization**: Used to analyze the data and visualize relationships and insights effectively.

## Requirements
- Python 3.x
- Jupyter Notebook
- Packages: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, and any other specific libraries for causal inference

