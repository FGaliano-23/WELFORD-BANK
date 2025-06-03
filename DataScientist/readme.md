# DataScientist

This repository brings together the resources developed by the Data Science team at **Welford-Bank**. It includes notebooks, datasets, and a theoretical document outlining the methodological approach we followed.  
You will find practical implementations focused on three key areas in the banking sector: fraud detection, default risk prediction, and customer segmentation.

---

## 🗂️ What's Inside?

```text
DataScientist/
├── Scientific Approach to Data/               # PDF with theoretical framework
│   └── Scientific Approach to Data.pdf
└── Models/                                    # Practical use cases
    ├── Fraud_Detection_in_Banking_Transactions/
    │   ├── data/
    │   └── notebook/
    ├── Loan_default_risk_prediction/
    │   ├── data/
    │   └── notebook/
    └── Segmentation_of_Banking_Customers/
        ├── data/
        └── notebook/
```

Each project folder contains:
- **data/** → one or more ready-to-use CSV files.
- **notebook/** → the corresponding `.ipynb` notebook and a `requirements.txt`.

---

## 🤓 What Is Each Model About?

| Project                    | Purpose                                        | Summary                                                                 |
|---------------------------|------------------------------------------------|-------------------------------------------------------------------------|
| **Fraud Detection**       | Spot unusual transactions before they happen.  | Uses an autoencoder to detect anomalies and a random forest to classify fraud. |
| **Loan Default Risk**     | Predict if a customer will default on a loan.  | Combines logistic regression and a Keras neural network to estimate risk. |
| **Customer Segmentation** | Group customers by behavior.                   | Applies K-Means on RFM metrics to find valuable and active client groups. |

Each notebook includes EDA, preprocessing, model training, evaluation metrics, and visualizations.

---

## 📌 Notebook Summaries

- **Fraud_Detection_in_Banking_Transactions.ipynb**:  
  Focuses on identifying suspicious transactions. It uses an autoencoder to understand “normal” patterns and a random forest to classify transactions. Additional techniques are also briefly explored.

- **loan_default_risk_prediction.ipynb**:  
  Estimates the likelihood of default using two approaches: a logistic regression model for interpretable insights and a Keras-based neural network for more flexible modeling.

- **Segmentation_of_Banking_Customers.ipynb**:  
  Groups banking customers based on RFM (Recency, Frequency, Monetary) analysis using K-Means. Ideal for creating client profiles and marketing strategies.

---
