# Syntecxhub_Netflix-Media-Dataset-Exploratory-Data-Analysis-EDA-
This repository contains an exploratory data analysis (EDA) project on a Netflix/media dataset. The analysis focuses on understanding content distribution, trends over time, genre popularity, runtime patterns, and relationships between key variables using statistical analysis and visualizations. The project demonstrates data cleaning, transformation, and visualization techniques commonly used in real-world data analytics workflows.

**Project Objectives**

Clean and prepare raw Netflix/media data for analysis
Explore content trends across decades
Analyze movie and TV show durations
Identify top genres, countries, and release years
Visualize trends and relationships using statistical plots
Generate actionable insights from exploratory analysis

**Dataset Overview**
The dataset contains information on Netflix movies and TV shows, including:
Title, type (Movie / TV Show)
Release year
Duration
Genre
Country
Cast
Date added to Netflix

**Description**
  **Data Cleaning & Preparation**
The following preprocessing steps were performed:
Loaded dataset and inspected structure using:
info(), shape, columns, describe(), nunique()
Checked and handled:
Missing values
Duplicate records
Created a copy of the dataset to preserve the original data
Cleaned text-based columns:
Removed extra quotes and whitespace from
cast, date_added, and description
Converted date-related columns from object type to datetime
Extracted numeric values from duration columns for analysis

**Exploratory Analysis Questions**

1️ What was the most frequent movie duration in the 1990s?
Filtered movies released between 1990–1999
Identified the most common duration using frequency counts

2️ How many short Action movies (< 90 minutes) were released in the 1990s?
Defined short movies as under 90 minutes
Filtered by genre and decade
Counted qualifying records

3️ What was the most frequent movie genre in the 2010s?
Filtered movies released between 2010–2019
Analyzed genre frequency

4️ What is the average duration of movies and TV shows on Netflix?
Calculated average runtime:
Movies (minutes)
TV Shows (number of seasons)

5️ Is there a relationship between release year and movie duration?
Visualized relationship using a scatter plot

6️ What is the trend in TV shows released over the years?
Aggregated TV show counts by year
Visualized trend using a line plot

7️ What are the top 10 countries producing movies?
Exploded country values
Visualized results using a horizontal bar chart

8️ What are the top 10 genres in the industry?
Analyzed genre frequency
Visualized using a horizontal bar chart

9️ What are the top 10 years with the highest content releases?
Ranked years by number of releases
Visualized results using a horizontal bar chart

10 Who were the most frequent cast members in 1990s movies?
Filtered 1990s movies
Exploded cast lists
Visualized using a vertical bar chart

1️1️ How does the average duration of Action and Comedy movies change over time?
Grouped by genre and release year
Visualized trends using line plots

**Visualizations Included**
Line plots for trends over time
Scatter plots for relationship analysis
Horizontal and vertical bar charts for rankings
Distribution and statistical plots
All charts were generated using Python visualization libraries.

**Tools & Libraries Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
