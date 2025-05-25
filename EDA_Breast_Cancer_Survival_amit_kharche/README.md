
---
# 🧬 Breast Cancer Survival Analysis – Exploratory Data Analysis (EDA)

This project investigates a curated dataset of breast cancer patients to understand survival outcomes based on clinical and demographic variables. By applying robust exploratory data analysis techniques, the study uncovers patterns in survival based on age, surgery year, and axillary lymph node involvement. The findings help shed light on key indicators influencing long-term survival among breast cancer patients.

---

## 📊 Dataset Overview

- **Source:** UCI Machine Learning Repository (Modified and cleaned)  
- **Instances:** 306 (reduced to 266 after outlier handling)  
- **Target Variable:** `status` (1 = survived 5 years or more, 2 = died within 5 years)  
- **Features Include:**
  - **Demographics:** Age  
  - **Clinical Metrics:** Year of operation, Positive axillary lymph nodes  
  - **Outcome:** Survival status (binary)  

> **Note:** Duplicates and outliers were removed, and column names were standardized during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess raw survival data  
- Explore univariate, bivariate, and multivariate distributions  
- Analyze the impact of age and lymph node involvement on survival  
- Compare survival trends across different operation years  
- Derive insights for improving predictive healthcare models  

---

## 🔧 Tools & Libraries

- **Python**  
- **Pandas, NumPy** for data handling  
- **Seaborn, Matplotlib** for static visualizations  
- **Plotly** for interactive exploration  
- **Jupyter Notebook** for step-by-step analysis  

---

## 📈 Key Analyses Performed

- Histogram and KDE plots for age and node distributions  
- Count plots for survival status and age groupings  
- Box plots comparing survival against age and lymph node counts  
- Correlation matrix to examine variable relationships  
- Joint plots and scatter plots to observe clinical variable interactions  
- Binned analysis (e.g., age groups vs survival) for categorical insights  

---

## 📌 Insights

- Most patients are in the **40–65 age range**, with survival being higher among **those with zero lymph node involvement**.  
- **Positive axillary node count** has the **strongest correlation** with survival; more nodes indicate poorer outcomes.  
- **Age alone** is not a strong predictor, as survivors and non-survivors span similar age ranges.  
- Survival trends were **highest around 1960–61**, and slightly lower in **1965 and 1969**.  
- The **majority (≈75%) survived** 5+ years, indicating encouraging prognosis in the dataset.  

---

## 💡 Actionable Recommendations

- 🧪 Focus clinical monitoring on **node-positive patients** with more than 2 lymph nodes involved.  
- 🧠 Leverage **node count as a primary predictor** in survival models, rather than relying heavily on age.  
- 🔁 Use **data balancing techniques** (e.g., stratified sampling) to address class imbalance in survival labels.  
- 🩺 Encourage **early detection** efforts to keep node count minimal, improving long-term survival odds.  
- 📊 Track survival trends over time to assess **treatment effectiveness and diagnostic practices** historically.  

---

## 🧪 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
   cd exploratory_data_analysis_projects_amit_kharche/EDA_Breast_Cancer_Survival_amit_kharche
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
   EDA_Breast_Cancer_Survival_Amit_Kharche.ipynb
   ```

   and run the cells to reproduce the analysis and visual outputs.

---

## 📜 License

This project is shared for **educational and analytical purposes**. Please refer to dataset source licensing for redistribution terms.

---

## 🤝 Acknowledgements

* Dataset adapted from UCI ML Repository
* Analysis inspired by clinical research on breast cancer prognosis
* Visuals aligned with EDA best practices for medical data

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If this project was helpful or insightful, please ⭐ the repository and share your feedback!

---
