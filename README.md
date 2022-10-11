# Amazon_Vine_Analysis
Using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Background:
### Video Game reviews was selected from Amazon's review site in order to examine the relationship between paid reviews and unpaid reviews. Paid reviews are reviews by members of the VINE program. Amazon Vine is an invitation-only program which selects the most insightful reviewers in the Amazon store to serve as Vine Voices. Vine Voices have the unique opportunity to order items free of charge and share their product experiences with Amazon customers to help them make informed buying decisions.

## Findings:
- The percentage of 5star ratings is not the same when comparing paid (vine reviews) to unpaid (not_vine reviews)
- Percentage_5star_vine = 51%
- Percentage_5star_not_vine = 38%
- There is reason to believe that the percentage of 5star ratings is directly tied to wether the reiewer is paid(vine) or unpaid(not_vine).
![Screen Shot 2022-10-11 at 6 09 27 PM](https://user-images.githubusercontent.com/105253626/195207640-8b2ece79-af5b-461b-a20d-1fb565eb162e.png)

## Summary:
It seems for the video game reviews case they do get more positive reviews for being paid on the vine program.

