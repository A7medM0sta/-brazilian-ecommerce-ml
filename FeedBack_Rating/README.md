# Customer Feedback Rating
### Pseudocode
1. Describe the structure of the data.
2. Explain each part of the data.

### Description
The data consists of several columns, each representing different aspects of customer feedback and order information. Here is a breakdown of each part:

1. **Index**: A unique identifier for each row in the dataset.
2. **Order ID**: A unique identifier for each order.
3. **Customer ID**: A unique identifier for each customer.
4. **Rating**: The rating given by the customer, typically on a scale from 1 to 5.
5. **Review Title**: The title of the review (if available).
6. **Review Comment**: The comment left by the customer (if available).
7. **Order Purchase Timestamp**: The timestamp when the order was placed.
8. **Review Creation Timestamp**: The timestamp when the review was created.

### Example Data
```plaintext
0,7bc2406110b926393aa56f80a40eba40,73fc7af87114b39712e6da79b0a377eb,4,NaN,NaN,2018-01-18 00:00:00,2018-01-18 21:46:59
1,80e641a11e56f04c1ad469d5645fdfde,a548910a1c6147796b98fdf73dbeba33,5,NaN,NaN,2018-03-10 00:00:00,2018-03-11 03:05:13
2,228ce5500dc1d8e020d8d1322874b6f0,f9e4b658b201a9f2ecdecbb34bed034b,5,NaN,NaN,2018-02-17 00:00:00,2018-02-18 14:36:24
3,e64fb393e7b32834bb789ff8bb30750e,658677c97b385a9be170737859d3511b,5,NaN,Recebi bem antes do prazo estipulado.,2017-04-21 00:00:00,2017-04-21 22:02:06
4,f7c4243c7fe1938f181bec41a392bdeb,8e6bfb81e283fa7e4f11123a3fb894f1,5,NaN,Parabéns lojas lannister adorei comprar pela I...,2018-03-01 00:00:00,2018-03-02 10:26:53
```
### EDA
1. **Data Cleaning**: Check for missing values and handle them appropriately.
2. **Data Transformation**: Convert timestamps to datetime objects for analysis.
3. **Data Analysis**: Explore the data to identify trends and patterns.
4. **Data Visualization**: Create visualizations to better understand the data.
5. **Statistical Analysis**: Perform statistical tests to draw meaningful conclusions.
6. **Feature Engineering**: Create new features to improve model performance.
6. **Machine Learning**: Build models to predict customer feedback ratings.
