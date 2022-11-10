# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

0.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.554373 |   nan       |
| auc       | 0.5      |   nan       |
| f1        | 0.39083  |     0.21857 |
| accuracy  | 0.242877 |     0.21857 |
| precision | 0.242877 |     0.21857 |
| recall    | 1        |     0.21857 |
| mcc       | 0        |     0.21857 |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.554373 |   nan       |
| auc       | 0.5      |   nan       |
| f1        | 0.39083  |     0.21857 |
| accuracy  | 0.242877 |     0.21857 |
| precision | 0.242877 |     0.21857 |
| recall    | 1        |     0.21857 |
| mcc       | 0        |     0.21857 |


## Confusion matrix (at threshold=0.21857)
|                     |   Predicted as Medical |   Predicted as Surgical |
|:--------------------|-----------------------:|------------------------:|
| Labeled as Medical  |                      0 |                    3348 |
| Labeled as Surgical |                      0 |                    1074 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
