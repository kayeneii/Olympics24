# Olympics24
This is an analysis of the athletes who participated in the 2024 Olympics held in Paris, France.

[Overview](#overview) [Data Source](#data-source) [Tools](#tools) [Insights](#insights) [Visualizations](#visualizations) [Conclusion](conclusion)

## Overview
---
This reports my analysis of the 2024 Olympics held in Paris, France with a focus on specific disciplines namely: Archery, Athletics, Badminton, Basketball, Boxing, Cycling, Diving, Equestrian, Fencing, Football, Golf, and Gymnastics. The goal is to develop the following KPIs:
  1. Gender Inclusivity
  2. Age Groups
  3. Total Number of Athletes


## Data Source
---
The data used in generating this report was authored by Willian Oliveira Gibin and can be found at [Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/olympics-2024).


## Tools
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
    
  4. Data Visualization: Cards, Donut Chart and Lines were used to visually plot out the representation and inclusivity trend, including other summarized data.
 
- **GitHUb:** For,
  1. Portfolio Building
  2. Communication


## Insights
---
The insights derived from the data following a thorough analysis, varied according to discipline.

 * Archery: A total of 128 archers participated, of which 50% were male. This discipline comprised 49 females and 43 males in the Gen Z category, while the Millenials comprised 21 males and 15 females.

 * Athletics: Had 48.79% female representation in a total of 2,023 athletes. Gen Z = 523 females and 644 males; while Millenial = 392 males and 464 females.

 * Badminton: 175 badminton players participated, of which 50.29% were male. Millenial = 34 females and 41 males; while Gen Z = 47 males and 53 females.

 * Basketball: A total of 352 'ballers participated. Equal gender representation of Gen Z = 82 females and 67 males, and Millenial = 109 males and 94 females.

 * Boxing: Also, equal gender representaion of a total 248 boxers that participated. Gen Z = 66 females and 89 males; while Millenial = 35 males and 58 females.

 * Cycling: Of a total of 571 cyclists, 49.39% were female. Gen Z = 188 females and 164 males; while Millenial = 125 males and 94 females.

 * Diving: There was a total of 135 divers, of which 50.37% were female. Gen Z = 49 males and 55 females; while Millenial = 18 males and 13 females.

 * Equestrian: 242 riders participated in this discipline. Of the total 12 sports included in this report, this had the largest gender gap of 38.43% being female and 61.57% being male. Millenial = 136 males and 82 females, and Gen Z = 11 females and 13 males.

 * Fencing: 50% male and female participation, with 63 females and 68 males in the Millenial category; and Gen Z = 67 females and 62 males. The total number of fencers was 260.

 * Football: Having 43.40% female participation, the total number of athletes recorded in this discipline was 563. The Gen Z category had 147 females and 294 males; while Millenial had 19 males and 93 females.

 * Golf: A total of 120 golfers participated, with 50% being male. Gen Z = 30 females and 18 males; while Millenial = 42 males and 30 females.

 * Gymnastics: 316 gymnasts were recorded, of which 64.56% were female. The second discipline with a large gender gap. Gen Z = 189 females and 74 males; while Millenial = 38 males and 15 females.

Based on these insights, it can be construed that the 2024 Olympics was largely gender-inclusive with representation of both GenZs and Millenials in several disciplines. Majority of the sports were dominated by Gen Zs, except Basketball, Equestrian, Fencing, and Golf. Disciplines such as Gymnastics had a low participation of females born before 1997 (>27 years). Additionally, there was a huge gender gap in both Equestrian and Gymnastics, with the former being a male-dominant discipline and the latter being a female-dominant discipline.


## Visualizations
---
![Data Viz1](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_1.png)
![Data Viz2](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_2.png)
![Data Viz3](https://github.com/kayeneii/Olympics24/blob/main/Olympics24_3.png)


## Conclusion
---
Did you found this report informative? Until my next report, you may find me [here.](https://www.linkedin.com/in/kayeneii) I look forward to connecting with you there!😄
