
# 🎬 IMDb Top 1000 Movies – Exploratory Data Analysis (EDA)
This project dives deep into a curated dataset of the **Top 1000 IMDb movies**, exploring patterns in movie genres, ratings, revenue, metascores, runtimes, and industry contributors. Using robust EDA techniques, the analysis uncovers insights into what makes a movie critically and commercially successful.

---

## 📊 Dataset Overview
- **Source:** Public IMDb Top 1000 Movies Dataset  
- **Instances:** 1000 movies  
- **Key Variables:**
  - **Title, Genre, Year, Director, Actors**  
  - **IMDb Rating, Votes, Revenue (Millions), Metascore**  
  - **Runtime (Minutes), Genre Count, Decade**

> **Note:** Null values in `Metascore` and `Revenue` were handled via imputation and removal during preprocessing.

---

## 📌 Project Objectives
- Clean and preprocess the raw IMDb movie data
- Analyze movie performance across genres, years, and contributors
- Explore relationships between revenue, rating, runtime, and metascore
- Visualize trends and outliers across different dimensions
- Generate actionable insights on movie success factors

---

## 🔧 Tools & Libraries
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Collections.Counter for frequency analysis  
- Jupyter Notebook  

---

## 📈 Key Analyses Performed
- Histograms and KDE plots to explore distributions of `Rating`, `Runtime`, and `Metascore`
- Boxplots for analyzing `Revenue` and outliers
- Count plots and bar charts for `Genre`, `Director`, `Actor`, and `Decade`
- Correlation heatmap for numerical attributes
- Line plot to visualize average rating trends over time
- Scatter plot to understand relationship between `Rating` and `Revenue`

---

## 📌 Insights
- Most movies have **IMDb ratings between 6.0 and 7.5** and **runtimes between 90–120 minutes**
- **Drama**, **Action**, and **Adventure** are the most common and highest-grossing genres
- **Ridley Scott** and **Mark Wahlberg** are the most frequent director and actor, respectively
- Movies in the **2010s** dominate the dataset, indicating a focus on recent film trends
- **Rating and Revenue** have a weak correlation, whereas **Votes and Revenue** show a stronger positive correlation
- **Multi-genre combinations** perform better commercially than single-genre films

---

## 💡 Actionable Recommendations
- 🎯 Focus production on **multi-genre films**—especially those including **Adventure, Action, or Fantasy**
- 🎥 Leverage known actors and directors to improve film visibility and engagement
- ⏱️ Keep movie **runtimes within the 100–120 minute range** to align with viewer preferences
- 📊 Use **Vote count and Metascore** as stronger indicators for commercial success than IMDb ratings alone
- 📅 Emphasize post-2010 content in marketing and streaming as it reflects current consumption trends
- 🎞️ Analyze outlier hits to identify what makes certain films break the revenue barrier

---

## 🧪 How to Run the Project
1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Movies_Data_amit_kharche
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
EDA_Movies_IMDB_Data_amit_kharche.ipynb
```
Run the cells to reproduce full analysis and visualizations.

---

## 📜 License
This project is intended for **educational and analytical purposes only**. Please refer to the dataset’s original license for any third-party usage restrictions.

---

## 🤝 Acknowledgements
- Dataset adapted from publicly available IMDb movie listings
- Visual and analytical design inspired by film industry analytics practices

---

## ✨ Connect with Me
- [LinkedIn](https://www.linkedin.com/in/amit-kharche)
- [Medium](https://medium.com/@amitkharche14)
- [GitHub](https://github.com/amitkharche)

If you found this project helpful or insightful, please ⭐ the repository and share your thoughts!
