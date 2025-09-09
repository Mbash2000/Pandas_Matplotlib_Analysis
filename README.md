# 📊 Analyzing Data with Pandas and Visualizing Results with Matplotlib

## 📝 Project Overview
This project demonstrates how to **load, analyze, and visualize a dataset** using Python libraries:
- **pandas** → for data handling and analysis  
- **matplotlib** → for creating charts and visualizations  

We use the **Iris dataset**, a classic dataset in machine learning, which contains measurements of iris flowers across three species.

---

## 🎯 Objectives
- Load and explore a dataset using pandas  
- Perform **basic data analysis** (summary statistics, grouping, etc.)  
- Create at least **four different types of plots** with matplotlib  
- Derive **findings and observations** from the dataset  

---

## 📂 Project Structure
Analyzing_Data_Pandas_Matplotlib/
│
├── analyze_iris_assignment.ipynb # Jupyter Notebook 
├── README.md # Documentation

---

## 🛠 Tools & Requirements
- Python 3.x  
- Jupyter Notebook  

- Libraries:
  ```bash
  pip install pandas matplotlib scikit-learn

  Steps Performed:
1. Load & Explore Dataset

Loaded Iris dataset using sklearn.datasets.load_iris()

Converted to a pandas DataFrame

Inspected with .head(), .info(), and checked missing values

2. Basic Data Analysis

Computed summary statistics using .describe()

Grouped by species and calculated average measurements

Key finding:

Iris-setosa has the smallest petal length/width

Iris-virginica has the largest measurements

Iris-versicolor lies between the two

3. Data Visualization

Created four customized plots:

Line Chart – Sepal length trend for first 30 samples

Bar Chart – Average petal length per species

Histogram – Distribution of sepal width

Scatter Plot – Sepal length vs petal length (by species)

📈 Example Output (Scatter Plot)

(one of the visualizations in the notebook)

🌍 Observations

Sepal length shows natural variation across samples

Petal length is a strong differentiator between species

Sepal width distribution is slightly skewed

Positive correlation exists between sepal length and petal length

✨ Author

Muhammad Bashir
Northwest University, Kano
2025 – Machine Learning Specialization
