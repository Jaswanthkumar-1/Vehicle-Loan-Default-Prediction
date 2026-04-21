# 🏦 Vehicle Loan Default Prediction
### Banking — Course-End Project 2 | Simplilearn

---

## 🔗 Live Tableau Dashboard
👉 [View Interactive Dashboard](https://public.tableau.com/views/VehicleLoanDefaultAnalysisDashboard/VehicleLoanDefaultAnalysisDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📌 Problem Statement
Financial institutions incur significant losses due to
vehicle loan defaults. This project analyzes 233,154
loan records to identify key default risk factors and
build a predictive model.

---

## 🛠️ Tools & Technologies
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![ScikitLearn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📊 Dataset
| Detail | Value |
|---|---|
| Total Records | 233,154 |
| Total Features | 41 |
| Target Variable | loan_default (0/1) |
| Default Rate | 21.7% |
| Source | Simplilearn LMS |

---

## ✅ Tasks Performed
| # | Task |
|---|---|
| 1 | Preliminary data inspection — structure, missing values, duplicates |
| 2 | Variable renaming — Python identifier standards |
| 3 | Missing value treatment — Employment Type filled with mode |
| 4 | Statistical description of quantitative variables |
| 5 | Target variable distribution analysis |
| 6 | Distribution across Branch, State, Manufacturer, Supplier |
| 7 | Employment type analysis with pie charts |
| 8 | Age distribution vs defaulters/non-defaulters |
| 9 | ID proof type analysis |
| 10 | Credit bureau score distribution analysis |
| 11 | Primary & secondary account details exploration |
| 12 | Sanctioned vs disbursed amount comparison |
| 13 | Enquiries vs default risk analysis |
| 14 | Credit history significance study |
| 15 | Logistic Regression modeling + Confusion Matrix + ROC-AUC |
| 16 | Tableau Dashboard with 6 interactive visualizations |

---

## 📈 Model Performance
| Metric | Value |
|---|---|
| Algorithm | Logistic Regression |
| Train/Test Split | 70% / 30% |
| Accuracy | 79% |
| ROC-AUC Score | 0.618 |
| Precision | 79% |
| F1-Score (Class 0) | 88% |

---

## 🔍 Key Findings
| Finding | Detail |
|---|---|
| 🏆 Highest Risk Group | Customers with No Bureau History |
| 📊 Credit Score Impact | Higher CNS score = Lower default rate |
| 🔍 Inquiries | More inquiries = Higher default probability |
| 💼 Employment | Self-employed default more than Salaried |
| 💰 Loan Amount | Higher loan amounts (180K+) = Higher default |
| 👤 Age | Younger customers (18-30) form majority of defaulters |

---

## 📊 Tableau Dashboard
![Dashboard](tableau_dashboard.png)

### Dashboard contains:
- 📌 Overall Default Rate KPI (21.71%)
- 💼 Employment Type vs Default Rate
- 👤 Age Distribution (Default vs Non-Default)
- 🏦 Credit Bureau Score Analysis
- 🔍 Number of Inquiries vs Default Risk
- 💰 Disbursed Amount vs Default Rate

---

## 📁 Repository Structure
