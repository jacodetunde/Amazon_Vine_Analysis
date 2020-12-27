# Amazon_Vine_Analysis
## Overview of the Analysis
 The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, I make use of musical instruments datasets.It contains reviews of musical intsruments. I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

# Results
- There are 60 Vine reviews and 14477 non-Vine reviews in the datasets.
![total_vine_review.png](total_vine_review.png) ![total_unpaid.png](total_unpaid.png)
- 34 were 5 stars out of 60 Vine reviews while 8212 were 5 stars for non-Vine reviews.
![vine_5_star.png](vine_5_star.png) ![unpaid_5_star.png]
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
There were 56.67% of 5 star rating reviews of Vine while there were 56.72% of 5 star rating for non-Vine
