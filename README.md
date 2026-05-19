A/B Testing at World Quant University
=====================================

Statistical hypothesis testing and experimental design for applicant engagement strategies in financial applications.

Overview
--------
This project involved designing and analyzing an A/B experiment to test the effectiveness of different engagement strategies for university applicants. The analysis included power calculations to determine required sample sizes, chi-square statistical testing for significance, and business metric visualization.

Key Techniques
--------------

**Power Analysis**
- Calculated sample size requirements using chi-square distribution
- Determined statistical power needed to detect meaningful differences
- Balanced Type I and Type II error rates for business decision-making

**Hypothesis Testing**
- Chi-square test for independence on contingency tables
- Evaluated relationship between treatment groups and outcomes
- Interpreted p-values in business context

**Data Analysis**
- MongoDB integration for experiment data management
- Odds ratio calculations for effect size
- Temporal aggregation and filtering by date ranges
- Geographic visualization of experimental results

Project Structure
-----------------
- `a_by_b_testing_wqu.py`: Main analysis script

Key Learnings
-------------
- Importance of pre-experiment power analysis for resource allocation
- How to translate statistical significance to business impact
- Managing experimental data in NoSQL databases
- Creating visualizations that tell the story of experimental results

Technologies Used
-----------------
- Python, pandas, numpy
- MongoDB for data storage
- Statistical testing via scipy
- Geographic visualization with plotly
