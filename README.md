# Autonomous Compliance Sentinel

AI agent that detects ethical and regulatory violations in internal project proposals.

## Features
- Synthetic proposal generation
- SVM risk detection model
- LLM-based policy analysis
- Compliance audit reports

## Architecture Overview

The system processes project proposals from Jira and Confluence and evaluates them through multiple responsible AI layers.

Pipeline:

1. Data ingestion from Jira / Confluence
2. Synthetic proposal generation
3. Text preprocessing and feature engineering
4. Risk detection using rule-based policies and SVM classifier
5. LLM audit for explainability
6. Dashboard reporting and compliance monitoring


## Technologies
Python\\
Scikit-learn
LLM (LLaMA)
Jupyter Notebook
