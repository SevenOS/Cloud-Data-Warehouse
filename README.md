# Cloud-Data-Warehouse
Welcome To The Data Warehouses Course In this course, we'll cover the following:  Introduction to Data Warehouses Introduction to the Cloud and AWS Implementing Data Warehouses on AWS

# Introduction To Data Warehouses
Welcome to this lesson on Introduction to Data Warehouses!

# Objective
Students will be able to understand the purpose, architecture, and technologies used in a data warehouse.

# Prerequisites
- Relational database design & SQL
- Programming in Python
- Basic familiarity with dimensional modeling

# Lesson Overview
- What is a Data Warehouse? A Business Perspective
- What is a Data Warehouse? A Technical Perspective
- Dimensional Modeling (Recap)
- DWH Architecture
- OLAP Cubes
- DWH Storage Technology

# What Is A Data Warehouse? A Business Perspective
You are in charge of a retailer’s data infrastructure. Let’s look at some business activities.

- Customers should be able to find goods & make orders
- Inventory Staff should be able to stock, retrieve, and re-order goods
- Delivery Staff should be able to pick up & deliver goods
- HR should be able to assess the performance of sales staff
- Marketing should be able to see the effect of different sales channels
- Management should be able to monitor sales growth

Ask yourself: Can I build a database to support these activities? Are all of the above questions of the same nature?
Let's take a closer look at details that may affect your data infrastructure.

- Retailer has a nation-wide presence → Scale?
- Acquired smaller retailers, brick & mortar shops, online store → Single database? Complexity?
- Has support call center & social media accounts → Tabular data?
- Customers, Inventory Staff and Delivery staff expect the system to be fast & stable → Performance
- HR, Marketing & Sales Reports want a lot information but have not decided yet on everything they need → Clear Requirements?

Ok, maybe one single relational database won’t suffice :)

# Business Process
![Business Process](/Images/Business-Process.png)

# Fact vs Dimension

![Fact-Dimension](/Images/Fact-Dimension.png)

![Fact-Dimension](/Images/Fact-Dimension2.png)
