# algorithmic-fairness
Private repo for the algorithmic fairness project

Group 3:
- Sarah Mayer
- Martin Quievre
- Camille Epitalon
- Nathan Aïm 
- Charles Proye

1. We first implement 2 surrogates methods of evalution on the the estimated default probability (PD) provided in the dataset :
- Partial Dependence Plot (PDP)
- Accumulated Local Effects (ALE)

2. Then we estimate your own black-box machine learning model:
- XGBoost ? 
- Random Forest ?

3. We analyze the performance of our own model : 
- RMSE 
- ROC / AUC etc..

4. Global interpretability we use the PDP and ALE method to interpret our own model and compare the different methods

5. Local interpretability : we implement the ICE, LIME and SHAP methods to interpret our own model and compare them.

6. Assess the fairness of your own model with respect to age. Use a statistical test for 
the following three fairness definitions: Statistical Parity, Conditional Statistical Parity 
(groups are given in the dataset), and Equal Odds. Discuss your results


7. Implement a FPDP using a fairness measure. Discuss your results.