# Data Analysis and Visualization with Pandas and Matplotlib

<hr>
This repository contains Python code for analyzing and visualizing survey data using the pandas library for data manipulation and Matplotlib for data visualization.

## Getting Started

Clone this repository to your local machine and ensure you have Python and the required libraries installed. You can
install the necessary libraries using the following command:


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bash Visual</title>
</head>

<body>

    pip install pandas matplotlib

</body>
</html>

## Code Description

### 1. Loading and Cleaning Data

The code starts by loading survey data from the 'survey_results_public.csv' file into a pandas DataFrame. It then cleans
the data, focusing on specific columns ('MainBranch', 'Age', 'Employment', 'Country') and removes rows with missing age
values.

### 2. Data Filtering

The script filters the data based on respondents who are:

<li>Aged between 45 and 54 years old</li>
<li>Employed full-time</li>
<li>Developers by profession</li>
<li>Filtered data is stored in the filtered_data DataFrame.</li>

### 3. Data Sorting

The script sorts the entire dataset based on 'Age' (ascending) and 'Country' (descending), creating a sorted DataFrame.

### 4. Statistical Analysis

The code includes a function extract_age() to clean and extract numerical age values from the 'Age' column. It then
calculates and prints the following statistics for the entire dataset:

<li>Mean Age</li>
<li>Standard Deviation of Age</li>
<li>Median Age</li>
<li>Minimum Age</li>
<li>Maximum Age</li>

## How to Run

Execute the code in a Python environment. Ensure the 'survey_results_public.csv' file is in the same directory as the
script.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bash Visual</title>
</head>

<body>

    python script_name.py

</body>
</html>

## Tags

<li>Python</li>
<li>Pandas</li>
<li>Matplotlib</li>
<li>Data Analysis</li>
<li>Data Visualization</li>
<li>Survey Data</li>