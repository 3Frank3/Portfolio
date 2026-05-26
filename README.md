# Frank Hsu | Data Science, AI & Quant Research Portfolio

Hi, I’m Frank Hsu, a Data Science master’s student at UCLA with hands-on experience in machine learning, NLP/LLM workflows, time-series modeling, large-scale data processing, statistical modeling, and real-world data analytics.

This portfolio highlights selected projects that demonstrate my ability to build end-to-end analytical pipelines, extract predictive signals from complex datasets, evaluate models rigorously, and translate data-driven insights into decision-support applications. While several projects are based on healthcare and clinical datasets, the core skills are highly transferable to quantitative research: feature engineering, noisy data processing, predictive modeling, model validation, calibration, causal reasoning, and systematic evaluation.

## Portfolio Focus

My work is especially aligned with AI-driven quantitative research through the following capabilities:

- Building reproducible data pipelines from raw, noisy, and heterogeneous data sources.
- Extracting structured signals from unstructured text, time-stamped events, and high-dimensional datasets.
- Applying machine learning, NLP, and time-series models to prediction and decision-support problems.
- Evaluating models with metrics beyond accuracy, including ROC-AUC, PR-AUC, Brier Score, calibration, and backtesting-style performance measures.
- Maintaining careful train-test separation to prevent data leakage and improve the reliability of model evaluation.

---

## Featured Projects

