
---
# 🍔 McDonald's Menu & Store Analysis – Exploratory Data Analysis (EDA)

This project combines two datasets from McDonald's to analyze **nutritional attributes of menu items** and **performance metrics of stores**. The goal is to uncover patterns in customer offerings and business operations using EDA techniques.

---

## 📊 Dataset Overview

| Dataset | Records | Features | Dataset Size |
|:--:|:--:|:--:|:--:|
| McDonald's Menu Nutrition | 340 | 13 | 38 KB |
| McDonald's Store Locations | 340 | 18 | 83 KB |

---

## 🔍 Feature Description

### 🍟 McDonald's Menu Nutrition Dataset
- **Category:** Item category (e.g., Burgers, Beverages)
- **Item:** Name of the menu item
- **Serve_Size:** Serving size in grams
- **Energy:** Caloric content (kcal)
- **Protein, Total_Fat, Saturated_Fat, Trans_Fat:** Macronutrients (grams)
- **Cholestrol:** Cholesterol (mg)
- **Carbohydrates, Sugar, Dietary_Fibre:** Carbs and related nutrients (g)
- **Sodium:** Sodium content (mg)

### 🏬 McDonald’s Store Location & Performance Dataset
- **Store ID, Store Name:** Identifiers
- **Ownership_Type:** Franchise or company-owned
- **Street_Address, City, State, Country, Postcode**
- **Phone_Number, Timezone**
- **Latitude, Longitude:** Geographic coordinates
- **Revenue, Profits:** Financial performance (in million INR)
- **Gross_Profit_Margin:** Profitability percentage
- **Number_of_Employees, Customers:** Operational metrics
- **Best_Selling_Item:** Top menu item per store

---

## 📌 Project Objectives

- Explore nutrition and menu variety across categories
- Analyze store performance by geography and ownership type
- Identify nutrient-dense vs. calorie-dense items
- Examine customer behavior through store-level KPIs
- Link best-selling items to profit margins and demographics

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

- It is analyzed that the items in menu dataset can be categorized as **nutritious** food and **non-nutritious** food based on different chart diagrams and range values in percentage obtained.

  - So it is beneficial for demonstrating different range values for food nutrients such as **Protein, Sugar, Dietary Fibers, Fats, Carbohydrates, Cholesterol, and Sodium** for their proper consumption from menu items.

  - The US food industry has risen as a high-development and high-benefit area because of its huge potential for esteem expansion, especially inside the food processing industry.

  - However, India is still taking its initial steps and this could be the reason for McDonald's India not being profitable after many years of operations.


---

## 💡 Actionable Recommendations

- In order to **increase** the **outlet metrics** like **Revenue, Profits** in **Indian outlets**, **McDonald's** need to **open new outlets** belonging to the **Company Owned** and **Licensed** ownership types **instead of Joint Ventures**.

  - The **nutritional content** of the food items can be **improved** if **good agricultural practices** are taken up in **India** like use of **Genetically Modified Crops (GM Crops)**, **High-Yield-Variety (HYV) seeds**, etc.

  - **McDonald's India** needs to **introduce more food items** on the menu, which have **higher nutritional content** like US and will eventually help them **increase** their **revenue and profits**.

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

---