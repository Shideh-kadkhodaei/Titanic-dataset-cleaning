# 🛳 Titanic Data Analysis Project

This repository contains a Python-based data analysis project using the famous Titanic dataset from Kaggle.  
The goal of this project is to clean the data, handle missing values, detect and analyze outliers, and explore relationships between different features (e.g., ticket class, fare, age, and survival).  

---

## 📂 Dataset
The dataset used in this project can be downloaded from Kaggle:  
👉 [Titanic Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

Make sure to place the file **Titanic-Dataset.csv** in the same directory as the notebook before running the code.

---

## ⚙️ Requirements
You need to have Python installed
The following Python libraries are required:

```bash
pip install pandas 
```

```bash
pip install numpy
```

```bash
pip install matplotlib
```

```bash
pip install seaborn
```

---

🚀 How to Run

1. Clone this repository or download the notebook.


2. Download the Titanic dataset from Kaggle and place it in the project folder.


3. Open the notebook in Jupyter Notebook or JupyterLab.


4. Run the cells step by step. Each cell corresponds to one stage of the analysis:

Data loading and exploration

Data cleaning (handling missing values, dropping irrelevant columns)

Outlier detection using IQR

Univariate analysis with histograms

Bivariate analysis (relationships between features like Pclass, Fare, Sex, Survived)

Correlation heatmap

Pairplot visualization





---

📊 What We Did

Cleaned missing values (Age → filled with median, Embarked → filled with mode, Cabin → dropped).

Detected outliers in Age and Fare using the IQR method.

Explored feature distributions with histograms.

Analyzed relationships between ticket class, fare, survival rate, and passenger sex.

Generated a correlation heatmap to highlight relationships between numerical variables.

Created a pairplot to visualize all numerical features together.



---

📌 Results & Insights

Higher-class passengers paid more for tickets and had a higher survival rate.

Women had a significantly higher survival rate compared to men.

Most passengers were between 20–40 years old.

Ticket fares are highly skewed with a few very expensive tickets.



---

📷 Example Visualizations

Histograms for Age and Fare.

Survival rates by class and sex.

Correlation heatmap.

Pairplot of numerical features.
