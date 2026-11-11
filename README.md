# Exploratory Data Analysis — Titanic Dataset

## Objective
Extract insights from the Titanic dataset using visual and statistical exploration.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
Titanic training dataset: `train.csv`

## What I Did
1. Loaded and inspected the dataset using `.head()`, `.info()`, `.describe()`, and `.value_counts()`.
2. Checked missing values and data quality issues.
3. Created derived features: `FamilySize`, `IsAlone`, `AgeGroup`, `FareGroup`, `Sex_male`.
4. Performed univariate analysis: histograms, countplots, boxplots.
5. Performed bivariate analysis: survival by sex, class, fare, age, family size.
6. Performed multivariate analysis: correlation heatmap, pairplot, survival pivot table by sex and class.
7. Identified trends, anomalies, relationships, and multicollinearity.
8. Summarized findings and interview-question answers.

## Key Findings
- Overall survival rate is about **38.4%**.
- **Sex** is the strongest predictor: female survival ≈ **74.2%**, male survival ≈ **18.9%**.
- **Passenger class** matters: 1st class ≈ **63.0%**, 2nd class ≈ **47.3%**, 3rd class ≈ **24.2%**.
- **Fare** is right-skewed and positively associated with survival.
- **Small families** of 2–4 had better survival than alone passengers and very large families.
- Missing data: `Cabin` missing ≈ **77.1%**, `Age` missing ≈ **19.9%**, `Embarked` missing **2** rows.
- Fare has extreme outliers and some zero fares.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
