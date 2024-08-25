# Overview 
Machine learning techniques are used to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Findings
Precision: 93.5% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
Accuracy: 94%
Recall: 94.5% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

# Summary
From test data sample of <i>19384</i>, in confusion matrix regression model predicted only 80 cases as False Positive(Predicted as high risk when they were actually low risk). 
And it predicted 67 cases as False Negative, which is around 12%. Precision degrades for high risk cases, and model performs better for low risk cases.
