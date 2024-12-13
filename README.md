# Scrape-IMDB-movie-rating-and-details-using-Python-
IMDB Top 250 Movies Scraper
This project is a web scraper built in Python to extract data about the IMDB Top 250 Movies. It uses the BeautifulSoup library to parse HTML content, collects information such as rankings, titles, years, ratings, and star casts, and saves it in a structured CSV file.

Features
Fetches data from the IMDB Top 250 Movies chart.
Extracts:
Movie Rank
Title
Year of Release
IMDB Rating
Star Cast
Saves the scraped data to a CSV file for easy analysis.
Technologies Used
Python 3: Main programming language.
BeautifulSoup: For parsing and navigating the HTML.
Pandas: For data handling and saving to CSV.
Requests: For making HTTP requests.
The script generates a file called imdb_top_250_movies.csv, which contains:

Rank of the movie
Movie title
Year of release
IMDB rating
Star cast details
