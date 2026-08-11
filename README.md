# Frank Hsu | Data Science, AI & Quantitative Research Portfolio

This repository is the **complete project catalog** behind my GitHub profile. It documents selected systems, research analyses, and applied data projects across **healthcare, finance, quantitative research, and decision systems**.

For a 30-second overview, visit my [GitHub profile](https://github.com/3Frank3). For project scope, methods, evidence, and source repositories, use this page.

## Portfolio at a Glance

| Area | Representative work | Core capabilities |
| --- | --- | --- |
| Healthcare data science | Diabetes risk, ICU ventilation, Parkinson's screening, perinatal risk | Predictive modeling, calibration, fairness, causal inference, clinical data processing |
| Finance & quantitative research | Stock prediction and AI-powered market signals | Financial NLP, BERT, LSTM, time series, signal evaluation |
| Applied analytics & monitoring | Institutional text analytics, SPC anomaly detection | Data standardization, NLP, process monitoring, stakeholder reporting |
| Statistical learning | UCLA coursework and research analyses | Regression, model selection, validation, interpretation |

## Featured Systems

### 1. Diabetes Risk Prediction, Fairness Evaluation & Causal Analysis

[Repository](https://github.com/3Frank3/Diabetes-Risk-Prediction-Fairness-Evaluation-and-Causal-Analysis-of-Physical-Activity-Using-PSM)

Built an end-to-end analysis of **253,680 CDC health records** spanning supervised learning, subgroup performance evaluation, and propensity score matching.

- Compared logistic regression, random forest, and XGBoost; XGBoost reached **ROC-AUC 0.829**, **PR-AUC 0.428**, and **recall 0.772**
- Evaluated performance across age, sex, education, and income groups
- Improved observed covariate balance to **|SMD| < 0.1** for every checked variable after matching
- Estimated a modest association between physical activity and lower diabetes odds while documenting observational-data limitations

**Stack:** Python · pandas · scikit-learn · XGBoost · statsmodels · causal inference

### 2. Explainable Parkinson's Disease Screening App

[Repository](https://github.com/3Frank3/Explainable-Parkinson-s-Disease-Screening-App-Using-Hand-drawn-Spiral-and-Wave-Images)

Developed an educational application that classifies hand-drawn spiral and wave images and explains model attention with Grad-CAM.

- Implemented baseline CNN and MobileNetV2 training workflows in PyTorch
- Added model evaluation, checkpointing, and Grad-CAM visual explanations
- Built a four-page Streamlit interface covering the dataset, performance, predictions, and responsible-use limitations

**Stack:** Python · PyTorch · CNN · MobileNetV2 · Grad-CAM · Streamlit

### 3. MIMIC-IV ICU Ventilation Duration Analysis

[Repository](https://github.com/3Frank3/Machine-Learning-on-MIMIC-IV-Data-ICU-Ventilation-Duration-Analysis)

Transformed complex, time-stamped ICU data into a reproducible multiclass prediction workflow for invasive mechanical ventilation duration.

- Processed **500,000+ ICU data points** and engineered **30+ clinical variables**
- Compared random forest and elastic-net multinomial logistic regression
- Reached approximately **ROC-AUC 0.80** and **Brier score 0.17**
- Used calibration, class-specific evaluation, and robustness checks alongside discrimination metrics

**Stack:** R · SQL · Linux · tidyverse · random forest · elastic net · ggplot2

## Finance & Quantitative Research

### 4. AI-Powered Stock Market Analysis & Quantitative Signal Research System

[Team repository](https://github.com/scfengv/GDSC-ai-stock) · [Project site](https://scfengv.github.io/GDSC-ai-stock/) · [Supporting research materials](https://github.com/3Frank3/Portfolio/tree/main/Quant%20Trading%20Signal%20Research%20System)

Collaborated in a GDSC AI team to build an end-to-end market research system combining financial text, sentiment signals, technical indicators, and LSTM-based stock prediction. The previously listed “AI-Powered Quantitative Trading Signal Research System” and “Stock Market Analysis & Prediction System” refer to this same project and are consolidated here.

- Contributed earnings-call summarization and BERT fine-tuning
- Helped transform unstructured earnings-call text into structured sentiment features
- Collaborated with teammates integrating news, tweets, earnings calls, VIX, technical indicators, and time-series inputs
- Team-reported project results: **MSE 9.73**, **IRR 12.83%**, and **win rate 62.38%**

**Stack:** Python · BART · Gemini · BERT · PyTorch · TensorFlow · LSTM · web crawling · financial NLP · time series

## Applied Analytics & Monitoring

### 5. NCKU Research Project Text Analytics

[Repository](https://github.com/3Frank3/TextAnalysis_NCKU-RD-Foundation)

Converted inconsistent institutional project records into a reusable analytical dataset and reporting taxonomy.

- Analyzed **4,610 projects from 2014–2024**
- Segmented approximately **38,867 Chinese-language tokens** with CKIP Tagger
- Organized terms into a **10-category** business taxonomy using rules and fuzzy similarity
- Supported reporting and data governance for **10+ stakeholders**

**Stack:** Python · pandas · CKIP Tagger · fuzzy matching · NLP · data visualization

### 6. SPC & Machine-Learning Anomaly Detection

[Repository](https://github.com/3Frank3/spc-anomaly-project)

Built a reproducible monitoring pipeline that combines statistical process control with Isolation Forest anomaly detection.

- Calculates I-MR control limits and common SPC signals
- Compares rule-based process signals with model-based anomaly flags
- Includes modular source code, automated outputs, and tests
- Provides a foundation for operational-risk, quality-control, and sensor-monitoring use cases

**Stack:** Python · statistical process control · Isolation Forest · pytest · Matplotlib

## Research Analyses

### 7. Early Parkinson's Disease Risk Analysis

Analyzed healthy, prodromal, and diagnosed groups to identify patterns across non-motor symptoms and clinical indicators. The work emphasized missing-data handling, risk-factor exploration, interpretable comparisons, and responsible clinical interpretation.

**Stack:** R · SQL · exploratory data analysis · clinical feature analysis

### 8. Maternal & Perinatal Risk Modeling

Modeled survival outcomes in U.S. multiple-birth records using plurality-stratified logistic regression.

- Evaluated twins, triplets, and quadruplets with ROC-AUC values of approximately **0.67**, **0.73**, and **0.79**
- Interpreted odds ratios, confidence intervals, and maternal or delivery-related risk factors
- Used stratification and goodness-of-fit diagnostics to avoid relying on a single aggregate model

**Stack:** SAS · logistic regression · ROC analysis · stratified modeling

### 9. Statistical Learning Coursework

[Repository](https://github.com/3Frank3/BIOSTAT-212B-statistical-Learning)

Supporting UCLA statistical-learning work covering the foundations behind the larger projects in this portfolio. This repository is presented as technical coursework rather than as a standalone production system.

## Evaluation Principles

Across projects, I prioritize:

1. Reproducible data pipelines and explicit cohort or target definitions
2. Train-test separation and leakage-aware feature engineering
3. Metrics matched to the problem, including PR-AUC, calibration, Brier score, and subgroup results
4. Interpretable outputs and clear limitations for high-stakes settings
5. Translation from model results to operational or research decisions

## Technical Toolkit

**Languages:** Python · R · SQL · SAS  
**Machine learning:** scikit-learn · XGBoost · PyTorch · TensorFlow · CNN · LSTM · BERT · elastic net  
**Statistics & evaluation:** causal inference · propensity score matching · ROC-AUC · PR-AUC · calibration · Brier score · subgroup analysis  
**Data & delivery:** pandas · tidyverse · Linux · Jupyter · Quarto · Streamlit · Tableau · Power BI · Git

## Contact

[GitHub Profile](https://github.com/3Frank3) · [LinkedIn](https://www.linkedin.com/in/chih-wei-hsu-4652041b6/) · [Email](mailto:f20020303@gmail.com)

> Research and educational projects only. Healthcare outputs are not clinical advice, and financial outputs are not investment advice.
