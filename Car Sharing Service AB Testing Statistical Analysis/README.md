# Designing Cancellation Policy - Statistical Analysis of AB Testing data
## Objective: 
Given AB Testing ride data, design a ride cancellation policy for rider.

## Experiment details:
- 3 experiment groups for different penalty fee price ($5.0, $3.0, $1.0), each with ~180,000 data point
- Duration: 42 days (April - May)
- Location: Los Angeles, U.S.

Note: For privacy reasons, Data was not uploaded and company name is masked.


## Files:
- The Pdf `DS A_B Testing Statistical Experiment Presentation.pdf` is the recommendation presentation dock.
- The Jupyter Notebook `ds A/B Testing & Statistical Experiment code.ipynb` is the analysis code.


## Executive Summary of Recommendation
![image](https://user-images.githubusercontent.com/42402011/202758239-33bf18c0-fee4-4687-a7b2-cf4698a9f72e.png)


## Skills involved
- EDA 
- Data Cleaning for missing data and outliers
- Feature Engineering
- Statistical Experiments
- Data Visualization
- Analysis with Domain Knowledge 


## Statistical Concept
- Sampling Method
- Statistical Tests
    - Parametric tests: 1-way ANOVA, Tukey's post-hoc pairwise test, independent z-test 
    - Non-parametric tests: Kruskal-Wallis H-test, Dunn’s post-hoc pairwise Test
    - p-values


## Packages / Tools
- Pandas
- Numpy
- Scipy
- Statsmodels
- Matplotlib
- Seaborn
