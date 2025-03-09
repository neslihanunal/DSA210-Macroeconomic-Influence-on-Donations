# DSA210 Project: The Impact of Macroeconomic Indicators on Donations

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
  - GDP growth, inflation rates, and unemployment rates from **World Bank, OECD, FRED Economic Database, and Eurostat**.

- **Donation Data:**  
  - Historical donation statistics sourced from **nonprofit annual reports, World Bank philanthropy reports, OECD databases, FRED records, Charity Navigator (USA), and Giving Europe reports**.

---

## Data Collection and Preprocessing

- **Collect data**: Retrieve macroeconomic indicator data from official databases and donation records from nonprofit organizations.
- **Clean and preprocess data**: Align timestamps, standardize formats, address missing values, and remove outliers.
- **Merge datasets**: Integrate macroeconomic indicators with donation statistics for correlation and trend analysis.

---

## Analysis Plan

### **Exploratory Data Analysis (EDA)**
- Examine donation trends in the **United States and Europe** during different economic conditions.
- Visualize relationships between macroeconomic indicators and donations using scatter plots, line charts, and correlation heatmaps.

### **Statistical Analysis**
- Conduct correlation analysis to measure relationships between economic factors and donations.
- Apply **linear regression models** to quantify the impact of macroeconomic indicators on donation amounts.
- Perform hypothesis testing to validate statistical significance.

### **Predictive Modeling**
- Develop **predictive models** (e.g., linear regression, random forest regression) to forecast donation behaviors based on economic trends.

---

## Tools and Technologies

- **Python** for data analysis and visualization (Pandas, NumPy, Matplotlib, Seaborn).
- **Statistical libraries** (Scikit-learn, SciPy) for hypothesis testing and regression analysis.

---

## Expected Challenges

- **Data availability**: Donation records may vary across regions and organizations, requiring careful dataset selection.
- **Standardization issues**: Different organizations and countries report donations using different formats.
- **Distinguishing correlation from causation**: Additional external factors could influence donation trends.

---

## Expected Findings

- Identify how different macroeconomic indicators correlate with donation levels in the **United States and Europe**.
- Determine whether **economic downturns lead to lower charitable contributions** or whether donors increase giving during crises.
- Provide data-driven recommendations for nonprofits in the **education and disaster relief sectors** on how to **adapt to economic fluctuations**.

---

## Limitations

- Analysis is based on publicly available data, which may not capture private donation trends.
- Different countries and organizations follow **varying reporting standards**, affecting data consistency.
- External influences, such as government policies and tax incentives, may also impact donation behaviors.

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
