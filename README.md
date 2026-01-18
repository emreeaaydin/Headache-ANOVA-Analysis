# Headache-ANOVA-Analysis
This project statistically examines the effect of different treatment methods on headache pain and their interaction with patients' gender and risk groups.

Project Summary
In this study, a Three-Way ANOVA analysis was performed using the headache dataset from R's famous datarium library. The analysis process was carried out using Python (Pandas, Seaborn, Statsmodels) libraries.

Variables:
Dependent Variable: Pain Score

Independent Variables: Gender, Risk Level, Treatment Type

Analysis Steps
1. Descriptive Statistics: Examination of the mean and standard deviation values of the groups.

2. Assumption Checks: * Outlier control (Boxplot & IQR).

    -Normality Test (Shapiro-Wilk & Q-Q Plot).

    -Homogeneity of Variance (Levene's Test).

3. 3-Way ANOVA: Calculation of main effects and triple interaction (Gender×Risk×Treatment).

4. Post-hoc Analyses: Resolution of significant interactions using "Simple Simple Main Effects" and "Tukey HSD" tests.

Key Findings
The Triple Interaction is Significant: p=0.0013. This proves that the effect of the treatment varies according to gender and risk level.

Critical Difference: Treatment X causes the highest pain scores in high-risk men, while Treatment Y yields the most effective results in low-risk women.
