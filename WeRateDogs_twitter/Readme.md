# Wrangling and Analyzing WeRateDogs twitter Data

## Project Details

Data wrangling, which consists of:

* Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).

* Assessing data.

* Cleaning data.

* Storing, analyzing, and visualizing your wrangled data

* Reporting on 1) data wrangling efforts and 2) data analyses and visualizations

### Gathering Data

Gather each of the three pieces of data as described below in a Jupyter Notebook titled wrangle_act.ipynb:

1. The WeRateDogs Twitter archive. This file is downloaded manually: twitter_archive_enhanced.csv.

2. The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network. This file (image_predictions.tsv) 
is hosted on Udacity's servers and was downloaded programmatically using the Requests library and the following
URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv

3. Each tweet's retweet count and favorite ("like") count at minimum, and any additional data you find interesting. Using the tweet IDs in the WeRateDogs Twitter archive, query 
the Twitter API for each tweet's JSON data using Python's Tweepy library and store each tweet's entire set of JSON data in a file called tweet_json.txt file. Each tweet's JSON 
data should be written to its own line. Then read this .txt file line by line into a pandas DataFrame with (at minimum) tweet ID, retweet count, and favorite count. Note: do not 
include your Twitter API keys, secrets, and tokens in your project submission.

### Assessing Data

After gathering each of the above pieces of data, they are assessed visually and programmatically for quality and tidiness issues. At least eight (8) quality issues and 
two (2) tidiness issues were detected and documented in the wrangle_act.ipynb Jupyter Notebook. 

### Cleaning Data

Each of the issues that were documented while assessing are cleaned. This was performed in wrangle_act.ipynb as well. The result was a high quality and tidy master pandas 
DataFrame (or DataFrames, if appropriate). 

### Storing, Analyzing, and Visualizion Data for this Project

The clean DataFrame(s) was stored in a CSV file named twitter_archive_master.csv

The wrangled data was analyzed and visualized in the wrangle_act.ipynb Jupyter Notebook. At least three (3) insights and one (1) visualization were produced.

### Reporting for the project

The wrangle_report.html report was created to briefly describe my wrangling efforts. 

The act_report.html report was created to communicate the insights and display the visualization(s) produced from my wrangled data. 

