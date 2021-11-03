# Assignment 4: Interviewing a Data Set

**Caty Buchaniec**

## Question 1: A link to the dataset, your questions, as well as the answers to those questions.
 
Link to data: https://github.com/ccbuchaniec/datavisualization-fall2021/blob/main/Extra-vehicular_Activity__EVA__-_US_and_Russia%20(1).csv

  * Which country had the most activities done by an astronaut or cosmonaut outside a spacecraft beyond the Earth's appreciable atmosphere?
  * Answer: USA

  * Which astronaut or cosmonaut did the most EVA's in space?
  * Answer: Anatoly Solovyev

  * What was longest EVA completed by an astronaut or cosmonaut?
  * Answer: 8:56

## Question 2: Write down all steps used to clean and analyze the data, including any Excel formulas.

1. I downloaded the csv file from NASA. 
2. I then created a separate sheet in the file to keep track of the original data as I downloaded it. 
3. I copied and pasted the data from the first sheet to the second. 
4. After doing a bit of Googling on the Russian astronauts, I standardized the spelling of some last names (notable Anatoly Solovyev)
5. I added five columns to the right of "Crew."
6. I wanted to split the names all featured into the "Crew" column into three separate columns. I did the following process: Select Data > Text to Columns. In the Convert Text to Columns Wizard, I selected Delimited > Next. I selected the Delimiters for my data, choosing Space. I hit Next. I then selected the five new columns as my destination.
7. I then fixed the last name Van Hoften so that it was together in one cell rather than two. 
8. TI used the CONCAT formula, combining the first name column with the last name column. I did this for all name-pair columns.  
9. I then copied and pasted the combined columns into a new sheet, getting rid of the first and last name categories. 
10. I labeled "Crew 2" and "Crew 3" columns. 
11. I deleted the purpose column. 
12. To answer my first question, I clicked command + a to copy all my data. I then hit Insert -> Pivot Table to create a pivot table in a new sheet. I sorted my data in the pivot table so that Country was in the columns section and Count of Country was in the values section, thus I was able to see the total number of activities for each country. 
13. To answer my second question, I again used pivot tables to count word frequency. I clicked command + a to copy the data and then inserted a pivot table in a new sheet. To sort my data, I placed Crew 1 in my Rows and Count of Crew 1 in my values section. I then repeated the same steps with the data for Crew 2 and crew 2. Adding together the frequencies per astronaut, I was ultimatly able to see that Anatoly Solovyev completed the most missions. 
14. To answer my third question, I just clicked "Sort and Filter," selecting the "Duration" column. I selected descending and then viewed the resulting order. 

## Question 3: Write a sample headline and nut graf based on the most interesting of the three questions.

Headline: USA Surpasses Russia in Activites Outside of Spacecrafts

Nut Graph: 

Extra-vehicular activities -- often referred to colloquially as "spacewalks" -- have been completed by astronauts from around the globe, with Russian astronaut Anatoly Solovyev venturing outside the spacecraft into the great beyond on 16 occasions. Historically, Russia and the United States have led the charge in space, but data from NASA shows that the United States has completed more spacewalks than their Russian counterparts. 

