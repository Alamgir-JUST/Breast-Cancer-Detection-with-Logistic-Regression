🧩 Logistic Regression Results on Breast Cancer Dataset

The logistic regression model was trained and evaluated on the Breast Cancer Wisconsin Diagnostic dataset.
After preprocessing, scaling, and an 80-20 train–test split, the model achieved the following performance metrics:

Metric	Score
Accuracy	0.9737
Precision	0.9762
Recall	0.9535
F1-Score	0.9647
ROC-AUC	0.9974
🔍 Confusion Matrix
<p align="center"> <img src="bcbad9a5-b658-42ee-909c-ed8af6413035.png" width="500"/> </p>

The confusion matrix above shows strong predictive power, with only 3 total misclassifications (1 false positive and 2 false negatives) out of the test samples.

🧠 Interpretation

High recall (0.95) → The model successfully identifies most malignant tumors.

High precision (0.97) → Very few benign cases are wrongly flagged as malignant.

ROC-AUC of 0.997 → Excellent separability between malignant and benign classes.

These results demonstrate that a well-regularized Logistic Regression model can perform extremely well on structured biomedical data when paired with proper preprocessing and scaling.
