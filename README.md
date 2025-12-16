# Stack Overflow Developer Survey 2025 – Data Analysis

## 📌 Project Overview
This project analyzes the **Stack Overflow Developer Survey 2025** dataset using **Python, Pandas, and Matplotlib**.  
The objective is to explore developer demographics, salary distribution, technology usage, and the relationships between experience, age, and compensation.

The project focuses on **real-world data analysis and visualization**, not machine learning.

---

## 🎯 Objectives
- Understand the demographic profile of developers
- Analyze yearly salary distribution and salary ranges
- Identify the most popular programming languages and technologies
- Study the relationship between salary, work experience, and age
- Visualize correlations between key numeric variables

---

## 🗂 Dataset
- **Source:** Stack Overflow Developer Survey 2025  
- **File:** `survey_results_public_2025.csv`

### Key Columns Used:
- `Country`
- `ConvertedCompYearly`
- `WorkExp`
- `Age`
- `EdLevel`
- `LanguageHaveWorkedWith`

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – data cleaning and analysis
- **Matplotlib** – data visualization
- **Jupyter Notebook**

---

## 📊 Analysis Performed

### 1️⃣ Data Cleaning & Preparation
- Handled missing values
- Processed multi-select columns using `split()` and `explode()`
- Simplified categorical columns for clearer analysis

---

### 2️⃣ Basic Exploration
- Total number of survey respondents
- Country-wise participation
- Average years of work experience
- Most commonly used programming languages

---

### 3️⃣ Technology Usage Analysis
- Programming languages popularity
- Platforms and tools used by developers
- Frequency analysis using bar charts

---

### 4️⃣ Salary Analysis
- Salary distribution using histograms
- Salary range binning (0–20k, 20–40k, 40–60k, etc.)
- Count of developers in each salary range
- Identification of salary spread and outliers

---

### 5️⃣ Demographics Analysis
- Age distribution of respondents
- Education level distribution
- Student vs professional participation

---

### 6️⃣ Correlation Analysis
- Correlation between:
  - Salary and work experience
  - Salary and age
  - Age and work experience
- Visualization using a correlation matrix heatmap

---

## 🔍 Key Insights
- Most developers fall into mid-level salary ranges, with a long tail of high earners.
- Age and work experience show a strong positive correlation.
- Salary has weak correlation with both age and experience at a global level.
- External factors such as country, job role, and industry likely influence salary more than age or experience alone.
- JavaScript and Python remain among the most widely used programming languages.

---

## 📁 Project Structure
├── stackoverflow_2025_analysis.ipynb

└── README.md

---

## 🚀 How to Run
1. Clone this repository
2. Install required libraries:
pip install pandas matplotlib
Open the notebook:

jupyter notebook stackoverflow_2025_analysis.ipynb
👤 Author
Ayon Sadhukhan

📌 Notes
This project is intended for learning and portfolio demonstration purposes.
The insights are exploratory and may vary due to geographic, economic, and role-based factors.

⭐ Acknowledgment
Thanks to Stack Overflow for providing the Developer Survey data publicly.
