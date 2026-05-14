```markdown
# 🚀 Credit Risk Assessment with Fair AI: A Data Scientist's Approach

## 💡 Project Overview

This project showcases a comprehensive solution for **credit risk assessment** for KreditSicher, a German bank, leveraging Machine Learning, with a critical focus on **algorithmic fairness** and **model interpretability**. Faced with increasing loan defaults and regulatory demands to address historical gender bias, this initiative demonstrates my ability to build robust, ethical, and transparent predictive models.

## ✨ Key Achievements & Skills Demonstrated

*   **End-to-End Data Science Lifecycle:** From rigorous **Exploratory Data Analysis (EDA)** and data preprocessing to advanced predictive modeling and model evaluation.

*   **Ethical AI & Fairness:** Implemented and utilized `Fairlearn` to meticulously **detect and quantify gender bias** in model performance, directly addressing regulatory concerns and demonstrating a commitment to responsible AI development. Identified and analyzed disparities in accuracy, precision, and recall between male and female applicants.

*   **Interpretable AI (XAI):** Employed `LIME (Local Interpretable Model-agnostic Explanations)` to generate **individualized, clear explanations** for model predictions. This crucial step ensures transparency, builds trust with stakeholders (analysts, regulators), and facilitates actionable insights into credit decisions.

*   **Robust Predictive Modeling:** Developed and evaluated two powerful classification models:
    *   **Logistic Regression:** Provided interpretable coefficients after strategic One-Hot Encoding with manual base category selection, enabling clear understanding of feature impact.
    *   **Random Forest:** Achieved strong predictive performance (AUC = 0.845, Gini = 0.691), demonstrating proficiency in ensemble methods. Effectively handled class imbalance using `SMOTE`.

*   **Data Quality & Critical Thinking:** Identified and managed `unknown` values and low-utility features (`ForeignWorker`, `Telephone`). Critically analyzed counter-intuitive model coefficients, highlighting potential underlying data issues and showcasing an analytical mindset.

*   **Data Preprocessing Expertise:** Mastered techniques such as `One-Hot Encoding` (with custom base categories for enhanced interpretability), `SMOTE` for class balancing, and intelligent feature selection.

*   **Strong Visualization & Communication:** Utilized `Matplotlib` and `Seaborn` for insightful data visualizations (e.g., correlation matrices, ROC curves, feature importance, bias analysis) and clear communication of complex findings.

## 🛠️ Technologies & Libraries

*   **Python**
*   **Pandas, NumPy** (Data Manipulation)
*   **Matplotlib, Seaborn** (Data Visualization)
*   **Scikit-learn** (Machine Learning: Logistic Regression, Random Forest, `train_test_split`, `metrics`)
*   **Imblearn (SMOTE)** (Handling Imbalanced Data)
*   **Fairlearn** (Algorithmic Fairness Assessment)
*   **LIME** (Model Explainability - XAI)

## 📊 Results & Impact

The project successfully developed models capable of accurately identifying high-risk clients while providing the necessary tools to analyze and mitigate gender bias. The interpretability features ensure compliance with regulatory demands for transparency, allowing KreditSicher to move towards a data-driven, fair, and efficient credit assessment process.

---

## 📁 Project Structure

```text
├── data/
│   └── german_credit_data.csv       # Dataset original de riesgo crediticio
├── .gitignore                       # Archivos y carpetas excluidos de Git (ej. .venv)
├── credit_risk_analysis.ipynb       # Notebook principal con EDA, SMOTE y modelos (RF, LR)
├── README.md                        # Documentación profesional del proyecto
└── requirements.txt                 # Lista de dependencias del entorno virtual

---

**Candidate's Note:** This project demonstrates my comprehensive skills in building responsible and effective ML solutions. I am eager to apply these abilities to drive impact in a dynamic team environment.
