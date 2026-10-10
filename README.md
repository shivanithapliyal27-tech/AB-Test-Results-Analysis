# A/B Test Results Analysis

## Project Overview
This project analyzes an A/B testing experiment to compare the conversion rates of two groups: Control and Treatment. The goal is to determine whether the treatment version performs better than the control version using statistical analysis.

## Project Objectives
- Analyze the A/B testing dataset.
- Calculate conversion rates for both groups.
- Compare control and treatment performance.
- Perform a statistical significance test.
- Visualize conversion rates using Python.
- Provide a data-driven recommendation.

## Dataset
The dataset is sourced from Kaggle.

**Dataset Link:** https://www.kaggle.com/datasets/zhangluyuan/ab-testing

The dataset contains user information, experiment group, landing page, and conversion status.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels

## Project Workflow
1. Imported the required Python libraries.
2. Loaded and inspected the dataset.
3. Checked missing values and duplicate records.
4. Cleaned and validated the data.
5. Calculated conversion rates for the Control and Treatment groups.
6. Created a conversion rate comparison chart.
7. Performed a two-proportion z-test.
8. Evaluated statistical significance using a 5% significance level.
9. Prepared a recommendation based on the results.

## Statistical Analysis
A two-proportion z-test was used to compare the conversion rates of the two groups.

**Significance level:** 0.05

- If p-value < 0.05, the difference is statistically significant.
- If p-value >= 0.05, there is insufficient evidence of a statistically significant difference.

Statistical significance alone does not guarantee that an observed improvement is commercially meaningful.

## Results
The final conversion rates, conversion lift, z-statistic, and p-value are available in the analysis notebook and result files.

## Key Deliverables
- `AB_Test_Results_Analysis.ipynb` — Python analysis notebook
- `conversion_summary.csv` — Conversion summary by group
- `ab_test_results.csv` — Statistical test results
- `conversion_rates.png` — Conversion rate comparison chart

## Conclusion
This project demonstrates how A/B testing can be used to compare two versions of a website or landing page. Conversion rates and statistical testing help evaluate whether an observed difference is supported by evidence.

The final decision should also consider experiment quality, practical business impact, and the reliability of the results.

