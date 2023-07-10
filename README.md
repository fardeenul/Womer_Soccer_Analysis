# Womer_Soccer_Analysis


### Summary

This R code analyzes the attendance data of the 2019 FIFA Women's World Cup. It performs various data cleaning and manipulation tasks and generates visualizations to explore the attendance patterns at different stadiums during the tournament.

### Key Tasks

1. **Data Loading and Exploration**: The code starts by loading the necessary packages and reading in the raw data from the "datasets/2019_WWCFIFA_summary.csv" file. It examines the dimensions and structure of the data to get an initial understanding.

2. **Data Cleaning**: The code performs data cleaning operations to remove rows with missing values and transform the data into a more usable format. It handles missing values in the "date" and "venue" columns by replacing them with appropriate values.

3. **Data Transformation**: The code separates the "score" and "pks" columns into home and away scores, and home and away penalty kicks, respectively. This step allows for easier analysis of these variables.

4. **Data Visualization**: The code utilizes the `ggplot2` package to create visualizations of the attendance data. It generates a boxplot of attendance by venue, with jittered points overlayed to show individual data points. It also plots the attendance at each stadium over time using a line plot.

5. **Summary Statistics**: The code calculates summary statistics such as the number of games played, minimum attendance, and maximum attendance for each venue. It also identifies and corrects an outlier in the attendance data.

6. **Identifying the Highest Attendance Match**: The code identifies the match with the highest attendance and determines the stadium in which the match was played.

### Usage

To use this code, make sure you have the necessary packages (`readr`, `dplyr`, `tidyr`, and `ggplot2`) installed. You can modify the file path in the code to match the location of the input dataset. Run the code in an R environment or an R script to perform the data analysis and generate visualizations.

Feel free to explore and modify the code to suit your specific requirements and analysis needs.

### License

This code is released under the [MIT License](LICENSE.md).
