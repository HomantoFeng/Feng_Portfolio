# Feng_Portfolio

# [Project 1: SQL Insights – Exploring 120 Years of Olympic Data](https://github.com/HomantoFeng/SQL-Insights-Exploring-the-120-Years-of-Olympics-Dataset) ![icons8-mysql-logo-48](https://github.com/swaapnaa/SQL-PROJECTS/assets/149737403/95180ab6-019c-4ba1-9165-e9449cb95614)

## Dateset Introduction

This project demonstrates my SQL skills by analyzing the "120 Years of Olympic History" dataset, which spans the modern Olympic Games from Athens 1896 to Rio 2016. The dataset, originally sourced from Sports Reference and hosted on [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results), contains detailed records of over 271,000 athlete-event entries across 15 columns. Each row represents an individual athlete competing in a specific Olympic event, providing a rich foundation for exploring trends, achievements, and patterns in Olympic history.

In this project, I wrote 20 SQL queries to answer key questions about the data, such as: "Which country has won the most medals overall?", "What are the top-performing countries in specific sports or events?" and "How has the participation of women in the Olympics evolved over time?"

By showcasing these queries, I aim to highlight my ability to work with complex datasets, extract meaningful insights, and present results in a structured manner.


## Key questions

- How many olympics games have been held?

- List down all Olympics games held so far.

- Mention the total no of nations who participated in each olympics game?

- Which year saw the highest and lowest no of countries participating in olympics?

- Which nation has participated in all of the olympic games?

- Identify the sport which was played in all summer olympics.

- Which Sports were just played only once in the olympics?

- Fetch the total no of sports played in each olympic games.

- Fetch details of the oldest athletes to win a gold medal.

- Find the Ratio of male and female athletes participated in all olympic games.

- Fetch the top 5 athletes who have won the most gold medals.

- Fetch the top 5 athletes who have won the most medals (gold/silver/bronze).

- Fetch the top 5 most successful countries in olympics. Success is defined by no of medals won.

- List down total gold, silver and broze medals won by each country.

- List down total gold, silver and broze medals won by each country corresponding to each olympic games.

- Identify which country won the most gold, most silver and most bronze medals in each olympic games.

- Identify which country won the most gold, most silver, most bronze medals and the most medals in each olympic games.

- Which countries have never won gold medal but have won silver/bronze medals?

- In which Sport/event, India has won highest medals.

- Break down all olympic games where india won medal for Hockey and how many medals in each olympic games.

## Data Preprocessing

Before loading the dataset into MySQL Workbench, I performed some preprocessing in R (convert_table.rmd) to ensure the data was clean and compatible with SQL operations. This step was necessary to address common data inconsistencies and avoid errors during the import process.

### Key Preprocessing Steps:
1. Handling Missing Values:
   * Replaced NA values in columns with NULL to align with SQL's handling of missing data.
2. Cleaning Text Data:
   * Removed any quotes (e.g., William ""Bill"" Abbott Jr. in the Name column) from columns to ensure smooth data ingestion into SQL tools like MySQL Workbench.

## Data Analysis with SQL: Answering Key Questions

### How It Works:
1. The SQL queries, combined into a single file (SQL_for_Q1-20.sql), were executed in MySQL Workbench using the cleaned dataset prepared during the preprocessing step.
2. Each query is designed to answer a specific question, with results generated directly in MySQL Workbench for analysis and interpretation.

# [Project 2: SQL and Tableau – Insights into Global COVID-19 Case Data](https://github.com/HomantoFeng/COVID_data_explore)![icons8-mysql-logo-48](https://github.com/swaapnaa/SQL-PROJECTS/assets/149737403/95180ab6-019c-4ba1-9165-e9449cb95614) ![Tableau_Software_Logo_Small_resize](https://github.com/user-attachments/assets/e24b9034-a92c-4863-b15f-a75ff70b0895)

