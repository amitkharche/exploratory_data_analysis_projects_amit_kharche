
---

# 🍷 Wine Quality Prediction – Exploratory Data Analysis (EDA)

This project investigates the physicochemical properties of red and white wines to understand their influence on **sensory quality ratings**. Through detailed **Exploratory Data Analysis (EDA)**, the study identifies key chemical factors that differentiate **low**, **average**, and **high-quality wines**, providing insights useful for **winemakers**, **data scientists**, and **product developers** aiming to enhance wine quality.

---

## 📊 Dataset Overview

* **Source:** UCI Machine Learning Repository (Portuguese "Vinho Verde" wine dataset)

* **Instances:** 6,497

* **Target Variable:** `quality` (Integer score from 0 to 10)

* **Features Include:**

  * **Acidity Attributes:** Fixed Acidity, Volatile Acidity, Citric Acid
  * **Chemical Properties:** Residual Sugar, Chlorides, pH, Sulphates, Density
  * **Preservatives:** Free Sulfur Dioxide, Total Sulfur Dioxide
  * **Alcohol Content**

> **Note:** No missing values were found. Duplicate rows were removed during preprocessing.

---

## 📌 Project Objectives

* Load, clean, and prepare the dataset for analysis
* Perform **univariate**, **bivariate**, and **multivariate** exploration of features
* Identify how each chemical property influences **wine quality ratings**
* Understand correlations and outliers affecting the target variable
* Extract **business-relevant insights** for winemaking improvements

---

## 🔧 Tools & Libraries

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**, **Plotly**
* **scikit-learn** (for feature importance via Random Forest)
* **Jupyter Notebook**

---

## 📈 Key Analyses Performed

* **Countplot:** Distribution of wine quality scores
* **Histogram & KDE:** Alcohol content and volatility by quality
* **Boxplots & Violin plots:** Influence of acidity, sulphates, alcohol
* **Heatmap:** Correlation matrix of all numerical features
* **Scatter and Bubble plots:** Bivariate relationships like sugar vs. density
* **Pairplot:** High-quality wine feature clusters
* **Feature Importance Plot:** Random Forest-based ranking of chemical variables

---

## 📌 Insights

* **Alcohol** shows the **strongest positive correlation** with wine quality.
* **Volatile acidity** negatively impacts quality, with higher values in lower-rated wines.
* **High-quality wines (7–9)** cluster around **higher alcohol** and **lower volatile acidity**.
* **Sulphates** and **citric acid** moderately support quality when present in balance.
* **pH** and **residual sugar** have limited direct influence on wine quality.
* **Density** increases with residual sugar but is not a strong quality determinant.

---

## 💡 Actionable Recommendations

* 🍷 **Target alcohol levels** between **12–13%** to improve overall wine ratings.
* 🚫 Reduce **volatile acidity** to maintain a clean, non-vinegary profile.
* ⚖️ Maintain **moderate sulphate levels** for antimicrobial benefits without overpowering taste.
* 📉 Avoid excessive **residual sugar**, especially in dry wines.
* 🧪 Use **balanced acidity** (fixed + citric) to support flavor complexity.
* 🤖 Incorporate **feature-based predictive models** to classify wine quality early in production.

---

## 🧪 How to Run the Project

1. **Clone the repository:**

```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Wine_Quality_Data_amit_kharche
```

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

5. **Open the notebook:**

```
EDA_Wine_Quality_Data_amit_kharche.ipynb
```

and run all cells to explore the full analysis and visual outputs.

---

## 📜 License

This project is intended for **educational and research purposes**. Redistribution or commercial use of the dataset may be subject to UCI licensing terms.

---

## 🤝 Acknowledgements

* Dataset courtesy of the **UCI Machine Learning Repository**
* EDA structure and visual inspiration adapted from **real-world wine analytics**
* Special thanks to the data science community for open-source inspiration

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If you found this project helpful, feel free to ⭐ the repo and share your thoughts!

---
