# Frank Hsu | Data Science & AI Portfolio

Hi, I’m Frank Hsu, a Data Science master’s student at UCLA with hands-on experience in machine learning, healthcare analytics, statistical modeling, causal inference, fairness evaluation, and large-scale data processing.

This portfolio highlights selected projects that demonstrate my ability to build end-to-end analytical pipelines, transform complex real-world data into structured insights, evaluate machine learning models rigorously, and communicate results through reports, notebooks, and visualizations.

## Featured Projects

| Project | Focus Area | Methods & Tools |
|---|---|---|
| [Diabetes Risk Prediction, Fairness Evaluation, and Causal Analysis](./Diabetes) | Healthcare ML, fairness, causal inference | Python, XGBoost, Logistic Regression, Random Forest, Propensity Score Matching |
| [Machine Learning on MIMIC-IV Data: ICU Ventilation Duration Analysis](./MIMIC%20IV) | Large-scale clinical data, predictive modeling | R, SQL, Linux, tidyverse, feature engineering, model evaluation |
| [Unmasking Parkinson's: Early Disease Risk Analysis](./Unmasking%20Parkinson%27s) | Clinical risk analysis, early disease signals | R, SQL, clinical data preprocessing, EDA, statistical analysis |
| [Maternal & Perinatal Risk Modeling for Survival Outcomes](./survival%20outcomes) | Survival outcome prediction, maternal health analytics | SAS, logistic regression, ROC analysis, stratified modeling |

---

## 1. Diabetes Risk Prediction, Fairness Evaluation, and Causal Analysis

This project analyzes diabetes risk using the CDC Diabetes Health Indicators dataset. The project combines predictive modeling, subgroup fairness evaluation, and causal analysis to better understand diabetes risk patterns and the association between physical activity and diabetes outcomes.

### Key Highlights
- Built machine learning models to predict diabetes risk using demographic, clinical, behavioral, and self-reported health indicators.
- Compared Logistic Regression, Random Forest, and XGBoost models using ROC-AUC, PR-AUC, recall, precision, F1-score, and Brier score.
- Conducted subgroup analysis across fairness-relevant variables such as age, sex, education, and income.
- Applied Propensity Score Matching to estimate the association between physical activity and diabetes after balancing observed confounders.
- Demonstrated the importance of evaluating both predictive performance and subgroup disparities in healthcare machine learning.

### Skills Demonstrated
`Python` · `Machine Learning` · `XGBoost` · `Fairness Evaluation` · `Propensity Score Matching` · `Healthcare Analytics`

---

## 2. Machine Learning on MIMIC-IV Data: ICU Ventilation Duration Analysis

This project uses MIMIC-IV ICU data to classify and predict invasive mechanical ventilation duration. The goal is to transform complex time-stamped ICU records into a structured supervised learning problem.

### Key Highlights
- Built an end-to-end clinical data pipeline using R, SQL, and Linux for large-scale ICU data extraction, cleaning, integration, and modeling.
- Defined a clinically meaningful outcome by calculating invasive mechanical ventilation duration from procedure timestamps.
- Engineered structured features from demographics, ICU stay records, procedure events, and time-stamped clinical events.
- Compared machine learning models such as Random Forest and Elastic-Net Logistic Regression.
- Evaluated model performance using ROC-AUC, PR-AUC, Brier Score, and calibration metrics while maintaining train-test separation to prevent data leakage.

### Skills Demonstrated
`R` · `SQL` · `Linux` · `MIMIC-IV` · `Feature Engineering` · `Machine Learning` · `Model Calibration`

---

## 3. Unmasking Parkinson's: Early Disease Risk Analysis

This project investigates early disease risk signals in Parkinson’s-related clinical data. The analysis focuses on identifying patterns across non-motor symptoms, clinical indicators, and diagnostic groups.

### Key Highlights
- Processed and integrated clinical data to compare healthy, prodromal, and diagnosed populations.
- Explored non-motor symptom indicators such as olfactory function, sleep behavior, autonomic symptoms, and related clinical measures.
- Conducted exploratory data analysis to identify meaningful differences across disease-risk groups.
- Built a structured workflow for data cleaning, missing value handling, and clinical feature analysis.
- Strengthened understanding of how real-world clinical variables can support early disease risk investigation.

### Skills Demonstrated
`R` · `SQL` · `Clinical Data Analysis` · `Exploratory Data Analysis` · `Data Cleaning` · `Risk Factor Analysis`

---

## 4. Maternal & Perinatal Risk Modeling for Survival Outcomes

This project analyzes maternal and perinatal factors associated with survival outcomes using large-scale U.S. multiple-birth records. The project applies statistical modeling to understand risk patterns across different pregnancy pluralities.

### Key Highlights
- Analyzed large-scale maternal and perinatal health records to study survival outcomes.
- Cleaned and encoded demographic, maternal health, pregnancy, and delivery-related variables.
- Built logistic regression models stratified by plurality groups, including twins, triplets, and higher-order pregnancies.
- Evaluated model performance using ROC curves, AUC, pseudo-R², Hosmer-Lemeshow tests, odds ratios, and confidence intervals.
- Interpreted key risk and protective factors such as maternal education, smoking, abnormal conditions, and delivery method.

### Skills Demonstrated
`SAS` · `Logistic Regression` · `Healthcare Analytics` · `Risk Modeling` · `ROC Analysis` · `Statistical Inference`

---

## Technical Skills

### Programming Languages
Python · R · SQL · SAS

### Machine Learning & Statistical Modeling
Logistic Regression · Random Forest · XGBoost · Elastic-Net Regression · Propensity Score Matching · ROC/PR-AUC Evaluation · Calibration · Subgroup Analysis

### Data Engineering & Analytics
Data Cleaning · Feature Engineering · Large-Scale Data Processing · Reproducible Pipelines · Clinical Data Integration · Exploratory Data Analysis

### Visualization & Reporting
ggplot2 · Matplotlib · Seaborn · Tableau · Power BI · Quarto · Jupyter Notebook · HTML Reports

---

## Portfolio Focus

My work focuses on applying data science and machine learning to complex real-world datasets, especially in healthcare, clinical research, and decision-support settings. Across these projects, I aim to demonstrate:

- Ability to build complete data pipelines from raw data to modeling-ready datasets.
- Strong understanding of model evaluation beyond accuracy, including calibration, PR-AUC, ROC-AUC, and subgroup performance.
- Experience working with high-dimensional, noisy, and real-world datasets.
- Interest in responsible machine learning, including fairness evaluation and causal reasoning.
- Ability to communicate technical results clearly through notebooks, reports, and visual summaries.

---

## Contact

- GitHub: [3Frank3](https://github.com/3Frank3)
- Email: f20020303@gmail.com