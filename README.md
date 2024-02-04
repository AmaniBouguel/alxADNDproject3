# Ford GoBike System_exploration

## Introduction
>This project was developed as a part of ALX Africa-Udacity Data Analysis NanoDegree. It is the final evaluation to get the certificate 
>It is divided in two parts:
>1. Exploratory analysis: it includes univariate exploration, bivariate exploration and multivariate exploration
>2. Explanatory analysis: it is  presentation including some visualization using the cleaned dataset
   
## Dataset

>The datasset contains information about individual trips made in a bike-sharing system covering the greater San Francisco Bay Area in February 2019. This dataset was chosen for its important ecological impact. It would help to get a greener environment. </br>
The dataset is composed of 183412 rows and 16 columns. 
Some features had wrong type:
>- start_time was object altered to datetime
>- end_time was object altered to datetime
>- bike_share_for_all_trip was object changed to boolean
During the exploration, some unexpected illogic entries for age feature were found and removed.

## Summary of Findings

> During exploration analysis, The focus was made on the trip duration, the start time, the users type and gender and the station popularity. 
Some unexpected relationships related to the number of trips, duration of trips, users type and gender were found. The main ones will be used in the explanatory presentation. 
>1. Univariate Exploration
>>- The highest usage rate of Ford GoBike System is on Thursday.
>>- In the dataset, there several entries of elders whose age is more than 100. The most of users are in their early thirties
>>- The most preferable start and end stations are almost the same
>>- The least preferable start and end stations are almost the same
>2. Bivariate Exploration
>>- People in their thirties are not only the most ones using Ford GoBike System. They are also the ones enjoying longer bike rides.
>>- Although 90% of users are subscribers, customers take longer rides using Ford GoBike System.
>>- Although 74.6% of users are male, female and other take longer rides using Ford GoBike System.
>3. Multivariate Exploration 
>>Customers’ usage rate is almost the same but their rides’ duration is variable. Their longest rides happen to be in the weekends which represent the lowest usage rate.
On the other hand, subscribers, the most users of the system, use the system in the opposite way


## Key Insights for Presentation

> For explanatory analysis, The focus was made on the users behaviour in order to find out some ways to make the system more popular in the future. 
Subplots were used to be able to visualize different charts developped during exploration analysis in the same slide and compare the findings.
During this part of analysis,:
>1. User types rate were compared to their ride duration
>2. Users gender rate was analysed based on their ride duration
>4. Usage rate was visualized with the duration of trips per day of the week by user type

## Project content
>1. Part_I_ Ford GoBike System_exploration.ipynb: It includes the code for the exploratory analysis
>2. Part_I_ Ford GoBike System_exploration.html: It is the HTML version of Part_I_ Ford GoBike System_exploration.ipynb
>3. Part_II_Ford_GoBike_System_explanatory.ipynb: It includes the code for the expanatory analysis
>4. Part_II_Ford_GoBike_System_explanatory.slides.html: It is the presentation of the explanatory anaysis
>5. 201902-fordgobike-tripdata.csv: It is the dataset file
>6. clean201902-fordgobike-tripdata.csv: It is the cleaned dataset generated after the exploation part
