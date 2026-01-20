
# Breast Cancer Survival Analysis Project

In this semi-personal project, I used Kaplan–Meier survival curves and Cox proportional hazards (PH) models to examine the effects of clinical factors on long-term survival of patients with breast cancer.

## Contributions and acknowledgements

I completed this as part of the University of Sydney SUDATA (Data Society) Research Mentoring Program. I completed all the analyses in R by myself and the project benefited from guidance from my program mentor. The final presentation slides (based off this analysis, see `presentation/`) were prepared and presented in collaboration with two additional contributors.

## File structure

- **analysis/** Quarto notebooks for data cleaning and analysis  
- **scripts/**
- **presentation/** Final presentation PDF  
- **README.md**  
- **.gitignore**

## Data

The METABRIC dataset used is from Kaggle: "Breast Cancer Gene Expression Profiles (METABRIC)" by Raghad Alharbi.  
https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric


## Running code

0. Download `METABRIC_RNA_Mutation.csv` from the data source above and place it in `data/`.

1. Run `analysis/01_data_cleaning.qmd` once to generate the cleaned dataset, `data/data_clean.csv`

2. You can then render the other two `.qmd` files in `analysis/`.

Each notebook sources a shared setup script, `source("../scripts/setup.R")`


## Methods/skills

- Data cleaning, bias considerations 
- Survival analysis (using Kaplan-Meier and Cox PH models)
- Analysing effect size and model diagnostics (PH assumption, linearity, interaction, etc)

## Extra notes

This project is for demonstration; results should not be interpreted as clinical conclusions.
