# Explainable Loan Model – HMDA 2022

A machine learning project that analyzes fairness in loan approvals and improves model transparency using SHAP and XGBoost on the HMDA 2022 dataset. This project leverages Explainable AI (XAI) techniques to detect and interpret bias related to race, gender, and income in real-world mortgage data, offering both insights and actionable transparency for ethical AI applications in finance.

---

## 📌 Project Goals
- Detect potential demographic bias in loan approval decisions
- Improve model interpretability using SHAP (SHapley Additive exPlanations)
- Compare model performance across Logistic Regression, Random Forest, and XGBoost
- Apply SMOTE to address class imbalance
- Present findings clearly for both technical and non-technical audiences

---

## 🧠 Key Features
- HMDA 2022 NJ data preprocessing, cleaning, and feature selection
- Fairness analysis by race, income, and gender
- Multiple model evaluations with precision/recall focus on non-approvals
- SHAP-based explainability visualizations
- Bar plots and chi-square tests to reveal approval disparities

---

## 🧪 Technologies & Tools
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- SHAP for model explainability
- imbalanced-learn (SMOTE)
- Jupyter Notebook, Matplotlib

---

## 📊 Results Summary
- **Race & Income** showed significant disparities in loan approval rates
- **Gender** had a statistically significant but smaller effect
- **XGBoost + SHAP** delivered the best model performance and interpretability
- Class imbalance remains a key challenge in predicting denials

---

## 📁 Files in This Repository
- `Project.ipynb` – Main notebook with all data preprocessing, modeling, and SHAP analysis
- `/docs/AI Project Report.pdf` – Full project report with references and results
- `/presentation/AI Project Presentation.pdf` – Final presentation slides

---

## 👩‍💻 Project Team
This project was completed as a **two-person final project** at Rutgers University.  
I contributed to data preprocessing, modeling, fairness analysis, and presentation development.  
This repository reflects our collaborative work and is shared for educational and portfolio purposes with respect to both contributors.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact
Feel free to explore the notebook and materials.  
Connect with me on [LinkedIn](https://www.linkedin.com/in/scarlett-medina-)  
Open to opportunities in ethical AI, data science, and software development.


