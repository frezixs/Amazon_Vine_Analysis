# Amazon_Vine_Analysis

## Overview of the analysis 
The purpose of this project is to analyze data from Amazon Vine program, and see if there are bias related to reviews.
We used PySpark for most of the analysis, and saved our tables in postgres by connecting to an AWS RDS instance. 
I choose the dataset of US reviews for shoes. 

## Results
### How many Vine reviews and non-Vine reviews were there ? 
![image](https://user-images.githubusercontent.com/49871539/129507809-7889cc6b-9688-4763-8c70-f3b5246e34d2.png)
![image](https://user-images.githubusercontent.com/49871539/129507789-15ad8839-fe1f-4211-95bc-3d072c12618a.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars ? 
![image](https://user-images.githubusercontent.com/49871539/129507951-84bcf2a8-d9dd-44aa-9353-1ce47d8b0a9d.png)
![image](https://user-images.githubusercontent.com/49871539/129507977-7e4afbe8-f308-438f-a566-cccbb3a46211.png)

### What percentage of Vine reviews were 5 stars ? What percentage of non-Vine reviews were 5 stars ? 
![image](https://user-images.githubusercontent.com/49871539/129508042-71e923f0-847e-411f-aa72-ce96885f3c8f.png)
![image](https://user-images.githubusercontent.com/49871539/129508079-79215559-d58b-4204-938e-9813c5b7c6af.png)

## Summary 
59.1% of the reviews in the Vine program were 5 star reviews 
53.6% of the reviews in the non-Vine program were 5 star reviews. 
There are positivity bias for both reviews. 

we can also analyse the distribution of the star rating or how many 1 star reviews for the 
Vine program and non-Vine program. 


































