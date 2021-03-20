# Amazon_Vine_Analysis

#### Overview
The purpose of this analysis was to determine if there is any bias towards reviews of Kitchen items that were written as part of the Vine program. For this analysis, I will determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

###### Datasets
* [Amazon review links](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
* [Home item reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Kitchen_v1_00.tsv.gz)

#### Results

**Vine Results(Paid Reviews)**
![Vine Results](https://github.com/mcginav/Amazon_Vine_Analysis/blob/main/Vine%20reviews.PNG)

**Non-Vine Results(Unpaid Reviews)**
![Non-Vine Results](https://github.com/mcginav/Amazon_Vine_Analysis/blob/main/non_vine%20reviews.PNG)

###### Vine Reviews Vs Non-vine Reviews
* Number of Vine reviews - **1207** 
* Number of Non-vine reviews - **97839** 

###### 5-star Vine Reviews Vs 5-star Non-vine Reviews
* Number of 5-star Vine reviews - **509**
* Number of 5-star Non-vine reviews - **45858**

###### % of 5-star Vine Reviews Vs % of 5-star Non-vine Reviews
* Percentage of 5-star Vine reviews - **42%**
* Percentage of 5-star Non-Vine reviews - **47%**

#### Summary
###### Is there a Positivity Bias for Reviews in the Vine Program?
* The percentage of 5-star reviews for Vine (paid) reviews was 42%
* The percentage of 5-star reviews for Non-vine (unpaid) reviews was 47%
* Because there were a greater number of positive reviews in the non-vine (unpaid) group, this shows that there is *not* a positivity bias for reviews of Kitchen items in the Vine program.
*For further analysis, we could look at the the 1-star ratings to see if there is any negativity bias for those in the Vine program. 
