````markdown
# 🏏 Indian Premier League (IPL) – Exploratory Data Analysis (EDA)

This project explores detailed match and ball-by-ball datasets from the **Indian Premier League (IPL)**, one of the world’s most popular T20 cricket tournaments. Using robust **Exploratory Data Analysis (EDA)** techniques, we analyze trends in team performance, player contributions, match outcomes, and gameplay dynamics to uncover **actionable insights** and **strategic patterns** in IPL history.

---

## 📊 Dataset Overview

- **Source:** Public IPL datasets (match-level and delivery-level)
- **Match Dataset:** `ipl_matches.csv`
- **Delivery Dataset:** `ipl_deliveries.csv`
- **Total Matches:** 636
- **Total Deliveries:** Over 1.5 million balls
- **Key Attributes Include:**
  - **Match-level:** Date, Venue, Toss Winner, Match Winner, Player of the Match, Umpires
  - **Delivery-level:** Over, Ball, Batsman, Bowler, Runs, Extras, Dismissals
  - **Teams:** Team1, Team2, Batting Team, Bowling Team

> **Note:** Missing values (e.g., cities, umpires) were imputed or dropped during preprocessing.

---

## 📌 Project Objectives

- Clean and merge **match-level** and **delivery-level** data
- Explore **team performance**, **win patterns**, and **venue dynamics**
- Analyze **batting and bowling trends** by overs, innings, and players
- Identify key **player partnerships**, **economy rates**, and **dismissal types**
- Generate **strategic insights** for franchises, analysts, and cricket enthusiasts

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive plots
- Jupyter Notebook
- Datetime handling and custom aggregation functions

---

## 📈 Key Analyses Performed

- Toss decision impact on match outcome
- Top teams by total wins and consistent performance
- Player rankings by total runs, wickets, and match awards
- Venue analysis and match frequency across cities
- Victory margin analysis (runs vs. wickets)
- Economy rate trends and bowling efficiency
- Batting partnerships and scoring patterns by season

---

## 📌 Insights

- **Mumbai Indians** and **Chennai Super Kings** are the **most successful teams**, both in total wins and match consistency.
- **Caught** is the most frequent **mode of dismissal**, while **wides** are the most common form of **extras**.
- **Fielding first** is the preferred toss decision in over **59%** of matches, supporting the **chasing advantage**.
- **Top players** like **Virat Kohli**, **CH Gayle**, and **SL Malinga** dominate multiple performance charts.
- **Average match scores have steadily increased**, highlighting the shift towards **aggressive T20 strategies**.

---

## 💡 Actionable Recommendations

- 🧠 Focus recruitment around **core match-winners** with proven long-term performance
- 🎯 Invest in **economical bowlers** and enhance training to minimize **wides and extras**
- 🕹️ Base **toss strategy** on opponent and ground conditions instead of default chasing
- 🤝 Encourage top-order **batting partnerships** for stronger starts and game stability
- 🌐 Expand fan engagement and branding efforts in **key cities** like Mumbai, Bengaluru, and Kolkata

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Indian_Premier_League\ \(IPL\)_Data_amit_kharche
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

5. **Open the analysis file:**

```text
EDA_Indian_Premier_League (IPL)_Data_amit_kharche.ipynb
```

Run the cells to explore the full analysis and visual breakdown.

---

## 📜 License

This project is shared for **educational and analytical purposes** only. Redistribution or commercial use of the IPL data may be subject to **official licensing restrictions**.

---

## 🤝 Acknowledgements

* IPL dataset sourced from public repositories
* Analytical framework inspired by best practices in **sports analytics**
* Visuals designed to support **data-driven storytelling** in cricket

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

If you found this project insightful, please ⭐ the repository and share your feedback!

```
