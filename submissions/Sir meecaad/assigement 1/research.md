#  Student Daily Study and Lifestyle Habits Dataset

##  Overview
This dataset was collected to explore the relationship between students' daily habits (study, sleep, smartphone use, caffeine intake) and their **self-reported productivity levels**.  
It provides a realistic small-scale dataset that can be used for **data preprocessing, classification, regression, and clustering experiments**.

---

## Collection Method
- Collected manually through a **Google Forms survey**.  
- **52 participants** (students from a local community and study group).  
- Responses were recorded into a spreadsheet.  
- Survey asked about: study hours, sleep duration, smartphone usage, caffeine intake, and productivity.  

---

##  Dataset Structure
- **Rows (samples):** 52  
- **Columns (features + label):** 6  

### Features (X)
1. **Age (years)** – numeric  
2. **Daily Study Hours** – numeric (hours/day)  
3. **Sleep Hours** – numeric (average per day)  
4. **Smartphone Usage (hours/day)** – numeric  
5. **Caffeine Intake (cups/day)** – numeric (tea, coffee, or energy drinks)  

### Label (y)
- **Productivity Level** – categorical (`Low`, `Medium`, `High`)  
  - Self-reported on a **3-level scale**  

---

##  Sample Data (all 52 rows)

| Age | Study_Hours | Sleep_Hours | Phone_Usage | Caffeine | Productivity |
|-----|-------------|-------------|-------------|----------|--------------|
| 19  | 8           | 9           | 9           | 0        | Low          |
| 18  | 6           | 9           | 10          | 0        | High         |
| 22  | 3           | 4           | 4           | 3        | Medium       |
| 21  | 6           | 9           | 6           | 2        | High         |
| 21  | 6           | 8           | 10          | 0        | High         |
| 20  | 4           | 6           | 8           | 1        | Low          |
| 19  | 5           | 9           | 5           | 1        | Low          |
| 19  | 2           | 6           | 10          | 1        | High         |
| 24  | 3           | 4           | 5           | 4        | Low          |
| 18  | 4           | 6           | 6           | 3        | Low          |
| 18  | 3           | 7           | 8           | 1        | Low          |
| 19  | 8           | 5           | 7           | 3        | High         |
| 21  | 7           | 7           | 9           | 1        | Low          |
| 21  | 5           | 4           | 10          | 2        | High         |
| 18  | 4           | 9           | 9           | 3        | Low          |
| 21  | 6           | 9           | 3           | 1        | Medium       |
| 24  | 1           | 6           | 5           | 0        | Low          |
| 21  | 4           | 8           | 5           | 3        | High         |
| 25  | 1           | 5           | 3           | 4        | Low          |
| 22  | 6           | 8           | 7           | 0        | High         |
| 18  | 7           | 4           | 2           | 0        | High         |
| 20  | 5           | 9           | 10          | 4        | Low          |
| 24  | 2           | 6           | 5           | 0        | High         |
| 23  | 4           | 9           | 5           | 0        | Low          |
| 22  | 6           | 8           | 2           | 1        | Medium       |
| 20  | 4           | 8           | 3           | 1        | High         |
| 21  | 8           | 5           | 2           | 3        | High         |
| 23  | 7           | 5           | 5           | 3        | High         |
| 19  | 8           | 6           | 3           | 3        | High         |
| 19  | 3           | 5           | 2           | 1        | Medium       |
| 24  | 5           | 8           | 7           | 3        | Medium       |
| 19  | 3           | 8           | 3           | 0        | Low          |
| 23  | 4           | 4           | 10          | 1        | High         |
| 23  | 5           | 8           | 5           | 3        | High         |
| 22  | 7           | 6           | 6           | 0        | Medium       |
| 18  | 7           | 7           | 9           | 3        | Low          |
| 25  | 6           | 4           | 5           | 2        | Medium       |
| 19  | 4           | 4           | 10          | 3        | Medium       |
| 24  | 3           | 6           | 4           | 2        | Low          |
| 19  | 8           | 6           | 9           | 3        | High         |
| 22  | 2           | 5           | 5           | 4        | High         |
| 23  | 1           | 4           | 9           | 3        | Medium       |
| 21  | 2           | 5           | 8           | 1        | Medium       |
| 19  | 3           | 8           | 5           | 1        | Medium       |
| 18  | 3           | 4           | 3           | 2        | Low          |
| 21  | 7           | 4           | 3           | 1        | Low          |
| 22  | 2           | 9           | 8           | 0        | Medium       |
| 19  | 7           | 7           | 7           | 4        | High         |
| 21  | 7           | 4           | 8           | 4        | High         |
| 19  | 8           | 8           | 8           | 0        | Low          |
| 24  | 5           | 5           | 9           | 2        | Low          |
| 22  | 1           | 5           | 2           | 0        | High         |

---

##  Data Quality Issues
The dataset includes **real-world messiness**:
- **Missing values** → some students skipped questions.  
- **Inconsistent formats** → e.g., “6 hrs” instead of `6`.  
- **Categorical variation** → typos like `"Hgh"` or `"Mediumm"`.  .
- **Class imbalance** → more students rated themselves `"Medium"`.  .
- **Outliers** → e.g., `12 hours of phone usage`.  .

---

##  Potential Use Cases
- **Classification** → Predict productivity level (`Low`, `Medium`, `High`).  
- **Regression** → Convert productivity to numeric scale and predict exact scores.  
- **Clustering** → Group students into lifestyle categories (e.g., *Night Owls*, *Balanced Learners*).  

---

##  Summary
This dataset provides a **practical foundation** for exploring:
- Data cleaning & preprocessing  
- Feature engineering  
- Supervised ML models (classification & regression)  
- Unsupervised learning (clustering)  

---guuled meecaad
