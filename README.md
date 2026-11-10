# Next-Day Rain Prediction

A supervised learning project to classify whether it will rain the following day using Australian weather observations.

## Dataset

The project uses the Rain in Australia dataset, which contains daily observations from multiple weather stations over roughly ten years:
[Kaggle dataset](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

The target is `RainTomorrow`.

## Workflow covered

- Exploratory data analysis and visualization.
- Missing-value handling.
- Scaling numerical features.
- Encoding categorical features.
- Training logistic regression, decision tree, and random forest models.
- Validation and hyperparameter tuning.

## Evaluation

The README should report the selected model, class balance, split strategy, and the measured evaluation metric from the notebook. Avoid presenting training-set performance as a test result.

## Data sources

The project references Australian Bureau of Meteorology observations:
- https://www.bom.gov.au/climate/data
- https://www.bom.gov.au/climate/dwo/