## Dateset Introduction
Dataset Introduction
For this project, I utilized the Our World in Data [COVID-19 Dataset](https://docs.owid.io/projects/etl/api/covid/
), a compact compilation of the most relevant COVID-19 indicators collected over the past few years. This dataset provides a comprehensive overview of global COVID-19 trends, including confirmed cases, deaths, vaccination rates, and testing statistics, making it ideal for exploratory data analysis and visualization.

In this project:

- SQL was used to explore and analyze the dataset, extracting meaningful insights and identifying key trends.
- Tableau was employed to visualize the analysis results, creating interactive and informative dashboards for better data interpretation.
By combining the analytical power of SQL with the intuitive visualization capabilities of Tableau, this project demonstrates my ability to handle complex data workflows and present insights effectively.

## Data Preprocessing

Before loading the dataset into MySQL Workbench, I performed some preprocessing in R (convert_table.rmd) using a script named convert_table.rmd to ensure the data was clean and compatible with SQL operations. This step was essential to address common data inconsistencies and avoid errors during the import process.

### Key Preprocessing Steps:
- Handling Missing Values: Replaced NA values in the dataset with NULL to align with SQL's handling of missing data.
- Data Type Conversion: Converted columns with the integer64 type to double to avoid compatibility issues during SQL ingestion.

## SQL Queries for Tableau: Creating Visualization-Ready Data

### How It Works:
1. The SQL queries, consolidated into a single file (COVID_queries.sql), were executed in MySQL Workbench using the cleaned dataset prepared during the preprocessing step.
2. These queries were designed to generate datasets that can be exported as CSV or Excel files, ready for visualization in Tableau.

## COVID-19 Cases Dashboard![COVID_Analysis](https://github.com/user-attachments/assets/d1e2b80c-4707-470f-8af8-c07ddc3b3313)
 
# [Project 3: Analyzing Music Store Database with SQL and ER Models](https://github.com/HomantoFeng/Music_store_data_analysis/tree/main)![icons8-mysql-logo-48](https://github.com/swaapnaa/SQL-PROJECTS/assets/149737403/95180ab6-019c-4ba1-9165-e9449cb95614)

In this project, I wrote five SQL queries to analyze the intricate relationships among [12 datasets](https://github.com/HomantoFeng/Music_store_data_analysis/tree/main/music_store_data) from the Music Store Data Analysis. I also developed an Entity-Relationship (ER) model to visually represent the table structures and their logical interconnections. By combining these SQL queries with the ER model, I demonstrate my ability to handle complex datasets, extract meaningful insights, and present results in a clear and organized way.

SQL queries to answer five questions:
- Q1: Find info of all Rock Music listeners returning emails, first name and last name
- Q2: List top 10 artist name and total track counts of the top 10 rock bands
- Q3: Find all the track names that have a song length longer than the average song length
- Q4: Find out the most popular music genre for each country
- Q5: Find out the customer that spent the most for each country

## Data Preprocessing

Before importing the datasets into MySQL Workbench, I performed preprocessing in Python using the [CSV2Json_convert.ipynb](https://github.com/HomantoFeng/Music_store_data_analysis/blob/main/CSV2Json_convert.ipynb) script. This process involved converting multiple CSV files into JSON format to ensure the data was clean and fully compatible with SQL operations. Special attention was given to handling non-ASCII characters, including the UTF-8 Byte Order Mark (BOM), to avoid potential encoding issues.

## Visualizing Relationships: ER Diagrams for Each Query

![image](https://github.com/user-attachments/assets/b99c64ff-ef3b-4350-95f4-3aeef67a9ed2)

# [Project 4: Python <sup>![python_logo](https://github.com/user-attachments/assets/5dd7e742-c458-4433-a35e-0f1be191dcc4)</sup> Visualization Toolkit – Exploring Data with Sankey in Drinking Water Distribution System (DWDS)](https://github.com/HomantoFeng/Sankey_Diagram_DWDS)
