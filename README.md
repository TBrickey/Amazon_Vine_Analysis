# Amazon_Vine_Analysis

## Overview of the analysis
Analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

We’ve selected the wireless dataset. Using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we’ve used PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results
-	There were 613 Vine reviews and 64,968 non-Vine reviews.
-	There were 222 Vine reviews with 5 stars & x non-Vine reviews with 5 stars.
-	36% of Vine reviews were 5 stars & 47% of non-Vine reviews were 5 stars.
## Summary: 
I do not believe there is a positivity bias for reviews in the Vine program because non-Vine reviews were more likely to give a 5-star rating.
To create an additional analysis we could include other data sources, such as apparel and home goods, in the same analysis to see if the percentages proof or disprove our statement. 
