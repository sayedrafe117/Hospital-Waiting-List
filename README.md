# Hospital-Waiting-List
#powerbi #Dataanalysis
HealthCare Data
Project Goal
1.	Track Current status of patient waiting list.
2.	Analyse historical monthly trend of waiting list in inpatient and outpatient categories.
3.	Detailed speciality level and age profile analysis
Metrics Required
1.	Average and Median waiting list
2.	Current total waiting list
 
Data Transformation and cleaning
Inpatient – A patient who stays in a hospital while under treatment.
Outpatient – A patient who receive medical treatment without being admitted to a hospital.
For data entry = I have used the folder connection but for that reason every excel or csv file needs to have same header so that we can concatenate them

Change the column name in Impatient and outpatient to append them. Create a new column in the outpatient section Case Type
Append them and make them a new table.

Measures
1.	Latest Month wait list (In here I have used the maximum date because I want to get the update of the latest month)
2.	Previous Month wait list.( In here I Have used the E-Date It use the latest month number and subtract 12 month from it so that I can get the previous year same month data) 
3.	Average Waiting list
4.	Median waiting list
5.	Switch for Average Median waiting list

