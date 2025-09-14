





# 📊 Netflix Data Analysis Using Python

<img width="944" height="320" alt="{ED2F05E5-8705-4D62-BDB5-C567C7382D05}" src="https://github.com/user-attachments/assets/2864490d-9d11-45aa-b6b3-fc45896192b8" />




---

## 🎯 About
This project explores the **Netflix Movies & TV Shows Dataset** to uncover insights about Netflix’s content catalog.  
The goal is to practice **data cleaning, exploratory data analysis (EDA), and visualization using Python**.  

Some business questions addressed:
- How has Netflix’s content changed over the years?
- Which countries and genres dominate Netflix’s catalog?
- Are there more movies or TV shows being added recently?
- What is the distribution of ratings and durations?

---

## 📂 Dataset
- **Source:** [Kaggle – Netflix Movies and TV Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows)
- **File:** `netflix_titles.csv`
- **Key Columns:**
  - `show_id` → Unique identifier  
  - `type` → Movie / TV Show  
  - `title` → Title of the content  
  - `director` → Director(s) of the content  
  - `cast` → Main actors/actresses  
  - `country` → Country of production  
  - `date_added` → Date added to Netflix  
  - `release_year` → Release year  
  - `rating` → Content rating (TV-MA, PG, etc.)  
  - `duration` → Duration (minutes for movies, seasons for TV shows)  
  - `listed_in` → Genres/categories  
  - `description` → Short summary  

---

## 🧹 Data Cleaning & EDA
Steps performed:
- Handled **missing values** in `director`, `cast`, and `country`.
- Standardized `date_added` column to datetime format.
- Converted **duration** to separate numeric columns (`minutes` for movies, `seasons` for TV shows).
- Split multiple `listed_in` (genres) into individual tags.
- Removed duplicates and irrelevant whitespaces.

---


## 📈 Visualizations
Here is sample output from the analysis:

 <img width="747" height="438" alt="{4BA2ABD7-E5B4-4A13-9399-B96A915F4460}" src="https://github.com/user-attachments/assets/f1b7714d-1ced-4403-899c-ff6a437d5eca" />


