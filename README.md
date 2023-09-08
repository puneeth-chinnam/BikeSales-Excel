# Bike Purchase Analysis Dashboard

## Find the Dashboard in the "Dashboard" sheet in Excel file.

## Dataset

This project analyzes a bike purchase dataset with 1000 records and the following attributes:

```
- Customer income 
- Age
- Gender
- Education level
- Children
- Home ownership
- Number of cars owned  
- Marital status
- Number of children
- Commute distance to work
- Region
- Purchase history
```

## Data Cleaning and Preparation

The data preprocessing followed these steps:

1. Removed duplicate rows using "remove duplicates" function

2. Renamed columns:

    - Gender: "M" -> "Male", "F" -> "Female"

    - Marital status: "S" -> "Single", "M" -> "Married"

3. Changed "Income" data type to currency( $ )

4. Binned "Age" column:

    - Below 31: Adolescent
    
    - Between 31-54: Middle Age
    
    - Greater than 54: Old

5. Created pivot tables to categorize data 

6. Generated visualizations:

    - Bar charts 
    
    - Line charts

7. Built interactive dashboard with filters

## Analysis and Insights

The final dashboard provides:
- High sales of Bikes in families with Zero cars or More than Three cars
- More sales with customers who are pursuing/completed Bachelor's degree
- High sales in the North American region
- Correlation of purchase trends with high income and lower commute distance to work

This self-service visualization enables quick analysis of customer segments and bike purchase patterns.
The project can be used to deliver an impactful data story to guide marketing strategy.
