# Garment Worker Productivity Analysis

## Project Overview

This project analyzes the **Productivity Prediction of Garment Employees** dataset from the [UCI Machine Learning Repository](https://archive-beta.ics.uci.edu/ml/datasets/productivity+prediction+of+garment+employees). The dataset contains **daily productivity data** for different teams in a garment factory during 2015, with variables such as department, quarter, day, team size, overtime, and incentives.

### Objectives:

* Perform **Exploratory Data Analysis (EDA)** and **Descriptive Statistics**
* Identify **factors influencing productivity**
* Conduct **Hypothesis Testing** (Z-tests, T-tests, Chi-square, ANOVA)
* Provide **actionable recommendations** to improve productivity

## Dataset Details

* **date**: Date of observation
* **quarter**: Week number within the month (1–4)
* **department**: Either `sewing` or `finishing`
* **day**: Day of the week
* **team**: Team ID
* **targeted\_productivity**: Expected productivity target
* **actual\_productivity**: Actual achieved productivity
* Additional factors: `smv`, `wip`, `over_time`, `incentive`, `idle_time`, `idle_men`, `no_of_style_change`, `no_of_workers`

## Technologies Used

* **Python** (Pandas, NumPy, SciPy, Statsmodels, Seaborn, Plotly, Matplotlib)
* **Statistical Methods**: Z-test, T-test, Chi-Square, ANOVA

## Analysis Steps

### 1. Exploratory Data Analysis (EDA)

* Generated summary statistics for numerical variables
* Counted records by department, team, and quarter
* Visualized distributions with histograms, boxplots, and interactive Plotly charts
* Computed correlations and visualized heatmap

### 2. Key Insights from EDA

* **Quarter1** had the highest productivity; **Quarter3/4** had lower averages.
* **Finishing department** outperformed **Sewing department** on average.
* **Overtime** did not show a strong positive correlation with productivity.
* **Incentives** were inconsistently applied and not strongly linked to higher output.

### 3. Hypothesis Testing

* **Z-tests**: Checked whether departments exceed the 0.75 productivity benchmark.
* **T-tests**: Compared productivity & incentives between departments.
* **Chi-Square Test**: Validated manager’s assumption on productivity distribution.
* **ANOVA Tests**: Assessed the impact of quarters, days, and department on productivity.

## Key Results

* Sewing department underperforms compared to finishing.
* Overall productivity is close to but not consistently meeting targets.
* Incentive policies do not effectively drive productivity improvements.
* Overtime contributes minimally to higher productivity.
* Department significantly affects productivity, while day of the week does not.

## Recommendations

1. **Revise incentive policies** to better align with productivity outcomes.
2. **Re-evaluate overtime strategies** to prevent inefficiency.
3. **Focus on improving the sewing department** through targeted training and support.
4. **Enhance planning** during low-performing quarters.
5. **Invest in process optimization** rather than relying on extended working hours.

---

**Conclusion:** By addressing these factors, the company can achieve more consistent productivity and better resource utilization.
