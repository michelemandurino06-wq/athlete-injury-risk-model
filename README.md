# Probabilistic Analysis of Injury Risk in Professional Athletes 🏃‍♂️📊

This repository contains the files for a statistical analysis project exploring the relationship between an athlete's workload and their risk of injury. 

## 🎯 Project Overview
The objective of this project was to determine how variables such as age, weight, height, training intensity, and recovery time affect the likelihood of injury. The analysis is based on a real dataset of 1,000 athletes.

## 🛠️ Methodology
1. **Exploratory Data Analysis:** Identified the target variable (`Previous_Injuries`) as binary, leading to the selection of a **Logistic Regression** model over a Poisson regression.
2. **Implementation in Excel:** The entire Maximum Likelihood Estimation (MLE) pipeline was built from scratch in Excel. 
   - Variables were standardized (z-scores).
   - The log-likelihood function was maximized using the Excel Solver (GRG Nonlinear method).
3. **Validation:** Results were independently verified using Python (`statsmodels`).

## 📁 Files in this Repository
* `Probabilistic analysis.xlsx`: The complete Excel spreadsheet containing the raw dataset, standardization columns, linear predictor calculations, and the Solver optimization block.

## 💡 Key Takeaway
Building statistical models from scratch provides a deep understanding of the underlying mathematics (linear combinations, likelihood theory, numerical optimization) before relying on automated Python/R libraries.
