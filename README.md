# Amazon_Vine_Analysis

## Purpose of the analysis

The purpose of this analysis is to use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.

In this analysis, we use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We focused on the US reviews for wireless.

## Process

- Read data online into a data frame, and filter out the helpful votes.

![Screen Shot 2021-10-05 at 10 42 27 PM](https://user-images.githubusercontent.com/81284888/136283044-eba81707-6481-4a0f-89fe-a37998b31eed.png)

![Screen Shot 2021-10-05 at 10 42 37 PM](https://user-images.githubusercontent.com/81284888/136283264-a728d7ac-e121-4cc2-be76-3371e48c4925.png)

![Screen Shot 2021-10-05 at 10 42 55 PM](https://user-images.githubusercontent.com/81284888/136283269-ee53dc23-25ca-4f8f-9b84-aa2446c6b049.png)

## Results

### Total number of reviews(Paid and unpaid)

- With a total of 65,581 reviews, 64,968 of them are unpaid reviews, and 613 of them are paid reviews.

![Screen Shot 2021-10-05 at 10 43 33 PM](https://user-images.githubusercontent.com/81284888/136283712-98446a0f-e756-442a-bee2-93d848453386.png)

![Screen Shot 2021-10-05 at 10 43 18 PM](https://user-images.githubusercontent.com/81284888/136283725-2724b45e-bb9c-427d-84f4-ef543eced735.png)

### Total number of five star reviews(Paid and unpaid)
- Within the 65,581 reviews, 30,765 of them are five star reviews. And within the 30,765 five star reviews, 30,543 of them are unpaid and 222 of them are paid.

![Screen Shot 2021-10-05 at 10 43 24 PM](https://user-images.githubusercontent.com/81284888/136283802-d66e1ae4-6a0a-4b78-ae76-c9b82ac8340c.png)

![Screen Shot 2021-10-05 at 10 43 38 PM](https://user-images.githubusercontent.com/81284888/136283840-1ac1cd28-6ae4-47ef-9263-4c4c1c9189a3.png)

### Percentage of five star reviews(paid and unpaid)

- The number then give us a percentage of 47.01% of the unpaid reviews are five star reviews and 36.22% of the paid reviews are five star reviews.

![Screen Shot 2021-10-05 at 10 43 29 PM](https://user-images.githubusercontent.com/81284888/136283902-0666c133-ea2a-454f-914a-bf814e681c95.png)

![Screen Shot 2021-10-05 at 10 43 44 PM](https://user-images.githubusercontent.com/81284888/136283916-ae367766-0001-40ec-8e99-b9c0be68a201.png)

## Summary

From the data showing above, we can say that there is no strong bias for five star reviews from paid Amazon Vine reviewrs since the percentage of paid reviews and unpaid reviews are farely close.
