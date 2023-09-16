# Mental-Health-Markers-On-Social-Media
Various means to detect mental health issues on social media
## Data Set
Dataset is too large for Github and can be found here:  https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch

## Classification Report Explanation:

The classification report shows the results of a binary classification task with two classes: non-suicide and suicide.

```
                precision    recall  f1-score   support

 non-suicide       0.94      0.86      0.90     23040
     suicide       0.87      0.94      0.91     23375

    accuracy                           0.90     46415
   macro avg       0.91      0.90      0.90     46415
weighted avg       0.91      0.90      0.90     46415
```

## Precision

This metric shows the ratio of correctly predicted positive observations to the total predicted positives. High precision relates to a low false positive rate.

non-suicide: 0.94
suicide: 0.87

## Recall (or Sensitivity)

Recall shows the ratio of correctly predicted positive observations to the all observations in actual class.

non-suicide: 0.86
suicide: 0.95

## F1-Score

The F1-Score is the weighted average of Precision and Recall. It tries to find the balance between precision and recall.

non-suicide: 0.90
suicide: 0.91

## Support

Support is the number of actual occurrences of the class in the specified dataset.

non-suicide: 23169 occurrences
suicide: 23246 occurrences

## Accuracy

Accuracy is the ratio of correctly predicted observation to the total observations. The model's accuracy is 0.90, indicating that it's correct 90% of the time.

## Macro Avg

This provides the average metrics without considering the class imbalance.

Precision, Recall, F1-Score: 0.91
Weighted Avg
This considers the number of true instances for each label (accounting for class imbalance).

Precision, Recall, F1-Score: 0.90
They model seems to be doing well in distinguishing between non-suicide and suicide based on these metrics.
