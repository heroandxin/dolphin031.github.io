---
layout: post
title: Smart Logistic Warehouse System in Walmart
image: "/posts/Walmart_warehouse.jpg"
tags: [Numpy, Python, Logistic]
---

# Table of contents

- [00. Project Overview](#overview-main)
    - [Context](#overview-context)
    - [Actions](#overview-actions)
    - [Results](#overview-results)
    - [Growth/Next Steps](#overview-growth)
    - [Key Definition](#overview-definition)
- [01. Data Overview](#data-overview)
- [02. Modelling Overview](#modelling-overview)
- [03. Linear Regression](#linreg-title)
- [04. Decision Tree](#regtree-title)
- [05. Random Forest](#rf-title)
- [06. Modelling Summary](#modelling-summary)
- [07. Predicting Missing Loyalty Scores](#modelling-predictions)
- [08. Growth & Next Steps](#growth-next-steps)

___

# 00. Project Overview  <a name="overview-main"></a>

### Context <a name="overview-context"></a>

Recently, Walmart is planning a 21-day countdown promotion for Christmas, and Marlon Brown, a manager of Walmart Company, must make sure that the stored products in each warehouse are proper and sufficient. After consideration, Marlon breaks this project into 2 parts:

1.Selecting products for each warehouse before the promotion starts

2.Simulating cross-warehouse-transshipment solution for possible product shortage problem for a random warehouse after the promotion starts 

##### Working as a consultant, I need to assist Marlon with my analysis to better preparation for the upcoming promotion. 

# My first project
## is all about
### how much
#### I LOVE
##### Python & Coffee!






---
# 01. Data Overview  <a name="data-overview"></a>

In the provided dataset named "Product.csv" as shown below, each column contains the weight and value of each product, and there are totally 50 available product options (Product No.0 - Product No.49) that can be selected into one warehouse.

Every two rows contain all product information in one warehouse, and there are 300 warehouses (Warehouse No.0 - Warehouse No.299) in total.

<br>
![alt text](/img/posts/Product_and_Warehouse_Information.jpg "Product and Warehouse Information Table")

<br>
For each warehouse, there are 4 variables:

1.n - total number of products chosen to be stored in the warehouse

2.C - total weight capacity of the warehouse

3.Vi - the value of available product i 

4.Wi - the weight of available product i 

Specifically, for each warehouse, there is a weight capacity (C) of 650, which means that the total weight of n products that are selected to be stored in a warehouse should be less than or equal to 650. Each available product i has its own weight (Wi) and value (Vi). Besides, the product information for each warehouse is different.

<br>
![alt text](/img/posts/Capacity_Limit.jpg "Capacity Limit For Each Warehouse")

```python

Firstly, I love Python so much, here is some code!

```
my_love_for_python = 0
my_python_knowledge = 0

for day in lifetime:
    my_love_for_python += 1
    my_python_knowledge += 1
```

Just so you really see how much I love Python, here is some code BUT with some colours for keywords & functionality!

```python
my_love_for_python = 0
my_python_knowledge = 0

for day in lifetime:
    my_love_for_python += 1
    my_python_knowledge += 1  
```

Here is an **unordered list** showing some things I love about Python

* For my work
    * Data Analysis
    * Data Visualisation
    * Machine Learning
* For fun
    * Deep Learning
    * Computer Vision
    * Projects about coffee

Here is an _ordered list_ showing some things I love about coffee

1. The smell
    1. Especially in the morning, but also at all times of the day!
2. The taste
3. The fact I can run the 100m in approx. 9 seconds after having 4 cups in quick succession

I love Python & Coffee so much, here is that picture from the top of my project AGAIN, but this time, in the BODY of my project!

![alt text](/img/posts/coffee_python.jpg "Coffee & Python - I love them!")

The above image is just linked to the actual file in my Github, but I could also link to images online, using the URL!

A line break, like this one below - helps me make sense of what I'm reading, especially when I've had so much coffee that my vision goes a little blurry

---

I could also add things to my project like links, tables, quotes, and HTML blocks - but I'm starting to get a cracking headache.  Must be coffee time.
