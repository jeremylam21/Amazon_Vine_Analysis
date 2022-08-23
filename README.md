# Amazon_Vine_Analysis

## Overview of Vine program
The purpose of this analysis was to import a large dataset of Amazon Video Game reviews to clean, filter, and process via Spark and then write them to our SQL server which runs off of AWS. Additionally, we were to determine the effectiveness of the paid vs. unpaid reviews (Vine program) by finding the total reviews, amount of 5 star reviews, and percentage of 5-star reviews given the review's participation in the Vine program. 

## Results
![Alt](https://github.com/jeremylam21/Amazon_Vine_Analysis/blob/4829cfe039cce5ed30d91be9db32918a8b555248/answers.png)

As seen in above screenshot:
* There are 40,471 non-Vine reviews and 94 Vine reviews
* 15,663 of the non-Vine reviews were 5-stars whereas 48 of the Vine reviews were 5-stars
* The percentage of 5-star non-Vine reviews is approximately 38.7%, whereas the percentage of 5-star Vine revies is approximately 51.06%

## Summary
It seems likely that there is a strong positivity bias for paid reviews when comparing the 5-star percentages. However, this may be due the large discrepancy in sample size (40,471 vs. 94). I believe that after collecting more data on Vine participants it will be important to analyze other descriptive statistics such as the mean star ratings and variance of the reviews. Perhaps conducting tests such as t-tests in order to determine if the difference is statistically significant will be helpful here. 
