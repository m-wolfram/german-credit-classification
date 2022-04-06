# german-credit-classification
Machine learning models for german credit dataset

The dataset is the following:
https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

The best models scores are(cv folds 3 = ~70%/30% test/train):

Catboost-
cross-validation roc_auc train→ 1.000 ±0.000
cross-validation roc_auc test→ 0.924 ±0.057

Gradient Boosting-
cross-validation roc_auc train→ 0.982 ±0.011
cross-validation roc_auc test→ 0.910 ±0.056

Logistic Regression-
cross-validation roc_auc train→ 0.929 ±0.037
cross-validation roc_auc test→ 0.902 ±0.088
