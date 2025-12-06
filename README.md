# Cole Maher, Advanced Data Analysis Final Project

## Abstract

Introduction: Influenza (flu) vaccination reduces the spread, severity, and likelihood of infection. Flu vaccination from 2020-2024 fell for all age groups in the United States (US). Most research indicates that as age increases, likelihood of flu vaccination increases. The objective of this research is to investigate differences in odds of flu vaccination across age categories for adults in the US in 2024.

Methods: Utilizing cross-sectional data from the 2024 Behavioral Risk Factor Surveillance System, the age-flu vaccine relationship was modeled using a binomial logistic regression. The model investigated if five year age groups differ in odds of flu vaccination compared to 18-25 year olds controlling for race and sex. Also, effect modification by education was evaluated. The study population included complete cases (n=405,844).

Results: After adjustment, odds of vaccination increased with age, reaching the highest odds among adults aged 80+ compared to adults aged 18-24 (OR=5.43; 95% CI: 5.24-5.62). Odds of flu vaccination for 25-29 year olds was 7% greater compared with 18-24 year olds (OR=1.07; 95% CI: 1.03, 1.11). Stratifying by education groups found younger (25-29 and 30-34) non-college graduates were less likely to get vaccinated compared to 18-25 year olds.

Conclusion: Consistent with existing evidence, results indicated that odds of flu vaccination increases as age group increases. These findings can help national vaccination programs develop programs targeted at specific age groups across education levels. 


## Files Included
- `ADAFinalProjCode.Rmd` : Completed Annotated Code for Analysis and Figure Creation
- `LLCP2024.XPT .zip` : BRFSS 2024 dataset from (https://www.cdc.gov/brfss/annual_data/annual_2024.html)
- `README.md`: This file


## What the Code Does
- Reads in the survey dataset
- Performs data cleaning (e.g., renaming columns, filtering)
- Creates summary statistics (e.g., age,  gender, flu shot, education, race responses)
- Evaluates the relationship between age group and flu shot, adjusted for race and sex
- Tests education as an effect modifier and stratifies analysis
- Generates plots and tables to visualize the data professionally

## How to Run the Code

1. Download or clone this repository to your computer
2. Open `ADAFinalProjCode.Rmd` in RStudio
3. Copy path name to fit location of dataset on your computer

cd
4. Run the script
## Author
- Name: Cole Maher
- Course: Advanced Data Analysis
- Date: December 2025