| Project | Main Focus | Quant-Relevant Skills |
|---|---|---|
| [AI-Powered Quantitative Trading Signal Research System](#1-ai-powered-quantitative-trading-signal-research-system) | Financial NLP, alpha signals, LSTM strategy backtesting | Python, LLM, BERT, LSTM, sentiment signals, backtesting |
| [Machine Learning on MIMIC-IV Data: ICU Ventilation Duration Analysis](#2-machine-learning-on-mimic-iv-data-icu-ventilation-duration-analysis) | Large-scale real-world data modeling | R, SQL, Linux, feature engineering, model validation |
| [Diabetes Risk Prediction, Fairness Evaluation, and Causal Analysis](#3-diabetes-risk-prediction-fairness-evaluation-and-causal-analysis) | Healthcare ML, fairness, causal inference | Python, XGBoost, Logistic Regression, PSM, model evaluation |
| [Unmasking Parkinson’s: Early Disease Risk Analysis](#4-unmasking-parkinsons-early-disease-risk-analysis) | Clinical risk signals and exploratory analysis | R, SQL, EDA, risk factor analysis, feature exploration |
| [Maternal & Perinatal Risk Modeling for Survival Outcomes](#5-maternal--perinatal-risk-modeling-for-survival-outcomes) | Statistical risk modeling and outcome prediction | SAS, logistic regression, ROC analysis, stratified modeling |

---

## 1. AI-Powered Quantitative Trading Signal Research System

This project explores how AI, NLP, and time-series modeling can be used to extract trading signals from financial text and market data. The project focuses on building a pipeline that transforms unstructured financial information into sentiment-based alpha signals and evaluates their usefulness in a trading strategy context.

### Key Highlights

- Built an end-to-end Python and LLM-assisted analytics pipeline to explore, clean, and analyze earnings calls, tweets, financial news, and market data.
- Fine-tuned BERT to extract sentiment-based alpha signals from unstructured financial text.
- Integrated sentiment signals with market microstructure features and financial indicators for time-series modeling.
- Backtested a Multivariate LSTM-based trading strategy to evaluate predictive signals and strategy performance.
- Achieved a 0.74 Sharpe Ratio and 23.1% annualized return in the backtested strategy evaluation.

### Skills Demonstrated

`Python` · `NLP` · `LLM Workflow` · `BERT` · `LSTM` · `Time-Series Modeling` · `Alpha Signal Research` · `Backtesting` · `Financial Data Analysis`

---

## 2. Machine Learning on MIMIC-IV Data: ICU Ventilation Duration Analysis

This project uses large-scale MIMIC-IV ICU data to classify and predict invasive mechanical ventilation duration. Although the dataset is clinical, the project demonstrates skills that are directly transferable to quantitative research: large-scale data extraction, complex event processing, feature engineering, predictive modeling, and robust model validation.

### Key Highlights

- Built an end-to-end large-scale data pipeline using R, SQL, and Linux to process MIMIC-IV ICU records.
- Integrated demographics, ICU stay records, procedure events, and time-stamped clinical events into modeling-ready datasets.
- Defined a supervised learning target by calculating invasive mechanical ventilation duration from procedure timestamps.
- Engineered structured features from complex real-world event data to support classification modeling.
- Compared Random Forest and Elastic-Net Logistic Regression models using ROC-AUC, PR-AUC, Brier Score, and calibration metrics while maintaining train-test separation to prevent data leakage.
- Achieved approximately ROC-AUC ≈ 0.80 and Brier Score ≈ 0.17.

### Skills Demonstrated

`R` · `SQL` · `Linux` · `Large-Scale Data Processing` · `Feature Engineering` · `Machine Learning` · `Model Calibration` · `Data Leakage Prevention`

---

## 3. Diabetes Risk Prediction, Fairness Evaluation, and Causal Analysis

This project analyzes diabetes risk using the CDC Diabetes Health Indicators dataset. It combines predictive modeling, subgroup fairness evaluation, and causal analysis to understand risk patterns and the association between physical activity and diabetes outcomes.

### Key Highlights

- Built machine learning models to predict diabetes risk using demographic, clinical, behavioral, and self-reported health indicators.
- Compared Logistic Regression, Random Forest, and XGBoost models using ROC-AUC, PR-AUC, recall, precision, F1-score, and Brier Score.
- Conducted subgroup evaluation across fairness-relevant variables such as age, sex, education, and income.
- Applied Propensity Score Matching to estimate the association between physical activity and diabetes after balancing observed confounders.
- Demonstrated the importance of evaluating predictive performance, subgroup disparities, and causal assumptions in real-world data analysis.

### Skills Demonstrated

`Python` · `Machine Learning` · `XGBoost` · `Logistic Regression` · `Random Forest` · `Fairness Evaluation` · `Propensity Score Matching` · `Causal Inference`

---

## 4. Unmasking Parkinson’s: Early Disease Risk Analysis

This project investigates early disease risk signals using Parkinson’s-related clinical data. The analysis focuses on identifying patterns across non-motor symptoms, clinical indicators, and diagnostic groups.

### Key Highlights

- Processed and integrated clinical data to compare healthy, prodromal, and diagnosed populations.
- Explored non-motor symptom indicators such as olfactory function, sleep behavior, autonomic symptoms, and related clinical measures.
- Conducted exploratory data analysis to identify differences across disease-risk groups.
- Built a structured workflow for data cleaning, missing value handling, and clinical feature analysis.
- Strengthened experience in extracting meaningful signals from complex, noisy, and heterogeneous real-world datasets.

### Skills Demonstrated

`R` · `SQL` · `Clinical Data Analysis` · `Exploratory Data Analysis` · `Data Cleaning` · `Feature Exploration` · `Risk Signal Analysis`

---

## 5. Maternal & Perinatal Risk Modeling for Survival Outcomes

This project analyzes maternal and perinatal factors associated with survival outcomes using large-scale U.S. multiple-birth records. The project applies statistical modeling to understand risk patterns across different pregnancy plurality groups.

### Key Highlights

- Analyzed large-scale maternal and perinatal health records to study survival outcomes.
- Cleaned and encoded demographic, maternal health, pregnancy, and delivery-related variables.
- Built logistic regression models stratified by plurality groups, including twins, triplets, and higher-order pregnancies.
- Evaluated model performance using ROC curves, AUC, pseudo-R², Hosmer-Lemeshow tests, odds ratios, and confidence intervals.
- Interpreted key risk and protective factors, including maternal education, smoking, abnormal conditions, and delivery method.

### Skills Demonstrated

`SAS` · `Logistic Regression` · `Statistical Modeling` · `Risk Modeling` · `ROC Analysis` · `Stratified Analysis` · `Model Interpretation`

---

## Technical Skills

### Programming Languages

`Python` · `R` · `SQL` · `SAS`

### Machine Learning & Statistical Modeling

`Logistic Regression` · `Elastic-Net Regression` · `Random Forest` · `XGBoost` · `LSTM` · `BERT` · `Propensity Score Matching` · `Model Calibration` · `ROC-AUC` · `PR-AUC` · `Brier Score`

### Quant & Financial Data Skills

`Alpha Signal Research` · `Financial NLP` · `Sentiment Analysis` · `Time-Series Modeling` · `Backtesting` · `Market Microstructure Features` · `Strategy Evaluation`

### Data Engineering & Analytics

`Data Cleaning` · `Feature Engineering` · `Large-Scale Data Processing` · `Reproducible Pipelines` · `Real-World Data Integration` · `Exploratory Data Analysis`

### Visualization & Reporting

`Jupyter Notebook` · `Quarto` · `ggplot2` · `Matplotlib` · `Seaborn` · `Tableau` · `Power BI` · `HTML Reports`

---

## Why This Portfolio Is Relevant to AI Quant Research

My projects demonstrate the core workflow required in AI-driven quantitative research:

1. Collect and clean noisy real-world data.
2. Convert raw text, time-stamped events, and structured variables into model-ready features.
3. Build predictive models and compare performance across methods.
4. Evaluate models carefully with robust metrics and leakage-aware validation.
5. Translate model outputs into interpretable signals that can support downstream decision-making.

I am particularly interested in applying machine learning, NLP/LLM workflows, and time-series modeling to alpha signal discovery, quantitative strategy validation, and data-driven investment research.

---

## Contact

- GitHub: [3Frank3](https://github.com/3Frank3)
- Email: f20020303@gmail.com