# NY High School Data Analysis

## Overview
Every year, American high school students take the SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. The SAT consists of three sections: reading, math, and writing, each with a maximum score of 800 points. These tests are crucial for students and colleges as they significantly influence the admissions process.

Analyzing the performance of schools is important for various stakeholders, including policy and education professionals, researchers, government officials, and parents deciding which school their children should attend.

In this project, we analyze data on SAT scores across public schools in New York City using SQL for Exploratory Data Analysis (EDA) on Jupyter Notebook.

## Dataset
The dataset used in this analysis contains information about SAT scores from public schools in New York City. The database comprises a single table named `schools`.

### Table: schools
| Column          | Type     | Description                                     |
|-----------------|----------|-------------------------------------------------|
| school_name     | varchar  | Name of the school                              |
| borough         | varchar  | Borough where the school is located             |
| building_code   | varchar  | Code for the building                           |
| average_math    | int      | Average math score for SATs                     |
| average_reading | int      | Average reading score for SATs                  |
| average_writing | int      | Average writing score for SATs                  |
| percent_tested  | numeric  | Percentage of students who completed the SATs   |

## Project Structure
- `NY_High_School_Data_Analysis.ipynb`: The Jupyter Notebook containing the SQL queries and analysis performed on the dataset.
- 
## Analysis
In the Jupyter Notebook, I performed EDA using SQL and asked some questions to draw insights. The questions focused on identifying missing values, counting unique school locations, finding top and bottom performers in various SAT sections, and comparing performance across different boroughs.
