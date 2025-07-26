# 🚢 Titanic Dataset Exploratory Data Analysis (EDA)

This project performs an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries like **Pandas**, **Seaborn**, **Matplotlib**, and **Plotly**. The goal is to understand the structure, patterns, and relationships within the dataset to uncover insights that are useful before building any Machine Learning model.

---

## 📁 Dataset

We use the **Titanic dataset** which contains data about passengers aboard the RMS Titanic, including whether they survived or not. This dataset is available from:

- Seaborn's built-in datasets (`sns.load_dataset('titanic')`)
- Or from [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

---

## 🧰 Tools & Libraries Used

- **Pandas** – Data manipulation and summary statistics
- **Seaborn** – Advanced statistical plots
- **Matplotlib** – Basic plotting
- **Plotly** – Interactive visualizations
- **NumPy** – Numerical computations

---

## 🧪 EDA Steps

### ✅ Data Summary
- Preview of dataset using `.head()`
- Summary statistics using `.describe()`
- Check for missing values and data types

### 📊 Visual Analysis

1. **Histograms** – Distribution of numeric variables like Age, Fare
2. **Boxplots** – Identify outliers and IQR for numeric features
3. **Correlation Matrix** – Heatmap showing feature correlation
4. **Pairplot** – Visual relationship among numeric features
5. **Categorical Plots** – Survival analysis by Sex, Pclass, etc.
6. **Interactive Plot** – Age vs Survival (using Plotly)

---

## 📈 Sample Outputs

- **Boxplots** to detect outliers  
- **Heatmap** to detect multicollinearity  
- **Histograms** for feature distributions  
- **Interactive Plotly histogram** for Age and Survival  

---
