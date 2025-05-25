````markdown
# 👨‍💼 Employee Attrition Analysis – Exploratory Data Analysis (EDA)

This project investigates a simulated dataset focused on **employee attrition**, analyzing key **demographic**, **job-related**, and **satisfaction metrics** to identify patterns behind voluntary exits in a corporate setting. Using detailed EDA techniques, the analysis reveals how various organizational and personal factors contribute to attrition risk.

---

## 📊 Dataset Overview

- **Source:** IBM HR Analytics Employee Attrition & Performance (publicly available)
- **Instances:** 1,470
- **Target Variable:** `Attrition` (Yes / No)
- **Features Include:**
  - **Demographics:** Age, Gender, Marital Status, Education
  - **Job Role:** Department, Job Level, Job Role, Total Working Years
  - **Satisfaction & Engagement:** Job Satisfaction, Work-Life Balance, Environment Satisfaction
  - **Performance & Compensation:** Monthly Income, Job Involvement, Performance Rating, Stock Option Level
  - **Logistics:** Distance From Home, Overtime, Business Travel, Years at Company

> **Note:** Missing values were not present in the dataset. Categorical features were encoded appropriately during preprocessing.

---

## 📌 Project Objectives

- Understand patterns associated with employee attrition
- Perform univariate, bivariate, and multivariate analysis
- Identify high-risk groups based on job role, satisfaction, and travel frequency
- Examine the impact of overtime, income, and work-life balance
- Derive actionable insights for **HR policy improvement** and **employee retention**

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive charts
- ydata-profiling for automated EDA reports
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Count plots for attrition across age groups, gender, department, and marital status
- KDE plots to visualize income, total working years, and satisfaction distributions
- Box plots for numeric comparison across attrition categories
- Correlation heatmap of continuous features for attrition-relevant variables
- Bar plots for categorical feature impact on attrition probability

---

## 📌 Insights

- **Overtime** and **frequent business travel** are strongly correlated with **higher attrition**.
- **Younger employees** and those with **short tenure** are more likely to leave.
- **Sales** and **Human Resources** departments show elevated attrition levels compared to others.
- Employees with **low work-life balance** and **low job satisfaction** are at **higher risk**.
- **Married employees** tend to stay longer, suggesting family stability as a retention factor.

---

## 💡 Actionable Recommendations

- 🕒 Reduce **overtime workload** through better staffing or task distribution.
- 🧭 Provide **career growth opportunities** to employees with < 3 years of experience.
- 🌐 Enhance **remote work or flexible options** for frequent travelers.
- 📈 Improve **employee engagement and recognition programs** in high-attrition departments.
- 👥 Target **at-risk segments** with mentorship, career pathing, and wellness programs.
- 💬 Periodic surveys to measure **work-life balance** and **job satisfaction** for early intervention.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Employee_Attrition_amit_kharche
````

2. **(Optional) Create and activate a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook:**

```bash
jupyter notebook
```

5. **Open the file:**

```
EDA_Employee_Attrition_amit_kharche.ipynb
```

and run all cells to reproduce the analysis and visual outputs.

---

## 📜 License

This project is shared for **educational and analytical purposes only**. Any reuse of the dataset should credit the original source or comply with relevant terms.

---

## 🤝 Acknowledgements

* Dataset sourced from IBM HR Analytics repository
* Visualization structure and EDA approach inspired by best practices in organizational analytics

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

⭐ If you found this project valuable, don’t forget to **star the repo** and share your feedback!

```
