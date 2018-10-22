# Cleaning the Airbnb Listings Dataset (2015–2017)
## Data Organisation
This dataset was downloaded from [published Airbnb rates](http://insideairbnb.com/san-francisco/?neighbourhood=&filterEntireHomes=false&filterHighlyAvailable=false&filterRecentReviews=false&filterMultiListings=false) within San Francisco, from 2015 to 2017. The data in it was gathered by Murray Cox's Inside Airbnb, a non-commercial and independent set of tools that collects publicly available data from Airbnb.

The dataset is organised into separate folders according to the year of listing (2015, 2016, and 2017), and then into separate csv files based on the date the data was extracted from Airbnb. For each year, a jupyter notebook is used to clean the data. These notebooks are labeled `Airbnb_xxxx.ipynb`, with "xxxx" equivalent to the year.


## Getting Started
Various Python (version 3.6) modules were used in cleaning the data: 
- [os](https://docs.python.org/3/library/os.html): view the contents of the folder. 
- [re](https://docs.python.org/3/library/re.html): filter through the contents of the folder and select files based on regular expressions (i.e., commonalities in file names).
- [Pandas](http://pandas.pydata.org/pandas-docs/version/0.15/tutorials.html): convert data into dataframes ([Python object organised into rows and columns](https://towardsdatascience.com/a-quick-introduction-to-the-pandas-python-library-f1b678f34673)) that can be subject to data munging.

## Method

## Output