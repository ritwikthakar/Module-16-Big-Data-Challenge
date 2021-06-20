# Module 16 Big Data Challenge


## Overview of Analysis

Amazon's customers rely on product reviews to make a decision for a product purchase. Amazon makes these datasets available for it's customers. These datasets are quite large and can exceed the capacity of local machines to handle. One dataset alone contains over 1.5 million rows; with over 40 datasets, this can be quite rigorous on the average local computer to process. The first goal for this project will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. The second goal will be to use PySpark or SQL to perform a statistical analysis of selected data.

Review of this data size was made a little easier using the following link

<a href="https://github.com/ritwikthakar/Module-16-Big-Data-Challenge/blob/main/Amazon_Reviews_ETL.ipynb">Amazon_Reviews_ETL.ipynb</a>: Amazon_Reviews

## Results

#### How many Vine reviews and non-Vine reviews were there?
- There is a total of 94 vine reviews for the paid porgram.
- There are 40,471 non-Vine reviews.

#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- There were a total of 48 five star Vine Reviews.
- Non Vine reviews had 15663 reviews which were rated 5 star.

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51.06% of the Vine Reviews were rated 5 Star.
- 38.70% of the Non Vine Reviews were rated 5 Star

Results of the above analysis can be seen using the following link

<a href="https://github.com/ritwikthakar/Module-16-Big-Data-Challenge/blob/main/Vine_Review_Analysis.ipynb">Vine_Review_Analysis.ipynb</a>: Vine_Review_Analysis on Vine Reviews

## Conclusion

We can see a significant gap between the percentage of 5-star reviews in Vine compared to non-Vine reviews which is 51.05% vs 38.70% respectively.
Although the sample size of Vine reviews is very low compared to non vine reviews. It would be recomended to gather a larger sample size to establish more accurate statistical results. Vine reivews for have no helpful vote and 48.95%% . This may indicate that there is a low confidence value from customers to trust the vine reviews. Based on the above argument we could conclued there is a bias present witin the reviews. 

#### Supporting Argument
The mean of the Vine Reviews for star ratings is 4.20 while the standard deviation is 0.98. The mean of the Non Vine Reviews is 3.35 with a standard deviation of 1.64. Based on the mean & standard deviation, we can see that paid subscribers have a larger mean and lower standard deviation for star ratings with a sample size of 94 while Non Vine reviews have a lower mean and a higher standard deviation with a sample size over 40,000. This will prove that paid subscribers have a bias towards the services compared to people who have used the products and reviewed it but have not subscribed.
