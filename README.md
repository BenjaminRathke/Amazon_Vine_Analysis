# Big Data

## Overview of the Analysis
The Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The purpose of the analysis is to determine whether or not members of The Vine program have a higher likelihood of writing a five-star review; important information to have to determine the veracity of the Vine five-star reviews.  First, the ETL process is executed on the raw data set provided by Amazon, then an analysis is performed using Python/PySpark.

## Results
![Vine Participant Data Example](YVine.PNG)  
*Vine Participant Example*  

![Non-Vine Participant Data Example](NVine.PNG)  
*Non-Vine Participant Data Example*  

* How many Vine reviews and non-Vine reviews were there?  
** Total number of reviews in the paid Vine program: 94  
** Total number of reviews in the unpaid program: 40471  

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?  
** Total number of 5-star reviews in the paid Vine program: 48
** Total number of 5-star reviews in the unpaid program: 15663

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?  
** Percentage of 5-star reviews in the paid Vine program:  51.06 %
** Percentage of 5-star reviews in the unpaid program:  38.7 %

### Summary  

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

