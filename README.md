# Amazon Vine Analysis
## Overview of the analysis
This analysis is to analyze the Amazon reviews on pet supplies written by both Vine and non-Vine members and determine if there is any bias toward favorable reviews from Vine members in the dataset.
## Results
Dataset is filtered to rerieve all reviews with equal or over 20 total votes and ratio of helpful votes is equal or greater than 50% of the total votes to get the relatively helpful and popular reviews.
- For filtered reviews, there are 37840 non-Vine reviews and 170 Vine reviews. <br/>
Figure 1. total reviews <br/>
![total_review](/Resources/total_reviews.png) <br/>
- For filtered reviews, there are 20612 non-Vine reviews and 65 Vine reviews giving 5 stars.<br/>
Figure 2. five star reviews <br/>
![fivestar_reviews](/Resources/fivestar_reviews.png) <br/>
- 54.47% of non-Vine reviews are 5 stars. 38.24% of Vine reviews are 5 stars.<br/>
Figure 3. percentage <br/>
![fivestar_perc](/Resources/fivestar_perc.png) <br/>
## Summary
Based on the data of percentage of five star reviews from Vine and non-Vine users, it seems like there is no positivity bias for reviews from pet supply as the Vine reviewers gave less 5 stars then non-Vine reviewers. Further analysis was done for reviews from one to five stars for both paid and unpaid reviewers and result shows below.
Figure 4. percentage_rating <br/>
![allstar_perc](/Resources/summary.png) <br/>
There is higher percentage of five star rating from non-Vine program while there is higher percentage of four star rating from Vine program. For lower ratings, the overall percentages between paid and unpaid users are similar. 
In conclusion, there does not seem to be any positive bias for reviews in the Vine program. Howerever ,it is worth noticing that we have a considerably smaller sample size of Vine users than non-Vine users so it may be not very representative of the paid reviews.
