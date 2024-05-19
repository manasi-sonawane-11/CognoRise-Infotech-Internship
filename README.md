# README for Data Analysis and Visualization Projects

## Overview
This repository contains three distinct data analysis and visualization projects:
1. Cereal Dataset Analysis
2. Customer Personality Analysis
3. Unemployment in India Analysis

Each project involves data preprocessing, exploratory data analysis (EDA), visualization, and, where relevant, some basic modeling. Below is a detailed explanation of each project.

## Project 1: Cereal Dataset Analysis

### Dataset
The dataset used in this project contains information about different cereal brands, including various nutritional attributes and ratings.

### Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn (OneHotEncoder, MinMaxScaler)

### Steps
1. **Data Loading and Preprocessing**
    - Loaded the dataset using pandas.
    - Dropped the 'name' column as it was not necessary for the analysis.
    - Identified numerical and categorical columns.
    - Checked for missing values and duplicates.
  
2. **Exploratory Data Analysis (EDA)**
    - Generated summary statistics for numerical features.
    - Visualized the count of cereals by manufacturer using a count plot.
    - Grouped data by manufacturer and calculated mean ratings, visualized using a bar plot.
    - Plotted the distribution of ratings per manufacturer using KDE plots.
    - Created a heatmap to show correlations between numerical features.
    - Visualized the distribution of vitamins using a histogram.
    - Created a scatter plot to explore the relationship between calories and protein content.
    - Created a pie chart to show the highest-rated cereal manufacturers.

### Visualizations
- Count plot of cereal manufacturers.
- Bar plot of average ratings per manufacturer.
- KDE plots of rating distributions.
- Correlation heatmap.
- Histogram of vitamin content.
- Scatter plot of calories vs. protein.
- Pie chart of highest-rated manufacturers.

## Project 2: Customer Personality Analysis

### Dataset
The dataset contains customer information and their interactions with a marketing campaign. It includes demographics, purchase history, and response to the campaign.

### Libraries Used
- pandas
- numpy
- seaborn
- matplotlib
- sklearn (KMeans, PCA)
- warnings

### Steps
1. **Data Loading and Preprocessing**
    - Loaded the dataset with a custom delimiter.
    - Handled missing values and duplicates.
    - Filled missing income values with the mean and dropped other missing values.

2. **Exploratory Data Analysis (EDA)**
    - Visualized the distribution of education levels and marital status.
    - Analyzed average income by number of kids and by marital status.
    - Examined correlations between key numerical features.
    - Created histograms for various features.
    - Analyzed customer response and purchases.

3. **Clustering Analysis**
    - Applied PCA for dimensionality reduction.
    - Used the Elbow method to determine the optimal number of clusters.
    - Applied KMeans clustering and visualized the clusters.

### Visualizations
- Bar plots for education level distribution and marital status.
- Bar plot for average income by number of kids at home.
- Distribution plot for income.
- Correlation heatmap.
- Histograms of various features.
- Scatter plot of customer clusters based on PCA.

## Project 3: Unemployment in India Analysis

### Dataset
The dataset contains information about the unemployment rate in India, along with employment and labor participation rates, segmented by region and date.

### Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- plotly (graph_objects, express)
- calendar
- warnings

### Steps
1. **Data Loading and Preprocessing**
    - Loaded the dataset and renamed columns for clarity.
    - Converted date columns to datetime format.
    - Created a new column for month abbreviation.
    - Handled missing values and duplicates.

2. **Exploratory Data Analysis (EDA)**
    - Analyzed unemployment rates and labor participation rates over time.
    - Examined regional differences in unemployment rates.
    - Visualized changes in unemployment before and during the COVID-19 lockdown.

3. **Visualizations**
    - Bar plots for monthly unemployment and labor participation rates.
    - Box plots for unemployment rates by area.
    - Bar plots for average unemployment rates by region.
    - Animated bar plots showing unemployment rates over time by region.
    - Scatter geo plots to visualize regional impact of lockdown on employment.
    - Sunburst charts to show unemployment rate distribution by region and area.
    - Scatter matrix plots to examine relationships between key variables.

### Advanced Analysis
- Compared unemployment rates before and during the COVID-19 lockdown.
- Calculated percentage change in unemployment rates.
- Visualized percentage change in unemployment rates by state after the lockdown.
- Created a correlation heatmap for unemployment-related features.
- Applied ARIMA modeling for forecasting future unemployment rates.

## How to Use This Repository
1. **Clone the Repository**
   ```
   git clone https://github.com/yourusername/your-repository-name.git
   ```
2. **Install Required Libraries**
   Install the necessary Python libraries using pip:
   ```
   pip install numpy pandas matplotlib seaborn scikit-learn plotly statsmodels
   ```
3. **Run the Jupyter Notebooks**
   Navigate to the project directory and run the Jupyter notebooks for each analysis.

## Contributing
Feel free to fork this repository, make your enhancements, and submit a pull request. Contributions are welcome!

## License
This project is licensed under the MIT License.
