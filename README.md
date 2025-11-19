# 📘 Lilly Data Engineer Technical Challenge – 2025  

### Candidate: Afzal Hakkim  

This repository contains my solution for the **Lilly UK Data Engineer Technical Challenge**. The challenge tests fundamental skills in **data engineering**, including dataset handling, SQL querying, data integration, and data quality assessment.  

---

## 📝 Task Overview

The objective of this challenge was to perform the following tasks using the provided datasets:

1. Calculate the **average number of goals per game** between 1900 and 2000.  
2. Count the **number of penalty shootout wins by country**, arranged alphabetically.  
3. Create a **reliable match key** for joining goalscorers, results, and shootouts.  
4. Identify **teams winning a penalty shootout after a 1-1 draw**.  
5. Identify the **top goal scorer by tournament** and calculate their percentage contribution to total goals.  
6. (Optional) Flag and **resolve data quality issues** in the `goalscorers` dataset.  

---

## 📂 Dataset

The following CSV files were provided for the challenge:

- `goalscorers.csv` – Contains goals scored in matches, scorer names, minute, team, own goals, and penalty info.  
- `results.csv` – Contains match results including home/away teams, scores, tournament, city, and country.  
- `shootouts.csv` – Contains penalty shootout results including winner and first shooter.  

---

## 💻 Approach & Tools

- **Python 3.x** – For data manipulation and analysis using `pandas`.  
- **SQLite (in-memory)** – Temporary database to run SQL queries efficiently inside the notebook.  
- **SQL Queries** – For calculating aggregates, joins, and ranking operations.  
- **Data Quality Checks** – Identified missing or invalid values and corrected them for analysis.  
- **Jupyter Notebook / Google Colab** – For structured analysis and step-by-step documentation.  

---

## 🛠 Notebook Structure

1. **Load and Inspect Data** – Validate datasets and understand the schema.  
2. **Create SQLite Database** – In-memory setup for querying.  
3. **Average Goals Query** – Calculate average goals per game (1900–2000).  
4. **Shootout Wins Query** – Count shootout wins by country.  
5. **Match ID Creation** – Create a consistent key for joining tables.  
6. **Shootout Winners after 1-1 Draw** – Identify teams winning shootouts after a tied match.  
7. **Top Scorer by Tournament** – Compute top scorer and contribution percentage.  
8. **Data Quality Checks & Cleaning** – Flag missing/invalid values and clean the data.  

---

## 📊 Notes

- All SQL queries are executed via an **in-memory SQLite database**.  
- Data cleaning ensures robust analysis and prevents incorrect results.  
- Each step is documented with **explanations** to make the process reproducible and understandable.  

---

## 🔗 Submission

- The completed notebook (`Lilly_DataEngineer_Task.ipynb`) is included in this repository.  
- All steps, queries, and results are clearly documented for review.  
