# WeRateDogsTwitterAnalysis
### Overview

The goal of this project is majorly focused on gathering data from different sources and in various 
formats, assess its quality and tidiness, then clean it. Extra data from twitter like retweets and 
favorite counts of each tweet were gathered through querying Twitter APIs with tweet IDs available 
in the dataset provided. The wrangled data was then store, analyzed and visualized to get useful insights 
from it. 

The dataset used for this project is the tweet archive of Twitter user @dog_rates, also known
as WeRateDogs which is a Twitter account that rates people's dogs using humorous comments.

### Data Gathering
This section involves;
1. Using the Requests library to download the tweet image prediction for the dogs tweeted.
2. Using the Tweepy library to query additional data(retweets and favorite counts of each tweets) via the Twitter API

### Data Assessing and Cleaning
In this section, the gathered data was visually and programatically assessed then subsequently cleaned. The 
following are some of the issues that were observed;
- #### Quality issues;
1. Missing values
2. Columns with Wrong datatypes
3. Columns with incorrect values
4. Outliers in a column
5. Rows that contains retweets instaed of actual tweeet
6. Inappopriate column names
7. Duplicate values

- #### Tidiness issues;
9. The dog stages should be fused to one column to make it more tidy
10. Tweet IDs is spread across all datasets and should be merged by the Tweet IDs common to all.

### Data Analysis
Analysis was then carried out on the wrangled and the following questions were posed and answered;
- What dog breed has the most engagement?
- What gender of dogs has more engagement?
- What dog stage is most liked?
- How does the average tweet engagement of the twitter user change over of time?
- What tweet source is most frequent?

### Conclusion

From the analysis, it is gathered that, people engage tweets related to french bulldogs the most and then followed by 
eskimo dogs.  Also female dogs seems to be more liked and prefered to males. The doggo and puppo dog stages have more 
tweet engagement to the rests of the dog stages. The tweets are mostly from Iphone. There is a progressive increase in 
tweet enagagement of @dog_rates's user tweets.

This project was done as part of Udacity's Data Analyst Nanodegree certification.
