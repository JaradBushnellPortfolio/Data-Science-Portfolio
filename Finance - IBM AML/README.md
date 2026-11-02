# IBM Anti-Money Laundering (AML) Analytics & Modeling

**Dataset:** [IBM Transactions for Anti-Money Laundering (Kaggle)](https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml/data?select=HI-Small_accounts.csv)

## 00. Data Preparation & Exploratory Analysis
- Data quality assessment and cleaning
- Transaction volume and distribution analysis
- Account-level behavioral analysis
- Transaction velocity and recipient diversity
- Feature engineering and model-ready dataset preparation

## 01. Supervised Learning, Transaction Classification
- Feature inspection and importance analysis
- Baseline classification model
- Logistic regression and class imbalance optimization
- Random forest and hyperparameter tuning
- LightGBM and XGBoost
- Model evaluation and performance comparison

## 02. Unsupervised Learning, Customer Segmentation & Anomaly Detection
- Customer behavioral feature engineering
- K-means clustering: elbow method and silhouette analysis
- Hierarchical clustering
- Principal Component Analysis (PCA)
- Baseline statistical anomaly detection
- Isolation Forest
- Local Outlier Factor (LOF)
- Autoencoder neural network
- Anomaly detection evaluation and model comparison

## 03. Actuarial Concepts & AML Risk Analysis
- Probability: Estimating the likelihood that a transaction is associated with suspicious activity
- Severity / Impact: Using transaction amounts as a proxy for potential financial exposure
- Expected Loss: Combining event probability and estimated impact to illustrate expected exposure
- Risk Appetite: Defining the institution's hypothetical willingness to accept a given level of risk
- Risk Tolerance: Establishing acceptable variation around the institution's risk appetite
- Base Rate: Measuring the overall prevalence of laundering-labeled transactions
- Conditional Probability: Estimating suspicious activity likelihood given observed transaction characteristics
- Uncertainty: Quantifying uncertainty around estimated risk using confidence intervals