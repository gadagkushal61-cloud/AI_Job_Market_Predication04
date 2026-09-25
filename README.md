
# 🤖AI Job Market Analytics & ML Lab

An end-to-end Machine Learning and Exploratory Data Analysis (EDA) application built to analyze salary distributions, industry trends, and job roles in the AI market. This repository includes both an interactive **Jupyter Notebook** model analysis pipeline and a real-time **Streamlit** dashboard web application.

---

## 📌 Project Overview

- **Data Processing & Standardization**: Parses structured salary ranges (e.g., `$92,860-$109,598`) into minimum, maximum, and average numerical metrics, followed by feature scaling via `StandardScaler`.
- **Exploratory Data Analysis (EDA)**: Dynamic visualizations analyzing compensation across industries, experience levels, and employment types.
- **Machine Learning Experiments**: Implements Linear Regression and Logistic Regression models to predict salary parameters and job metrics.
- **Interactive Streamlit Web App**: Interactive UI allowing users to upload datasets, explore insights, evaluate model metrics, and make real-time predictions.

---

## 🛠️ Project Structure

```text
├── NaviBayes.ipynb      # Data preprocessing, feature engineering & model training notebook
├── app.py               # Interactive Streamlit dashboard and real-time prediction app
├── ai_job_market.csv    # Dataset file (2,000 AI job market postings)
└── README.md            # Project documentation

<img width="1120" height="658" alt="WhatsApp Image 2026-09-23 at 12 00 03 PM" src="https://github.com/user-attachments/assets/28dbe360-8dc2-4cae-b55e-c0651e610d1e" />
<img width="1355" height="632" alt="Screenshot 2026-09-25 114317" src="https://github.com/user-attachments/assets/6bad7d09-a0bc-4a1b-bdb1-6d844a7b8383" />
<img width="1352" height="627" alt="Screenshot 2026-09-25 114336" src="https://github.com/user-attachments/assets/52c5960d-f80f-4ca7-a55e-1f53beda60b6" />
