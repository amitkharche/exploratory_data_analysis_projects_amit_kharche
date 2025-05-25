# 🌫️ Air Quality Exploratory Data Analysis (EDA) – Urban Pollution Monitoring

This project explores a year-long dataset of air quality sensor readings collected in a heavily polluted urban environment in Italy. Using various data preprocessing, visualization, and statistical techniques, the analysis uncovers hidden patterns, relationships, and actionable insights related to atmospheric pollutants, environmental conditions, and sensor performance.

---

## 📊 Dataset Overview

- **Source:** UCI Machine Learning Repository  
- **Time Period:** March 2004 – February 2005  
- **Frequency:** Hourly recordings  
- **Location:** Road-level monitoring in an Italian city  
- **Instances:** 9,358  
- **Target Variables:**
  - `CO(GT)` – Carbon Monoxide (mg/m³)
  - `NMHC(GT)` – Non-Methane Hydrocarbons (µg/m³)
  - `C6H6(GT)` – Benzene (µg/m³)
  - `NOx(GT)` – Nitrogen Oxides (ppb)
  - `NO2(GT)` – Nitrogen Dioxide (µg/m³)

- **Sensor Readings:** 5 metal oxide chemical sensors (`PT08.S1` to `PT08.S5`)
- **Environmental Variables:** Temperature (°C), Relative Humidity (%), Absolute Humidity

> **Note:** Missing values are encoded as `-200` and are handled through filtering or imputation during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess raw data (handling invalid `-200` values)
- Perform univariate, bivariate, and multivariate exploratory data analysis
- Detect seasonal, hourly, and day/night variations in pollutant concentrations
- Analyze correlation between pollutants and environmental conditions
- Identify anomalies, sensor drift, and cross-sensitivity
- Generate actionable insights for policy, public health, and environmental planning

---

## 🔧 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- ydata-profiling / pandas-profiling (for initial data profiling)

---

## 📈 Key Analyses Performed

- Time series trends for CO, NOx, NO2, Benzene, and NMHC
- Violin plots for temperature and pollutant distributions
- Hourly and weekday-based pollutant pattern analysis
- Scatter plots between NOx & NO2, temperature & humidity, sensor responses & RH
- Donut and bar charts showing average pollutant concentrations
- Boxplot comparisons (e.g., CO levels by day/night)
- Correlation heatmap for all numeric features
- Removal and visualization of missing/invalid (`-200`) data

---

## 📌 Insights

- **NOx(GT)** and **NO2(GT)** are the dominant pollutants across the dataset, with strong correlation.
- **CO(GT)** and **C6H6(GT)** concentrations peak during **rush hours**, confirming traffic as a key emission source.
- Environmental variables like **temperature and humidity** have measurable influence on sensor behavior.
- Multiple sensors (e.g., `PT08.S3(NOx)`) exhibit **cross-sensitivity** and may need calibration.
- **Invalid -200 values** notably affect variables such as `NMHC(GT)` and were successfully filtered out to improve reliability.

---

## 💡 Actionable Recommendations

- 🚦 Implement **stricter vehicle emission controls** during high-traffic hours to reduce CO and Benzene levels.
- 🌡️ Regularly **calibrate air quality sensors** to account for environmental influences like RH and temperature.
- 📉 Focus pollution reduction efforts on **NOx and NO2**, which dominate the overall urban emission profile.
- 🧹 Ensure **data logging infrastructure** is monitored to prevent prolonged data gaps and improve sensor uptime.
- 🌦️ Use **seasonal weather trends** (e.g., winter heating patterns) for better pollution forecasting and public alerts.

---

## 🧪 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/air_quality_eda.git
   cd air_quality_eda
   ```

2. **(Optional) Create and activate a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate        # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. Open the main notebook file (`Air_Quality_EDA.ipynb`) and run cells step by step to explore the complete analysis and visualizations.

---

## 📜 License

This project is provided **for academic and research purposes only**.  
**Commercial use of the dataset is strictly prohibited**, as per the UCI repository license.

---

## 🤝 Acknowledgements

- Dataset from the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+Quality)**
- Original research: *De Vito et al., Sensors and Actuators B: Chemical, Vol. 129(2), 2008*

---

## ✨ Connect

If you found this project useful or insightful, consider ⭐️ starring the repository.  
Let’s connect on [LinkedIn](https://www.linkedin.com/) to discuss data science, AI, and real-world analytics solutions.
