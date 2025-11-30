# Exploratory Data Analysis on Netflix Movies and TV Shows

This project presents a complete Exploratory Data Analysis (EDA) of the Netflix Movies and TV Shows dataset. The goal is to understand patterns in content type, genres, release trends, audience ratings, and the countries producing content available on the platform.

## Project Objectives
- Load and explore the Netflix dataset  
- Identify trends and patterns using EDA  
- Analyze Movies vs TV Shows distribution  
- Explore top genres  
- Study yearly release trends  
- Analyze ratings distribution  
- Identify top content-producing countries  
- Clean and prepare the data for accurate analysis  
- Visualize results using Python libraries  

## Technologies Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Dataset Information
The dataset used is `netflix_titles.csv`, containing information about over 8,800 Netflix titles.  
Important columns include:  
- type  
- title  
- director  
- cast  
- country  
- date_added  
- release_year  
- rating  
- duration  
- listed_in  
- description

## Workflow Overview

### 1. Data Loading  
- Imported required libraries  
- Loaded dataset using `pd.read_csv()`  
- Previewed data using `df.head()`

### 2. Data Understanding  
- Checked dataset dimensions using `df.shape`  
- Viewed column information with `df.info()`  
- Generated statistical summaries with `df.describe(include='all')`

### 3. Data Cleaning  
- Checked for missing values using `df.isnull().sum()`  
- Removed rows with missing data using `df.dropna()`  
- Converted object columns to appropriate formats where necessary  

### 4. Exploratory Data Analysis  

#### a. Movies vs TV Shows  
Counted and visualized the distribution of content types.

#### b. Top 10 Genres  
Split the multi-genre column and identified the most common genres.

#### c. Release Year Trend  
Analyzed how Netflix content has increased over the years.

#### d. Ratings Distribution  
Examined the frequency of different audience ratings.

#### e. Highest Content-Producing Countries  
Determined which countries contribute the most titles to Netflix.

### 5. Visualizations  
All major insights are supported with visualizations using Matplotlib and Seaborn.

## Key Insights
- Netflix hosts more Movies than TV Shows.  
- Content releases have increased significantly, especially after 2015.  
- Dramas, International Movies, and Documentaries are among the most frequent genres.  
- TV-MA is the most common rating on Netflix.  
- The United States and India are the top content-producing countries.

## Folder Structure
Netflix_EDA_Project/
│── netflix_titles.csv
│── Netflix_EDA_Project.ipynb
│── README.md
│── images/ (optional folder for saved plots)


## Future Enhancements
- Build an interactive dashboard using Plotly or PowerBI  
- Compare Netflix with other OTT platforms such as Amazon Prime or Disney Plus  
- Create content recommendation models  
- Perform sentiment analysis using title descriptions  

## Author
Durwissh  
Beginner Data Analyst and Python Learner
