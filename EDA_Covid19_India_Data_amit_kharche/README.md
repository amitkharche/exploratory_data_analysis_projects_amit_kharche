
# 🦠 COVID-19 Global Dataset – Exploratory Data Analysis (EDA)

This project explores a large-scale global dataset of COVID-19 statistics including confirmed cases, deaths, recoveries, and active cases across countries and regions. Using robust EDA techniques, it analyzes global trends, highlights regional disparities, and identifies key correlations influencing the pandemic’s spread and severity.

---

## 📊 Dataset Overview

- **Source:** Aggregated global COVID-19 dataset (publicly available)
- **Instances:** 49,068
- **Target Variables:** `Confirmed`, `Deaths`, `Recovered`, `Active`
- **Features Include:**
  - **Geography:** Province/State, Country/Region, Latitude, Longitude
  - **Date Information:** Daily observations
  - **Epidemiological Metrics:** Confirmed, Deaths, Recovered, Active
  - **WHO Classification:** WHO Region
> **Note:** Missing values (especially in 'Province/State') were handled during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess the global COVID-19 dataset
- Analyze temporal trends of cases and deaths
- Identify top 10 affected countries and WHO regions
- Visualize correlations and distributions among key metrics
- Derive actionable public health insights and reporting

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive charts
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Line plots to show trends over time for confirmed, deaths, active cases
- Area plots for cumulative global impact
- Bar and pie charts for top 10 countries by cases, deaths, and recoveries
- Violin and strip plots by WHO Region to analyze spread and severity
- Heatmaps and scatter plots for correlation between cases and deaths
- Geospatial bubble map showing case distribution across countries

---

## 📌 Insights

- The **United States**, **Brazil**, and **India** consistently top the charts in confirmed, active cases, and deaths.
- The **Americas** and **Europe** are the most severely affected WHO regions.
- The distribution of cases is **highly skewed**, with a small group of countries reporting extremely high volumes.
- **Deaths and confirmed cases are strongly correlated**, but outliers suggest variability in healthcare effectiveness.
- **Recovery patterns vary widely**, with some countries showing strong post-peak responses.

---

## 💡 Actionable Recommendations

- 📦 Provide **targeted international aid** and medical support to countries with high active case loads.
- 📈 Monitor **death-to-case ratios** to detect healthcare system stress and fatality management.
- 🌍 Use **regional strategies** based on WHO zones to align lockdowns, testing, and vaccination programs.
- 🧪 Promote **data transparency** and standardization across nations to ensure accurate monitoring.
- 💉 Prioritize vaccination and public health communication in **high-density impact zones**.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Covid19_India_Data_amit_kharche
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

5. **Open the file:**
```
EDA_COVID-19_Global_Dataset_amit_kharche.ipynb
```
and run all cells to reproduce the analysis and visual outputs.

---

## 📜 License

This project is shared for **educational and analytical purposes**. Redistribution or commercial use of the dataset may be subject to third-party licensing.

---

## 🤝 Acknowledgements

- Dataset adapted for analysis from global COVID-19 sources
- Visual and EDA framework inspired by epidemiological research and global health dashboards

---

## ✨ Connect with Me

- [LinkedIn](https://www.linkedin.com/in/amit-kharche)
- [Medium](https://medium.com/@amitkharche14)
- [GitHub](https://github.com/amitkharche)

If you found this project insightful, please ⭐ the repository and share your thoughts!
