
# 🌍 COVID-19 Global EDA Project

This project performs **exploratory data analysis (EDA)** on a global COVID-19 dataset to understand trends, regional patterns, and impacts of the pandemic across confirmed cases, deaths, recoveries, and active cases.

---

## 📊 Objective

- To analyze global COVID-19 data using statistical summaries and visualizations.
- To identify top affected countries and WHO regions.
- To uncover actionable insights to support public health response and policy formulation.

---

## 📁 Dataset Description

The dataset includes the following columns:

| Column           | Description                                 |
|------------------|---------------------------------------------|
| Province/State   | Name of the province or state (if any)      |
| Country/Region   | Country or territory name                   |
| Lat              | Latitude of the location                    |
| Long             | Longitude of the location                   |
| Date             | Date of record                              |
| Confirmed        | Total confirmed cases                       |
| Deaths           | Total deaths due to COVID-19                |
| Recovered        | Total recovered cases                       |
| Active           | Total active cases                          |
| WHO Region       | WHO classified regional grouping            |

---

## 📈 Visualizations & Analysis

- 📅 **Global trends over time** for Confirmed, Deaths, Active Cases
- 🌎 **Geographical bubble maps** showing case density
- 🏆 **Top 10 Countries by** Confirmed, Deaths, Recoveries, Active
- 📊 **WHO Region-wise analysis** (Bar, Pie, Strip, Violin plots)
- 📉 Distribution plots to assess skew and outliers
- 📌 Correlation analysis between Confirmed cases and Deaths

---

## 📌 Key Observations

- The **United States** leads in all metrics: confirmed, active, deaths, and recoveries.
- **Americas and Europe** are the most severely affected WHO regions.
- The distribution of confirmed cases is **highly right-skewed**, with few countries bearing most of the burden.
- **Strong positive correlation** exists between confirmed cases and deaths.
- Countries like **Russia and India** demonstrate high recovery effectiveness.

---

## ✅ Conclusion & Insights

- Regional strategies and healthcare infrastructure impact case fatality rates.
- Real-time data dashboards and predictive models can enhance readiness.
- Countries with fewer resources need targeted support for outbreak response.
- Transparent and standardized data collection is crucial for global collaboration.

---

## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook / Google Colab
- Geo visualization with Folium and Plotly Express

---

## 📁 Folder Structure

```
covid19_global_eda/
│
├── data/                  # Raw & cleaned datasets
├── notebooks/             # Jupyter notebooks for EDA
├── visuals/               # Saved charts and maps
├── insights/              # Summary reports & conclusions
├── README.md              # Project overview
```

---

## 🙌 Contribution

If you’d like to contribute, feel free to fork the repository and submit a pull request. All contributions are welcome.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🔗 Acknowledgments

- Johns Hopkins University for COVID-19 data repository.
- WHO for regional classification and global case monitoring.
