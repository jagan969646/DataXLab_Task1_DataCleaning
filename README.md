# 🧹 DataXLab Internship – Task 1: Data Cleaning and Preprocessing

### 🎯 Objective
This task focuses on cleaning and preparing a raw dataset by handling missing values, duplicates, inconsistent formatting, and incorrect data types using **Python (Pandas)**.

---

### 📊 Dataset Used
**Mall Customer Segmentation Data**  
Source: [Kaggle - Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

### 🧠 Steps Performed
1. **Loaded Dataset** – Imported data using Pandas and viewed structure.  
2. **Checked Missing Values** – Used `isnull().sum()` to identify nulls.  
3. **Handled Missing Data** – Filled missing `Age` values using column mean.  
4. **Removed Duplicates** – Applied `drop_duplicates()` to eliminate duplicate rows.  
5. **Standardized Text Values** – Converted `Gender` column to lowercase and stripped whitespace.  
6. **Renamed Columns** – Replaced spaces with underscores and converted all to lowercase.  
7. **Converted Data Types** – Ensured numeric columns have correct types (`int` / `float`).  
8. **Verified Final Data** – Checked structure, missing values, and summary stats.  
9. **Exported Clean Dataset** – Saved as `cleaned_dataset.csv`.

---

### 🧰 Tools & Libraries Used
- **Python 3**
- **Pandas**
- **Jupyter Notebook**

---

### 📁 Files Included
| File | Description |
|------|--------------|
| `Mall_Customers.csv` | Raw dataset (before cleaning) |
| `Data_Analyst_Internship_Task1.ipynb` | Jupyter Notebook with full cleaning process |
| `cleaned_dataset.csv` | Final cleaned dataset ready for analysis |
| `README.md` | Documentation summary for GitHub submission |

---

### 📈 Key Learnings
- Identified and treated missing values.  
- Removed duplicates and standardized data formats.  
- Practiced data type conversions and column renaming.  
- Learned to prepare clean, structured data for analysis or visualization.

---

### 🧑‍💻 Author
**Jagadeesh.N**  
Data Analyst Intern – *DataXLab*  
📧 Email: jagadeesh.n10d@gmail.com 
🌐 GitHub: https://github.com/jagan969646
