
---
# 🧠 Mental Health in Tech – Exploratory Data Analysis (EDA)

This project investigates mental health issues in the technology workplace using a rich survey dataset. The analysis explores how factors like company culture, support systems, demographics, and job roles influence employee mental wellness. Through comprehensive EDA, the project aims to identify high-risk groups, systemic gaps, and opportunities to improve mental health awareness and support at work.

---

## 📊 Dataset Overview

- **Source:** Open survey on mental health in the tech industry (public dataset)
- **Instances:** 1,250+
- **Target Variable:** `treatment` (Whether the respondent has sought treatment for a mental health condition)
- **Features Include:**
  - **Demographics:** Age, Gender, Country, Work Location
  - **Workplace Factors:** Company Size, Remote Work, Tech Role, Benefits
  - **Mental Health Aspects:** Family History, Past Diagnoses, Employer Support
  - **Awareness and Comfort:** Discussing mental health with coworkers and supervisors

> **Note:** Missing values were handled using imputation and filtered during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess raw mental health survey data
- Perform univariate and bivariate visualizations
- Identify trends in treatment-seeking behavior across countries and roles
- Understand the effect of company size, benefits, and remote work on mental health support
- Generate actionable insights for mental health advocacy in the tech sector

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive visualizations
- ydata-profiling for data profiling and summarization
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Distribution plots for age, gender, and country representation
- Count plots for treatment by company size, role, and remote work status
- Cross-tabulation of family history vs. seeking treatment
- Heatmaps and bar charts to explore correlations between workplace support and mental health openness
- KDE and box plots to assess demographic patterns

---

## 📌 Insights

- **Younger employees** (20–30 age group) are more likely to report mental health concerns.
- **Small and medium-sized companies** tend to lack formal mental health benefits.
- Employees with **family history** of mental health issues are significantly more likely to seek treatment.
- A **lack of awareness and comfort** in discussing mental health with supervisors is widespread.
- **Remote workers** exhibit slightly better mental health outcomes, possibly due to flexible work environments.

---

## 💡 Actionable Recommendations

- 🧑‍💼 Promote **manager training** to improve mental health communication and support culture.
- 🏥 Encourage **mental health benefits and resources** in companies of all sizes.
- 🌐 Enhance **remote work options** to support well-being and reduce stress.
- 📢 Launch **awareness campaigns** to normalize mental health conversations at work.
- 📋 Use anonymous surveys to continuously assess **employee wellness** and adapt strategies.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Mental_Health_Data_amit_kharche
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

5. **Open the analysis file:**

```
EDA_Mental_Health_in_Tech_Workspace_Amit_Kharche.ipynb
```

and run the cells to explore the analysis, charts, and insights.

---

## 📜 License

This project is shared for **educational and awareness purposes**. The dataset is from a public domain source; always verify original licensing before commercial use.

---

## 🤝 Acknowledgements

* Dataset by OSMI (Open Sourcing Mental Illness) or similar community surveys
* Inspired by global efforts to de-stigmatize mental health in the tech industry

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If you found this project valuable, please ⭐ the repo and share your feedback!

---
