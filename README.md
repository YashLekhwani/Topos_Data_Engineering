# Topos_Data_Engineering
Steps for Web Scraper:
1. Run the Python Notebook, to scrape the list of top Cities in the United States and scrape important data  like zipcode, city's website and a description of the city. 

2. A dataset called "dataset.csv" is generated. This dataset needs to be cleaned for any kind of data analysis.

3. Run the Python notebook for Data Cleaning, that handles missing values, cleans and parses data scraped from Wikipedia, such that it makes sense for analysis.

4. A dataset called "finaldataset.csv" is generated. This dataset is ready for use. Further cleaning and preprocessinf techniques will be updated soon.

* It was taken care of, that the finaldataset.csv is fit for use for BigQuery since the file loaded from a local data source is less than 10 M and contains fewer than 16,000 rows.
