# PHP2550-Project2-Regression-Analysis
# Predictive Modeling for Tracheostomy in Severe Bronchopulmonary Dysplasia (sBPD)

## Overview
This repository hosts the research and analysis for the project "Predicting the need for tracheostomy in infants with severe bronchopulmonary dysplasia." The project develops regression models using NICU data to predict tracheostomy or death in infants with sBPD.

## Data Source
The analysis is based on a national dataset encompassing demographic, diagnostic, and respiratory parameters of infants diagnosed with sBPD. Parameters measured at 36 and 44 weeks Post-Menstrual Age (PMA) were crucial in the analysis.

## Methods
- `Data Preprocessing`: Included removing duplicates, addressing discrepancies, and handling missing values.
- `Model Development`: LASSO regression for predictive modeling.
  - **LASSO Regression**: Fitted and validated using training and validation datasets. Included converting categorical to numerical variables using one-hot encoding.
  - **Mixed-Effects Models**: Employed to consider the random effects of different medical centers, alongside LASSO models, providing insights into fixed and random effects on the outcome.
- `Performance Evaluation`: Models were evaluated using sensitivity, specificity, F1 score, and Brier score.

## Repository Structure
-  `Images/`: Contains images used in the project.
-  `LICENSE`: The license file for the project.
- `Project 2.Rmd`: R Markdown file containing the detailed code.
- `Project 2.pdf`: PDF document of the compiled analysis and findings.
- `README.md`: Describes the project, methodology, and repository contents.
