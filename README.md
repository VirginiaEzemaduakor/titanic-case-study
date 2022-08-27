# **Titanic-Case-Study**

  ## Table of contents

 1. [Introduction](#Introduction) 

    - [Objective of the analysis](#Objective-of-the-analysis)
    - [Data cleaning](#Data-cleaning)

2.	[Exploratory Data Analysis](#Exploratory-Data-Analysis) 

    - [Passengers by class and sex](#Passeners-by-class-and-sex)
    - [Passengers by age group and embarkment](#Passengers-by-age-group-and-embarked-location)
    - [Passengers by children and siblings](#Passengers-by-children-and-siblings)
    - 

3. [Overview Dashboard](#Overview-Dashboard)

4. [Tailored Data Analysis](Tailored-Data-Analysis)
 
    - [Survived passengers by sex and class](#Survived-passengers-by-sex)
    - [Survived passengers by age group and embarked location](#Survived-passengers-by-age-group-and-embarked-location) 

    - [Survived Male to Female Ratio by Class and age group](#Survived-male-to-female-ratio-by-class-and-age-group)

    - [Survived passengers dashboard](#Survived-passengers-dashboard)
    
    - [Dead passengers dashboard](#Dead-passengers-dashboard)

5. [Conclusion](#Conclusion)
---

## Introduction

Titanic was a British passenger liner, operated by the White Star Line, which sank in the North Atlantic Ocean on 15 April 1912 after striking an iceberg during her maiden voyage from Southampton, UK, to New York City. The collision with the iceberg ripped off many parts of the Titanic. Many classes of people of all ages and gender where present on that fateful night, but the bad luck was that there were only few life boats to rescue. The dead included a large number of men whose place was given to the many women and children on board. Of the estimated 2,224 passengers and crew aboard, more than 1,500 died, which made the sinking possibly one of the deadliest for a single ship up to that time. It remains to this day the deadliest peacetime sinking of a superliner or cruise ship. The disaster drew much public attention, provided foundational material for the disaster film genre, and has inspired many artistic works. 

### Objective of the analysis

Analysis of what happened on the titanic will be performed based on the dataset available, presenting which passengers survived or died at the time of sinking of the Titanic. The data analysis provides features like fare prices, class, sex, age group, siblings, child and location embarked which will be used to make exploratory and tailored analysis of what happened. The objective is to perform exploratory data analysis to mine various information in the dataset available and to know 	effect of each field on survival of passengers with regards to there class, sex, age group and port of embarkation by applying analysis between every field of dataset with “Survival” and “Dead” field. The data analysis will be done on Microsoft excel.

### Data cleaning
Before applying any type of data analytics on the dataset, the data is first cleaned. There are some missing values in the 	dataset which needs to be handled. In attributes like Age and Cabin, missing values are replaced with the mean value of the existing age. Adding columns to calculate passenger age group, count number of male and female.

## Exploratory Data Analysis

We are going to perform exploratory data analysis in the first stage. In exploratory data analysis dataset is explored to give account of what happened. The data is deeply analyzed to find the total number of passengers that onboard the ship base on the dataset, and calculating the numbers of passengers with regard to each feature. 

According to the dataset, analysis shows that 418 passengers onboard the Titanic ship. And out of the 418 passengers that aboard the ship, 266 passengers died while 152 survived.

### Passengers by class and sex
class                      |  description
----------------------------------|------------------------------------------------------------------------------------
 ![Chart2.2](Picture2.2b.png)     | The data shows that 218 (~52%) passengers boarded the ship with 3rd class ticket, 107 (~26%) passengers boarded with 1st class ticket, while 93(~22%) passengers boarded with 2nd class ticket.

sex                      |  description
----------------------------------|------------------------------------------------------------------------------------
   ![Chart2.2](Picture2.2b.png)                         | In the dataset, 266 passenger were male and 152 female that is; ~64% and 36% respectively. In other words, they were more male passengers than female.  
 
### Passengers by age group and embarked location

age group                     |  description
----------------------------------|------------------------------------------------------------------------------------
 ![Chart2.2](Picture2.2b.png)     |  From the given data, I observed 332 registered ages and 86 missing. In order to capture all the registered ages, I manipulated the data using measure of Centre by filling the missing ages with the average age. From my analysis, they were more passengers between the ages of 20 – 39 years (~66%) and  lesser passengers that is; 14 (~3%) passengers are >60 years old.
	
embarked location                      |  description
----------------------------------|------------------------------------------------------------------------------------
   ![Chart2.2](Picture2.2b.png)                         |Passengers embarked on the ship from three (3) locations namely; Cherbourg, Queenstown and Southampton. 270 passengers went aboard the ship at port Southampton, 102 at port Queenstown and 46 at port Cherbourg. Southampton had the most passengers while Queenstown had the least passengers.

### Passengers by children and siblings

children                     |  description
----------------------------------|------------------------------------------------------------------------------------
 ![Chart2.2](Picture2.2b.png)     |  The analysis on the dataset shows total of 94 passengers whose children aboard the ship. Of all the passengers who had children aboard the ship, ~55% (52) of the them had a child aboard the ship.
 
siblings                      |  description
----------------------------------|------------------------------------------------------------------------------------
   ![Chart2.2](Picture2.2b.png)                         |From my analysis on the data dataset, they were 135 passengers whose siblings aboard the ship; of all the passengers who had siblings aboard the ship, ~81% (110) of them had one(1) siblings aboard the ship. 


### 2.7 Fare Prices
![Table2.7](Picture2.7.png)
The total fare prices was £15,784.24, the average fare prices was £37.76, the maximum fare prices was £263 and the minimum fare prices was £3.17 respectively.


### 2.9 Passengers by Sex and Class
![Table2.9](Picture2.9.png)
![Chart2.9](Picture2.9b.png)
From my analysis, they were 57 males and 50 females who used the 1st class ticket, 63 males and 30 females who used the 2nd class ticket and finally, 146 males and 72 females used the 3rd class ticket.

## Overview dashboard
![Fig.1](Figure%201.png)


## 3. TAILORED DATA ANALYSIS

The next stage is tailored data analysis. The analysis in this study aims to make comparative analysis of passengers between each feature to determine the feature which would influence the survival rate as well as the dead rate. 



### 3.2.2 Survived Passengers by Sex
![Table 3.2.2](Picture3.2.2.png)
From the dataset, all the 152 females aboard the ship survived while none of the male passengers survived.

### 3.3 Survived Passengers by Class
![Table3.3](Picture3.3.png)
![Chart3.3](Picture3.3b.png)
152 passengers from all 3 classes survived from the sank ship; of which 72(47%) of the survived passengers were 3rd class, 50(33%) passengers were 1st class and finally, 30(20%) passengers were of 2nd class.

### 3.4 Survived Passengers by Age Group
![Table3.4](Picture3.4.png)
![Chart3.4](Picture3.4b.png)
The analysis of survived passengers by age group shows that 94 passengers within the youth (20-39years) age bracket survived from the sank ship, 28  passengers within the teenager age (1-19years), 23 passengers within the adult age (40-59years) and finally, 7 passengers were elders (>60) also survived.

### 3.5 Survived Passengers by Embarked Location
![Table 3.5](Picture3.5.png)
![Chart 3.5](Picture3.5b.png)
Some numbers 0f passengers who aboard the ship at different port of embarkation survived from the wrecked ship. 88 passengers survived at Southampton, 40 survived at Cherbourg, while 24 passengers survived at Queenstown respectively.

### 3.6 Survived Male to Female Ratio by Class
![Table 3.6](Picture3.6.png)
The ratio of male to female that survived the wrecked based on passenger’s class were; 0:50, 0:30 and 0:72 that is; 1st class, 2nd class and 3rd class respectively. Which entails no male survived the wrecked ship but all the females survived from the given dataset.

### 3.7 Survived Male to Female Ratio by Age Group
![Table3.7](Picture3.7.png)
The ratio of male to female that survived the wrecked based on passenger’s age group were; 0:23, 0:7, 0:53 and 0:69 that is; 40-59 years, >60years, 0-19 years and 20-39 years respectively. Meaning no male survived the wrecked ship but all the females survived from the given dataset.

### Figure 2 Survived Passengers Dashboard
![Fig.2](Figure%202.png)

### Figure 3 Dead Passengers Dashboard
![Fig.3](Figure%203.png)
### 3.2.1 Dead Passengers by Sex
![Table 3.2.1](Picture3.2.1.png)
From the dataset, all the 266 males aboard the ship died while none of the female passenger died.

## 4. CONCLUSION
Data cleaning is the first step while performing data analysis. Exploratory data analytics in this context helps one to understand the dataset by showing the number of passengers in each features. EDA is used to figure out the total number of passengers that boarded the titanic ship based on class, sex, port of embarkation, passengers whose siblings aboard the ship and passengers whose children aboard the ship. Tailored data analytics in this study helps to give a simple comparison of passengers in each of the features in other to make predictions of how certain features could influence the survival rate and dead rate of the passengers. This is done by using graphical techniques.

By applying TDA some conclusions are drawn and facts are found. There is high influence of sex on survival. We can see from table-3.2 that the number of dead passengers are the total number of male (266), while in table-3.3, it can be seen that the number of survived passengers are the total number of female(152). With the high influence rate, we can say the female passengers are more likely to survive giving the 100 percent survival rate.

The influence of age on survival. The table below shows how age could influence the possibility of survival. Out of the total 418 passengers that aboard the ship, 152 (~36) passengers survived the wrecked ship; out of the 14 passengers within the elders ( >60 years) ages that boarded the ship, 7 survived; out of the 61 passengers within the teenager (0-19years) age bracket, 28 survived; out of the 68 passengers within the adult (40-59years) age bracket, 23 survived; and lastly, out of the 275 passengers within the youth (20-39years) age bracket, 94 passengers survived the wrecked ship.
![Table4.](Conclusion%20.png)
With the above table we can say the passengers >60 years old with 50% survival rate is more likely to survive, followed by passengers between ages of 0-19years with survival rate of ~46%, while ages between 20-39years and 40-59years with the  survival rate of ~34% respectively, had less chance of survival.

















