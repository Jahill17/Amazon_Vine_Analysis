# Amazon_Vine_Analysis
Analysis on Amazon's vine reivew program

## Overview
This is an analysis on Amazon's vine review program using PySpark, AWS, RDS, and PostgreSQL.  I used US sports product reviews from Amazon. This was performed to analyze if it is beneifcial to subscribe to a Vine program if we were to sell similar products on their platform. The vine review program is an incentive model that gifts items to customers based on positive reviews. PySpark was used in order to extract, transform, and load (ETL) the data to a AWS RDS.  The AWS RDS was connected to PostgreSQL server which enabled a query and extraction of the final table. One of the primary objectives was to get familiar with Spark.  Spark uses its in-memory computation to perform analytics for large-scale data processing.

## Resources
- Datasets / Resources:
  - [US Sports Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Software / Technology:
  - Google Colob 
  - AWS SD
  - AWS RDS
  - PostgreSQL

## Steps Performed
- First was to extract the dataset from an AWS S3 (using PySpark) to transform and load it to AWS.
- Subsequently I created the necessary tables in [pgAdmin4](https://github.com/Jahill17/Amazon_Vine_Analysis/blob/main/pgAdmin_TableCreation.png)

## Results

## Summary
