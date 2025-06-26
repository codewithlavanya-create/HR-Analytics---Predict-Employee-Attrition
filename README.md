# 📊 HR Analytics – Predict Employee Attrition

## 📘 Abstract
Employee attrition can significantly impact an organization’s productivity, team morale, and operational costs. This project utilizes **machine learning** —specifically a **Decision Tree Classifier** —to predict employee attrition. It also incorporates **SHAP** for model explainability and **Power BI** for visualization. The goal is to identify key drivers of attrition and suggest data-backed strategies for improving employee retention.

---

## 📌 Introduction
In today's competitive work environment, retaining skilled employees is critical. High turnover rates not only lead to increased recruitment and training costs but also hurt team performance and culture.  
This project aims to:
- Build a predictive model for employee attrition  
- Analyze and understand major factors influencing attrition  
- Develop actionable, data-driven HR strategies  
- Visualize findings through interactive dashboards using Power BI

---

## 🧰 Tools & Technologies Used
- **Python** – for data processing & machine learning  
- **Pandas, NumPy** – for data manipulation  
- **Matplotlib, Seaborn** – for EDA and visualization  
- **Scikit-learn** – Decision Tree Classifier  
- **SHAP** – for explainable AI and feature importance  
- **Power BI** – for dynamic dashboards  
- **Jupyter Notebook** – development environment

---

## 🔄 Workflow & Methodology

### 1️⃣ Data Collection & Preprocessing
- Imported HR dataset containing features such as: `Age`, `Job Role`, `Department`, `Salary`, `Attrition Status`
- Performed data cleaning and handled missing values  
- Encoded categorical variables using Label Encoding and One-Hot Encoding  
- Created derived metrics like **Salary Band** for deeper insights  

---

### 2️⃣ Exploratory Data Analysis (EDA)
Visualized trends in attrition across various dimensions such as:

- 📌 **Departments**  
- 📌 **Job Roles**  
- 📌 **Salary Bands**

**Example Visuals**:
- Attrition by Department  
- Attrition by Salary Band

---

### 3️⃣ Model Training & Evaluation
- Split dataset into training and testing sets  
- Trained a **Decision Tree Classifier**  
- Evaluated using:
  - ✅ Accuracy Score  
  - ✅ Confusion Matrix  
  - ✅ Classification Report

**Example Output**:
- Confusion Matrix Heatmap  
- Accuracy Score

---

### 4️⃣ Model Explainability – SHAP
- Applied **SHAP (SHapley Additive exPlanations)** for model interpretability  
- Identified top contributing features:
  - **Salary Band**
  - **Job Role**
  - **Department**

**Example Output**:
- SHAP Summary Plot

---

### 5️⃣ Power BI Dashboard
Developed a dynamic dashboard to support HR teams with data-driven decisions. Features include:

- Filters: Department, Gender, Age Group, Salary Band  
- Interactive visuals showing attrition rates and high-risk segments  

**Example Output**:
- Power BI Attrition Dashboard Screenshot

---

## ✅ Attrition Prevention Strategies

| Area              | Suggested Action |
|-------------------|------------------|
| 💰 Compensation    | Conduct regular pay reviews and maintain parity across roles |
| 🚀 Career Growth   | Promote internal mobility and provide training programs |
| 🧠 Work Environment| Invest in leadership and culture in high-turnover teams |
| 💬 Engagement      | Encourage recognition, feedback, and inclusion |
| 🧘‍♀️ Work-Life Balance | Promote flexible work arrangements and wellness initiatives |

---

## 🏁 Conclusion
This project demonstrates how HR teams can use machine learning and data analytics to:

- Predict which employees are likely to leave  
- Understand the **"why"** behind attrition using SHAP  
- Leverage Power BI dashboards for real-time monitoring  
- Implement strategies to **reduce turnover and retain talent**

---

## 👩‍💻 Prepared by:
**Lavanya Sharma**  
 

