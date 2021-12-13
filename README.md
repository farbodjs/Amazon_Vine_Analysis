# Amazon_Vine_Analysis
## Overview of the Project
The main goal of this project is analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we were provided a list of approximately 50 datasets. We picked "Amazon US Furniture Reviews Dataset" and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and then loaded the transformed data into pgAdmin. Next, we used PySpark to determine if there is any bias toward favorable reviews from Vine members in selected dataset.
## Resources
DataSources: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt and https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Furniture_v1_00.tsv.gz
