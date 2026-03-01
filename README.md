# 📊 Life Expectancy Data Analysis  
**STAT 431 – Multiple Linear Regression Project**

---

## Project Overview

This project analyzes global life expectancy using the Global Health Observatory (GHO) dataset, which contains health, economic, and social indicators for 193 countries between 2000 and 2015.

The objective of this study was to determine which factors significantly influence life expectancy and to construct a statistically valid multiple linear regression model.

---

## Research Objectives

- Identify key determinants of life expectancy  
- Compare developed and developing countries  
- Evaluate the impact of health investments and education  
- Diagnose multicollinearity and regression assumptions  
- Refine the model using statistical selection techniques  

---

## Dataset Description

The dataset includes the following variables:

- Adult Mortality  
- Infant Deaths  
- Alcohol Consumption  
- Percentage Health Expenditure  
- Hepatitis B, Polio, and Diphtheria Immunization  
- BMI  
- HIV/AIDS  
- GDP & Income Composition of Resources  
- Schooling  
- Country Development Status  

**Dependent Variable:** Life Expectancy (continuous)

---

##  Methodology

### Exploratory Data Analysis

- Histogram confirmed approximate normality of life expectancy  
- Boxplots showed significant differences between developed and developing countries  
- Correlation matrix revealed multicollinearity among predictors  

### Initial Linear Model

A full multiple linear regression model was constructed using all predictors.

**Results:**

- R² ≈ 0.81  
- Statistically significant overall F-test  
- Several insignificant variables detected  
- Multicollinearity present (high VIF values)  

---

## Model Diagnostics

Identified Issues:

- Multicollinearity among mortality and health variables  
- Residual dependence (Durbin-Watson < 2)  
- Potential influential observations  

Stepwise model selection (AIC-based) was applied to refine the model.

---

## Final Model Results

After removing multicollinear variables:

- Model assumptions satisfied  
- Multicollinearity resolved  
- Adjusted R² ≈ 0.80  

**Significant Predictors Included:**

- Adult Mortality  
- Infant Deaths  
- Schooling  
- Income Composition  
- Vaccination Coverage  
- Development Status  

---

## Key Findings

1. Developing countries have significantly lower life expectancy.
2. Education (schooling) is a strong positive predictor.
3. Vaccination programs significantly reduce mortality.
4. Adult mortality and infant deaths negatively impact life expectancy.
5. Alcohol consumption was not statistically significant after controlling for other variables.

---

## Policy & Economic Implications

- Investment in education improves national health outcomes.
- Expanding vaccination programs increases life expectancy.
- Economic stability and healthcare funding are critical in developing countries.

---

## Tools Used

- R  
- Multiple Linear Regression  
- VIF (Variance Inflation Factor)  
- AIC Model Selection  
- Residual Diagnostics  
- Data Visualization  

---

## Full Presentation

The complete project presentation is available below:

[View Full Analysis (PDF)](Life_Expectancy.pdf)