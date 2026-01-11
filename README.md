🚀 DataBricks Challenge Learning + Project Journey

Sponsored by Databricks × CodeBasics × Indian Data Club
A 14 day intensive learning sprint followed by a hands on project phase designed to build end to end proficiency in Databricks, Spark, and the Lakehouse ecosystem.

📌 Challenge Structure

Phase 1 Learning & Sharing
⏳ 9th Jan to 22nd Jan | Hosted by Indian Data Club
Hands on learning for 14 days
Deep dive into Databricks concepts
Social sharing and community driven learning

Phase 2 Project Phase
⏳ 24th Jan to 30th Jan | Hosted by CodeBasics
Build a real world end to end project
Apply Lakehouse, Spark, and ETL workflows

📅 Daily Progress Log

⭐ Day 1 Platform Setup & First Steps

📘 Key Learnings
Why Databricks over Pandas and Hadoop
Lakehouse architecture fundamentals
Databricks workspace ecosystem
Real world use cases including Netflix, Shell, and Comcast

🛠️ Tasks Completed
Created Databricks Community Edition account
Explored Workspace, Compute, and Data Explorer
Created first notebook
Executed initial PySpark commands

⭐ Day 2 Apache Spark Fundamentals

📘 Key Learnings
Spark architecture including Driver, Executors, and DAG execution
DataFrames vs RDDs and why DataFrames dominate using Catalyst Optimizer
Lazy evaluation and how Spark optimizes workload execution
Notebook magic commands such as %sql, %python, and %fs
Using col() for safe column handling, filtering, null checks, and transformations

🛠️ Tasks Completed
Uploaded e commerce dataset in xlsx format
Created PySpark DataFrame
Executed core operations
select()
show()
dtypes()
filter()
groupBy()
orderBy()
Used col() for clean transformations and null handling

⭐ Day 2 PySpark Transformations Deep Dive

E-commerce Data Analysis with PySpark
📊 Project Overview
A comprehensive PySpark-based analysis of e-commerce user behavior data, featuring complex data transformations, window functions, and derived feature engineering. This project demonstrates big data processing capabilities for e-commerce analytics.

🚀 Features
Data Loading: Efficiently loads large-scale e-commerce datasets

Complex Joins: Multi-table joins for comprehensive user and product insights

Window Functions: Advanced running totals and time-based aggregations

Feature Engineering: 30+ derived features for behavioral analysis

Analytics: Built-in insights and user segmentation

📁 Dataset Structure
The dataset contains the following columns:

event_time: Timestamp of user activity

event_type: Type of event (view/cart/purchase)

product_id: Unique product identifier

category_id: Product category ID

category_code: Hierarchical category path

brand: Product brand

price: Product price

user_id: Unique user identifier

user_session: Session identifier


1. Data Loading & Preparation

2. Complex Joins
User session summary aggregation

Product performance metrics

User behavior profiling

3. Window Functions
User-level running totals

Product view sequences

Time-based calculations

Session-based aggregations

4. Derived Features
Temporal Features: Hour, day, weekend flags

Behavioral Features: Engagement scores, funnel stages

Business Features: Price categories, conversion rates

Session Features: Intensity metrics, duration analysis
