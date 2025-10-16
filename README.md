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

<p align="center"> <img src="https://github.com/Alamgir-JUST/Breast-Cancer-Detection-with-Logistic-Regression/blob/a128624d0fccba6d62a05e77fdfd309ed1dd5864/CM.png"/> </p>

The confusion matrix above shows strong predictive power, with only 3 total misclassifications (1 false positive and 2 false negatives) out of the test samples.

🧠 Interpretation

High recall (0.95) → The model successfully identifies most malignant tumors.

High precision (0.97) → Very few benign cases are wrongly flagged as malignant.

ROC-AUC of 0.997 → Excellent separability between malignant and benign classes.

🔍 ROC Curve

<p align="center"> <img src="https://github.com/Alamgir-JUST/Breast-Cancer-Detection-with-Logistic-Regression/blob/b373ed356771083850840767b43c6c0c88e7d8e7/ROC%20Curve.png"/> </p>


🔍 Cost Function Convergence Over Iterations

<p align="center"> <img src="https://github.com/Alamgir-JUST/Breast-Cancer-Detection-with-Logistic-Regression/blob/c6fb738ca39f9cb65caff09d71d568433ec93772/Convergence.png"/> </p>

🔍 LIME (Local Interpretable Model-Agnostic Explanations)

<p align="center"> <img src="https://github.com/Alamgir-JUST/Breast-Cancer-Detection-with-Logistic-Regression/blob/16d82ae4d7db34b8bfdc814dbd1cab1396af9bc9/LIME.png"/> </p>


🔍 Explain a single instance with SHAP

<p align="center"> <img src="https://github.com/Alamgir-JUST/Breast-Cancer-Detection-with-Logistic-Regression/blob/16d82ae4d7db34b8bfdc814dbd1cab1396af9bc9/Single%20Instance.png"/> </p>


These results demonstrate that a well-regularized Logistic Regression model can perform extremely well on structured biomedical data when paired with proper preprocessing and scaling.


Thank you very much, 
Md. Alamgir Hossain
MSc in ICT, IICT, BUET; BSc in CSE, JUST. 
Director, Skill Morph Research Lab., Skill Morph, Dhaka, Bangladesh
Mail: alamgir.cse14.just@gmail.com
