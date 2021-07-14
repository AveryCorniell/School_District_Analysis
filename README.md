Skip to content
Search or jump to…

Pull requests
Issues
# School_District_Analysis  

## Purpose of this Analysis is to Provide the Following:  

- Preparing all standardized test data for the purposes of analysis, reporting, and presentation  
- Used to inform discussions and make informed decisions at both the school and district levels
- Aggregate data to showcase trends and patterns and school performance

- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format

### Tables presenting each of the following metrics are delivered as a part of this analysis:  
- Top 5 and bottom 5 performing schools, based on the overall passing rate  
![Bottom_5](https://user-images.githubusercontent.com/83401820/125694809-e4430560-6a3a-498b-b836-294a997af79f.png)  
![Top_5](https://user-images.githubusercontent.com/83401820/125694816-57be5c30-83f9-44b9-96ea-75e248e43c72.png)  

- The average math score received by students in each grade level at each school  
![Average_Math_ByGrade_NaN-THS](https://user-images.githubusercontent.com/83401820/125694817-c5226b8c-9a1c-4f73-b9a1-74116629d4fd.png)  
 
- The average reading score received by students in each grade level at each school  
![Average_Reading_ByGrade_NaN-THS](https://user-images.githubusercontent.com/83401820/125694818-89170b11-0cfd-4dce-a0bd-42d64582f200.png)  

- School performance based on the budget per student  
![Performance_Budget](https://user-images.githubusercontent.com/83401820/125694813-8eca2e82-1d8d-48e2-b72c-30ea010b52c3.png)  

- School performance based on the school size  
![Performance_School_Size](https://user-images.githubusercontent.com/83401820/125694814-f5c484f0-104d-424e-a9c5-532327e7fd9e.png)  

- School performance based on the type of school  
![Performance_School_Type](https://user-images.githubusercontent.com/83401820/125694815-b905c953-fafc-4de1-91ee-0c15a8a49eab.png)  
  


## The following two data sets were reviewed and utilized for analysis:  
### -File: students_complete.csv  
- 39170 records  
- 7 columns
- 1 header row - (resized columns and updated Headers to proper case for readability)  
	- Student_ID  
	- Student_Name - need to remove the Dr. from all students with this prefix  
	- Gender  
	- Grade  
	- School_Name   
	- Reading_Score  
	- Math_Score  
### -File: schools_complete.csv     
	- 15 records  
	- 5 columns  
	- 1 header row - (resized columns and updated Headers to proper case)  
	- Student_ID  
	- School_Name  
	- Type  
	- Size  
	- Budget      

**NOTE: THE STRICT ADHERENCE TO THE FERPA ACT OF 1974 APPLIED WHEN ACCESSING/ANALYZING/REPORTING ANY AND ALL STUDENT/SCHOOL DATA**  

## Results:  

#### The district summary shows that:  
![District_Summary_NaN-THS](https://user-images.githubusercontent.com/83401820/125694810-00fee603-77bd-4cb4-ad7a-95d28dc89150.png)  
	- The total budget for all 15 schools in the district amounts to well over $25 million
	- Of the 39,170 students in the district where 70% is a passing score 
		- average math scores were 78.9  
		- average reading scores were 81.9  
		- 75% of the students passed math  
		- 86% of the students passed reading (11% better than math)  
		- 65% of the students passed both math and reading  
			- approximately 4,000 students who passed math did not pass reading   
			- approximately 8,000 students who passed reading did not pass math  
	- The total budget for all 15 schools in the district amounts to well over $25 million  
	
#### The school summary shows that with the exception of Thomas High School, the following is true:  
![Per_School_NaN-THS](https://user-images.githubusercontent.com/83401820/125694811-23f9ae1c-1694-457f-ad09-45605097594d.png)  
	- The Charter schools did considerbly better than the District schools  
	- The Charter schools had a much smaller student body compared to the District schools  
	- The Charter schools and and the District schools budgets per student are within $100 difference  
	- The Charter schools had a more balanced math/reading score ratio with both scores being the same or nearly the same  
		- the same is true for the percent of students who passed math and reading
	- The District schools had a wider gap between math and reading scores  
		- the same is true for the percent of students who passed math and reading
	- There is nearly a 40 point gap in the overall percentage of students who passed both math and reading  
	  between the Charter and District schools

#### By removing the 9th graders from the summary, the following is true: 
	- the aforementioned analysis becomes wholly true  
	- the test scores remained exactly the same  
	(indicates 9th graders did not take test or their scores were not calculated)  
	- the passing percentage now appears to be consistent with other Charter Schools

#### Replacing the ninth-grade scores had the following affects:  
	- Math and reading scores by grade  
	None
	- Scores by school spending  
	None
	- Scores by school size   
 	None
	- Scores by school type   
	None

### To summarize changes in the updated school district analysis after reading and math scores  
for the ninth grade at Thomas High School have been replaced with NaNs was that:  
	- the data between the Charter schools became more uniform/consistent as Thomas High School was previously the outlier among them 
	- the passing math percentages increased by 27%  
	- the passing reading percentages increased by 28%
	- the overall passing percentages increased by 25%
	
	
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
