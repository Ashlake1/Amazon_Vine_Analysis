# Amazon_Vine_Analysis

## Analysis Overview

The Amazon_Vine_Analysis program explores if there is a positivity bias torwards the reviews on US Video Games for Vine members. By using PySpark to extract the dataset and then transform them. I then connected to and created an AWS RDS instance. From there I loaded and transformed the data into PGAdmin. Once the data was loaded and transformed, I then used PySpark to determine bias.


## Results

### Total Number of Vine Reviews
 
#### Vine Reviews

![total_paid_reviews.png](/Resources/total_paid_reviews.png)

#### Non-Vine Reviews

![total_unpaid_reviews.png](/Resources/total_unpaid_reviews.png)


### Total Number of 5 Star Reviews

#### Vine Reviews

![paid_5_star_reviews.png](/Resources/paid_5_star_reviews.png)

#### Non-Vine Reviews

![unpaid_5_star_reviews.png](/Resources/unpaid_5_star_reviews.png)


### Percentage of Five Star Reviews

#### Vine Reviews

![paid_5_star_percentage.png](/Resources/paid_5_star_percentage.png)

#### Non-Vine Reviews

![unpaid_5_star_percentage.png](/Resources/unpaid_5_star_percentage.png)


## Summary
There appears to be a positivity bias based on the results: 
%51 of the reviews in the Vine program were 5 stars while the percentage for the Non-Vine reviews was %39. We can further explore this bias by comparing the average review scores for both Vine and Non-Vine reviews.