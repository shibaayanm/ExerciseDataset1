## Context

*A Team of Data Analysts from West Bengal planned to survey on the people of the state West Bengal, India and managed to collect some datapoints initially. With a hardwork of more than 1 year they managed to collect some datapoints.*

*Some information such as **DateOfBirth** required evidences to attach by the participant as well. Manual surveys are so time-consuming, hence they took help from a web-application to reach people in order to fill up the details by them when they're comfortable.*

*From mondays to saturdays went hectic with their past 1 year with other projects, so they want your help to find out answers from this dataset. Also feel free to share any other observations apart from the asked questions if you want. I have their contacts, on any issues please reach out to me, will pass them.*

## Brief on the dataset

Column                         | About
|------------------------------|------------------------------------------------------------------------------------------------------------------------|
|DataInputDate                 | Refers to the date on when the data was entered by participant on the web-application.
|DataInputTime                 | Subsequently refers to the time.
|Name                          | Refers to the name of the participant.
|District                      | Refers to the Districts of the state 'West Bengal' where their primary address are in.
|AgeInYears                    | Refers to their age in years.
|Occupation                    | Refers to the job their in, this field in web app was a text field so participants were asked to be comfortable to select any existing occupation or to create their own.
|Industry                      | Refers to the industry their occupation relates to. It was some existing distinct drop down values which the team decided.
|JobDescription                | Describes their job, participants were given freedome of fill anything on the provided text field.
|HoursSpentInOccupationPerDay  | Out of 24 hours how many hours they spend on their workplace.
|DateOfBirth                   | Refers to the date on which the participant was born.


Please prepare an .csf file answering the following questions.

## Questions

1. Assign an auto increment numeric column **ID** arranging the entered dataset in ascending order by the date and time when the data entered. The line which was entered at very first should have an **ID** of '1' then '2' then '3' etc.

2. Fetch the lines those denote that the data was entered on weekends.

3. How many participants weren't aware of their actual age while filling up the form. Display the table in below format.
   | Gender | Number of people | DateofBirth | DataInputDate | DateInputTime | AgeInYears | ActualAge |
   |--|--|--|--|--|--|--|

4. Fetch the names of the participants who were promoted to senior levels at the mimimum age entered by the other professionals in the same industry. Display the table in below format.
   | ID | Name | DateOfBirth | Occupation | Industry | MinimumAgeFoundInTheIndustry | HoursSpentInOccupationPerDay |
   |--|--|--|--|--|--|--|

5. Fetch the names of the people who weren't probably careful while selecting their gender. Display the table in below format.
   | ID | Name | DateOfBirth | Gender | ActualProbableGender |
   |--|--|--|--|--|

6. Fetch the names of the participants who usually have to work on weekends.
   | ID | Name | DateOfBirth | Occupation | Industry | JobDescription |
   |--|--|--|--|--|--|

7. Fetch the names where participants submitted the form in between 12:00 am to 06:00 am. Display the table in below format.
    | ID | Name | DateOfBirth | DataInputTime | DataInputDate |
    |--|--|--|--|--|

8. Fetch the **Name** of the participants who share the same Date of Births. Display the table in below format.
    | ID | DateOfBirth | Name | Gender |
    |--|--|--|--|

9. Display the Gender ratio in Each Industry. Display the table in below format.
    | Industry | Gender | Percentage |
    |--|--|--|

10. How many people in each industry have the minimum age compared to the other people in the same occupation, still have above average working hours in the industry. Diaplay the table in below format.
    
   | Industry | Occupation | NumberOfYoungMostPeople | TotalNumberOfPeopleInTheOccupation | AverageDailyHoursInTheOccupation | TotalNumberOfPeopleInTheIndustry | AverageDailyHoursInTheIndustry |
   |--|--|--|--|--|--|--|
