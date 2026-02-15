# 📊 Task 2 – Exploratory Data Analysis (EDA)

## 🧾 Overview

This project is part of the **AI & ML Internship – Task 2**.
The objective of this task is to perform **Exploratory Data Analysis (EDA)** to understand the dataset using **statistics and visualizations** before applying Machine Learning models.

EDA helps uncover patterns, detect anomalies, test assumptions, and prepare data for further analysis.

---

## 🎯 Objective

* Understand the structure of the dataset
* Generate descriptive statistics
* Visualize distributions and relationships
* Detect missing values and outliers
* Identify trends, correlations, and patterns

---

## 📂 Dataset Used

**Titanic Dataset**

This dataset contains information about passengers aboard the Titanic, including:

* Age
* Fare
* Passenger Class
* Gender
* Survival Status

---

## 🛠️ Tools & Libraries Used

* **Python**
* **Pandas** → Data manipulation & analysis
* **Matplotlib** → Basic visualizations
* **Seaborn** → Advanced statistical plots

---

## 🔎 Steps Performed

### 1️⃣ Data Loading

* Loaded dataset using Pandas.
* Inspected structure using `.head()` and `.info()`.

### 2️⃣ Data Cleaning

* Checked missing values using `.isnull().sum()`.
* Filled missing **Age** values using median.
* Dropped **Cabin** column due to excessive missing data.

### 3️⃣ Summary Statistics

Generated:

* Mean
* Median
* Standard Deviation
* Minimum / Maximum
* Feature distributions using `.describe()`.

### 4️⃣ Data Visualization

#### 📈 Histograms

Used to understand feature distributions such as:

* Age Distribution
* Fare Distribution

#### 📦 Boxplots

Used to detect:

* Outliers
* Spread of numerical features

#### 🔥 Correlation Matrix (Heatmap)

Analyzed relationships between variables.

#### 🔗 Pairplot

Visualized feature-to-feature relationships.

---

## 📊 Key Insights Discovered

✔ Passengers who paid **higher fares** had a greater survival rate.
✔ **Passenger Class (Pclass)** strongly influenced survival probability.
✔ The **Fare feature contains outliers**.
✔ Age distribution is slightly **right-skewed**.
✔ Strong correlation exists between **Fare and Passenger Class**.

---

## 📉 Why EDA is Important in Machine Learning

EDA helps to:

* Improve data quality before modeling
* Avoid incorrect assumptions
* Detect multicollinearity
* Understand feature importance
* Build better-performing ML models

---

## ▶️ How to Run This Project

### Step 1: Install Dependencies

```bash
pip install pandas matplotlib seaborn
```

### Step 2: Place Dataset

Download the dataset and place:

```
titanic.csv
```

inside the project folder.

### Step 3: Run the Analysis

```bash
python eda_analysis.py
```

---

## 📁 Project Structure

```
EDA_Task2/
│
├── titanic.csv
├── eda_analysis.py
├── README.md
└── outputs/ (optional screenshots)
```

---

## 📚 Interview Questions Covered

This project demonstrates understanding of:

* Purpose of EDA
* Use of boxplots for outlier detection
* Correlation and feature relationships
* Detecting skewness in data
* Identifying multicollinearity
* Role of visualization in ML workflows

---

## ✅ Conclusion

Exploratory Data Analysis provided meaningful insights into the dataset and prepared the data for potential Machine Learning applications. Visualization and statistical summaries helped reveal patterns that are not obvious from raw data alone.

---

## 👨‍💻 Author

**Aman Shafeek**
B.Tech Computer Science
AI & ML Internship – Task Submission
