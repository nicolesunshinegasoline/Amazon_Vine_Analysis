## Purpose

The purpose of this project is to provide an overview analysis of the Vine Program for the SellBy stakeholders.

PySpark was used to perform an ETL process to extract, transform, and load an AWS RDS instance into pgAdmin. Next, PySpark was then used to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results

Paid
- total paid reviews = 170
- total paid 5-star reviews = 65
- percentage of paid five-star reviews against total paid reviews = 38%

Unpaid
- total unpaid reviews = 37,840
- total unpaid 5-star reviews = 20,612
- percentage of unpaid 5-star reviews against total unpaid reviews = 54%

## Summary

Based on this analysis, we see there is no evidence of positivity bias for Vine-member reviews considering that the number of 5-star ratings was 16% less than non-Vine members. However, considering we are working with big data, the sample size used to perform this analysis is relatively small.

It is important to note that, we are only looking at reviews for a specific category (pet products). It would be interesting to see how the percentages vary across categories by picking top categories based on total number of reviews. 