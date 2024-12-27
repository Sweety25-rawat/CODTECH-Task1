# Exploratory Data Analysis (EDA) on Trending Movies Dataset

This repository contains the Exploratory Data Analysis (EDA) performed on a **Trending Movies Dataset**. The dataset provides information about trending movies, including popularity, vote averages, and other relevant details.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Steps in EDA](#key-steps-in-eda)
- [Tools & Libraries](#tools--libraries)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Project Overview
This project involves exploring and analyzing a dataset of trending movies to uncover insights, patterns, and correlations between different numerical features. The goal is to understand the distribution of variables, detect outliers, and identify any strong relationships between variables like popularity and vote count.

## Dataset
The dataset used in this analysis contains information about trending movies, such as:
- **original_title**: The title of the movie.
- **release_date**: The release date of the movie.
- **popularity**: Popularity score of the movie.
- **vote_average**: Average rating of the movie.
- **vote_count**: Number of votes the movie has received.
- **media_type**: Type of media (e.g., movie, show).
  
The dataset is stored in `data/trending.csv` and can be used for further analysis or modeling tasks.

## Key Steps in EDA
1. **Data Cleaning**:
   - Removed the irrelevant column (`Unnamed: 0`).
   - Filled missing values in `original_title` and `release_date` with "Unknown".

2. **Exploring Dataset Characteristics**:
   - Displayed the shape and summary of the dataset.
   - Generated a statistical summary of numerical features.

3. **Data Distribution Visualization**:
   - Used histograms to visualize the distributions of numerical columns such as `popularity`, `vote_average`, and `vote_count`.

4. **Correlation Analysis**:
   - Calculated and visualized the correlation matrix of numerical features using a heatmap.
   
5. **Scatter Plot**:
   - Visualized relationships between `popularity` and `vote_count` with a scatter plot, colored by `media_type`.

6. **Outlier Detection**:
   - Created boxplots to check for outliers in the `popularity` variable by `media_type`.

7. **Distribution of Categorical Variables**:
   - Used countplots to visualize the distribution of the `media_type` variable.

8. **Saved Cleaned Data**:
   - The cleaned dataset was saved as `trending_cleaned.csv` for future analysis.

## Tools & Libraries
The following Python libraries were used in this project:
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Matplotlib**: For basic plotting and visualizations.
- **Seaborn**: For advanced visualizations, including heatmaps and scatter plots.

## Results
The analysis generated several key insights:
- Visualized the distribution of numerical features and detected potential outliers.
- Identified correlations between `popularity`, `vote_average`, and `vote_count`.
- Explored the relationship between `popularity` and `vote_count` using scatter plots.
- Examined how `popularity` varies by `media_type` using boxplots.

### Example Plots:
1. **Histogram of Numerical Columns**:
   - Shows the distribution of `popularity`, `vote_average`, and `vote_count`.

2. **Correlation Heatmap**:
   - Highlights the relationships between numerical variables.

3. **Scatter Plot (Popularity vs. Vote Count)**:
   - Visualizes how popularity and vote count relate, colored by `media_type`.

4. **Boxplot (Popularity by Media Type)**:
   - Visualizes outliers in the `popularity` column based on `media_type`.

5. **Countplot (Distribution of Media Types)**:
   - Shows the distribution of the `media_type` variable.

## Conclusion
The EDA process provided a comprehensive understanding of the **Trending Movies Dataset**, identified relationships between variables, and uncovered outliers. The cleaned data is now ready for further analysis or model building.

## Future Work
- Build predictive models using the cleaned data to predict movie popularity or ratings.
- Explore other features, such as release year or genre, to further refine analysis.
- Implement machine learning models to predict trends in movie data.

---

Feel free to explore the analysis and provide feedback or suggestions for improvement.

