# Netflix Movies & TV Shows Data Analysis

This project analyzes Netflix’s Movies and TV Shows dataset to uncover trends, popular genres, top producing countries, and yearly content distribution.

---

## Dataset

- **Source:** [Kaggle - Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)  
- **File:** `netflix_titles.csv`  
- **Format:** CSV  
- **Columns include:** show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

---

## Tools & Libraries

- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **IDE:** Jupyter Notebook  

---

## Steps Followed

1. **Load Dataset:** Loaded CSV into a pandas DataFrame  
2. **Clean Data:**  
   - Removed duplicates  
   - Filled missing values in `country`, `director`, `cast` columns with `Unknown`  
3. **Explore Data:** Checked shape, column names, and value counts  
4. **Visualize & Analyze:**  
   - Movies vs TV Shows count  
   - Year-wise content releases  
   - Most popular genres  
   - Top countries producing content  

---

## Insights

1. Netflix has more Movies (4266) than TV Shows (1968).  
2. 2019 and 2020 had the highest number of content releases.  
3. Most popular genres: Drama, Comedy, and Action.  
4. Top content producing countries: USA, India, and UK.  

---

## How to Run the Project

1. Download `netflix_titles.csv` from Kaggle.  
2. Place the CSV file in the project folder.  
3. Open the Jupyter Notebook in this repo.  
4. Install required libraries if not already installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
