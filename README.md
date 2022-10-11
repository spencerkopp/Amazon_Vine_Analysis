# Amazon_Vine_Analysis

## Overview
The purpose of this project is to analyze bias towards favorable reviews from Amazon Vine members. The chosen dataset for this project contains watch review information. PySpark is used as park of the ETL process to extract, transform the data, and connect to an AWS RDS instance. The transformed review data is then loaded into pgAdmin. Jupyter Notebook and Pandas dataframes are then used to filter the data further, and analyze bias. 

## Results
These results can also be found in the following image of the Vine_Reviews_Analysis.ipynb file.
- The total number of reviews with over 20 votes and over 50 percent positive votes is 8409.
- The total number of vine reviews with over 20 votes and over 50 percent positive votes is 47.
- The total number of non-vine reviews with over 20 votes and over 50 percent positive votes is 8362.
- The percentage of vine reviews with 5 stars is 32%.
- The percentage of non-vine reviews with 5 stars is 52%.
<img width="586" alt="jupyter" src="https://user-images.githubusercontent.com/107224097/195180437-dc5a08d1-4245-4f35-ae94-35f7152c1dda.PNG">

## Summary 
In conclusion, there doesn't seem to be any positivity bias for reviews in the Vine program when looking at this watch review dataset. The percentage of vine reviews with 5 stars is 32%, while the percentage of non-vine reviews with 5 stars is 52%. Unfortunately, the number of non-vine reviews with over 20 votes and over a 50 percent positive votes rate is much larger than the number of similar vine reviews (8362 vs. 47), which leaves some uncertainty in this analysis. Future analysis could include less strict restrictions on the number of votes or positive vote percentage so that more Vine reviews could be compared. Additionally, further analysis could compare the distribution of review scores for vine and non-vine reviews. 
