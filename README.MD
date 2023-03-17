# Data Cleaning Challenge  : Cleaning the FIFA21 dataset scraped and Available on [KAGGLE](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring "KAGGLE FIFA21 dataset")

![FIFA2](FIFA21.png)


## Introduction
A #Data Cleaning Challenge (#datacleaningchallenge) was recently organised in the data tech area. It gave beginners, intermediates and senior retrainers the opportunity to work on a data cleaning project. The challenge allowed each participant to put their data cleansing skills to use using one of their favourite tools (Python, R, Power Query, Excel, SQL, Google Sheets, ...). 

> As a participant in the challenge, I used the python language to build this data cleaning project using the FIFA 21 dataset provided.  at [KAGGLE](https://www.kaggle.com/datasets/yagunnersya/fifa-21-messy-raw-dataset-for-cleaning-exploring "KAGGLE FIFA21 dataset")


## About the Data
The dataset in its messy and raw state was gotten from Kaggle and contains 18979 rows and 77 columns. Below are the columns contained in the data;
photoUrl, LongName, playerUrl, Nationality, Positions, Name, Age, OVA, POT, Team & Contract, ID, Height, Weight, foot, BOV, BP, Growth, Joined, Loan Date End, Value, Wage, Release Clause, Attacking, Crossing, Finishing, Heading Accuracy, Short Passing, Volleys, Skill, Dribbling, Curve, IFK Accuracy, Long Passing, Ball Control, Movement, Acceleration, Speed, Agility, Reactions, Balance, Power, Shot Power, Jumping, Stamina, Strength, Long Shots, Mentality, Aggression, Interceptions, Positioning, Vision, Penalties

## My systematic cleaning process
### Choice of the tool to use
As a data analyst working in the field with all these tools, the first thing I had to do was to choose the tool with which I was going to clean this dataset. To do this, I went through a data discovery phase where I observed the quality, profile and distribution of the data, for which I used python and power BI. After a brief exploration of the data, I decided to use python to perform this cleaning.

### Preliminary exploration
This preliminary exploration process allowed me to identify basic information such as dataset dimensions, column data types, types of problems present and to discover that the dataset had dirty data problems (data with problematic content, including missing, invalid, inaccurate or inconsistent data) and messy data problems (data that has problems with its structure (columns, rows or table).

### Cleaning step
After this preliminary exploration step, I applied a systems approach that I use in my data analysis and data science projects in the cleaning phase. In this approach, I clean the dataset column by column by applying the following steps:
1- **Assessment:** here I analyze the column for possible problems. I use both visual and programmatic assessment
2- **Documentation:** If a problem is found in step 1, I clearly document it. Here I assign a title and a number to the problem so that I can discuss it with a colleague based on the problem number.
3- **Definition of the action plan** of the solution to be applied to correct the problem
4- **Implementation of the action plan** to correct the problem
5- **Final evaluation:** to check that the solution worked and the problem was solved. If there is a problem, I go back to step 1, 3 or 4.
**N.B.** _I document my work as I go along._

### Consult the project
You will find in the following github repository the complete jupyter notebook of my work, the starting datasets and the cleaned one [Data Cleaning Challenge : FIFA2021] (https://github.com/bovebove/FIFA21-Data-Cleaning). 

### What's next?
In the next few weeks, I will clean this same dataset with Power BI, SQL and eventually Excel, I will publish an article with all my work each time; At the end I will do a synthesis article on the comparative study of data cleaning with each of these tools.
Subscribe to my profile to stay informed of my next publications. Like and share if you think I deserve it. Leave me your comments on my work. 
See you soon.