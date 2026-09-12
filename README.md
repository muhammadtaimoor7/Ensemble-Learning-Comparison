# Ensemble Learning Comparison

Compare 3 ensemble learning techniques on Iris flower classification.

## Techniques

1. **Bagging (Bootstrap Aggregating)**
   - Random Forest: 97.78%
   - Trains multiple trees in parallel, combines votes

2. **Boosting (Sequential Learning)**
   - AdaBoost: [score]%
   - Gradient Boosting: [score]%
   - XGBoost: [score]%
   - Sequential learning, each model corrects previous

3. **Stacking (Meta-learner)**
   - Accuracy: [score]%
   - Combines multiple models with meta-learner

## Results
Winner: [Best model] with highest accuracy

## Dataset
150 iris flowers, 4 features, 3 classes (setosa, versicolor, virginica)

## Tech Stack
Python • scikit-learn • XGBoost • pandas • matplotlib

## Key Insight
Stacking combines strengths of all models. Trade-off: complexity vs accuracy.
