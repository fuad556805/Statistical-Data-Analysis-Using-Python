# Statistical Data Analysis Using Python 📊

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Statistics](https://img.shields.io/badge/Statistics-Data%20Analysis-blue?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Datasets Used](#datasets-used)
3. [Tools & Technologies](#tools--technologies)
4. [Project Workflow](#project-workflow)
    - [Data Loading & Cleaning](#data-loading--cleaning)
    - [Sampling Strategy](#sampling-strategy)
    - [Assumption Checking](#assumption-checking)
    - [Hypothesis Testing](#hypothesis-testing)
5. [Key Statistical Analysis & Insights](#key-statistical-analysis--insights)
6. [Statistical Methods Used](#statistical-methods-used)
7. [Files Included](#files-included)
8. [Conclusion](#conclusion)
9. [Author](#author)

---

## Project Overview

This project demonstrates **Statistical Data Analysis** using **Python**, focusing on applying correct **hypothesis testing techniques** to real-world datasets.

The analysis includes **data cleaning, random sampling, assumption checking, statistical testing, and interpretation of results**.  
The project follows an **end-to-end statistical workflow**, ensuring appropriate test selection and valid inference.

---

## Datasets Used

- **Heart Disease Dataset** (Kaggle)
- **Iris Dataset** (Seaborn)
- **Marketing Revenue Dataset**
- **Cardiovascular & Smoking Dataset**

---

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **SciPy**
- **Seaborn**
- **Matplotlib**
- **Statsmodels**

---

## Project Workflow

### Data Loading & Cleaning
- Imported datasets using Pandas
- Removed or handled missing values
- Converted variables to appropriate data types
- Selected relevant columns for analysis

### Sampling Strategy
- Random sampling of 30 observations (`random_state = 42`)
- Group-wise sampling where required (e.g., gender, species)

### Assumption Checking
- Checked normality using **Shapiro-Wilk Test**
- Verified assumptions before applying parametric tests

### Hypothesis Testing
- Applied suitable statistical tests based on data structure
- Calculated test statistics and p-values
- Decision-making at **5% significance level**

---

## Key Statistical Analysis & Insights

1. One-sample t-test on resting blood pressure vs standard value
2. Independent sample t-test for gender-based heart rate comparison
3. Paired sample t-test for before-after marketing revenue analysis
4. One-way ANOVA for petal length differences among Iris species
5. Post Hoc Tukey HSD analysis
6. Chi-square test for association between smoking and cardiovascular disease
7. Assumption validation using normality tests
8. Interpretation of statistical significance using p-values

---

## Statistical Methods Used

- **One-Sample t-Test**
- **Independent Sample t-Test**
- **Paired Sample t-Test**
- **One-Way ANOVA**
- **Tukey HSD Post Hoc Test**
- **Chi-Square Test of Independence**
- **Shapiro-Wilk Normality Test**

---

## Files Included

| File Name | Description |
| --------- | ----------- |
| `statistics_project.ipynb` | Complete statistical analysis code |
| `Statistics_Module_Assesment.pdf` | Project Assesment |
| `README.md` | Project documentation |
| Dataset Files(.csv) | Raw and processed datasets |

---

## Conclusion

This project highlights practical skills in **statistical analysis using Python**, including correct hypothesis test selection, assumption verification, and result interpretation.  
It reflects real-world analytical thinking and supports **data-driven decision-making** using statistical evidence.

---

## Author

**Al Fahim Fuyad**  
BSc in Computer Science & Engineering  
East West University
