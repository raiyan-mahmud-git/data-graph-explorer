# data-graph-explorer

# Project Overview

The Data Graph Explorer is a Python-based tool that allows users to load, explore, and visualize data from CSV files. It provides multiple ways to input data and enables users to generate graphs for better understanding and analysis.

# Features

- Load CSV data in three different ways:
  - Upload from local computer (Google Colab)
  - Enter a CSV file URL
  - Use a predefined dataset


- Display:
  - Column headings
  - First two rows of the dataset
- Convert selected columns into NumPy arrays
- Visualize data using:
  - Scatter plots
  - Line graphs
- Perform basic data analysis using correlation
- Explore multiple column combinations interactively


# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colaboratory


# How to Run the Project

Step 1: Open Google Colab

Go to: https://colab.research.google.com

Step 2: Create a New Notebook

Click on "New Notebook"

Step 3: Add the Code

Copy and paste the provided Python script into a single cell.

Step 4: Run the Code

Click the Run button.


# How to Use

1. Choose how to load your CSV file:
   
   - Upload from your computer
   - Enter a CSV URL
   - Use the default dataset

2. The program will:
   
   - Display column names
   - Show the first two rows

3. Select two columns for analysis
   (Make sure they are numeric)

4. Choose a graph type:
   
   - Scatter Plot
   - Line Graph

5. View the graph and interpretation

6. Repeat with different columns if desired


# Example Dataset

You can use this sample CSV file:
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv


# Notes

- Only numeric columns should be selected for plotting
- Invalid or non-numeric data may cause errors
- Upload option works only in Google Colab


# Objective

This project demonstrates:

- Data handling using Pandas
- Numerical processing with NumPy
- Data visualization with Matplotlib
- Basic data interpretation using correlation
