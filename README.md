# Introduction
Crime is a pervasive social issue affecting communities worldwide, with significant economic, emotional, and social consequences.
In today's world, crime rates have surged, posing complex challenges for law enforcement globally. Effective crime prevention and management require a thorough understanding of crime patterns, trends, and underlying factors.

The increasing rate of criminal activity in urban areas has become a major concern for public safety and community well-being. Traditional methods of crime analysis are often manual, time-consuming, and limited in scope. This project seeks to leverage advanced data analytics techniques to examine crime data, uncover hidden patterns, and inform data-driven decision-making to enhance crime prevention strategies.
   You are a junior data analyst at Datafied Technologies. You are required to harness the power of data analytics to:
Identify and understand crime patterns and trends, Identify potential crime hotspots based on data-driven insights and Enhance proactive crime prevention strategies.


To tackle these issues head-on, the integration of advanced technologies and data analysis is crucial. This case study delves into how crime data analysis can elevate the effectiveness of law enforcement in a major city, the project aims to analyze the crime dataset to identify key trends, hotspots, and correlations, providing valuable insights for law enforcement agencies, policymakers, and community stakeholders.
  
  
# Problem Statement
Cities in the uK have experienced a steady increase in crime rates over the past seven years, with a significant surge in non-violent crimes(Assault without injuries). This trend poses a significant threat to public safety, undermines community trust, and imposes substantial economic burdens on residents and businesses. This project aims to investigate the underlying factors contributing to this trend.
    
# Data sourcing
The dataset is built from The ‘Police recorded crime open data tables, year ending March 2013 onwards’ release. An Official Statistics output produced to the highest professional standards and free from political interference.
- [Location Data](https://docs.google.com/spreadsheets/d/12_rGg2I15b8fcCuI3-sa6s_ZFo_GO6ODY4_CmGzXqms/edit?usp=classroom_web&authuser=0)
- [Crime Data](https://docs.google.com/spreadsheets/d/10tMLxKFBo_yIbFgpzbFul6xO9JhHG8yth8ZM2RXc6Gc/edit?usp=classroom_web&authuser=0)
- [Data Dictionary](https://drive.google.com/file/d/1UanB-0CzhQIlMBdpBprS7t8d0W_L2jHx/view?usp=classroom_web&authuser=0)
# Data transformation and cleaning
The dataset was cleaned by removing duplicates, correcting any inconsistencies, and ensuring the data is in a suitable format for analysis and visualization.

![image](https://github.com/user-attachments/assets/046c0186-1ac7-4dc8-9756-6a828a754092)

# Data Modelling
The Analysis was broken down into different dimensions and new tables for identified dimensions were created. These included:
- **Date Dimension**
- **Location Dimension**
- **Offense Dimension**
- **Crime Record Fact Table**

  The data model was designed using the Star Schema and the different dimensions were connected to the Facts table in a one-to-many relationship.

   ![image](https://github.com/user-attachments/assets/2c3662b1-551f-4db6-93a6-1fca6673b612)
  ## **Visualization and Chart**
  Barcharts, a Linechart and a Piechart was used to represent the metrics and insights.

  ![image](https://github.com/user-attachments/assets/95b4b7ed-af25-403f-af5f-379f56fa0c73)




