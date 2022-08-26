# Amazon_Vine_Analysis

## Analysis Overview:
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Resources:
Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS


## Results:
## Total Number of Reviews :
- Vine Reviews
<img width="233" alt="image" src="https://user-images.githubusercontent.com/104597335/186811961-c3c5cc17-73ce-4bf9-b9c4-763f4e659a07.png">

- Non Vine Reviews
<img width="293" alt="image" src="https://user-images.githubusercontent.com/104597335/186812035-dc269681-cb7d-4592-8b21-1dcefe5c0590.png">

## Total Number of 5-star Reviews :
- Vine Reviews
<img width="495" alt="image" src="https://user-images.githubusercontent.com/104597335/186812173-1501c7a8-8e63-49fb-911b-98d215189c3b.png">

-  Non Vine Reviews
<img width="510" alt="image" src="https://user-images.githubusercontent.com/104597335/186812246-3f2e2548-b1d9-4799-be9b-8741b1a3b31a.png">

## Percentage of 5-Star Reviews :
- Vine Reviews

<img width="509" alt="image" src="https://user-images.githubusercontent.com/104597335/186812343-fd2c3183-1afb-4a23-9587-d145f139a910.png">


- Non Vine Reviews
<img width="560" alt="image" src="https://user-images.githubusercontent.com/104597335/186812372-c0e27c22-2a46-4773-ac95-edaec4805d1d.png">

 

## Summary:
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.


