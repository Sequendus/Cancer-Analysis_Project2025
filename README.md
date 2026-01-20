
# Breast Cancer Survival Analysis Project

In this semi-personal project, I investigated the role of clinical factors in the long term survival of cancer patients. Statistical techniques I used were Kaplan-Meier survival curves and Cox proportional hazards (PH) models.

## Contributions and acknowledgements

I worked on this project as part of the University of Sydney SUDATA (Data Society) Research Mentoring Program--the topic/dataset was chosen out of personal interest. I completed all the analyses in R by myself while receiving guidance from my program mentor throughout. 

The final pdf presentation slides (based off this analysis, see `presentation/`) were prepared and presented in collaboration with two additional people.

## File structure

- `analysis/` Quarto notebooks
- `scripts/`
- `presentation/` Final presentation PDF  

## Data

The METABRIC dataset used is from Kaggle: "Breast Cancer Gene Expression Profiles (METABRIC)" by Raghad Alharbi.  
https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric


## Running code

0. Download `METABRIC_RNA_Mutation.csv` as above and put it in `data/`.

1. Run `analysis/01_data_cleaning.qmd` once to get the cleaned dataset, `data/data_clean.csv`

2. You can then render the other two `.qmd` files in `analysis/`.

Each notebook sources a shared setup script, `source("../scripts/setup.R")`


## Methods/skills

- Data cleaning, bias considerations 
- Survival analysis (using Kaplan-Meier and Cox PH models)
- Analysing effect size and model diagnostics (PH assumption, linearity, interaction, etc)

## Extra notes

This project is for demonstration; results should not be interpreted as clinical conclusions.
