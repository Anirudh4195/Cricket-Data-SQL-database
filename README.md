Abstract
Cricket is sport enjoyed across India. We have extracted data for the cricket's newest format t20 and fit it in our
conceptual database.
Data Description
The dataset for all three methods has been gathered from the espncricinfo and Kaggle websites. The file from
Kaggle is t20_matches.csv. It contains 26 columns and 6417 entries. Below is the link for the dataset:
https://www.kaggle.com/imrankhan17/t20matches (https://www.kaggle.com/imrankhan17/t20matches)
We have also used the same dataset to create a different file which we have used for API data extraction.

We searched for data for cricket and zeroed in on the t20 format as it is the latest format. For the CSV file and Web
API scraping we have created a schema which show the match ID's and Match description against it. This will give
the viewer an idea about the teams that played the match and where and when the match was played. Additionaly
the viewer will also get an idea about the series which the match was a part of.
We have deleted the columns which contained null entries from the csv file for Audit Validity. We have taken the
match ID's from the CSV file and created another file named india.csv whcih we used in conjuction with API and
put the extracted data in the schema.
We used the espncricinfo site for webscraping and used it extract data of t20 playing india batsmen. We used
BeautifulSoup library for the same.

