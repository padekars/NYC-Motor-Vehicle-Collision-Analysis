# NYC Motor Vehicle Collision Analysis

## Goal - 
The objective of this project was to design a robust data infrastructure and provide valuable insights to support key business decisions. The dataset was used from the NYC open data website  and it had 4 files - collisions, crashes, vehicle and persons with over 2 millions rows

## Tasks - 

Dimensional Model Design: I designed a multi-star schema dimensional model, which included 7 fact tables and 26 dimension tables using Alteryx. 
 
Data Profiling and Cleansing: To ensure the quality of the data, I conducted thorough data profiling and cleansing. I used SQL queries to identify and rectify data anomalies, inconsistencies, and inaccuracies as part of the data quality check.
 
ETL Workflow: I utilized Talend to create a comprehensive ETL workflow that loaded all the tables in a scheduled and automated manner. This ETL process was orchestrated through a single master job for efficiency.
 
Data Visualization: To provide meaningful insights, I established data visualization using Power BI and Tableau. Specifically, I created visualizations that showcased the places where most Collisions happened or the time when most collisions happened.

## Results -
The project resulted in several significant outcomes:

A well-structured multi-star schema dimensional model was created.

The ETL workflow, coordinated through a single master job, improved data loading efficiency.

The visualization of the top 1000 collisions using Power BI and Tableau enhanced decision-making by providing clear and actionable insights to stakeholders.
