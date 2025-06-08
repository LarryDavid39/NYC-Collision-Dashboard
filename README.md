# NYC Collision Analysis


### Project Overview

This data analysis project aims to provide insights into the collision of New York city over the past three years. By analyzing various aspect of the accident data, we seek to identify trends, make data-driven recommendation, and get deeper understanding of the city's activities.

[NYC Collision Dashboard.pdf](https://github.com/user-attachments/files/20643000/NYC.Collision.Dashboard.pdf)

[NYC Collision Dashboard2.pdf](https://github.com/user-attachments/files/20643002/NYC.Collision.Dashboard2.pdf)

![Screenshot (11)](https://github.com/user-attachments/assets/f719f6f6-a8d4-46e0-a4ea-b549a2739a5c)
![Screenshot (10)](https://github.com/user-attachments/assets/766a3356-e5d4-46e8-a558-ab621d0af83d)



### Data Sources

The Primary dataset used for this analysis is the "nyc-collision-data.csv" file

### Tools

- Excel - This is used for data cleaning
- Power Query - Also used for data cleaning
- Excel - Used for data analysis
- Excel - Creating dashbord
- Excel VBA - Making all buttons active


  ### Data Cleaning/Preparation

  In the initial data preparation phase, we performed the following task:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.
 
  ### Exploratory Data Analysis

  - What is the overall collision?
  - What is the overall fatalities and injured?
  - Which month has the highest collision?
  - Which city has the highest collision?
  - What is the peak collision periods?
  - Which season does collisions happens most?
  - What are the causes of these collision?
  - Which year has the highest collision?
 
    ### Data Analysis

    Include some interesting code/features worked with
    ``` VBA
    Sub ToggleRecommendation02()
    'Declare a variable to reference the shape group
    Dim shp As Shape
    Set shp = ActiveSheet.Shapes("Group 49")
    
    'Check if the shape is currently visible
    If shp.Visible = msoTrue Then
        'if visible then hide
        shp.Visible = msoFalse
        Else
            'if hidden, show it
        shp.Visible = msoTrue
        End If
    End sub
    ```

### Result/Findings

The analysis result are summarized as follow:
The year 2021 has the most collisions,and majority happened in the month of June. Hours of 4pm-8pm on Fridays are the peak hours as most collisons happend during that pedriod.
Drivers intention/distraction is the cause of most of the collisions. More pedestrians suffers casuality, as most collisions happens in Spring.


### Recommendations

- Deploy targeted enforcement, improve road signage, and run public awareness campaign during peak collision month.
- Launch targeted awareness and enforce campaigns addressing these high-risk-behaviour
- Focus more on motorist and pedestrians. Install more pedestrians,crossing and investigate frequent collision hotspots.
- Drivers should be active and alert at peak hours, to avoid fatique and sleepiness. And also reduce speed  at peak hours.



    
