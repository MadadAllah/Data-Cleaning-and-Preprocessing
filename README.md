# 🧹 Data Cleaning & Preprocessing Project

> Internship Project | Role: Data Analyst  
> Dataset: Business Analyst Job Listings from LinkedIn (sourced via Kaggle)

---

## 📌 Objective

The goal of this project is to clean and preprocess a real-world job listing dataset to prepare it for insightful analysis. This includes identifying and resolving common data quality issues such as missing values, duplicates, inconsistent formats, and incorrect data types.

---

## 🗂 Dataset Overview

- **Source**: [Kaggle - Business Analyst Job Listings](https://www.kaggle.com/datasets)
- **Format**: CSV
- **Rows**: 921  
- **Columns**: 10  
- **Size**: ~72KB

### Columns:
| Column             | Description                                 |
|--------------------|---------------------------------------------|
| `title`            | Job title of the position                   |
| `location`         | Location of the job                         |
| `publishedAt`      | Date the job was posted                     |
| `companyName`      | Name of the company                         |
| `description`      | Full job description                        |
| `applicationsCount`| Number of applicants                        |
| `contractType`     | Type of contract (Full-time, Internship)    |
| `experienceLevel`  | Required experience level                   |
| `workType`         | Remote, On-site, or Hybrid                  |
| `sector`           | Industry or field the job belongs to        |

---

## 🔍 Key Tasks Performed

### ✅ 1. Loading the Dataset
- Used `pandas` to load and preview the dataset.

### ✅ 2. Initial Data Exploration
- Checked data types and memory usage with `.info()`
- Viewed basic statistics using `.describe()`
- Previewed column names and sample rows with `.columns` and `.head()`

### ✅ 3. Handling Missing Values
- Identified missing values using `df.isnull().sum()`
- Found `companyName` has 10 missing values (handled accordingly)

### ✅ 4. Dealing with Duplicates
- Checked for duplicates using `df.duplicated().sum()`
- Removed duplicates with `df.drop_duplicates()`

### ✅ 5. Data Type Conversion
- Converted columns like `publishedAt` to `datetime` format
- Verified numeric fields (`applicationsCount`) for correct data types

### ✅ 6. Data Standardization
- Cleaned categorical values for consistency (e.g., standardized `contractType`, `workType`)
- Removed unnecessary white spaces or inconsistent formatting

### ✅ 7. Data Visualization (Optional)
- Visualized missing values using `seaborn` heatmaps
- Plotted value counts for key categorical fields

---

## 📸 Dashboard / Notebook Screenshot

![Internship](Internship_Program_Analysis_Dashboard.jpg)

---

## 📈 Insights Gained

- Identified structure and key fields in job listings
- Prepared data for advanced analytics and visualization
- Discovered data quality issues that can mislead analysis
- Gained experience in real-world preprocessing workflow

---

## 🛠️ Tech Stack

- Python
  - Pandas
  - Matplotlib
  - Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 🤝 Let's Connect

If you found this helpful or want to collaborate on future data projects, feel free to connect on:

- 💼 [LinkedIn](https://linkedin.com/in/madadallah-bhatti-9698b1217)

---

> 📌 *This project was done as part of my Data Analyst Internship to demonstrate skills in handling and preparing messy real-world datasets.*
