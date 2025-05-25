````markdown
# 🍔 McDonald's Customer Behavior – Exploratory Data Analysis (EDA)

This project dives into customer behavior and service perception using a McDonald’s feedback dataset. By applying robust EDA techniques, the analysis uncovers patterns in customer satisfaction, meal preferences, service expectations, and store-level feedback to provide actionable insights for improving the fast-food customer experience.

---

## 📊 Dataset Overview

- **Source:** McDonald's Feedback Survey Dataset (publicly available/simulated)
- **Instances:** 38,682
- **Target Variable:** `Rating` (1 to 5)
- **Features Include:**
  - **Demographics:** Age, Gender, Income Group
  - **Visit Info:** Day of Visit, Time of Visit, Purpose of Visit
  - **Menu Feedback:** Food Quality, Taste, Cleanliness, Service Time, Price
  - **Experience Ratings:** Staff Courtesy, Seating Comfort, Ambience, Hygiene
  - **Satisfaction Drivers:** Return Intent, Recommendation Likelihood

> **Note:** Missing values were handled via appropriate imputation methods during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess raw customer feedback data
- Conduct univariate, bivariate, and multivariate analysis
- Identify factors contributing to high vs. low satisfaction ratings
- Compare service attributes across demographic groups and visit patterns
- Provide actionable recommendations to improve customer retention and satisfaction

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive data visualization
- ydata-profiling for auto-EDA
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Count plots for age groups, visit timing, and income categories
- KDE and pie charts for rating distribution across customer segments
- Box plots and bar plots for comparing food quality, taste, service speed, and pricing
- Heatmaps to identify correlations between experience variables
- Grouped bar plots and point plots to explore return/recommend intention by visit purpose and demographic factors

---

## 📌 Insights

- **Younger customers** (18–30) visit more frequently but give **lower ratings** compared to older groups.
- **Service Time** and **Taste** are the strongest drivers of overall satisfaction.
- **Higher income groups** tend to rate **ambience and staff courtesy** more critically.
- **Evening visitors** are more satisfied than those visiting during lunch hours.
- **Recommendation likelihood** is closely tied to **cleanliness and food quality**.

---

## 💡 Actionable Recommendations

- 🕑 Reduce **waiting time** by optimizing kitchen and counter operations.
- 🍟 Innovate menu to improve **taste profiles**, especially for younger demographics.
- 🧹 Maintain high standards in **cleanliness and ambience**, especially during peak hours.
- 🗣️ Train staff to enhance **courtesy and interpersonal engagement**.
- 📱 Gather **digital feedback** from return customers for ongoing service improvements.
- 🎯 Create targeted campaigns for **different income groups and visit times** to personalize experience.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_McDonalds_Data_amit_kharche
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
EDA_McDonalds_Data_Analysis_amit_kharche.ipynb
```

and run all cells to reproduce the analysis, visualizations, and insights.

---

## 📜 License

This project is shared for **educational and analytical purposes**. Redistribution or commercial use of the dataset may be subject to external licensing constraints.

---

## 🤝 Acknowledgements

* Dataset adapted from publicly available survey responses
* Visual framework and insights inspired by fast food retail and customer analytics practices

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If you found this project insightful, please ⭐ the repository and feel free to connect and share your thoughts!

```
