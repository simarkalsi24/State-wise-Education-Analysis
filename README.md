# 📊 Enrollment Data Analysis (2021)

## 📌 Project Overview  
This project explores **enrollment data** from 2021 using **Python and Pandas**. The analysis focuses on:  
- Understanding dataset structure  
- Identifying missing values  
- Summarizing categorical distributions  
- Preparing the data for further modeling  

---

## 🛠️ Tools & Libraries  
- Python  
- Pandas  
- Jupyter Notebook  

---

## 📂 Dataset  
- **File**: `Enrolment_2021.xlsx` (not uploaded for privacy reasons)  
- Includes attributes such as:  
  - `statename`, `state_code`  
  - `father_name`, `clustername`  
  - and other enrollment-related fields  

---

## 🔍 Workflow  

1. **Data Import**  
   - Loaded Excel data into a Pandas DataFrame.  

2. **Exploration**  
   - Checked shape, first few rows, and column names.  

3. **Distribution Analysis**  
   - Used `value_counts()` to see how states and other columns are distributed.  

4. **Missing Value Analysis**  
   - Checked for missing values.  
   - Calculated percentage of null values per column.  
   - Flagged columns with more than **50% missing data**.  

5. **Deep Dive**  
   - Examined specific columns like `father_name` and `clustername` for missing or unusual data.  

---

## 📈 Key Insights  
- Several columns (e.g., `father_name`, `clustername`) had **high null values**.  
- Some categorical fields were **imbalanced**.  
- Dataset needs **cleaning and preprocessing** before deeper analysis.  
