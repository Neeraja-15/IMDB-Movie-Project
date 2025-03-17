# IMDB-Movie-Project
Hi! This is my beginner project to scrape IMDb’s Top 250 movies page (`https://www.imdb.com/chart/top/`). I wanted to get the titles, years, and ratings of the top movies, clean them up, and save them in CSV files. I did it in Python using Jupyter Notebook.
## What You Need
To run this, you need:
- Python (I used 3.11)
- Libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
Install them with:```bash
pip install requests beautifulsoup4 pandas

###  How to Run It
Open imdb_scraper.ipynb in Jupyter Notebook.
Run each cell one by one (use Shift+Enter).
You’ll get these files:
imdb_raw_data.csv: The movies I scraped.
imdb_raw_sample.csv: First 5 raw movies.
imdb_processed_data.csv: After fixing numbers.
imdb_processed_sample.csv: First 5 fixed movies.
imdb_cleaned_data.csv: Cleaned up data.
imdb_final_data.csv: Final sorted list.

#### What It Does
Step 1: Gets the IMDb webpage and Scrapes movie titles, years, and ratings 
Step 2: Shows a sample of 5 movies.
Step 3: Makes years and ratings into numbers.
Step 4: Shows a sample of the fixed data.
Step 5: Cleans out bad rows.
Step 6: Sorts by rating and saves the final list.

##### Files
imdb_scraper.ipynb: My Jupyter Notebook with all the code and notes.
Project_Report.md: My report about the project.
README.md: This file!

Thanks for checking out my project! I had fun learning how to scrape websites.
