# Reducing-number-of-high-fatality-accidents-UK

# Title

Insights in a database published by the UK department for transport 

# Introduction

In 2020, 1516 people were killed on UK roads, with 1460 deaths recorded in Britain and 56 recorded in Norther Ireland. This was significant decline compared with the previous year is due in part to the lockdown measures that were imposed in response to the COVID-19 pandemic.  The number of road deaths in the UK plateaued from 2012 to 2019 at around 1850 deaths a year, or equivalent of five a day, on average.
The trend relating to serious injuries is more difficult to analyze, as the method the police use to record severity has changed in recent years. However, this number has declined slightly since 2010, the total figure is still more than 22,000 serious injuries a year, or the equivalent of around 60 a day (Brake, 2021)
The reporting department have been collecting data on every accident that is reported in 2020, looking for insights to reduce the number of major incidents. The safety team classes major incidents as fatal accidents involving 3+ casualties.
The data used in this report was published by the department for transport. Contains public sector information licensed under the Open Government License v3.0. Link: https://data.gov.uk/dataset/road-accidents-safety-data 

# Content

## 1.	What time of day and day of the week do most major incidents happen?

The day of the week where most of the major incidents happens was Saturday with 821 reports, in second Friday with 798, for reference look in Figure 1. 
The time of the day where most of the major incidents happens were 15:30 pm and 16:00 pm with 35 reports both. 
As we can see in the Figures referent to the day of the week where most incidents happen, more reports appear as the weekend approaches, 
and according to the time, most of the hours go from the mid- afternoon range of 14:00 pm to 16:40 pm.

## 2.	Are there any patterns in the time of day/ day of the week when major incidents occur?

Using the time of the day and day of the week where most major incidents happen, four graphs were created to search for patterns.
In Figure 3 was compared first road number, first road class and road type. 
The first step was searching for the top five first road number with most reports finding the numbers of 0 with 281 reports, 
6 with 12 reports, 1 with 12 reports, 25 with 11 and 34 with 8. 
Next, we look up the road type and find that most of the reports are for the road type 6 with more than 628, 3 with 181, 1 with 41, 7 with 20 and 9 with 7. 
Finally, in the first road class the value with most of the reports goes for 3 with 426 reports, 6 with 240 reports, 4 with 111, 1 with 60 and 5 with 41.

As we merge the values in the Figure 3, we perceive that the first road number 0 with road type 6 and firs road class 5 and 6 is the only graph with most of the reports, 
making a possible point.
In the next Figure where was compared the first road number, speed limit, light conditions, and weather conditions. 
We can see that most of the reports goes for the graph where the light conditions are 1, second 4 and third 6 with weather condition between 1 and 3 and occasionally 4 to 9. 
As we can observe in the speed limit almost every graph is between 30 and 60.
For the next graph is compared the junction detail and junction control, finding that all the junction control type 1 lies with the junction detail 0, 
while the other junction detail has junction control type 2 and 4, being the junction detail 3 the one with the most elevated junction control 4. 
In the Figure 6 was compared the road surface conditions and urban or rural area, 
perceiving that the urban or rural area 1 has more reports road surface conditions 1 than the urban or rural area 2. 
While the road surface conditions 2 are similar for both graphs. 

## 3.	What characteristics stand out in major incidents compared with other accidents?

Looking for a standout characteristic in major incidents compared with other accidents, it was found out that there are more reports for <=2 number of casualties. 
Even if the reports are more the distribution between fist road number, road type and first road class look be the same, with road type 6 
and first road class distribution standing out. Another difference between this graph is that the top five first road number changed with less casualties, 
changing 25,5 and 38 for 4,23 and 3 respectively. 

For the junction detail and junction control relationship the distribution looks to be the same, standing out in both the junction detail 1 and 3. 
A difference can be seen in the junction control relationship 6, where the junction control changes being 2 more than 4.
For the first road number, speed limit, light conditions, and weather conditions graph, as we said there are <=2 number of casualties report. 
But even that said, in both graphs most of the accidents occur with light conditions 1,4 and 6. 
About weather conditions looks like most of the <=2 casualties happen between 2 and 4, while major accidents occur with 1 and 3.
In the last graph where urban or rural area and road surface conditions are monitored, 
for major accidents the count of reports are similar for road surface conditions 2, and a less than 200 reports for road surface conditions 1. 
Looking in the second graph the difference between road surface conditions 1 and 2 looks being the triple for urban or rural area 1, 
while in the urban or rural area 2 the condition 1 are two times more than condition 2. And comparing both areas, the 1 first one is three times more than area 2. 

## 4.	On what areas would you recommend the planning team focus their brainstorming efforts to reduce major incidents?

To focus the brainstorming efforts to reduce major incidents a decision tree was created using the values x and y, being y the dependent variable (number of casualties). 
For the decision tree the min samples leaf used was 5, the criterion was Gini, and a random state was 111. 
Using an accuracy of 70 as accept or decline the weight of the analysis.

Looking for the weight of each independent variable the top five are:
•	First road number
•	Day of the week
•	Number of vehicles
•	Speed limit
•	Junction detail

# Reference
Brake (2021). UK road death and casualty statistics. From: https://www.brake.org.uk/get-involved/take-action/mybrake/knowledge-centre/uk-road-safety
