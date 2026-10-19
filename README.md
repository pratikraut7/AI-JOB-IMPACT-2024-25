# AI Impact on Jobs (2010–2025) | NumPy & Pandas Practice

## 📌 Project Overview

This project focuses on exploring and analyzing the impact of Artificial Intelligence (AI) on jobs using Python, NumPy, and Pandas.

The project uses a dataset containing **5,000 records and 22 columns** related to job postings, salaries, AI adoption, automation risk, and reskilling requirements. A Jupyter Notebook is used to practice data analysis and manipulation techniques.

## 🎯 Objectives

- Practice data analysis using NumPy and Pandas.
- Load and explore a real-world-style dataset.
- Understand dataset structure, data types, and statistical summaries.
- Identify and handle missing values.
- Filter, sort, and group data.
- Analyze salary trends across different years.
- Explore AI adoption and job displacement risk.
- Perform numerical operations and correlation analysis.
- Create new features and export processed data.

## 🛠️ Technologies Used

- **Python** – Programming language
- **NumPy** – Numerical computations
- **Pandas** – Data manipulation and analysis
- **Jupyter Notebook** – Interactive coding and analysis

## 📂 Project Structure

```text
AI-Impact-on-Jobs/
│
├── ai_impact_jobs_2010_2025.csv
├── numpy_pandas_practice_ai_jobs.ipynb
└── README.md
```

## 📊 Dataset Description

The dataset contains information about job postings, companies, salaries, and the impact of AI on employment.

**Dataset size:** 5,000 rows × 22 columns

### Important Features

| Column | Description |
|---|---|
| `posting_year` | Year of the job posting |
| `country`, `region`, `city` | Geographic information |
| `company_name` | Name of the company |
| `company_size` | Size of the company |
| `industry` | Industry associated with the job |
| `job_title` | Job title |
| `seniority_level` | Seniority level of the position |
| `ai_mentioned` | Whether AI is mentioned in the job posting |
| `ai_intensity_score` | AI intensity score |
| `core_skills` | Core skills associated with the job |
| `ai_skills` | AI-related skills |
| `salary_usd` | Salary in US dollars |
| `automation_risk_score` | Score representing automation risk |
| `reskilling_required` | Indicates reskilling requirements |
| `ai_job_displacement_risk` | AI-related job displacement risk |
| `industry_ai_adoption_stage` | Stage of AI adoption in the industry |

Other columns include job IDs, salary changes, job description clusters, and additional job-related information.

## 🔍 Data Analysis Tasks

The Jupyter Notebook covers the following tasks:

1. Import NumPy and Pandas.
2. Load the CSV dataset into a Pandas DataFrame.
3. Display the first five rows.
4. Examine dataset information, shape, and column names.
5. Generate descriptive statistics.
6. Check and handle missing values.
7. Identify unique values in categorical columns.
8. Inspect data types.
9. Sort job postings by year.
10. Filter job postings from years after 2020.
11. Identify jobs with high displacement risk.
12. Calculate average salaries by year.
13. Perform numerical operations using NumPy.
14. Analyze correlations between numerical columns.
15. Create a new feature based on job impact.
16. Count values in the newly created feature.
17. Export the processed dataset to a new CSV file.

## ⚙️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd AI-Impact-on-Jobs
```

### Step 2: Install Required Libraries

```bash
pip install numpy pandas jupyter
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Notebook

Open `numpy_pandas_practice_ai_jobs.ipynb` and execute the cells sequentially.

**Note:** Update the CSV file path in the notebook to match your local project folder before running it.

## 📈 Expected Outcomes

By completing this project, you can practice:

- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Data filtering and aggregation
- GroupBy operations in Pandas
- Numerical analysis using NumPy
- Correlation analysis
- Feature engineering
- Exporting processed datasets

The analysis can help explore patterns in salaries, AI adoption, automation risk, and reskilling requirements within the dataset.

## 🚀 Future Improvements

- Perform deeper exploratory data analysis.
- Create visualizations using Matplotlib and Seaborn.
- Compare salary trends across industries and countries.
- Analyze relationships between AI adoption and automation risk.
- Build an interactive dashboard using Power BI.
- Develop a machine learning model to investigate job displacement risk, if supported by the data.

## 👨‍💻 Author

**Pratik Laxman Raut**

- GitHub: [pratikraut7](https://github.com/pratikraut7)
- LinkedIn: [Pratik Raut](https://linkedin.com/in/pratik-raut-942490273)

## 📄 License

This project is intended for educational and data analysis practice. Add an appropriate license if you plan to distribute the project publicly.
