# School_District_Analysis
Challenge #4

School_District_Analysis

Overview of the School District Analysis
Results

The school board has requested us to analyze the entire district involving funding and student grades and provide any new insights and performance of the schools. During the analysis we were informed of suspect results from a particular group of students at one of the schools. Our process was to perform the analysis twice - once with the full data set then again isolating the suspect data and excluding it.
•	How is the district summary affected?
Once taking a look at district summaries from both pycityschools_challenge district summary was not affected.
•	How is the school summary affected?
![Screen Shot 2021-12-26 at 12 56 44 PM](https://user-images.githubusercontent.com/91812090/147417523-7e161dd6-cbb4-484f-b032-8cdc5295ac90.png)
  .All scores changed by less than 0.5 percentage points(or changed by less than 0.5%) - there is no changes on school or student count.

  .The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN.
The passing for Thomas High School was 90.94% in pycityschools, with the 9th graders removed the total passing shrinks by 0.3%
•	How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
[Screen Shot 2021-12-26 at 1 02 27 PM](https://user-images.githubusercontent.com/91812090/147417628-f2ede974-804e-4d51-ba66-1d7fd8bd1137.png)
 This does not affect either the math scores or the reading scores. Upon investigation we believe they are not including most 9th graders scores because they might bring the school even further down in test scores.
 Top 5 performing schools:
![Screen Shot 2021-12-26 at 1 07 20 PM](https://user-images.githubusercontent.com/91812090/147417710-a8157023-a715-44be-8327-e9d59d8eb946.png)
Bottom 5 performing schools:
![Screen Shot 2021-12-26 at 1 08 50 PM](https://user-images.githubusercontent.com/91812090/147417757-9a836562-b2b5-4e20-a708-a8670959e8af.png)

 
Purpose

The purpose of this project is to analyze the School District data on basis of school budget, student scores as per their grades. Also, to learn new insights which will give us clear view of results on each school's performance.


•	How does replacing the ninth-grade scores affect the following:
  .The overall passing percentage for Thomas High School fell to 65%
  .The overall passing percentage for the entire district fell to 64.9%
  .Thomas High School was no longer included on the list of top five schools.

How does replacing the ninth-grade scores affect the following:
  .The overall passing percentages of Thomas High School decreased by 0.11%
  .The average scores of Thomas High School for math and reading increased by 0.06
  .For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
  .School rankings are unchanged. Thomas High School is still the second-best performing school in the district with an overall passing rate of 90.63% among their            tenth through twelfth graders.

Math scores by grade
![Screen Shot 2021-12-26 at 1 16 24 PM](https://user-images.githubusercontent.com/91812090/147417908-705ab203-db3e-4a70-bd2f-dfcbe712ada0.png)
Reading scores by grade
![Screen Shot 2021-12-26 at 1 17 48 PM](https://user-images.githubusercontent.com/91812090/147417929-8a5dd19a-5f03-492f-8b73-dd79d6a003a9.png)

Scores by school spending

Score by school spending Original:
![Screen Shot 2021-12-26 at 1 19 09 PM](https://user-images.githubusercontent.com/91812090/147417962-e85fd58c-d19c-48ac-8f9e-6b507975fe18.png)
Score by school spending Updated: 
![Screen Shot 2021-12-26 at 1 21 12 PM](https://user-images.githubusercontent.com/91812090/147417994-4d65890a-4f9e-4ec2-bd9a-2b36aa258f54.png)
Scores by school size:
![Screen Shot 2021-12-26 at 1 22 31 PM](https://user-images.githubusercontent.com/91812090/147418031-6904913e-766e-4fc9-9c19-fe2bdc83e55d.png)
Scores by School Size - changes to Medium (1000-2000) grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).
Scores by school type:
![Screen Shot 2021-12-26 at 1 24 06 PM](https://user-images.githubusercontent.com/91812090/147418057-a6c181b3-4e1f-4259-8dba-b1ff6c505dfb.png)
Scores by School Type - changes to Charter type grouping for all scores by less than 0.1 percentage points (or change by less than 0.1%).

Summary:

After replacing reading and math scores to Nan for the ninth grade at Thomas High School, some changes occurs in School district analysis:

Relacing by the ninth graders' scores with NaN, Thomas High School's overall passing percentages and average scores changes abruptly.

The district has also had its average math and reading scores decrease, as well as the overall passing percentage for students.

In addition, Thomas High School lost its ranking as a top five school within this District.

But after updating the total student counts and exclude it to the Thomas High School ninth graders and removing their scores from the school data, Thomas High School again reach to its high average scores and gain its position as the number two school in the District.



