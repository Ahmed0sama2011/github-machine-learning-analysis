# GitHub Machine Learning Repository Analysis

## Project Overview

This project analyzes Machine Learning repositories collected from the GitHub API.

The project covers the complete data analytics workflow, including data collection, data cleaning, SQL analysis, visualization, and interpretation of results.

## Objectives

- Collect repository data using the GitHub API.
- Clean and prepare the dataset using Python and Pandas.
- Store and analyze the data using SQLite and SQL.
- Create visualizations using Matplotlib.
- Identify patterns and useful insights from the data.
- Manage and publish the project using Git and GitHub.

## Tools & Technologies

- Python
- Pandas
- SQLite
- SQL
- Matplotlib
- Git
- GitHub
- GitHub API
- Google Colab

## Dataset

The dataset contains information about 100 Machine Learning repositories collected using the GitHub Search API.

The analysis includes information such as:

- Repository name
- Repository owner
- Programming language
- Stars
- Forks
- Watchers
- Open issues
- Creation date
- Update date
- License

## Analysis

The project analyzes the repositories using SQL and Python.

The analysis includes:

- Filtering repositories with more than 10,000 stars.
- Searching for repositories containing "Machine" in their names.
- Using AND, OR, and NOT logical operators.
- Finding the Top 10 repositories by stars.
- Calculating the total number of repositories.
- Calculating the average number of stars.
- Grouping repositories by programming language.
- Analyzing repository creation trends over time.

## Key Insights

- The dataset contains 100 Machine Learning repositories with an average of 20,822.23 stars.
- TensorFlow is the most popular repository in the dataset, with 197,330 stars.
- Python is the most common programming language, appearing in 30 repositories.
- Repository creation reached its highest point in 2018, with 18 repositories.
- The selected repositories are concentrated around the 2016–2018 period.

## Project Files

- `github_analysis.ipynb` — Python code, SQL analysis, visualizations, and results.
- `github_projects.csv` — Cleaned repository dataset.
- `github_projects.db` — SQLite database containing the repository data.

## Data Source

The repository data was collected from the GitHub Search API.

The data represents the repositories returned by the selected Machine Learning search query at the time of collection.

