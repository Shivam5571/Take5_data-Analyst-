# Take5_data-Analyst
# 🧠 Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover insights, detect patterns, and visualize trends that influence survival outcomes.

## 📁 Dataset

We use the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data), which contains information about passengers aboard the Titanic. The dataset includes features like age, sex, ticket fare, class, etc.

- `train.csv` (uploaded): The primary dataset used for analysis.

## 🎯 Objective

To extract insights using both **statistical** and **visual** exploration methods. The goal is to build an understanding of the data that can later be used for modeling or decision-making.

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## 📊 EDA Highlights

- Data Cleaning: Checked for missing values and data types
- Descriptive Stats: `.describe()`, `.info()`, `.value_counts()`
- Visual Analysis:
  - Histograms for distributions (e.g., Age, Fare)
  - Boxplots for outlier detection
  - Scatterplots for relationships
  - `sns.pairplot()` for multivariate analysis
  - `sns.heatmap()` for correlation matrix
- Relationship Exploration: Gender vs Survival, Class vs Survival, Age distributions by class
- Insights & Observations: Each plot is followed by brief conclusions

## 📄 Deliverables

- ✅ `Titanic_EDA.ipynb` – Jupyter Notebook containing all code, visuals, and insights
- ✅ `Titanic_EDA_Report.pdf` – Cleaned PDF report with charts and summarized findings
- ✅ `train.csv` – Dataset used

## 📌 Key Takeaways

- **Sex** and **Passenger Class (Pclass)** are strong predictors of survival.
- Younger passengers and those in higher classes had better survival rates.
- Fare and Embarkment location showed patterns worth deeper exploration.
- Several features contain missing values that need handling before modeling.

## 🧠 Skills Practiced

- Data Cleaning & Preparation
- Statistical Summary Interpretation
- Visual Insight Extraction
- Pattern, Trend & Anomaly Identification

## 📬 Feedback

Feel free to fork this repo, give a ⭐️, or raise an issue if you spot anything that could be improved!

---

> This project is part of a data analysis assignment to build practical EDA skills using the Titanic dataset.
