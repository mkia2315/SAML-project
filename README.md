Suspicious Anti-Money Laundering (SAML) Detection Pipeline

Project Overview
Financial systems generate vast amounts of transaction data where money laundering anomalies are rare but highly damaging. This project develops and evaluates an end-to-end Machine Learning pipeline designed to identify suspicious banking activities, optimize detection rates, and minimize operational false positives.

Models Implemented
The repository contains a progressive exploration of model architectures, structured sequentially within the notebooks directory:

1. SAML\_Model01\_LogReg.ipynb : Baseline evaluation using  Logistic Regression  to establish initial benchmarking metrics.
2. SAML\_Model02\_03\_RFC\_XGBoost.ipynb : Transitioned to ensemble tree-based architectures using  Random Forest Classifier (RFC)  and  XGBoost  to effectively capture non-linear transaction features.
3. SAML\_Model04\_SVM.ipynb : Evaluated a  Support Vector Machine (SVM)  to determine high-dimensional classification boundaries for anomaly detection.
4. SAML\_Model05\_Ensemble.ipynb : Final production framework combining the strengths of the top-performing base models into an  Ensemble method  to maximize overall robustness and predictive consistency.

Key Methodology Highlights
Handling Class Imbalance:  Applied technique variations downsampling to address the extreme scarcity of suspicious transactions in financial datasets.
Evaluation Criteria:  Prioritized  Recall  and  F1-Score  over standard accuracy, ensuring that critical suspicious activities are not missed (minimizing false negatives) while maintaining practical operational limits on false alarms.











\## Setup and Installation



To run the notebooks in this project, you need to install the required Python libraries. 



1\. Clone or download this repository to your machine.

2\. Open your terminal inside the project folder.

3\. Run the following command to automatically install all dependencies:



```bash

pip install -r requirements.txt

```



