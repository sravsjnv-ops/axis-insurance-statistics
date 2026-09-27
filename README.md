# Axis Insurance — Applied Statistics & Hypothesis Testing

Statistical analysis of a medical-insurance claims dataset to answer business questions with **formal hypothesis tests**, not just charts.

## Questions tested
1. **Do smokers have higher claims?** — two-sample t-test on charges (smokers vs non-smokers)
2. **Is BMI different between females and males?** — two-sample t-test on BMI by gender
3. **Does smoking depend on region?** — chi-square test of independence
4. Supporting EDA: distributions, outliers, and correlation structure of charges, age, BMI, and dependents

## Method
For each question: state H0/H1 → check test assumptions → run the test → interpret the p-value → translate the result into a business recommendation for the insurer.

## Files
- `axis_insurance_statistics_report.html` — full rendered analysis (open in any browser)

## Tech stack
Python · pandas · scipy.stats · seaborn/matplotlib

*Built as part of the PGP in AI & Machine Learning (Great Learning) — Applied Statistics module.*
