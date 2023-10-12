# Los Angeles Crime Data Analysis and Time Series Forecasting

 #Introduction

The Los Angeles Crime Data Analysis and Time Series Forecasting code provides insights into crime patterns and victim characteristics in Los Angeles. The code covers various aspects of data analysis, visualization, and forecasting using crime data.

## Code Sections

The code is divided into several sections, each serving a specific purpose.

# Data Preprocessing and Exploratory Data Analysis

In this section, the code prepares the data for analysis and explores various aspects of crime data:

1. Filtering Male and Female Victims:
   - The code separates crime records based on the gender of victims (Male and Female).
   - It calculates and displays the number of male and female victims.

2. Visualizing Crime Trends Over Time:
   - It visualizes the temporal distribution of crimes in Los Angeles, showing how the number of crimes changes over time.
   - Data is aggregated by month, and a line plot is generated to illustrate the trends.

3. Analyzing Crime by Area:
   - The code calculates the number of crimes in each geographical area.
   - A bar chart is created to show the areas with the highest crime rates.

4. Identifying Common Crime Types:
   - The code identifies the most common types of crimes.
   - It generates a bar chart displaying the top 10 crime types.

5. Exploring the Distribution of Victim Ages:
   - Victim ages are visualized using a histogram.
   - The distribution of victim ages is displayed.

6. Analyzing the Distribution of Victim Sex:
   - The code calculates the distribution of victim genders.
   - A pie chart is created to visualize the proportions.

7. Analyzing Victim Descent Categories:
   - The code identifies the top 10 victim descent categories.
   - A bar chart is generated to show the distribution of victim descents.

8. Analyzing Weapons Used in Crimes:
   - The code calculates the frequency of weapon usage in crimes.
   - A bar chart displays the most frequently used weapons.

# Creating a Subset and Displaying on a Map

The code selects a random subset of crime data and displays it on a map using the Folium library.

# Analyzing Victim Characteristics

This section focuses on analyzing victim characteristics, including age, sex, and descent.

# Time Series Forecasting Using ARIMA

In this section, time series forecasting is performed using the ARIMA (AutoRegressive Integrated Moving Average) model:

1. Data Preprocessing:
   - 'DATE OCC' column is converted to datetime and set as the index.
   - Data is aggregated by day.

2. Stationarity Check:
   - The Augmented Dickey-Fuller test is used to check for stationarity in the time series data.

3. Differencing:
   - If the time series is not stationary, differencing is applied.

4. Building the ARIMA Model:
   - ARIMA model with hyperparameters (p, d, q) is created.

5. Making Predictions:
   - Future crime counts are forecasted.

6. Plotting the Forecast:
   - The forecasted crime counts are plotted along with historical data.

## Conclusion

My code provides a comprehensive analysis of Los Angeles crime data, offering insights into crime patterns and victim characteristics. Additionally, it performs time series forecasting to predict future crime counts. This code can serve as a valuable resource for understanding and analyzing crime trends in Los Angeles.
