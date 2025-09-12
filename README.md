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

 ## 🌟 Project Highlights 
 The questions we answered through our Analysis:

Q1: What is the most frequent genre in the dataset?
Ans: Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres. 

Q2: What genres have the highest votes? 
Ans: We have 25.5% of our dataset with popular vote (5528 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movie genres. 

Q3: What movie got the highest popularity? What's its genre? 
Ans: Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Science Fiction. 

Q4: Which year has the most filmed movies? 
Ans: Year 2020 has the highest filming rate in our dataset.

 ## 👨‍💻 Author 
💡 **Mohammad Arish Khan**  
📧 Email: [md.arishk10@gmail.com]  
🌍 GitHub: [https://github.com/Mohammad-Arish-Khan]  

Thank you for reading ⭐ .
 
