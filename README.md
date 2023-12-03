# Pizzeria Restaurant Data Insights

In this project, I used a CSV file to create a dataset using Excel and Python. Afterwards, I developed a dashboard for the dataset using PowerBI and used MySQL queries to examine the dashboard output.


The task involves:
* Utilizing a CSV file to generate a dataset.
* Creating the dataset using both Excel and Python.
* remove Data redunduncy
* adding data integrity constraints.
* Developing a dashboard for the dataset with PowerBI.
* Employing MySQL queries to inspect the output of the dashboard.

Tools that I used are:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![mysql](https://img.shields.io/badge/mysql-%23150458.svg?style=for-the-badge&logo=mysql&logoColor=white)
![mysql](https://img.shields.io/badge/quickDB-0062AD.svg?style=for-the-badge&logo=azure-functions&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-F37626.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/excel-217346.svg?style=for-the-badge&logo=microsoft-excel&logoColor=white)


## Dataset

Below is the dataset that I downloaded

| pizza_id | order_id | pizza_name_id | quantity | order_date | order_time | unit_price | total_price | pizza_size | pizza_category | pizza_ingredients                                               | pizza_name                   |
|----------|----------|---------------|----------|------------|------------|------------|-------------|------------|-----------------|-----------------------------------------------------------------|------------------------------|
| 1        | 1        | hawaiian_m    | 1        | 1/1/2015   | 11:38:36   | 13.25      | 13.25       | M          | Classic         | Sliced Ham, Pineapple, Mozzarella Cheese                          | The Hawaiian Pizza           |
| 2        | 2        | classic_dlx_m | 1        | 1/1/2015   | 11:57:40   | 16         | 16          | M          | Classic         | Pepperoni, Mushrooms, Red Onions, Red Peppers, Bacon              | The Classic Deluxe Pizza     |
| 3        | 2        | five_cheese_l | 1        | 1/1/2015   | 11:57:40   | 18.5       | 18.5        | L          | Veggie          | Mozzarella Cheese, Provolone Cheese, Smoked Gouda Cheese, Romano Cheese, Blue Cheese, Garlic | The Five Cheese Pizza         |


I divided this file into multiple files to remove data redundancy and add data integrity.

![Alt Text](https://github.com/Muhammad1umer-tech/Pizzeria-Data-Analytics/blob/main/images/quickdb.JPG?raw=true)


I used the QuickDB tool to re-create the schema of the database.

---
> You can download the DDL file from the repository, to interact with the schema code and open it in mysql workbench locally.
---


I learned snowflake and star schema and managed to implement both concepts in this dataset.

Customers, restaurants, cities, pizza, pizza_size_type, and order_date are the dimension tables, and order is the fact table.

# Purpose and Objectives
This project aims to gain hands-on experience in various aspects of data management and visualization. This includes:

* Dataset Creation: Understanding the process of constructing datasets and addressing issues such as data redundancy.
* Data Integrity: Implementing measures to ensure the accuracy and reliability of data.
* Schema Design: Learning to structure data using snowflake and star schema models and establishing relationships between tables.
* Dashboard Creation: Exploring the development of dashboards for effective data representation and analysis.
* MySQL Concepts: Revisiting MySQL concepts, including schema creation and relational database management.
* Testing Dashboard Output: Utilizing MySQL queries to validate and test the output of the created dashboard.

# Dashboard images
![Alt Text](https://github.com/Muhammad1umer-tech/Pizzeria-Data-Analytics/blob/main/images/dashboard-1.JPG?raw=true)

![Alt Text](https://github.com/Muhammad1umer-tech/Pizzeria-Data-Analytics/blob/main/images/dashboard-2.JPG?raw=true)


This is the dashboard that I created, 
I have included important Key Performance Indicators (KPIs) at the top of the page. Besides KPIs, you will find buttons for filtering data by city, gender, weekdays, and weekends, allowing you to gain insights based on these parameters. I have also implemented features to visualize daily trends and monthly total orders.

Furthermore, I've developed a functionality to identify the popularity of specific pizzas, differentiating which ones are giving more sales and which are not. I also developed which pizza category contributes the most to revenue. You'll find a list of restaurant names with ratings on the right side of the page. I have designed this to enable the selection of a specific restaurant, allowing you to view detailed sales insights for that particular establishment.

Moving on to the second page, it provides comprehensive information on the performance of pizzas. Specifically, it showcases the top 5, middle 5, and bottom 5 pizzas based on sales data.



---
> You can download the file from the repository, to interact with the dataset, dashboard and mysql queries.
---
