# automated-home-web-scraper
Developed an automated web scraper that takes from gumtree in joburg and compares prices in notebook

It first scrapes from gumtree listings
Works through nested pages
Cleans data automatically and represents in different graphs and explains trends 


Note on Clustering: The K-Means clustering was implemented manually from scratch (without using scikit-learn's built-in KMeans). While the manual implementation is present in the code to demonstrate the underlying math, the live scraped data contained outliers that caused centroid instability, so the final output prioritizes the cleaned CSV
