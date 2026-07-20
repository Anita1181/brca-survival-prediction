# Breast Cancer Survival Prediction Using ML

A machine learning project exploring survival prediction in breast cancer patients using clinical and molecular data from the METABRIC dataset. This project develops a Random Survival Forest (RSF) 
model to estimate patient risk and predicted survival probabilities from genomic and clinical features. Model performance was evaluated using survival analysis metrics including the concordance index (C-index) 
and integrated Brier score.

## Methods
- Dataset: METABRIC breast cancer cohort (https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric)
- Model: Random Survival Forest
- Features: Clinical and molecular variables
- Evaluation:
  - Concordance Index
  - Integrated Brier Score
  - Predicted survival curves
  - Feature importance analysis

## Results

The final model achieved:
- C-index: 0.716
- Integrated Brier Score: 0.0998

Feature analysis identified survival-associated biological pathways involving apoptosis, cell growth regulation, signaling, and gene regulation.

## Disclaimer
This project is for educational and research purposes only. It is not intended for clinical use, diagnosis, prognosis, or medical decision-making. 
Model predictions have not been externally validated and should not be interpreted as patient-specific medical predictions.
