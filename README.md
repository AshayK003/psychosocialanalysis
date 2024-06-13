# Psychosocial-Health Analysis

## Project Overview

This project involves the analysis of a real-world Kaggle dataset that focuses on psychosocial health. The aim is to explore, clean, and visualize the data to uncover meaningful insights that can inform strategies for addressing various psychosocial issues.

## Dataset

The dataset used in this project is sourced from Kaggle and contains information on individuals' psychosocial health, including their age, gender, problem descriptions, problem summaries, problem categories, and psychological categories.

## File Descriptions

- `Psychosocial_Health_Analysis.csv`: The raw dataset used for analysis.
- `Psychosocial_Health_Analysis_Cleaned.csv`: The cleaned version of the dataset.
- `Psychosocial Health analysis final.ipynb`: Jupyter Notebook containing the code for data cleaning and generating visualizations.
- `README.md`: This file, describing the project.

## Data Cleaning

The data cleaning process includes:

1. **Loading the Data**: Reading the CSV file into a DataFrame.
2. **Checking for Missing Values**: Identifying and handling any missing values.
3. **Checking for Duplicates**: Removing duplicate rows.
4. **Correcting Data Types**: Ensuring all columns have the correct data types.
5. **Normalizing Text Data**: Cleaning and standardizing text data by converting to lowercase and removing punctuation.
6. **Handling Outliers**: Identifying and handling outliers in the numerical data (Age).

## Visualizations

The project includes the following visualizations to effectively communicate insights from the dataset:

1. **Age Distribution (Histogram)**: Shows the distribution of ages.
2. **Gender Distribution (Pie Chart/Bar Chart)**: Displays the proportion of males and females.
3. **Problem Categories Distribution (Bar Chart)**: Shows the frequency of different problem categories.
4. **Psychological Categories Distribution (Bar Chart)**: Displays the distribution of different psychological categories.
5. **Age vs. Problem Category (Box Plot)**: Compares age distribution across different problem categories.
6. **Problem Category by Gender (Stacked Bar Chart)**: Shows the distribution of problem categories within each gender.
7. **Problem Description Word Cloud**: Visual representation of the most common words and themes in the problem descriptions.
8. **Problem Category vs. Psychological Category (Heatmap)**: Displays the relationship between problem categories and psychological categories.
9. **Problem Category Trend by Age Group (Line Chart)**: Illustrates how certain problems vary with age.

## Requirements

To run the notebooks and reproduce the analysis, you need the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- wordcloud

You can install the required packages using pip:
```bash
pip install pandas numpy matplotlib seaborn wordcloud
```

## How to Use

1. Clone this repository:
    ```bash
    git clone https://github.com/your_username/psychosocial_health_analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd psychosocial_health_analysis
    ```
3. Run the Jupyter Notebook to see the data cleaning and visualizations:
    ```bash
    jupyter notebook Psychosocial Health analysis final.ipynb
    ```
