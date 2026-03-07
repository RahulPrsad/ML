# 🚢 Day 2 -- Exploratory Data Analysis (EDA) \| Machine Learning

## 📌 Project Overview

This project is part of my **Machine Learning Journey -- Day 2**.\
In this project, I performed **Exploratory Data Analysis (EDA)** on the
Titanic Dataset to understand the data, clean it, visualize patterns,
and extract meaningful insights.

------------------------------------------------------------------------

## 📂 Dataset Used

-   📊 Dataset: Titanic Dataset\
-   🎯 Target Variable: `Survived`\
-   📏 Rows: 891\
-   📑 Columns: 12

Dataset loaded using:

``` python
import pandas as pd

df = pd.read_csv('/content/Titanic-Dataset.csv')
df.head()
```

------------------------------------------------------------------------

## 🔍 Steps Performed

### 1️⃣ Data Understanding

-   Used `df.head()` to preview data\
-   Checked structure using `df.info()`\
-   Statistical summary using `df.describe()`\
-   Checked missing values using `df.isnull().sum()`

------------------------------------------------------------------------

### 2️⃣ Data Cleaning

-   Filled missing values in **Age** using median\
-   Filled missing values in **Embarked** using mode\
-   Encoded categorical variables:
    -   `Sex` → Male = 0, Female = 1\
    -   `Embarked` → S = 0, C = 1, Q = 2

------------------------------------------------------------------------

### 3️⃣ Outlier Detection

-   Used **IQR (Interquartile Range)** method\
-   Visualized using boxplots

------------------------------------------------------------------------

### 4️⃣ Data Visualization

-   Countplot (Gender distribution)\
-   Histogram (Age distribution)\
-   Barplot (Sex vs Age)\
-   Scatterplot (Age vs Fare)\
-   Correlation Heatmap\
-   Pairplot (Age, Sex, Fare, Survived)

------------------------------------------------------------------------

## 📊 Key Insights

-   Around **65% passengers were male**
-   Females had a higher survival rate than males
-   Passenger class (Pclass) negatively correlates with survival
-   Fare positively correlates with survival
-   Age shows slight negative correlation with survival

------------------------------------------------------------------------

## 🛠️ Libraries Used

-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn

------------------------------------------------------------------------

## 🎯 Learning Outcomes

-   Understood dataset structure\
-   Handled missing data\
-   Applied encoding techniques\
-   Performed outlier detection\
-   Created meaningful visualizations\
-   Interpreted feature correlations

------------------------------------------------------------------------

## 🚀 Machine Learning Journey

This project marks **Day 2** of my Machine Learning journey.\
More projects coming soon!
