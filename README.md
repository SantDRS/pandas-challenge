# pandas-challenge
Jose Santos
Module 4 Challenge Analysis

In this assignment, we have used Pandas DataFrames to analyze school and standardized test data. Under the guise of Chief Data Scientist for the district, we attempt to help the school board and mayor make strategic decisions regarding future school budgets and priorities. 

We start by importing the "school_data" to uncover that we're provided with School ID's, school_name, type, size, and budget. 

![Screenshot 2023-01-25 at 9 57 14 PM](https://user-images.githubusercontent.com/43708777/214755640-fcafd4cf-9ddb-4b24-afe3-ae49cd7ac5a1.png)

Additionally, we import the "student_data". This consists of: Student ID, student_name, gender, grade, school_name, reading_score, and math_score. With school_name as a common factor, we merge the files using the schoool_name. 

![Screenshot 2023-01-25 at 9 59 49 PM](https://user-images.githubusercontent.com/43708777/214755881-83c50345-b580-41fb-85e4-f43996c8be53.png)

We count the school data and run the mean of the test scores to find the district summary: 

![Screenshot 2023-01-25 at 10 01 07 PM](https://user-images.githubusercontent.com/43708777/214756006-e8879f91-4a1a-4daf-8091-34ff253ab284.png)

After producing the district summary we proceed to analyze per school and determine: 

  Highest & Lowest Performing Schools (by % Overall Passing). Where based on the information provided we can clearly see that the top five schools are Charter Schools, and that the lowest are District Schools. 
  
  ![Screenshot 2023-01-25 at 10 08 32 PM](https://user-images.githubusercontent.com/43708777/214756735-6e7a88f6-ebff-4725-9efc-f1a5bdf03b13.png)

  ![Screenshot 2023-01-25 at 10 08 57 PM](https://user-images.githubusercontent.com/43708777/214756779-c5a7b015-d144-48e3-be01-a4f5213d9c23.png)

After reviewing the overall schools performance, we continue to analyze the data by grades (Math & Reading Scores by Grade) which I don't include snapshots of here, but instead want to drive the attention to the following. 
  
The Scores by School Spending are filtered and ran to show the below. Surprising, at first we might expect that spending per student might reflect a direct impact on scores. However, after analyzing the data, it doesn't seem to be the case. This could merit more digging into the school budget's to determine how much of the school spending was towards direct education vs administration or other services. Also, this is not analyzed by type of school, which could be skewing the data one way or another. 
  ![Screenshot 2023-01-25 at 10 17 16 PM](https://user-images.githubusercontent.com/43708777/214757547-e11f082a-edc6-42a5-9a7f-0ab58d8a8998.png)

We do however analyze the data by School Size:
![Screenshot 2023-01-25 at 10 21 28 PM](https://user-images.githubusercontent.com/43708777/214757912-d03c803b-d780-43df-a538-c24bf93838e7.png)
&
School Type:
![Screenshot 2023-01-25 at 10 21 56 PM](https://user-images.githubusercontent.com/43708777/214757958-aab91955-05c1-419b-9171-348f31c94500.png)

Based on this information we can understand that the larger District Schools also have signficantly lower average scores compared to the Charter Schools. And, that based on the School Type the average District School has more than two times the number of students and lower scores. However, after taking our analysis one final step forward and including the budgets per school and per student we actually see that Charter Schools have significantly smaller budgets and therefore, also smaller budgets per student. This begs the question, then why/how do Charter Schools achieve significantly higher scores. One inference is that it could be classroom size leading to more attention per student. 

  
  


Additionally, by simply looking at the Total School Budget's we'd be misled to believe that a lack of resources is not the case when compared to charter schools. However, if we were to compare 

•	Summarizes the analysis (5 points)
•	Draws two correct conclusions or comparisons from the calculations (10 points)
