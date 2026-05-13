# AI-Powered Audit & Fraud Detection System

## Overview
This project presents an AI-driven Audit & Fraud Detection framework designed to identify suspicious financial transactions within a highly imbalanced dataset. The system combines Machine Learning with Explainable AI (XAI) techniques to deliver accurate, transparent, and auditable risk predictions.

The project demonstrates how Artificial Intelligence can support modern Internal Audit, Risk Management, and Fraud Analytics processes.

---

# Objectives
- Detect potentially fraudulent transactions
- Support risk-based auditing
- Improve fraud identification accuracy
- Reduce false negatives in high-risk cases
- Provide transparent AI explanations for auditability

---

# Dataset Information

| Description | Value |
|---|---|
| Total Records | 284,807 |
| Training Samples | 227,845 |
| Testing Samples | 56,962 |
| Features | 30 |
| Problem Type | Binary Classification |
| Dataset Characteristic | Highly Imbalanced |

---

# Machine Learning Performance

| Metric | Score |
|---|---|
| Accuracy | 99.94% |
| ROC-AUC | 97.53% |
| Precision | 83.16% |
| Recall | 80.61% |
| F1-Score | 81.87% |
| PR-AUC | 83.20% |

---

# Confusion Matrix

```python
[[56848    16]
 [   19    79]]
```

## Interpretation
- True Negatives (TN): 56,848
- False Positives (FP): 16
- False Negatives (FN): 19
- True Positives (TP): 79

The model successfully identified most high-risk transactions while maintaining a very low false alarm rate.

---

# Explainable AI (XAI)

## SHAP (SHapley Additive Explanations)
- Global feature importance analysis
- Local prediction interpretation
- SHAP summary visualization
- Feature contribution analysis

## LIME (Local Interpretable Model-Agnostic Explanations)
- Instance-level prediction explanations
- Human-readable local decision analysis
- Local fraud prediction interpretation

## Permutation Feature Importance (PFI)
- Global feature importance evaluation
- Risk driver identification

---

# Technologies Used

```python
Python
Pandas
NumPy
Scikit-learn
XGBoost / Random Forest
SHAP
LIME
Matplotlib
Seaborn
Jupyter Notebook
```

---

# Key Features
- Fraud detection using Machine Learning
- Explainable AI integration
- Highly imbalanced dataset handling
- Risk-based classification
- Transparent audit analytics
- Professional AI governance workflow

---

# Business & Audit Relevance
This project is relevant for:
- Internal Audit
- Fraud Detection
- Governance, Risk & Compliance (GRC)
- Financial Risk Analytics
- AI Governance
- Continuous Auditing
- Regulatory Technology (RegTech)

---

# Project Structure

```bash
├── data/
├── notebooks/
├── models/
├── reports/
├── images/
├── requirements.txt
├── README.md
└── audit_fraud_detection.ipynb
```

---

# Example Use Case
The model identified suspicious and potentially fraudulent transactions by detecting hidden risk patterns and anomalous behavior within highly imbalanced financial data using Explainable AI methodologies.

---

# Future Improvements
- Real-time fraud monitoring dashboard
- Model deployment with Streamlit or Flask
- Deep Learning implementation
- Advanced threshold optimization
- Automated audit reporting
- Enterprise GRC integration

---

# Conclusion
This project demonstrates the practical application of Machine Learning and Explainable AI in Audit Analytics and Fraud Detection. By combining predictive performance with transparency, the framework supports trustworthy AI-driven decision-making for auditors, compliance professionals, and risk managers.
