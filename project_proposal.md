Name: Raed Altuwaijri\
Email / Github: AltuwaijriRaed@gmail.com


# Project Proposal

## Background:

* Company info:\
we are an online shoping store our goal is to maximize the profits and minimize the costs. 
<!-- we are a Dates Fruit company called Tamrifier (Tamr + classifier) for Date fruit classification using image processing. -->
<!-- we are an advertising company caller AdSpam our goal is to make websites visitors live harder by maximizing there chance to click on an Ad (clickbait) -->
* Problem or opportunity:\
predict the items the customers will buy again, this will help us to know the quantity to provide for each product and where to store it to minimize the logistic costs, and to recommend the apropriate product for each customer to increase the sales.


## Data Description:
data obtained from [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis/data)

### order_products dataset:

| Field Name        | Description                                                          |
|-------------------|----------------------------------------------------------------------|
| order_id          | unique identifier for each order                                     |
| product_id        | unique identifier for each product                                   |
| add_to_cart_order | the sequence in which they have been added to the cart in that order |

### orders dataset

| Field Name             | Description                                                    |
|------------------------|----------------------------------------------------------------|
| order_id               | unique identifier for each order                               |
| user_id                | unique identifier for each user                                |
| order_number           | user order number                                              |
| order_dow              | order day of week                                              |
| order_hour_of_day      | order hour of day                                              |
| days_since_prior_order | days between this order and the prior                          |

### products

| Field Name        | Description                                                    |
|-------------------|----------------------------------------------------------------|
| product_id        | unique identifier for each product                             |
| product_name      | the name of product                                            |
| aisle_id          | unique identifier for each aisle                               |
| department_id     | unique identifier for each department                          |

the total number or rows is 262,203

## Tools:
* Technologies: Python, Jupyter notebook
* Libraries: Numpy, Pandas, plotly, Seaborn, Sklearn, imblearn, xgboost, matplotlib, multiprocessing
