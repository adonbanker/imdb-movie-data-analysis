# imdb-movie-data-analysis
#  IMDb Movie Data Analysis Project

This project is part of my learning journey in Data Science. It involves web scraping, data cleaning, exploratory data analysis (EDA), and visualizations using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

##  About Me

I'm an IBDP Grade 12 student passionate about programming, data science, and solving real-world problems using data. This project helped me understand the data science lifecycle — from raw data to useful insights.

---

##  Project Objective

To analyze IMDb movie data and explore patterns in movie ratings, genres, runtimes, and trends over the years.  
Main questions addressed:
- What type of movies get the highest ratings?
- Does runtime affect ratings?
- Which genres consistently perform better?
- How have movie trends changed over the years?

---

##  Dataset Source

-  IMDb Datasets: https://www.imdb.com/interfaces/  
  Used: `title.basics.tsv.gz`, `title.ratings.tsv.gz`

---

##  Technologies Used

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Steps Followed

1. Web Scraping / Download IMDb datasets  
2. Data Cleaning
   - Removed missing values
   - Converted datatypes (e.g., years, runtime)
   - Filtered out invalid/misleading entries (e.g., no votes, extreme durations)

3. Exploratory Data Analysis (EDA) 
   - Distribution of ratings  
   - Runtime vs rating  
   - Ratings by genre  
   - Number of movies released over years

4. Visualizations  
   - Histograms, Boxplots, Countplots, Scatterplots

5. Conclusion 
   - Documentaries and Biographies tend to have higher ratings  
   - Very short or very long movies often have lower ratings  
   - Steady increase in movie production over the 2000s

---

## Example Visualizations

-  Rating distribution  
-  Boxplot of genres vs average ratings  
- Scatter plot of runtime vs rating  
- Countplot of movies released per year

---

## Output File

Final cleaned dataset:  
