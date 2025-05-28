
---

# 👨‍💼 Employee Attrition Analysis – Exploratory Data Analysis (EDA)

This project investigates employee attrition using **three interconnected datasets**—capturing departmental structures, individual demographics, and detailed work-related metrics. The goal is to identify key drivers of voluntary attrition and provide data-driven recommendations for improving employee retention.

---

## 📊 Dataset Overview

This project uses three related datasets:

### 📁 1. Department Data (`department_data.csv`)
| Feature Name     | Description                            |
|------------------|----------------------------------------|
| `dept_id`        | Unique department code                 |
| `dept_name`      | Name of the department                 |
| `dept_head`      | Name of the head of the department     |

### 📁 2. Employee Details (`employee_details_data.csv`)
| Feature Name      | Description                                  |
|-------------------|----------------------------------------------|
| `employee_id`     | Unique ID for each employee                  |
| `age`             | Age of the employee                          |
| `gender`          | Gender of the employee                       |
| `marital_status`  | Marital status of the employee               |

### 📁 3. Employee Work & Status Data (`employee_data.csv`)
| Feature Name         | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `status`             | Employment status (Employed / Left)                                         |
| `department`         | Department the employee belongs or belonged to                              |
| `salary`             | Salary level relative to others in the department                           |
| `tenure`             | Years spent at the company                                                   |
| `recently_promoted`  | Whether promoted in the last 3 years                                         |
| `employee_id`        | Unique identifier to merge with demographics                                |
| `n_projects`         | Number of projects handled                                                   |
| `avg_monthly_hrs`    | Average hours worked per month                                               |
| `satisfaction`       | Employee's satisfaction score (higher is better)                             |
| `last_evaluation`    | Most recent performance evaluation score                                     |
| `filed_complaint`    | Whether a formal complaint was filed in the last 3 years                     |

> **Note:** Datasets were clean and integrated using `employee_id`. Categorical values were encoded and no missing data was found during preprocessing.

---

## 📌 Project Objectives

- Merge and clean datasets for holistic employee profiling
- Conduct univariate, bivariate, and multivariate analysis
- Identify key drivers of employee attrition (e.g., satisfaction, workload, promotions)
- Discover department-level and demographic patterns
- Generate actionable insights for **HR retention strategy**

---

## 🔧 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Plotly for interactive charts
- ydata-profiling for automated EDA
- Jupyter Notebook

---

## 📈 Key Analyses Performed

- Attrition distribution across **age**, **gender**, **marital status**, and **department**
- KDE and box plots to compare **salary**, **tenure**, and **satisfaction** by attrition
- Evaluation of **promotion history**, **overtime**, **complaints**, and **project load**
- Correlation matrix for continuous features
- Department-level attrition benchmarking

---

## 📌 Insights

- **Employees who work overtime** or have **lower satisfaction** are **more likely to leave**.
- **Short-tenured employees** and those with **no recent promotion** show higher attrition risk.
- Departments like **Sales** and **Human Resources** show **elevated attrition rates**.
- **Low evaluation scores** coupled with **high average monthly hours** indicate possible burnout.
- **Married employees** and those with longer tenure tend to **stay longer**.

---

## 💡 Actionable Recommendations

- Reevaluate **workload distribution** to avoid burnout and reduce overtime hours.
- Introduce **targeted retention strategies** for high-risk departments.
- Promote early career advancement programs for **under-3-years-tenure** employees.
- Improve **work-life balance** and satisfaction through flexible scheduling or benefits.
- Use data to build an **employee early warning system** for HR teams to intervene proactively.

---

## 🧪 How to Run the Project

1. **Clone the repository:**
```bash
git clone https://github.com/amitkharche/exploratory_data_analysis_projects_amit_kharche.git
cd exploratory_data_analysis_projects_amit_kharche/EDA_Employee_Attrition_amit_kharche
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

5. **Open the file:**

```
EDA_Employee_Attrition_amit_kharche.ipynb
```

and run all cells to reproduce the analysis and visual outputs.

---

## 📜 License

This project is shared for **educational and analytical purposes only**. Any reuse of the dataset should credit the original source or comply with relevant terms.

---

## 🤝 Acknowledgements

* Dataset sourced from IBM HR Analytics repository
* Visualization structure and EDA approach inspired by best practices in organizational analytics

---

## ✨ Connect with Me

* [LinkedIn](https://www.linkedin.com/in/amit-kharche)
* [Medium](https://medium.com/@amitkharche14)
* [GitHub](https://github.com/amitkharche)

⭐ If you found this project valuable, don’t forget to **star the repo** and share your feedback!

---
