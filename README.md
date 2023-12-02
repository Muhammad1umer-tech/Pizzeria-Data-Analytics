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
