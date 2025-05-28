
# 🚗 Automobile CO₂ Emissions – Exploratory Data Analysis (EDA)

This project explores a comprehensive dataset on vehicle specifications and fuel performance, analyzing the factors that influence fuel consumption and CO₂ emissions. Using extensive EDA techniques, the analysis identifies how engine characteristics, fuel type, transmission, and vehicle class impact emission efficiency across various automobile models.

---

## 📊 Dataset Overview

- **Source:** Natural Resources Canada
- **Instances:** ~1067 vehicles
- **Target Variable:** `co2emissions` (in grams per kilometer)
- **Features Include:**
  - **Vehicle Specs:** Engine size, cylinders, transmission
  - **Fuel Attributes:** Fuel type, fuel consumption in city, highway, combined (L/100 km and MPG)
  - **Classifications:** Make, model, vehicle class
  - **Emissions:** CO₂ emissions, fuel efficiency (MPG)

> **Note:** Dataset is clean with no missing values; transformations were performed for transmission type and fuel categories.

---

## 📌 Project Objectives

- Explore and preprocess vehicle emissions data
- Conduct univariate, bivariate, and multivariate analysis
- Examine the influence of engine features and fuel type on CO₂ output
- Compare emission levels by transmission, vehicle class, and manufacturer
- Generate actionable insights to support greener transportation choices

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly Express for interactive visualizations
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Histograms, boxplots, and KDE plots for CO₂ and MPG distribution
- Violin plots and scatter plots for emission behavior across variables
- Correlation matrix of numerical features
- Fuel consumption comparison between city and highway driving
- Analysis of top eco-friendly brands and most efficient models
- Emission trends by fuel type, transmission, engine size, and vehicle class

---

## 📌 Insights

- **Diesel vehicles** tend to emit **less CO₂** on average compared to gasoline and ethanol-based vehicles.
- **Engine size**, **cylinders**, and **fuel consumption** are **strongly correlated** with higher CO₂ emissions.
- **Manual transmissions** and **smaller vehicles** like compacts and subcompacts are generally more efficient.
- **Passenger vans**, **cargo vans**, and **pickup trucks** are the **highest emitters**.
- **Hybrid models** from **Toyota, Honda, and Lexus** dominate in fuel efficiency and lower emissions.

---

## 💡 Actionable Recommendations

- 🚙 Promote **compact and hybrid models** for sustainability and cost savings.
- 🛠 Encourage **manual transmission adoption** in urban vehicles for better efficiency.
- 🛑 Regulate **high-emission vehicle classes** through stricter emission caps or incentives for electrification.
- 📉 Focus on **fuel optimization** in models with engine sizes over 5L to reduce emissions.
- 🏷 Highlight and support **eco-friendly manufacturers** in consumer awareness campaigns.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
    cd exploratory_data_analysis_projects_amit_kharche/EDA_Automobile_CO2_Emissions_amit_kharche
    ```

2. **(Optional) Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate          # On Windows: venv\Scripts\activate
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
    EDA_Automobile_CO2_Emissions_amit_kharche.ipynb
    ```
    and run the cells to reproduce the complete analysis and insights.

---

## 📜 License

This project is shared for **educational and analytical purposes only**. Usage of the dataset must comply with the source licensing by Natural Resources Canada.

---

## 🤝 Acknowledgements

- Dataset sourced from **Natural Resources Canada** via open data portal
- EDA framework and visual storytelling inspired by **real-world automotive sustainability challenges**

---

## ✨ Connect with Me

- [LinkedIn](https://www.linkedin.com/in/amit-kharche)
- [Medium](https://medium.com/@amitkharche14)
- [GitHub](https://github.com/amitkharche)

If you found this project valuable, please ⭐ the repository and share your thoughts!
