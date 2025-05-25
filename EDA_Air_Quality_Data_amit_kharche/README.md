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
- Generate actionable insights for public health, policy-making, and environmental planning

---

## 🔧 Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Plotly for interactive visualization  
- ydata-profiling / pandas-profiling for automated EDA  
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Time-series trends for CO, NOx, NO2, Benzene, and NMHC  
- Violin and box plots for distribution and variability  
- Hourly and weekday-based pollutant pattern analysis  
- Sensor vs environment interactions using scatter plots  
- Donut and bar charts showing pollutant dominance  
- Correlation matrix for numerical features  
- Removal and handling of invalid/missing data (`-200`)  
- Day vs Night CO level comparisons  

---

## 📌 Insights

- **NOx(GT)** and **NO2(GT)** dominate the average pollutant concentration and are highly correlated.
- **CO(GT)** and **C6H6(GT)** spike during morning and evening rush hours, indicating traffic impact.
- Environmental variables like **temperature and humidity** influence sensor readings and pollutant dispersion.
- Certain sensors exhibit **cross-sensitivity**, reinforcing the need for calibration.
- **NMHC(GT)** and other features affected by `-200` values were cleaned for reliable analysis.

---

## 💡 Actionable Recommendations

- 🚦 Apply stricter emission control policies during peak traffic hours.
- 🔧 Calibrate sensors for humidity and temperature effects to enhance accuracy.
- 🔁 Enhance data logging mechanisms to avoid missing values and sensor outages.
- 🔍 Focus emission mitigation strategies on **NOx** and **NO2**, the most dominant pollutants.
- 🌦️ Utilize temperature and humidity trends for **seasonal pollution forecasting**.

---

## 🧪 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
   cd exploratory_data_analysis_projects_amit_kharche/EDA_Air_Quality_Data_amit_kharche
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

5. Open the notebook file:  
   **`EDA_Air_Quality_Data_Amit_Kharche.ipynb`**  
   and run the cells step by step to explore the complete analysis and visualizations.

---

## 📜 License

This project is provided **for academic and research purposes only**.  
**Commercial use of the dataset is strictly prohibited**, as per the UCI repository license.

---

## 🤝 Acknowledgements

- Dataset from the **[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+Quality)**
- Original research reference: *De Vito et al., Sensors and Actuators B: Chemical, Vol. 129(2), 2008*

---

## ✨ Connect with Me

- [LinkedIn](https://www.linkedin.com/in/amit-kharche)  
- [Medium](https://medium.com/@amitkharche14)  
- [GitHub](https://github.com/amitkharche)

If you found this project insightful, feel free to ⭐️ the repository and share your thoughts!
