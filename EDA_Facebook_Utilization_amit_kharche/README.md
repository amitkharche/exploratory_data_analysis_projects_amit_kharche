````markdown
# 📘 Facebook Utilization – Exploratory Data Analysis (EDA)

This project dives into a user-level dataset from Facebook to uncover how **age**, **gender**, **tenure**, and **engagement metrics** such as **friendships** and **likes** shape user behavior. Through comprehensive exploratory data analysis, the project reveals key patterns, anomalies, and behavioral insights that can help platforms or businesses understand their audience better.

---

## 📊 Dataset Overview

- **Source:** Simulated Facebook user data (publicly available)
- **Instances:** 99,000+
- **Target Attribute:** No specific target – Unsupervised analysis
- **Features Include:**
  - **Demographics:** Age, Gender, Date of Birth
  - **Behavioral Metrics:** Tenure, Friend Count, Friendships Initiated
  - **Engagement:** Likes (Mobile, Web), Likes Received (Mobile, Web)
  - **Derived Fields:** Age Group, Date of Birth Grouping

> **Note:** Missing values were handled via imputation; outliers were retained for behavior profiling.

---

## 📌 Project Objectives

- Clean, preprocess, and enrich raw Facebook user data
- Create derived variables such as age groups and age bands
- Perform univariate, bivariate, and multivariate EDA
- Analyze patterns in friendships, likes, and user activity
- Identify correlations between user attributes and engagement levels
- Generate business-ready insights for platform optimization

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive visuals
- ydata-profiling for automated data reports
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- **Distribution plots** for age, tenure, likes, and friendships
- **Count plots** for age groups, gender splits, and DOB analysis
- **Box plots** for tenure and engagement by age group
- **Correlation heatmap** and **pair plot** for feature relationships
- **Scatter plots** comparing friendships vs. likes, gender patterns
- **Pie charts** to visualize platform (Mobile vs Web) usage
- **Outlier detection** for high-friend-count or like-heavy users

---

## 📌 Insights

- The **21–30 age group** dominates Facebook usage.
- **Female users** show **higher engagement** in likes and initiating friendships despite being fewer.
- A **strong positive correlation** exists between **friend count** and **friendships initiated**.
- Most users have **low to moderate likes**, while a few show **extremely high engagement**.
- **Tenure increases with age**, suggesting **older users stay longer** on the platform.
- Likes are more frequent on **mobile apps** than websites.
- Activity drops off after **1000 days of tenure**, indicating a **decline in long-term user engagement**.
- Age groups **above 80 and below 30** show **higher friend counts**, suggesting generational extremes are more connected.

---

## 💡 Actionable Recommendations

- 📲 Prioritize **mobile-first UX enhancements** due to high mobile engagement.
- 🎯 Tailor features toward the **15–30 age group** to strengthen user retention.
- 👥 Promote friend suggestion algorithms for users with **low friend counts or initiation**.
- 🧠 Introduce **re-engagement campaigns** targeting users with **tenure > 1000 days**.
- 🧓 Build specialized content experiences for **older users**, who show longer retention.
- 📊 Use **female-oriented campaign strategies**, as they demonstrate stronger engagement.
- ⚠️ Apply data validation rules to flag **anomalies** (e.g., users aged 113).
- 📌 Monitor high-activity outliers for potential **influencer identification or misuse detection**.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Facebook_Utilization_amit_kharche
````

2. **(Optional) Create and activate a virtual environment:**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required dependencies:**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook:**

```bash
jupyter notebook
```

5. **Open the file:**

```
EDA_facebook_utilization_amit_kharche.ipynb
```

and run the cells to explore the full analysis and visual insights.

---

## 📜 License

This project is provided for **educational and analytical purposes only**. Use of data may be subject to licensing terms from external sources if reused commercially.

---

## 🤝 Acknowledgements

* Inspired by social behavior modeling and platform analytics
* Dataset enriched and profiled for EDA and learning
* Visualization strategies based on exploratory data techniques

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

> If this project helped you learn or build something cool, consider ⭐ starring the repository and sharing your feedback!

```
