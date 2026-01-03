# 📊 Netflix / Media Dataset – Exploratory Data Analysis (EDA)

This repository contains **Week 3 – Project 2**, completed as part of the **SyntexHub Internship Program**.  
The project performs an in-depth **Exploratory Data Analysis (EDA)** on a movie/media dataset to uncover trends in content production, genres, ratings, languages, and audience engagement using Python.

---

## 🎯 Project Objectives

- Analyze movie release trends over time  
- Explore genre distribution and identify dominant genres  
- Categorize and analyze movie ratings  
- Study audience engagement using popularity and vote counts  
- Perform language-wise content analysis  
- Generate Top-10 analytical lists  
- Create and export a complete **visual report (saved plots)**  

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas** – data manipulation and analysis  
- **NumPy** – numerical operations  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical and advanced visualizations  

---

## 📂 Dataset Information

- **Dataset Name:** `mymoviedb.csv`
- **Dataset Type:** Movie / Media Metadata
- **Key Columns:**
  - `Title`
  - `Release_Date`
  - `Genre`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average`
  - `Original_Language`

> ⚠️ The dataset does not include Movie/TV type, runtime, or country information.  
> All limitations are clearly documented and justified in the analysis.

---


---

## 📊 Analysis & Visualizations

All visualizations are saved inside the **`plots/`** folder.

### 🔹 Genre Analysis
- Overall genre distribution  
- Top-10 most common genres  

### 🔹 Release Trend Analysis
- Movie release distribution by year  
- Identification of peak content production periods  

### 🔹 Rating & Engagement Analysis
- Categorized vote average distribution  
- Popularity vs vote count scatter analysis  
- Vote count distribution (rating reliability)  

### 🔹 Language-wise Analysis (Extended Scope)
- Top-10 original languages by number of movies  
- Used as a proxy for geographic diversity due to dataset limitations  

---

## 📌 Requirement Coverage Summary

### 1. Counts by Type, Year Trends, and Top Genres

| Requirement           | Status           | Evidence |
|----------------------|------------------|----------|
| Movie / TV type count | ⚠️ Not available | Dataset does not contain a `Type` column |
| Year trends           | ✅ Covered        | Movie release distribution by year |
| Top genres            | ✅ Covered        | Genre distribution + Top-10 genres |

---

### 2. Content Growth & Runtime Distribution

| Requirement              | Status           | Evidence |
|--------------------------|------------------|----------|
| Content growth over time | ✅ Covered        | Release year histogram |
| Runtime distribution     | ⚠️ Not available | No runtime column in dataset |

---

### 3. Top-10 & Distribution Analysis

| Requirement        | Status    | Evidence |
|--------------------|-----------|----------|
| Top-10 genres      | ✅ Covered | Table + saved bar chart |
| Top-10 years       | ✅ Covered | Release year analysis |
| Top languages      | ✅ Covered | Language-wise distribution plot |

---

### 4. Visual Report

| Requirement  | Status    | Evidence |
|--------------|-----------|----------|
| Visual plots | ✅ Covered | All plots saved in `plots/` |
| Summary      | ✅ Covered | Detailed notebook conclusion |

---

## 🔍 Key Insights

- A small set of genres dominates the content library, reflecting focused content strategies.
- Movie releases have increased significantly in recent years, showing content expansion.
- Most movies fall under **Average** and **Popular** rating categories.
- Higher popularity generally aligns with higher vote counts, indicating strong audience engagement.
- Content is dominated by a few original languages, suggesting limited linguistic diversity.

---

## ✅ Conclusion

All **core and extended objectives of Week 3 – Project 2** have been successfully completed.  
Any unmet requirements are due to **dataset limitations**, not incomplete analysis.

By incorporating **language-based analysis**, **audience engagement metrics**, and a **complete saved visual report**, this project now aligns with **Netflix-level EDA standards**.

The project is suitable for:
- ✅ Academic evaluation  
- ✅ GitHub portfolio presentation  
- ✅ Internship and interview discussions  

---

## 🔗 Internship Program

This project was completed under the **SyntexHub Internship Program** as part of **Week 3 – Project 2**.

---

### 👩‍💻 Author

**Iqlas Tharannum**  



