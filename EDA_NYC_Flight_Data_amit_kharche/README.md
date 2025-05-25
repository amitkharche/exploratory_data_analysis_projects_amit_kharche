
---

# 🛫 NYC Flights 2013 – Exploratory Data Analysis (EDA)

This project performs a comprehensive exploratory data analysis on flights departing from New York City’s three major airports (**JFK, LGA, and EWR**) throughout the year **2013**. Leveraging data from the Bureau of Transportation Statistics, the analysis uncovers patterns in flight volume, delays, speed, and route performance to provide actionable insights into aviation operations and service efficiency.

---

## 📊 Dataset Overview

* **Source:** [NYC Flights 2013 Dataset](https://www.kaggle.com/datasets/jonthoward/nycflights13)
* **Instances:** 336,776
* **Target Variables:** `dep_delay`, `arr_delay`, `air_time`
* **Features Include:**

  * **Flight Info:** Flight number, carrier, tail number
  * **Schedule Info:** Scheduled and actual departure/arrival times
  * **Location Info:** Origin, destination
  * **Time Stamps:** Year, month, day, hour, minute
  * **Performance Metrics:** Delay (departure & arrival), air time, distance

> **Note:** Missing values were imputed using mean/mode where appropriate during preprocessing.

---

## 📌 Project Objectives

* Clean and preprocess raw flight data
* Perform univariate, bivariate, and multivariate analysis
* Identify high-delay carriers, routes, and time periods
* Analyze temporal patterns in flight volume and delays
* Examine correlations between flight characteristics (distance, speed, air time)
* Deliver actionable insights for improving airline operations

---

## 🔧 Tools & Libraries

* Python
* Pandas, NumPy
* Seaborn, Matplotlib, Plotly
* Calendar module for month mapping
* Jupyter Notebook

---

## 📈 Key Analyses Performed

* Monthly and hourly flight volume distribution
* Carrier-wise flight activity and average speed comparison
* Delay patterns by route, month, and airport
* Violin and histogram plots for air time and delay distributions
* Correlation between air time and distance
* Pie charts and bar plots for airport and route frequency
* Boxplots for airport-level departure delay variability

---

## 📌 Insights

* **Summer months (July–August)** saw peak flight volumes, while **February** had the lowest.
* **EWR** contributed the most flights but also had the **highest average delays**.
* **Departure delay** strongly correlates with **arrival delay**, confirming schedule impact.
* **UA**, **B6**, and **EV** emerged as the most active carriers from NYC.
* **Morning flights (6–9 AM)** dominate departure slots, while late-night activity drops sharply.
* Most flights fall in the **60–200 minute air time range**, indicating domestic short-to-medium haul coverage.

---

## 💡 Actionable Recommendations

* 🚦 Implement **delay mitigation strategies** at EWR, particularly for high-delay routes.
* 🧠 Develop **predictive models** for arrival delays based on departure time and distance.
* 🕑 Optimize **resource allocation** during peak hours (6–9 AM) for smoother operations.
* 🧭 Encourage efficient routing for **low-speed carriers** to minimize air time.
* 🌤️ Prepare for **summer congestion** with additional staffing and buffer scheduling.
* 📉 Benchmark JFK and LGA’s **on-time performance** to improve EWR reliability.

---

## 🧪 How to Run the Project

1. **Clone the repository:**

```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_NYC_Flight_Data_amit_kharche
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
EDA_NYC_Flights_Data_Analysis_amit_kharche.ipynb
```

and run the cells to reproduce the full analysis and visual insights.

---

## 📜 License

This project is shared for **educational and analytical purposes**. Redistribution or commercial use of the dataset may be subject to external licensing restrictions.

---

## 🤝 Acknowledgements

* Data curated from **Bureau of Transportation Statistics**
* Analysis inspired by **real-world airline performance monitoring**
* Visualization strategies inspired by best practices in data storytelling

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If you found this project insightful, please ⭐ the repository and share your feedback!

---
