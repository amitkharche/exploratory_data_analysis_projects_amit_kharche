
# ✈️ Airline Passenger Satisfaction – Exploratory Data Analysis (EDA)

This project explores a large-scale dataset of airline passenger survey responses, analyzing the key drivers behind passenger satisfaction and dissatisfaction. Using robust EDA techniques, the analysis uncovers how service quality, travel attributes, and demographic factors influence customer sentiment across different travel scenarios.

---

## 📊 Dataset Overview

- **Source:** Simulated airline survey dataset (publicly available)
- **Instances:** 83,123
- **Target Variable:** `satisfaction` (Satisfied / Neutral or Dissatisfied)
- **Features Include:**
  - **Demographics:** Gender, Age, Customer Type
  - **Travel Attributes:** Class, Travel Type, Flight Distance
  - **Service Ratings:** Wi-Fi, Seat Comfort, Food, Entertainment, Online Services
  - **Delays:** Departure and Arrival Delay in Minutes

> **Note:** Missing values were handled via imputation during preprocessing.

---

## 📌 Project Objectives

- Clean and preprocess raw survey data
- Perform univariate, bivariate, and multivariate analysis
- Identify satisfaction trends across travel classes, customer types, and trip attributes
- Examine the influence of service ratings and delays on satisfaction
- Generate actionable insights for airline service enhancement and customer retention

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive charts
- ydata-profiling for automated EDA reporting
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Count plots to explore satisfaction by customer type, gender, and travel class
- KDE plots for age distribution comparison by satisfaction level
- Box plots for service ratings, delays, and digital services
- Bar plots showing average ratings of key service features
- Correlation heatmap of numerical variables to identify strong relationships

---

## 📌 Insights

- **Business class** and **loyal customers** show higher satisfaction levels.
- **Online boarding**, **seat comfort**, and **entertainment** are top-rated among satisfied passengers.
- **Flight delays** are significantly linked with dissatisfaction.
- **Younger and disloyal customers** report lower satisfaction, suggesting the need for targeted engagement.
- **Longer flights** are associated with better satisfaction, possibly due to better service coverage.

---

## 💡 Actionable Recommendations

- ✈️ Enhance service offerings for **Economy** and **Eco Plus** class passengers.
- 🎯 Strengthen loyalty programs and rewards for **returning customers**.
- 🧾 Improve **online booking and check-in systems** to enhance digital touchpoints.
- 🕑 Minimize **departure and arrival delays** to increase trust and satisfaction.
- 🎥 Focus service enhancements on **seat comfort, entertainment, and cleanliness**.
- 🔍 Monitor correlated services (e.g., check-in and online boarding) for bundled improvements.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
    ```bash
    git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
    cd exploratory_data_analysis_projects_amit_kharche/EDA_Airline_Flight Passenger Satisfaction_amit_kharche
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
    EDA_Airline_Flight Passenger Satisfaction_amit_kharche.ipynb
    ```
    and run the cells to reproduce the full analysis and visual insights.

---

## 📜 License

This project is shared for **educational and analytical purposes**. Redistribution or commercial use of the dataset may be subject to external licensing constraints.

---

## 🤝 Acknowledgements

- Dataset adapted for analysis and learning
- Visual and EDA framework inspired by airline industry applications

---

## ✨ Connect with Me

- [LinkedIn](https://www.linkedin.com/in/amit-kharche)
- [Medium](https://medium.com/@amitkharche14)
- [GitHub](https://github.com/amitkharche)

If you found this project insightful, please ⭐ the repository and share your feedback!
