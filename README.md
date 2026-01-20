# Breast Cancer Survival Analysis (METABRIC)

This repository contains a personal research project exploring breast cancer survival outcomes using clinical data from the METABRIC dataset. The analysis focuses on Kaplan–Meier survival curves and Cox proportional hazards models to examine the effects of tumor characteristics and patient factors on overall survival.

## Contribution and Acknowledgements

This project was initiated and analysed by the author as part of the University of Sydney SUDATA (Data Society) Research Mentoring Program. The project benefited from feedback and recommendations provided by a program mentor. The accompanying presentation was prepared collaboratively by two additional contributors based on the results generated from this analysis.

## Repository Structure

- **analysis/** — Quarto notebooks for data cleaning and analysis  
- **data/** — Raw and cleaned datasets (raw data not tracked in Git)  
- **scripts/** — Shared setup and helper functions  
- **presentation/** — Final presentation PDF  
- **README.md**  
- **.gitignore**

## Data Source

The METABRIC dataset used in this project was obtained from Kaggle: "Breast Cancer Gene Expression Profiles (METABRIC)" by Raghad Alharbi.  
https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric


## How to Run

0. Download `METABRIC_RNA_Mutation.csv` from the data source above and place it in `data/`.

1. Run `analysis/01_data_cleaning.qmd` once to generate the cleaned dataset:  
   `data/data_clean.csv`

2. You can then render any other `.qmd` file in `analysis/` independently.

Each notebook sources a shared setup script:  
`source("../scripts/setup.R")`


## Methods

- Reproducible data analysis using R and Quarto
- Survival analysis (Kaplan–Meier and Cox proportional hazards models)
- Data cleaning and bias considerations
- Effect size and model diagnostics (PH assumption, linearity, multicollinearity, interactions)
- Version control with Git and project documentation

## Notes

This project is intended for learning, demonstration, and portfolio use. Results should not be interpreted as clinical conclusions.
