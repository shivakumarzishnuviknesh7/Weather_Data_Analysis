

# Weather Data Analysis using Pandas

This project is a comprehensive analysis of a time-series weather dataset. The dataset contains per-hour information about weather conditions at a specific location, recording metrics such as Temperature, Dew Point Temperature, Relative Humidity, Wind Speed, Visibility, Pressure, and Weather Conditions. The analysis is performed using Python's  Pandas library.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Dataset](#dataset)
- [Data Analysis Steps](#data-analysis-steps)
- [Results](#results)


## Project Description

The purpose of this project is to explore and analyze the weather dataset, performing operations such as:
- Displaying basic information and statistics about the data.
- Identifying unique values and counts of specific weather conditions.
- Filtering the data based on various conditions.
- Calculating statistical metrics such as mean, standard deviation, and variance.
- Grouping the data to find minimum and maximum values of weather conditions.

The analysis covers a broad range of data exploration tasks, providing insights into the weather conditions over time.

## Installation

To run this project, you need to have Python installed on your system along with the Pandas library. Follow the steps below to set up the environment:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/weather-data-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd weather-data-analysis
    ```
3. Install the required Python libraries:
    ```bash
    pip install pandas
    ```

## Dataset

The dataset used in this project is a CSV file containing weather information collected hourly. The key attributes in the dataset are:

- **Temperature**
- **Dew Point Temperature**
- **Relative Humidity**
- **Wind Speed (km/h)**
- **Visibility (km)**
- **Pressure (kPa)**
- **Weather Condition**

## Data Analysis Steps

The analysis includes the following steps:

1. **Loading the Data**: Importing the CSV file into a Pandas DataFrame.
2. **Basic Data Exploration**:
    - Viewing the first few rows using `.head()`.
    - Understanding the shape of the data using `.shape`.
    - Listing the columns and their data types with `.columns` and `.dtypes`.
3. **Unique Values and Counts**:
    - Finding unique values using `.unique()` and counting them with `.nunique()`.
    - Counting occurrences of each weather condition with `.value_counts()`.
4. **Handling Missing Data**:
    - Identifying null values using `.isnull().sum()`.
5. **Renaming Columns**:
    - Renaming the "Weather" column to "Weather Condition".
6. **Statistical Calculations**:
    - Calculating mean, standard deviation, and variance of specific columns.
7. **Data Filtering and Grouping**:
    - Filtering the dataset for specific weather conditions.
    - Grouping the data by "Weather Condition" and finding the minimum and maximum values for each group.

## Results

The analysis results provide insights into the weather conditions over the period covered by the dataset. Key findings include:

- The number of occurrences for various weather conditions like "Clear", "Snow", etc.
- The average visibility, standard deviation of pressure, and variance of relative humidity.
- Specific weather conditions based on combinations of different metrics like wind speed and visibility.
