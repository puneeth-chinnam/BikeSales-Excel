# Bike Purchase Analysis Dashboard

## Dataset

This project analyzes a bike purchase dataset with 1000 records and the following attributes:

```
- Customer income ($)
- Age
- Gender
- Education level
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

3. Changed "Income" data type to currency

4. Binned "Age" column:

    - < 31: Adolescent
    
    - 31-54: Middle Age
    
    - > 55: Old

5. Created pivot tables to analyze trends 

6. Generated visualizations:

    - Bar charts 
    
    - Line charts

7. Built interactive dashboard with filters

## Analysis and Insights

The final dashboard provides:

- Demographic segmentation by age, gender, region

- Correlation of purchase trends with income, commute distance to work


This self-service visualization enables quick analysis to understand customer segments and their bike purchase patterns. The project can be used to deliver an impactful data story to guide marketing strategy.
