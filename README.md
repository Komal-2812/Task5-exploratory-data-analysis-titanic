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

📊 Key Analyses Performed
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

📌 Summary of Findings
- 👩‍🦱 Most survivors were female.
- 🛳 1st class passengers had the highest survival rate.
- 💰 Higher Fare correlated with higher survival chances.
- 👶 Younger passengers had a slightly better survival rate.
- ⚓ Passengers from Cherbourg (C) survived more than those from Southampton (S) or Queenstown (Q).


