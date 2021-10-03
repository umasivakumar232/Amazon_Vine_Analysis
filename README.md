# Amazon_Vine_Analysis

## Project Overview

In this project we have been tasked to analyzing Amazon reviews written by members of the **Amazon Vine program**. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products by a few choosen **Vine Voices**.  The purpose of this project is to to check if there is a **bias** towards **favorable reviews** from vine members.  

## What is Amazon Vine?

**Amazon Vine** is a program where Amazon invites the most trusted reviewers on Amazon to post opinions about new and pre-release items to help their fellow customers make informed purchase decisions. Amazon invites customers to become Vine Voices based on their **reviewer rank**, which is a reflection of the **quality and helpfulness** of their reviews as judged by other Amazon customers. Amazon provides Vine members with free products that have been submitted to the program by participating vendors. Vendors do not have direct access to vine reviewers. Vine reviews are the independent opinions of the Vine Voices. The vendor cannot influence, modify or edit the review. Voices are not paid to participate in the program and write reviews and they are free to give their unbaised opinion on the products they review. A Vine review is identified with the green stripe Customer review from the Amazon Vine Program

## Our Analysis
For the purpose of this analysis we have picked up **Pet Products** as the choosen category from the available list of 50 databases. (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz)

## Resources

**PySpark** was used to perform the ETL process to extract the dataset, transform the data connect to an AWS RDS instance, and load the transformed data into pgAdmin 

**Apache Spark (Spark)**  a unified analytics engine for large-scale data processing - The Spark API supports many languages including python and SQL

**Google Colab** A cloud based Google-hosted notebooks

**PostgreSQL & PGAdmin4**

**Amazon Web Services** 

## Results of our Analysis

 ### Analysis of the vine reviews - Total reviews, number of 5Star reviews and % of 5Star reviews
 
 <img width="561" alt="vine_review" src="https://user-images.githubusercontent.com/85518330/135773409-b7c6eaca-f507-471c-b8ac-8d9407f699c0.png">
 
 ### Analysis of the non vine reviews - Total reviews, number of 5Star reviews and % of 5Star reviews
 
<img width="623" alt="nonvine_reviews" src="https://user-images.githubusercontent.com/85518330/135773426-ce727d0f-d2c9-489d-a22b-08790ccd4846.png">

 Vine Voices reviewed the pet category 170 times and only **38%** of those reviews were 5Star reviews
 
 Non Vine reviews in the pet category were 37840 and **54%** of those were 5Star reviews
 
 So evidently the Vine reviews **don't** have a **bias** towards favorable reviews and seem like they are unbaised atleast for the category chosen 
 
 ## Additional Analysis
 

 



 
  



