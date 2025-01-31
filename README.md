# Fraud Detection Project

## Overview
Imagine a world where fraudulent transactions go unnoticed, siphoning money from innocent victims and damaging financial institutions. This project dives deep into the realm of fraud detection, leveraging machine learning techniques to uncover hidden patterns in transaction data. By analyzing financial transactions and email communications, we aim to separate legitimate activities from fraudulent ones, ensuring a safer financial ecosystem.

## Dataset
Fraud often hides in plain sight, blending into the vast ocean of legitimate transactions. To combat this, we analyzed multiple datasets:
- **banksim.csv & banksim_adj.csv** – Simulated banking transactions reflecting real-world spending patterns.
- **creditcard_sampledata.csv & creditcard_sampledata_3.csv** – Datasets capturing credit card transactions, some of which are fraudulent.
- **enron_emails_clean.csv** – A collection of email communications from the infamous Enron scandal, providing insight into suspicious interactions.

## Project Structure
- `FinalProject_FraudDetection_TeamDataDetective.ipynb`: This Jupyter notebook is the heart of the project, containing data processing, visualization, and machine learning modeling.
- `datasets/`: A repository of financial transactions and communications data fueling our analysis.

## Methodology
1. **Data Preprocessing**
   - Fraud is often buried beneath missing values and noisy data, so we cleaned and transformed the dataset to extract meaningful insights.
2. **Exploratory Data Analysis (EDA)**
   - Visualizing transaction behaviors to detect anomalies and high-risk activities.
   - Identifying red flags—such as unusual spending patterns—that might indicate fraud.
3. **Feature Engineering**
   - Crafting powerful features that improve our model's ability to distinguish fraudulent from legitimate transactions.
4. **Modeling & Evaluation**
   - Training multiple machine learning models, from Logistic Regression to Random Forest, and selecting the best performer.
   - Evaluating results with accuracy, precision, recall, and F1-score to measure the model’s effectiveness in real-world scenarios.

## Results & Insights
Numbers tell a compelling story, and our findings were no exception:
- **Accuracy:** 99.01% – Our model confidently classifies transactions with high precision.
- **Precision:** 90.91% – When it flags a transaction as fraud, it is highly likely to be correct.
- **Recall:** 99.99% – Almost no fraudulent transactions slip through unnoticed.
- **F1 Score:** 95% – A perfect balance of precision and recall, ensuring minimal false positives and negatives.

These results show promise in real-world fraud detection applications, where minimizing false positives is as important as catching fraudulent transactions. However, no model is perfect—there's always room to refine our approach and stay ahead of ever-evolving fraud tactics.

The fight against financial fraud is an ongoing battle, but with machine learning and data-driven insights, we can make transactions safer, one prediction at a time.
