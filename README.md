# Feng_Portfolio
Portfolio for Feng Feng
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
