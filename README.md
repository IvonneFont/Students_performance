# Student Performance in High School Mathematics

## Project Overview

In this project, I analyzed high school student data to investigate whether students without prior academic failures perform better on their final exam scores compared to those who have failed in the past. I used statistical hypothesis testing to assess the difference between the two groups.

## Dataset

The dataset includes variables such as:

- Gender  
- Parental education level  
- Lunch program eligibility  
- Test preparation course completion  
- Number of past class failures  
- Final exam scores (math, reading, writing)

## Problem Statement

The goal was to determine whether having no previous failures is associated with higher final exam marks in mathematics.

## Statistical Approach

- **Null Hypothesis (H₀):** Students without past failures do not achieve higher final marks; any difference is due to random chance.  
- **Alternative Hypothesis (H₁):** Students without past failures achieve higher final marks.  
- **Significance Level:** 5% (α = 0.05)

I performed a **two-sample z-test** to compare the means of the two independent groups (students with vs. without past failures).

## Tools Used

- Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)
- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Hypothesis Testing (z-test for difference in means)

## Results

- The z-test produced a **z-statistic of 7.0156** and a **p-value of 0.0000**.
- Since the p-value was below 0.05, I rejected the null hypothesis.
- **Conclusion:** Students without prior failures tend to achieve higher final exam scores in mathematics.

## Next Steps

Future extensions of this analysis could include:

- Expanding to reading and writing scores
- Controlling for other variables via multivariate analysis (e.g. regression, ANCOVA)
- Exploring whether other factors such as parental education or test preparation courses interact with prior failures
