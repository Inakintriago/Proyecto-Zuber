# 🚖 Zuber: Chicago Taxi Data Analysis

## 📝 Context
**Zuber** is a data analysis project focused on understanding the behavior of taxi companies and travel patterns in Chicago during November 2017. The goal is to perform an exploratory data analysis of the taxi companies, trip completion locations, trip durations, and evaluate how weather conditions affect trip durations from the Loop to O'Hare International Airport. This analysis will provide valuable insights on how to optimize taxi services and adapt to weather conditions.

## 🛠️ Tools Used
- **Python**: Data analysis and statistical modeling.
- **Pandas**: Data cleaning, transformation, and analysis.
- **Matplotlib** and **Seaborn**: Visualization of patterns and trends in trips and locations.
- **SciPy**: Statistical tests to validate hypotheses about trip duration under specific weather conditions.
- **Jupyter Notebook**: Interactive and detailed documentation of the analysis workflow.

## 📈 Results Analysis
The project was structured in several phases:

1. **Data Preprocessing**:
   - Importing the datasets `project_sql_result_01.csv` and `project_sql_result_04.csv`.
   - Data verification and cleaning to ensure data integrity.
   - Converting data into appropriate formats and checking data types.

2. **Descriptive Analysis**:
   - Analyzing the taxi companies and the number of trips made on November 15th and 16th, 2017.
   - Identifying the 10 Chicago neighborhoods with the most trip completions.
   - Creating visualizations to show the relationship between taxi companies and the number of trips, as well as the 10 most popular neighborhoods by trip completion.

3. **Hypothesis Testing**:
   - Testing the hypothesis that "The average duration of trips from the Loop to O'Hare International Airport changes on rainy Saturdays."
   - Analyzing trip duration, weather conditions, and dates to determine if there is a significant difference in trips on rainy Saturdays.

4. **Data Visualization**:
   - Bar chart showing the number of trips made by each taxi company.
   - Bar chart with the top 10 Chicago neighborhoods by the number of trip completions.

## 📋 Conclusions
- **Taxi Companies**: Companies with a higher number of trips likely have greater coverage or popularity among users, which may be related to location or service quality.
- **Trip Locations**: The most popular neighborhoods for trip completions are concentrated in downtown Chicago, reflecting the areas with the highest demand for transportation.
- **Impact of Weather Conditions**: The hypothesis test showed whether weather conditions significantly affect trip duration, and the results helped understand how rainy days impact trips from the Loop to O'Hare Airport.
- **Service Optimization**: The results of this analysis can help taxi companies adjust their operations and improve route and schedule planning, especially under unfavorable weather conditions.

This project provides valuable insights into taxi travel patterns in Chicago, which can be used to optimize operational efficiency for transportation companies in the city.
