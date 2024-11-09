# Olympics24-Athletes
This is an analysis of the athletes who participated in the 2024 Olympics held in Paris, France.

## Overview
---
This report is an analysis of the 2024 Olympics held in Paris, France with a focus on the athletes who performed during the global event. The goal is to identify key trends in participation, track representation and inclusivity, and to communicate these insights in the best manner.

## Data Source
---
The data used in generating this report was obtained from [Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/olympics-2024) and authored by Willian Oliveira Gibin.

## Methods
---
The following tools were utilised in the creation of this report:

- **Microsoft Excel:** For data cleaning, preparation, and sorting.
  1. Data Cleaning and Preparation:
     - Data loading and inspection
     - Data cleaning and formatting
    
  2. Data Sorting: This involved sorting the large data according to sports category.

- **Microsoft Power BI:** For initial exploration, analysis and visualization of the data.
  
  1. Initial Exploration: This entailed an exploration of the data to develop questions and answers that best align with the objectives of the report. These questions include:
     - What was the total number of athletes?
     - What was the average year of birth?
     - How gender-inclusive was the sport?
     - How many GenZs participated?
     - How many athletes were Millenials?
     - What was the male-female distribution of the GenZs?
     - What was the female-male distribution of the Millenials?
     - What was the rate of athletes with refugee status?
 
  2. Data Analysis: During analysis, Conditional Columns were created using DAX functions.

      = Gender Count
      ```DAX
      If GENDER equals Female Then 1
     Else 0
     ```
 
     = Generation
     ```DAX
     If YOB before 1997 Then Millenial
     Else GenZ
     ```

     = Generation Count
     ```DAX
     If Generation equals GenZ Then 1
     Else 0
     ```
     
     = Refugee Count
     ```DAX
     If COUNTRY contains Refugee Then 1
     Else 0
     ```
     
  3. Data Visualization: Cards, Donut Chart and Matrix were used to visually plot out the representation and inclusivity trend, including other summarized data. 

## Findings and Insights
---

## Visualizations
---
![Data Viz](https://github.com/kayeneii/Olympics24-Athletes/blob/main/Olympic-24-Athletes-Viz.png)
