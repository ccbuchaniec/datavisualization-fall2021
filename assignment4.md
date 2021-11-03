# Assignment 4: Interviewing a Data Set

**Caty Buchaniec**

## Question 1: A link to the dataset, your questions, as well as the answers to those questions.
 
Link to data: https://github.com/ccbuchaniec/datavisualization-fall2021/blob/main/Extra-vehicular_Activity__EVA__-_US_and_Russia%20(1).csv

  * Which country had the most activities done by an astronaut or cosmonaut outside a spacecraft beyond the Earth's appreciable atmosphere?
  * Answer: 

  * Which astronaut or cosmonaut did the most EVA's in space?
  * Answer: 

  * What was longest EVA completed by an astronaut or cosmonaut?
  * Answer: 

## Question 2: Write down all steps used to clean and analyze the data, including any Excel formulas.

1. I downloaded the csv file from NASA. 
2. I then created a separate sheet in the file to keep track of the original data as I downloaded it. 
3. I copied and pasted the data from the first sheet to the second. 
4. I added five columns to the right of "Crew."
5. I wanted to split the names all featured into the "Crew" column into three separate columns. I did the following process: Select Data > Text to Columns. In the Convert Text to Columns Wizard, I selected Delimited > Next. I selected the Delimiters for my data, choosing Space. I hit Next. I then selected the five new columns as my destination.
6. To join first names and last names into pairs, I used the CONCAT function. 
7. I then copied and pasted the combined columns into a new sheet, getting rid of the first and last name categories. 
8. I labeled "Crew 2" and "Crew 3" columns. 
9. I deleted the purpose column. 
10. 
