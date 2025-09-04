# 📊 Netflix Data Analysis  

This project explores and analyzes the **Netflix dataset** to uncover insights about movies and TV shows available on the platform. The analysis focuses on **data cleaning, exploratory data analysis (EDA), visualization, and feature engineering** to identify trends in ratings, genres, and popularity.  

---

## 🚀 Project Overview  

- Cleaned and preprocessed the dataset (9,827 rows × 9 columns).  
- Converted `Release_Date` into a datetime format and extracted **year values**.  
- Removed irrelevant columns such as `Overview`, `Original_Language`, and `Poster_URL`.  
- Handled missing values, duplicates, and whitespace issues in categorical columns.  
- Identified and treated **outliers in the Popularity column**.  
- Categorized the `Vote_Average` column into 4 bins:  
  - `not_popular`  
  - `below_average`  
  - `average`  
  - `popular`  
- Performed trend analysis and visualization of genres, ratings, and popularity.  

---

## 🛠️ Tech Stack  

- **Python**  
- **Pandas** – Data manipulation and cleaning  
- **Matplotlib / Seaborn** – Data visualization  
- **NumPy** – Numerical computations  
- **Jupyter Notebook** – Interactive analysis environment  

---

## 📂 Dataset  

The dataset consists of:  
- **9,827 rows** and **9 columns**  
- Key columns: `Title`, `Genre`, `Release_Date`, `Popularity`, `Vote_Average`, `Vote_Count`  

---

## 🔍 Key Insights  

- The dataset was relatively tidy with **no NaN or duplicated values**.  
- **Popularity** values contained noticeable outliers.  
- **Genres** contained comma-separated values that were split into categories for deeper analysis.  
- `Vote_Average` was binned into four distinct groups for better interpretability.  
- Trends in release years and genres highlighted how Netflix content has evolved over time.  

---

## 📈 Visualizations  

Some visualizations included in this project:  
- Distribution of `Vote_Average` ratings  
- Genre-wise content distribution  
- Popularity distribution with outliers  
- Trends in content release by year  

---

## 📌 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/Mohammad-Arish-Khan/Netflix-Data-Analysis.git

2. Navigate to the project bar:
   ```bash
   cd Netflix-Data-Analysis

3. Install the Dependencies:
   ```bash
   pip install -r requirements.txt
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Netflix Data Analysis.ipynb"


   ## 👨‍💻 Author  

💡 **Mohammad Arish Khan**  
📧 Email: [md.arishk10@gmail.com]  
🌍 GitHub: [https://github.com/Mohammad-Arish-Khan]  

Thank you for reading ⭐ .
