# Olympics24-Athletes
This is an analysis of the athletes who participated in the 2024 Olympics held in Paris, France.

## Overview
---
This reports my analysis of the 2024 Olympics held in Paris, France with a focus on specific disciplines namely: Archery, Athletics, Badminton, Basketball, Boxing, Cycling, Diving, Equestrian, Fencing, Football, Golf, and Gymnastics. The goal is to develop the following KPIs:
  1. Gender Inclusivity
  2. Age Groups
  3. Total Number of Athletes


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
    

- **Microsoft Power BI:** For initial exploration, analysis and visualization of the data.
  
  1. Initial Exploration: This entailed an exploration of the data to develop questions and answers that best align with the objectives of the report. These questions include:
     - What was the total number of Athletes?
     - How gender-inclusive was the sport?
     - How many GenZs participated?
     - How many Athletes were Millenials?
     - What was the male-female distribution of the GenZs?
     - What was the female-male distribution of the Millenials?
 
  2. Data Analysis: During analysis, Conditional Columns were created using DAX functions.
    - Conditionals
         ```DAX
         If discipline contains Archery Then 1
         Else if discipline contains Athletics Then 2
         Else if discipline contains Badminton Then 3
         Else if discipline contains Basketball Then 4
         Else if discipline contains Boxing Then 5
         ```
         And so on.

         ```DAX
         If YOB is greater than or equal to 1997 Then Gen Z
         Else Millenial
         ```
    
     
  3. Data Visualization: Cards, Donut Chart and Lines were used to visually plot out the representation and inclusivity trend, including other summarized data.
 
- **GitHUb:** For,
  1. Portfolio Building
  2. Communication


## Insights
---
Insights varied according to discipline.
 * Archery: A total of 128 archers participated, of which 50% were male. This discipline was Gen Z dominant with 49 females and 43 males while the Millenials comprised 21 males and 15 females.

 * Athletics: There was a total of 2,023 athletes. 48.79% were female. Gen Z = 523 females and 644 males; while Millenial = 392 males and 464 females. (Gen Z dominant)

 * Badminton: 175 badminton players participated, of which 50.29% were male. Millenial = 34 females and 41 males; while Gen Z = 47 males and 53 females. (Gen Z dominant)

 * Basketball: A total of 352 'ballers participated. Equal gender representation of Gen Z = 82 females and 67 males, and Millenial = 109 males and 94 females. (Millenial dominant)

 * Boxing: Also, equal gender representaion of a total 248 boxers that participated. Gen Z = 66 females and 89 males; while Millenial = 35 males and 58 females. (Gen Z dominant)

 * Cycling
 * Diving
 * Equestrian
 * Fencing
 * Football
 * Golf
 * Gymnastics

Based on these insights, it can be construed that the 2024 Olympics was largely gender-inclusive with representation of both GenZs and Millenials in several disciplines.


## Visualizations
---
![Data Viz1](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_1.png)
![Data Viz2](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_2.png)
![Data Viz3](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_3.png)


## Conclusion
---
Hope you found this report informative? Until my next report, you may find me [here.](https://www.linkedin.com/in/kayeneii) I look forward to connecting with you there!😄
