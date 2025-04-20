
#  Data Integration & Insight Extraction  
### Task 2 & 3 – Data Cleaning, Merging, and Business Insight Generation

This notebook project demonstrates hands-on data wrangling techniques for real-world business datasets. It includes thorough cleaning, translation, merging of two datasets (Work Order and Repair Data), and extraction of meaningful insights for operational decision-making.

---

## Contents

-  **Notebook**: `Parvej_task_2_AND_3.ipynb`  
-  **Data File**: `Data for Task 2.xlsx` with two sheets:
  - `Work Order Data`
  - `Repair Data`

---

##  Objectives

###  Task 2: Data Cleaning & Integration
1. **Primary Key Identification**
   - Identified the most reliable unique identifier for safe merging.
   - Addressed challenges like duplicate or null values, and data type mismatches.

2. **Cleaning Operations**
   - Removed duplicates and handled missing data.
   - Standardized columns (e.g., datetime formatting and numeric conversions).
   - Translated multilingual text fields (e.g., “Correction”) using Google Translate API.

3. **Data Merging**
   - Cleaned datasets were joined on a validated primary key to create a consolidated dataset for further analysis.

---

###  Task 3: Insight Generation & Reporting

- Performed aggregation and exploration to understand cost distribution and revenue trends.
- Created summaries and identified key columns important for stakeholders.
- Prepared the final dataset for predictive modeling or dashboard integration.

---

##  Tools & Libraries Used

- **Pandas** and **NumPy** – Data wrangling
- **Googletrans** – Multilingual translation
- **Matplotlib / Seaborn** – *(if visualizations included later)*
- **Excel file handling** – via `pd.read_excel(sheet_name=None)`

---

##  Key Learnings

- **Data Consistency**: Primary keys must be unique and clean before merging.
- **Multilingual Support**: Translating feedback text helps unify global datasets.
- **Business Relevance**: Cost, repair history, and feedback were identified as critical drivers of value.
- **Practical Cleaning Steps**: Included regex-based string processing, datetime coercion, and financial field sanitization.

---

##  Recommendations

- **Data Validation Pipelines**: For future datasets, automated checks for uniqueness and formatting should be implemented.
- **Feedback Text Analysis**: Further exploration with NLP can uncover recurring issues and sentiment.
- **Dashboard Ready**: The cleaned and merged data can now support business intelligence use cases in tools like Power BI or Tableau.

---

##  Author

**Parvej Akhter**  
📧 parvejakhter2303@outlook.com  
🔗 [GitHub](https://github.com/parvej8461) | [Portfolio](https://parvej8461.github.io/)

