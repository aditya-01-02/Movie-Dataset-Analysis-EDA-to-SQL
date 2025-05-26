# 🎬 EDA to SQL: Movie Dataset Analysis

This project combines **Exploratory Data Analysis (EDA)** with **SQL querying** to explore and analyze movie data from the **TMDB Movie Dataset**. The project demonstrates the transition from pandas-based EDA in Python to executing equivalent SQL queries on a SQLite database.


📁 Project Structure

    📦EDA-to-SQL-Movie-Analysis
    ├── TMDB_movie_dataset_v11.db          # SQLite database of the dataset
    ├── EDA_to_SQL.ipynb                   # EDA using Pandas + SQL execution using sqlite3
    ├── eda_to_sql_queries.ipynb           # Focused SQL queries based on insights from EDA
    └── README.md                          # Project documentation

📌 Dataset

    Source: Originally inspired by [Kaggle's TMDB dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata)


🎯 Objective

The main goal of this project is to perform a comprehensive analysis of the TMDB Movie Dataset by integrating two essential data handling techniques: Exploratory Data Analysis (EDA) using Python and Structured Query Language (SQL) for database querying. This project demonstrates the complete data pipeline, from raw dataset inspection to structured querying and highlights how SQL can be used to complement or replicate insights traditionally gathered through Python-based analysis.

🧪 Tools & Technologies

    **Python 3.x**
    **Pandas / NumPy** – Data manipulation
    **Matplotlib / Seaborn** – Data visualization
    **SQLite / sqlite3** – SQL database and querying
    **Jupyter Notebook** – Interactive exploration

📊 Key Analysis Performed

🔹 In `EDA_to_SQL.ipynb`:

    * Data cleaning and preprocessing using pandas
    * Univariate analysis: distribution of genres, revenues, runtimes
    * Bivariate analysis: budget vs revenue, popularity vs rating
    * Creation of a SQLite database from the cleaned dataset

🔹 In `eda_to_sql_queries.ipynb`:

    * SQL queries replicating EDA logic:
    
      * Top 10 highest-grossing movies
      * Most popular genres by average rating
      * Movie count per year
      * Filtering movies with high ROI, specific genres, or runtime ranges

      
🛠️ How to Run

1. Clone the repository:

   
       git clone https://github.com/your-username/EDA-to-SQL-Movie-Analysis.git
       cd EDA-to-SQL-Movie-Analysis
   

2. Install dependencies:

   
       pip install pandas numpy matplotlib seaborn
   

3. Launch Jupyter Notebook


4. Open and run the notebooks


✅ Project Highlights

    * Demonstrates real-world data-to-database transformation
    * Compares insights gathered via Python and SQL
    * Bridges the gap between data science and database querying


