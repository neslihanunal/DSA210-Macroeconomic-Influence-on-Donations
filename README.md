# DSA210 Project: The Impact of Macroeconomic Indicators on Donations

## Table of Contents

- [Project Overview](#project-overview)
- [Motivation](#motivation)
- [Objectives](#objectives)
- [Hypotheses](#hypotheses)
- [Data Sources](#data-sources)
- [Data Collection and Preprocessing](#data-collection-and-preprocessing)
- [Analysis Plan](#analysis-plan)
- [Tools and Technologies](#tools-and-technologies)
- [Expected Challenges](#expected-challenges)
- [Expected Findings](#expected-findings)
- [Limitations](#limitations)
- [Future Work](#future-work)
- [Conclusion](#conclusion)
- [Disclaimer](#disclaimer)

---

## Project Overview

I am Neslihan Ünal, a sophomore at Sabancı University majoring in Computer Science and Economics. This project, conducted as part of my DSA210 course, examines how macroeconomic indicators—GDP growth, inflation rates, and unemployment rates—affect charitable donations. The objective is to assess whether economic fluctuations influence donation patterns and provide insights for nonprofit organizations and policymakers.

This study focuses on **the United States and Europe**, where publicly available donation records and macroeconomic data are well-documented. The research primarily investigates the **education and disaster relief sectors**, as these are among the most economically sensitive areas of philanthropy.

---

## Motivation

During financial crises, nonprofits often struggle to maintain donation levels as individuals and corporations adjust their spending priorities. This study aims to analyze whether macroeconomic conditions influence charitable contributions and, if so, which indicators are the most significant predictors.

By integrating economic theory with data analysis, this research will contribute to understanding donor behavior, particularly in response to economic uncertainty.

---

## Objectives

- Analyze how macroeconomic indicators such as GDP growth, inflation rate, and unemployment rate affect donation behaviors in the **United States and Europe**.
- Assess whether variations in these indicators significantly predict changes in charitable donations.
- Provide actionable insights for nonprofit organizations in the **education and disaster relief sectors** to enhance financial planning during different economic conditions.

---

## Hypotheses

1. **GDP Growth and Donations**  
   - **H₀ (Null Hypothesis):** GDP growth does not significantly influence the volume of donations.  
   - **H₁ (Alternative Hypothesis):** Higher GDP growth leads to an increase in charitable donations.

2. **Inflation and Donations**  
   - **H₀ (Null Hypothesis):** Inflation rates have no significant impact on donations.  
   - **H₁ (Alternative Hypothesis):** Higher inflation rates reduce donation amounts due to lower disposable income.

3. **Unemployment and Donations**  
   - **H₀ (Null Hypothesis):** Unemployment rates do not significantly affect donations.  
   - **H₁ (Alternative Hypothesis):** Higher unemployment rates decrease charitable contributions as individuals prioritize essential expenses.

---

## Data Sources

- **Macroeconomic Indicators:**  
  - GDP growth, inflation rates, and unemployment rates.
  - Data will be sourced from reputable databases such as:
     - [World Bank](https://www.worldbank.org)
     - [OECD](https://www.oecd.org)
     - [FRED Economic Database](https://fred.stlouisfed.org)
     - [Eurostat](https://ec.europa.eu/eurostat)


- **Donation Data:**  
  - Historical donation statistics will be obtained from:
    - Nonprofit annual reports
    - World Bank philanthropy reports
    - OECD databases
    - FRED records
    - [Charity Navigator](https://www.charitynavigator.org) (USA)
    - Giving Europe reports

---

## Data Collection and Preprocessing

#### Collect Data
- Retrieve macroeconomic indicator data from official databases.
- Obtain donation records from nonprofit organizations and related sources.

#### Clean and Preprocess Data
- **Align timestamps** and standardize formats.
- **Address missing values** and remove outliers.
- **Account for regional differences** in data reporting standards between the United States and Europe.

#### Merge Datasets
- Integrate macroeconomic indicators with donation statistics for correlation and trend analysis.

#### Handling Confounding Variables
- Include additional variables such as government policies, tax incentives, and cultural factors that could influence donation behaviors, ensuring a more robust analysis of causal relationships.

---

## Analysis Plan

#### **Exploratory Data Analysis (EDA)**
- **Examine** donation trends in the United States and Europe during different economic conditions.
- **Visualize** relationships between macroeconomic indicators and donations using scatter plots, line charts, and correlation heatmaps.
- **Compare** trends between regions to highlight differences in economic environments and reporting practices.

### **Statistical Analysis**
- **Correlation Analysis:**  
  Measure relationships between economic factors and donations.
- **Regression Analysis:**  
  Apply linear regression models to quantify the impact of macroeconomic indicators on donation amounts.
  - **Multicollinearity:** Address potential multicollinearity among predictors using techniques such as Variance Inflation Factors (VIF) or Principal Component Analysis.
- **Hypothesis Testing:**  
  Validate statistical significance using appropriate tests.
- **Robustness Checks:**  
  Incorporate methods to validate the predictive models, ensuring reliability and accuracy.

### **Predictive Modeling**
- Develop **predictive models** (e.g., linear regression, random forest regression) to forecast donation behaviors based on economic trends.

---

## Tools and Technologies

- **Programming Language:** Python
- **Data Analysis and Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **Statistical Libraries:** Scikit-learn, SciPy
- **Additional Techniques:** Methods for detecting multicollinearity and validating predictive models


---

## Expected Challenges

- **Data Availability:**  
  Donation records may vary across regions and organizations, requiring careful dataset selection.
- **Standardization Issues:**  
  Different organizations and countries report donations using different formats.
- **Confounding Variables:**  
  External influences such as government policies, tax incentives, and regional cultural factors may also impact donation behaviors.
- **Causality vs. Correlation:**  
  Distinguishing true causal relationships from mere correlations in the presence of multiple influencing factors.

---

## Expected Findings

- Identify how different macroeconomic indicators correlate with donation levels in the **United States and Europe**.
- Determine whether **economic downturns lead to lower charitable contributions** or whether donors increase giving during crises.
- Provide data-driven recommendations for nonprofits in the **education and disaster relief sectors** on how to **adapt to economic fluctuations**.
- Offer insights into the effectiveness of public policies and incentive structures on fostering charitable giving.


---

## Limitations

- Analysis is based on **publicly available data,** which **may not capture private donation** trends.
- Different countries and organizations follow **varying reporting standards**, affecting data consistency.
- External influences, such as **government policies and tax incentives,** may also impact donation behaviors.

---

## Future Work

- Expand the study to include **individual donor demographics** and psychographic insights.
- Incorporate **additional economic factors** such as consumer confidence indices and tax incentives.
- Conduct a **comparative study across multiple European countries** to identify regional differences in donation behaviors.

---

## Conclusion

This research will provide valuable insights into how macroeconomic fluctuations impact donation behaviors in the **United States and Europe**. By identifying key economic predictors of charitable giving, this study can assist nonprofit organizations in financial planning and policy formulation. The findings will contribute to a broader understanding of how economic conditions shape philanthropic behavior.

---

## Disclaimer

This project is conducted for academic purposes only. The conclusions drawn from this study are based on publicly available data and statistical models and should not be interpreted as financial or professional advice.
