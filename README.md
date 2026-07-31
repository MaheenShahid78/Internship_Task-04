# Major Cities in Pakistan Population Analysis using Pandas and NumPy

## Overview

This task is a simple population analysis of Pakistan's major cities using **Python**, **Pandas**, **NumPy**, and **Matplotlib**. It demonstrates how to load, inspect, analyze, and visualize a real-world dataset containing population statistics of major cities in Pakistan.

The task performs basic data cleaning, statistical analysis, and data visualization to extract meaningful insights from the dataset.

---

## Objectives

* Load the dataset using Pandas
* Inspect the dataset structure
* Check data types
* Detect missing values
* Check duplicate records
* Detect invalid population values
* Generate descriptive statistics
* Calculate province-wise total population
* Count the number of cities in each province
* Calculate the average growth rate for each province
* Calculate the mean population
* Find the five smallest major cities by population
* Identify the province with the highest average growth rate
* Count the number of cities with a population above one million
* Calculate the difference between the mean and median population
* Visualize the analysis using Matplotlib

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib

---

## Dataset

**Dataset Name:** `Major Cities in Pakistan by population.csv`

The dataset contains information about 100 major cities of Pakistan with the following columns:

* Rank
* City
* Population 2017 Census
* Population 1998 Census
* Change
* Province

---

## Project Features

### 1. Load Dataset

Loads the CSV file using Pandas.

### 2. Inspect Dataset

Displays:

* Dataset shape
* Column names
* First five rows
* Data types

### 3. Data Cleaning Checks

Performs the following checks:

* Missing values
* Duplicate rows
* Invalid population values
* Descriptive statistics

### 4. Province-wise Population Analysis

Calculates the total population of each province based on the 2017 Census.

### 5. Cities per Province

Counts the number of major cities in each province.

### 6. Average Growth Rate

Calculates the average population growth rate for every province.

### 7. Mean Population

Calculates the average population of all cities.

### 8. Five Smallest Cities

Finds the five smallest major cities based on the 2017 Census population.

### 9. Highest Average Growth Rate

Identifies the province with the highest average population growth rate.

### 10. Cities Above One Million Population

Calculates how many cities have a population greater than one million.

### 11. Mean vs Median Population

Calculates:

* Mean population
* Median population
* Difference between mean and median

Also explains why the mean is significantly higher than the median.

### 12. Data Visualization

Generates the following charts:

* Bar Chart of the Five Smallest Major Cities
* Bar Chart of Average Growth Rate by Province
* Pie Chart of Cities Above and Below One Million Population
* Bar Chart Comparing Mean and Median Population

---

## Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
```

---

## Project Structure

```
Internship_Task-04/
│── Major Cities in Pakistan by population.csv
│── Task 4.py
│── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/MaheenShahid78/Internship_Task-04.git
```

### Navigate to the project directory

```bash
cd Internship_Task-04
```

### Install the required libraries

```bash
pip install pandas numpy matplotlib
```

### Run the project

```bash
python "Task 4.py"
```

---

## Program Output

The program displays:

* Dataset information
* Missing values report
* Duplicate records
* Invalid population values
* Descriptive statistics
* Province-wise total population
* Number of cities in each province
* Average growth rate by province
* Mean population
* Five smallest major cities
* Province with the highest average growth rate
* Number of cities above one million population
* Mean, median, and their difference
* Graphical visualizations

---

## Concepts Used

* Python
* Pandas DataFrame
* NumPy
* CSV File Handling
* Data Cleaning
* Data Analysis
* Descriptive Statistics
* GroupBy Operations
* Sorting
* Filtering
* Matplotlib Visualization

---

## Author

**Maheen Shahid**

---

## Contact

If you have any questions or suggestions, feel free to reach out.

**Email:** maheenshahid0302@gmail.com
