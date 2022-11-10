# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        3 |

## Metric details
|           |      score |     threshold |
|:----------|-----------:|--------------:|
| logloss   | 0.00762922 | nan           |
| auc       | 0.99991    | nan           |
| f1        | 0.995812   |   0.235033    |
| accuracy  | 0.997965   |   0.235033    |
| precision | 1          |   0.998556    |
| recall    | 1          |   1.39117e-07 |
| mcc       | 0.994468   |   0.235033    |


## Metric details with threshold from accuracy metric
|           |      score |   threshold |
|:----------|-----------:|------------:|
| logloss   | 0.00762922 |  nan        |
| auc       | 0.99991    |  nan        |
| f1        | 0.995812   |    0.235033 |
| accuracy  | 0.997965   |    0.235033 |
| precision | 0.995349   |    0.235033 |
| recall    | 0.996276   |    0.235033 |
| mcc       | 0.994468   |    0.235033 |


## Confusion matrix (at threshold=0.235033)
|                     |   Predicted as Medical |   Predicted as Surgical |
|:--------------------|-----------------------:|------------------------:|
| Labeled as Medical  |                   3343 |                       5 |
| Labeled as Surgical |                      4 |                    1070 |

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
