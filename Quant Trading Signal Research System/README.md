# AI-Powered Quantitative Trading Signal Research System

A research prototype for transforming unstructured financial text into structured sentiment signals that can support downstream quantitative analysis.

## Research Question

Can financial language from news and related sources be converted into reproducible model features for market-signal research?

## Current Scope

This project folder focuses on the **financial NLP and signal-generation layer**:

1. Prepare and label financial text for supervised learning
2. Fine-tune BERT-based sentiment classifiers
3. Evaluate classification behavior and generate sentiment outputs
4. Save reusable model assets for later inference
5. Structure signals for integration with market, technical, and time-series features

## Repository Contents

| Item | Purpose |
| --- | --- |
| `Sentiment.ipynb` | Sentiment analysis experiments and signal exploration |
| `Finetune.ipynb` | Model fine-tuning workflow |
| `PyTorch BertClassification Model Training.py` | Script-based BERT classification training |
| `NLP_model_for_predicting_news/` | Saved model assets and inference-related files |

## Methods

**Modeling:** BERT-based text classification  
**Frameworks:** Python · PyTorch · Transformers  
**Research skills:** financial NLP · sentiment analysis · feature construction · experiment design

## Next Research Steps

- Add timestamp-aligned market data and explicit point-in-time joins
- Define train, validation, and test periods chronologically
- Compare text signals against price-only and technical-feature baselines
- Add transaction costs, turnover, drawdown, and benchmark comparisons
- Test signal stability across market regimes and securities

## Responsible Use

This repository is an educational research prototype. It does not provide investment advice, and any strategy evaluation should account for look-ahead bias, survivorship bias, transaction costs, and changing market regimes.

[Return to the complete portfolio](https://github.com/3Frank3/Portfolio)
