# 🎓 Student Performance and Behavior Analysis

## 🧩 Project Overview
This project focuses on analyzing student performance trends and behavioral patterns using data-driven insights. The dataset (in CSV format) includes details like students' academic percentages, school activities, and other categorical information. The goal is to uncover patterns that help educational institutions understand academic performance, student engagement, and key factors influencing outcomes.

## 🎯 Aim
To analyze and visualize student performance data to identify insights such as:
* Academic trends (10th and 12th percentages)
* Influence of school activities on performance
* Branch-wise and year-wise distribution of students
* Data cleaning and preprocessing for accurate visualization

## 🧰 Tools & Libraries Used
* **Python** – Core programming language
* **Pandas** – Data manipulation and cleaning
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **re & unidecode** – Text cleaning and preprocessing
* **Jupyter Notebook / Google Colab** – Development environment

## 🧹 Data Cleaning Process
* Removed irrelevant rows (e.g., containing "backshot")
* Normalized and standardized columns (`Branch`, `School_Area`, `Year`)
* Categorized percentage/CGPA ranges (Above 90%, 80–90%, 60–80%, Under 60%)
* Cleaned textual data in School Activities using regex and keyword mapping

## 📊 Analysis Performed
* Distribution of grades (10th and 12th)
* Categorization of students based on performance
* Visualization of participation in different activities
* Handling missing and inconsistent data
* Branch-wise and year-wise insights

## 💡 Key Insights
* Students actively involved in sports and tech activities show balanced performance.
* Most students fall in the 60–80% range, with consistent patterns across branches.
* Data cleaning was crucial — multiple invalid and inconsistent entries were normalized to achieve accurate results.

## 🏁 Outcome
The project successfully provides a structured and visual representation of student performance data. The insights can help educational institutions identify improvement areas, plan better academic strategies, and encourage holistic student development through academics and extracurricular activities.
