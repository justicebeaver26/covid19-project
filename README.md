# covid19-project
This is my project on predicting severe COVID-19 cases in unvaccinated patients.

# Predicting Severe COVID-19 Symptoms in Unvaccinated Patients

This project investigates the risk factors and predictors of severe COVID-19 symptoms in unvaccinated patients admitted to **Auckland General Hospital**, and examines the role of **general practitioner (GP) availability** in managing severe cases in West Auckland.

The study applies **Bayesian, resampling, and regression methods** to:
- Analyze weight differences by sex  
- Assess whether weight and age predict illness duration  
- Model severe symptom risk using Logistic Regression, Quantile Regression, and GAMs  
- Evaluate ROC curve limitations  
- Forecast severe case numbers with **Quasi-Poisson and Negative Binomial models** to address overdispersion  

The findings aim to help hospital staff **allocate resources more effectively** during COVID-19 surges.  

---

## Purpose
Between **August–October 2022**, Auckland General Hospital operated at **95% capacity** due to unvaccinated COVID-19 patients.  
The Hospital Board raised concerns about severe symptoms prolonging patient stays and sought predictive models to support hospital planning.

This study addresses two main problems:
1. Predicting the likelihood of severe COVID-19 symptoms  
2. Estimating the expected number of severe cases in **West Auckland (Dec 2021–Apr 2022)** and examining GP availability as a factor  

---

## Data
- **Hospital Data**: 460 unvaccinated COVID-19 patients (Auckland General Hospital, Aug–Oct 2022)  
- **Community Data**: Severe cases and GP availability in West Auckland (Dec 2021–Apr 2022)  

---

## Methods
1. **Statistical Analysis**  
   - Resampling & Bayesian methods → test if females weigh more than males  
   - Regression (Linear & Bayesian) → assess if weight and age predict illness duration  

2. **Main Analysis**  
   - Logistic Regression, Quantile Regression, Generalized Additive Models → predict severe symptoms  
   - Compare models to select the “winner”  

3. **Model Evaluation**  
   - Discuss strengths/limitations of ROC curves  

4. **Forecasting Severe Cases**  
   - Quasi-Poisson & Negative Binomial regression → address overdispersion  
   - Assess impact of GP availability  

---

## Results (Summary)
- Weight and age show predictive value for illness duration  
- Logistic, quantile, and GAM models tested; best-performing model recommended  
- Overdispersion addressed using Quasi-Poisson & Negative Binomial approaches  
- GP availability shown to influence severe case outcomes in West Auckland  

---

## Objectives Recap
- Predict severe symptoms in unvaccinated COVID-19 patients  
- Compare male vs. female weight using Bayesian & resampling approaches  
- Evaluate weight and age as predictors of illness duration  
- Identify best predictive model for severe symptoms  
- Assess ROC curve limitations  
- Forecast expected severe cases and examine GP availability impact  

---

## Tools & Methods
- **Python / R** (Bayesian analysis, regression, resampling)  
- **GLM (Quasi-Poisson, Negative Binomial)**  
- **Logistic Regression, Quantile Regression, GAMs**  
- **ROC Curve Analysis**  

---

