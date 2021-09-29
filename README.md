# E-Commerce-Product-and-Customer-Segmentation

## Table of Content

- [Data](#Data)
- [User Segmentation](# User Segmentation)
- [Product&Brand&Category Segmentation](# Product&Brand&Category Segmentation)
- [Sales]


## Data
The original data contans 20692840 rows × 10 columns.
It descries the users' activity for the product from an E-commerence company for 5 months.
Each data point contains the following information:
- **event_time**: The time for user activity. [datetime]
- **event_type**: User's action of the product(add, view, cart purchase). [categorical]
- **product_id**: product ID. [int]
- **category_id**: product's category ID. [int]
- **category_code**: product's category code. [int]
- **brand**: product brand. [string]
- **price**: product price. [double]
- **user_id**: user ID. [int]
- **user_session**: user session ID. [string]
<img width="939" alt="CleanShot 2021-09-29 at 03 01 42@2x" src="https://user-images.githubusercontent.com/81413871/135219053-4817b5f4-5652-4d86-a6e1-1b85279d2a36.png">

## User Segmentation
I conducted the user segmentation by applying the Recency-Frequency-Monetary framework to calculate the R, F, M value for each users.
And I applied K-Menas clusting method to each user's R, F, M values, and segmented the users into four groups:
- At-Risk
- New Customers
- Loyal Customers
- Potential Loyalist
And I analyzed the sales portion of each user groups, and offered retention strategy.

## Product&Brand&Category Segmentation
I condected the segmentation to product&brand&category by calculating the retention rate for each product&brand&category:
View-Purchase(VP): rate of item purchased from viewed
View-Cart(VC): rate of item added from viewed
Cart-Purchase(CP): rate of item added from viewed
Cart-Remove(CR): rate of item removed from addedde

## Sales
I forecast the sales, and calculated the top selling day&time within half year and day.

