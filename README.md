# Confidence Intervals Case Study (Titanic Dataset)

## Overview

This project is a simple case study to understand how sampling works and how we can estimate population values using confidence intervals.

Instead of focusing on machine learning, the main goal here is to build a clear understanding of how a sample can represent the entire dataset.

For this, the Titanic dataset is used, and the analysis is done on the Fare column.

---

## Problem Statement

In real-world situations, we usually don’t have access to the full population data.

So the main question is:

Can we use a small sample to estimate the true population value accurately?

This project tries to answer that using statistical methods.

---

## What is done in this project

- Took samples from the Titanic dataset  
- Calculated sample mean and standard deviation  
- Repeated sampling to observe variation  
- Used T-distribution for estimation  
- Calculated confidence intervals (50% and 95%)  
- Compared results with the actual population mean  

---

## Data Understanding

- Dataset used: Titanic dataset  
- Column used: Fare  

The Fare values are not normally distributed.

Reason:
- Most passengers paid lower fares  
- A few passengers paid very high fares  

This creates a right-skewed distribution.

This is important because many statistical methods assume normal distribution, but real-world data often does not follow that.

---

## Approach

1. Load and clean the dataset  
2. Focus on the Fare column  
3. Draw random samples from the data  
4. Calculate sample statistics  
5. Apply T-distribution  
6. Compute confidence intervals  

---

## Key Observations

- The true population mean lies within the 95% confidence interval  
- Higher confidence level results in a wider interval  
- Lower confidence level gives a narrower but less reliable range  
- Data variability affects the width of the interval  

---

## Conclusion

This project shows that:

- A sample can be used to estimate population values  
- But there is always some uncertainty  
- Confidence intervals help measure that uncertainty  

The accuracy of estimation depends on:
- Sample size  
- Data variability  
- Confidence level  

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- SciPy  

---

## How to Run

1. Clone the repository  
2. Open the notebook in Jupyter or Kaggle  
3. Run all cells step by step  

---

## Final Note

This project is mainly focused on building intuition behind sampling and confidence intervals in a simple and clear way.
