# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 4
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.3 seconds

### Metric details
|           |         0 |   1 |   2 |   3 |   accuracy |   macro avg |   weighted avg |   logloss |
|:----------|----------:|----:|----:|----:|-----------:|------------:|---------------:|----------:|
| precision |  0.45614  |   0 |   0 |   0 |    0.45614 |    0.114035 |       0.208064 |   1.23411 |
| recall    |  1        |   0 |   0 |   0 |    0.45614 |    0.25     |       0.45614  |   1.23411 |
| f1-score  |  0.626506 |   0 |   0 |   0 |    0.45614 |    0.156627 |       0.285775 |   1.23411 |
| support   | 26        |  10 |  16 |   5 |    0.45614 |   57        |      57        |   1.23411 |


## Confusion matrix
|              |   Predicted as 0 |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|-----------------:|
| Labeled as 0 |               26 |                0 |                0 |                0 |
| Labeled as 1 |               10 |                0 |                0 |                0 |
| Labeled as 2 |               16 |                0 |                0 |                0 |
| Labeled as 3 |                5 |                0 |                0 |                0 |

## Learning curves
![Learning curves](learning_curves.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Precision Recall Curve

![Precision Recall Curve](precision_recall_curve.png)



[<< Go back](../README.md)
