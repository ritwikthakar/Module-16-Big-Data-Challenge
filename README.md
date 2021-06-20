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
