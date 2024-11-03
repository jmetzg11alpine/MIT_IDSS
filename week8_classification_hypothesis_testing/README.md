# Important Terms 
- type 1 Error: rejection of null hypothesis when it should not have been rejected. α is the probability of Type 1 Error (significance level)
- type 2 Error: A Hypothesis test fails to reject the null hypothesis that is false. β is the probability of Type 2 error.
- P-value – It is the actual risk level calculated from the data. p-value provides information on the probability of the observations, given that the null hypothesis is correct. A p-value less than 0.05 is considered statistically significant. It indicates strong evidence against the null hypothesis, as there is less than a 5% probability that the null is correct.
- Confidence Level – Indicates how much % confident are we in the decision, usually at a 95% level. This means if we repeat the test multiple times, 95% of the time the results will match the population result.
- Confidence Interval - The most common value for α is 0.05 and typically 95% confidence intervals are constructed. A confidence interval provides an interval, or a range of values, which is expected to cover the true unknown parameter values. This provides richer information in comparison to the point estimates, where we have only a single value, thereby exposing any vulnerability in the single estimate.
- Confidence Interval is calculated as X̅ ± Z * (σ /√𝒏), Where X̅ is the sample mean, Z is the critical test statistic, σ is the population standard deviation, and n is the sample size.


| Decision / Reality | \(H_0\) True | \(H_0\) False |
|:-------------------|:-------------|:--------------|
| Reject \(H_0\)     | Type I Error | Correct       |
| Do not reject \(H_0\) | Correct      | Type II Error |

# Logistic Regression 
- binary classification 

# Support Vector Machines 
- maximize the margin between the line and the margins

# Bagging and Random Forest 
- Ensemble model, multiple models built on a subset of the data.
- Bagging = Bootstrap + Aggregation (Random Forest)


# Performance measurements
- True Positive (TP): The values which belonged to class 1 and were predicted 1.
- False Positive (FP): The values which belonged to class 0 and were predicted 1.
- False Negative (FN): The values which belonged to class 1 and were predicted 0.
- True Negative (TN): The values which belonged to class 0 and were predicted 0.

|                      | Actual Negative | Actual Postive |
|----------------------|-----------------|----------------|
|**Predicted Negative**| True Negative   | False Negative |
|**Predicted Positive**| False Positive  | True Positive  | 

Accuracy = (TN + TP) / (TN + FN + TP + FP)

Recall = TP / (TP + FN), fewer false negatives, disease screening because you don't want to miss someone with a deadly or contagious disease 

Precision = TP / (TP + FP), fewer false positives, spam detection because you don't want to miss real important emails

F1 Score = 2 * (precision * recall) / (precision + recall)

# Decision Tree 
- splits happens where there will be a higher information gain lower entropy 

# Ensemble 
- Bagging = Bootstrap + Aggregation 
- make smaller datasets from sampling with replacement. Build models from that and then take the average of those models from the final prediction. As long as the average error rate of the esembled models is less than 50% then it will perform better than one model trained on all the data. 
- Random Forest is like Bagging but we're also sampling the features for each tree
