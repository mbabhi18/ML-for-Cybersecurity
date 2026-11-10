# Machine-Learning-for-Cyber-security
Machine Learning Cybersecurity Lab experiments


| Exp | Title | Dataset |
|-----|-------|---------|
| 1 | Time series decomposition (seasonal & trend) | network_traffic.csv |
| 2 | Time series forecasting to predict DDoS attacks | network_traffic.csv |
| 3 | Ensemble learning to classify cyber-attacks | Attack_Dataset.csv |
| 4 | Logistic regression for malicious URL detection | phishing_url_dataset.csv |
| 5 | SVM for malicious URL detection | phishing_url_dataset.csv |
| 6 | Abnormal URL patterns using feature engineering | phishing_url_dataset.csv |
| 7 | ML model to solve CAPTCHA challenges | captcha (CAPTCHA Images dataset, Kaggle) |
| 8 | Email spoofing pattern detection | SpamAssasin.csv (Kaggle: Phishing Email Dataset) |
| 9 | Spam classification with Naive Bayes & SVM | SpamAssasin.csv (Kaggle: Phishing Email Dataset) |
| 10 | K-Means for normal vs abnormal network events | KDDTrain+_20Percent.txt (NSL-KDD) |
| 11 | Decision tree for SQL injection detection | Modified_SQL_Dataset.csv (Kaggle: SQL Injection Dataset) |
| 12 | Context-based malicious event detection in WSNs | WSN-DS.csv (Kaggle: WSN-DS) |

Datasets are not included in this repository (except network_traffic.csv) due to size.
Place them in the same folder as the notebooks before running.

## Requirements
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels
