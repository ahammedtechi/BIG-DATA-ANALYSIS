## DATASET USED
*Air Travel Dataset**: Monthly international passenger counts from 1958 to 1960.

##  OPERATIONS PERFORMED
-  Data Cleaning: Renamed columns, reshaped wide format to long format.
-  Aggregation: 
  - Total passengers per year.
  - Average passengers per month across years.
-  Trend Analysis: Identified seasonal patterns and peak travel months.
-  Data Transformation using Spark DataFrame operations.

## TOOLS AND TECHNOLOGIES
- *Apache PySpark** – For distributed data processing and transformation.
- *Google Colab** – Cloud-based notebook for PySpark setup.


## PROJECT SUMMARY 

This project demonstrates the application of **Apache PySpark** in analyzing a structured air travel dataset in a scalable, efficient manner. PySpark, the Python API for Apache Spark, is widely used in industry for **big data analysis** and **distributed computing**. The dataset used captures monthly international passenger counts between 1958 and 1960 and serves as a great entry point for applying Spark's transformation and aggregation capabilities.


##  KEY STEPS
1. **Data Reshaping**: The original dataset came in a wide format. Using PySpark, it was reshaped into a long format to make it suitable for grouping and summarization.
2. **Column Cleaning**: All column names were standardized to lowercase without spaces.
3. **Aggregation**: 
   - **Total Yearly Passengers**: Grouped by year and calculated sums to understand year-over-year growth.
   - **Monthly Averages**: Grouped by month to find seasonal travel behavior across all years.
4. **Sorting & Filtering**: Peak travel months were identified using `orderBy`, and insights were drawn from the data distributions.
5. **Performance Highlight**: Even with a small dataset, the use of PySpark illustrated how large datasets would benefit from similar transformations in a distributed system.

##  RESULT
Successfully demonstrated large-scale data processing using PySpark.
