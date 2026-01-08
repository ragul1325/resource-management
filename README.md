# resource-management
Main-Workers-Industrial-Analysis/
│
├── data/
│   ├── main_workers_1.csv
│   ├── main_workers_2.csv
│   ├── main_workers_merged.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── src/
│   ├── merge_data.py
│   ├── preprocessing.py
│   ├── eda.py
│   ├── nlp_industry_classification.py
│   ├── model.py
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
# Industrial Human Resource Analysis Using Data Science

## 📌 Project Overview
This project analyzes the industrial classification of main workers in India using data science techniques. 
It focuses on merging multiple datasets, performing exploratory data analysis (EDA), applying NLP for 
industry categorization, and building a machine learning model to extract workforce insights.

---

## 🎯 Objectives
- Merge multiple CSV datasets into a single DataFrame
- Perform data cleaning and exploratory data analysis
- Classify industries using NLP techniques
- Build and test a machine learning model
- Visualize workforce distribution using dashboards

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Plotly
- Scikit-learn
- Streamlit
- NLP (Text Processing)

---

## 📂 Dataset Description
The dataset contains state-wise industrial classification of main workers by gender.
Multiple CSV files were merged to form a unified dataset for analysis.

---

## 🔄 Workflow
1. Data Collection
2. Data Merging
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. NLP-based Industry Classification
7. Model Building & Testing
8. Visualization using Streamlit

---

## 🤖 Machine Learning Model
- Model Used: Linear Regression
- Input Features: Male Workers, Female Workers
- Target Variable: Total Workers

---

## 📊 Key Insights
- Manufacturing and construction sectors employ the highest number of workers
- Male workforce dominates industrial employment
- NLP helps group complex industries into meaningful categories

---

## ▶️ How to Run the Project

### Step 1: Clone Repository
```bash
git clone https://github.com/yourusername/Main-Workers-Industrial-Analysis.git
