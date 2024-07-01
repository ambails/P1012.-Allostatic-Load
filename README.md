# P1012.-Allostatic-Load

The goal of this project was to compare physiological markers of stress across various demographic groups.

# 1. Mediator Score Calculation
- Imputed missing data using the Quantile Regression Imputation of Left-Censored (QRILC) technique
- Performed a min-max normalization to calculate the mediator scores

# 2. Allostatic Load Calculation
- Calculated allostatic load (AL) scores for each subject which serves as a measure of stress (combines acute and chronic stress)
- t tests were run to test for statistical difference in acute stres, chronic stress, and AL across race, sex, and smoking status groups
- ANOVA and post hoc t tests were run to test for differences in subjects further stratified within those demographic groups
