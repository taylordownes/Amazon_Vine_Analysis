# Amazon_Vine_Analysis
## Overview of the analysis
The purpose of this analysis was to analyze Amazon reviews written by members of the paid Amazon Vine program. In this case, we analyzed a grocery datatset and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. we also used PySpark to determine if there was any bias toward favorable reviews from Vine members in the dataset.

## Results

- How many Vine reviews and non-Vine reviews were there?
    - 61 Vine (paid) reviews
    - 28287 non-Vine (unpaid) reviews
    
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - 20 Vine reviews were 5 stars
    - 15689 non-Vine reviews were 5 stars
    
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - 32.79% of Vine reviews were 5 stars
    - 55.46% of non-Vine reviews were 5 stars


## Summary
Based on the results, there does not appear to be any positivity bias for reviews in the Vine program. Since only 32.79% of Vine reviews were 5 stars and there were only 20 Vine reviews out of 28,348, the positivity rate does not appear to be bias based on this statistical analysis. It would be beneficial to analyze other ratings to see if there is any negative bias based on the paid Vine program reviews.
