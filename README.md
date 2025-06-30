🚢 Titanic Survival Analysis — Exploratory Data Analysis (EDA)

This project performs in-depth Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. 
The goal is to uncover insights about passenger demographics and how different factors (like class, gender, age, etc.) influenced survival.

📁 Dataset
- Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- File used: `train.csv`

🛠 Tools & Libraries
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

🧾 Step-by-Step Process

✅ 1. Basic Understanding of the Dataset
Performed basic inspection using:
- `df.head()` – View top 5 rows
- `df.info()` – Data types and null values
- `df.describe()` – Summary statistics
- `df.isnull().sum()` – Count of missing values
- `df['Sex'].value_counts()` – Frequency count of categorical features

✅ 2. Data Cleaning
Cleaned and prepared the data by:
- **Handling Missing Values:**
  - Filled missing `Age` values using median.
  - Filled missing `Embarked` values using mode.
  - Dropped `Cabin` due to excessive missing data.
- **Data Type Conversion:**
  - Converted `Survived` and `Pclass` to categorical for appropriate analysis.
- **Renamed Columns:**
  - `Pclass` was renamed to `PassengerClass` for clarity.
  - 
📊 3. Key Analyses Performed
- **Univariate Analysis**:
  - Age, Fare, Sex, Pclass distributions using histograms, boxplots, and countplots.
- **Bivariate Analysis**:
  - Survival rates by Sex and Pclass
  - Age vs Fare scatter plot
  - Correlation heatmap
- **Multivariate Analysis**:
  - Survival by Pclass & Sex
  - Crosstab: Embarked × Pclass × Survival (heatmap)
- **Handling Skewed Data**:
  - Log transformation applied to skewed Fare column

📌 4. Summary of Findings
- 👩‍🦱 Most survivors were female.
- 🛳 1st class passengers had the highest survival rate.
- 💰 Higher Fare correlated with higher survival chances.
- 👶 Younger passengers had a slightly better survival rate.
- ⚓ Passengers from Cherbourg (C) survived more than those from Southampton (S) or Queenstown (Q).


