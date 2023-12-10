# webscrape-challenge
Completed by Daniel Stephens

## About this project
This is a two part project demonstarting use of Beautiful Soup to scrape data from websites and storing scraped data into Pandas dataframes for analysis and data visualization. 

### part_1_mars_news.ipynb
The notebook can be accessed in the root folder in this repo

This application scrapes a webpage that contains a list of articles, which include titles and preview text for each article. Once the data is scraped and stored in a Beautiful Soup object, a for loop is used to store each article title and preview text into a dictionary.

### part_2_mars_weather.ipynp
The notebook can be accessed in the root folder in this repo

This application scrapes a webpage with a table containing Mars weather data and stores it in a Beautiful Soup object. A for loop is then used to store each row of data in a list of lists, which is then converted to a Pandas dataframe. Finally some light weight analysis of the data is completed and Matplotlib is used to create data visualizations. 

#### Running the app

To run the app: 
* Each notebook can be downloaded and ran independently.
* Splinter and Chromedriver are required to run each notebook. Instructions for installing Splinter and Chromedriver can be found here: https://splinter.readthedocs.io/en/latest/install/install.html
