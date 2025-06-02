🔍 **Overview**
This project explores employee attrition data to uncover the key factors driving workforce turnover. Leveraging a dataset from an HR department, I developed an interactive Power BI dashboard to visualize essential metrics such as attrition rate, total employee count, and more.

🎯 **Objectives**
The main goals of this project are:
+ To identify trends and patterns in employee attrition.
+ To provide actionable insights for HR to reduce turnover.
+ To gain hands-on experience with Power BI for data visualization.

🗂️ Dataset Information
The dataset (`HRAnalyticsEmployeeAttrition`) contains the following columns:
+ `Data Dictionary` – The worksheet that contains the meaning of a column/field and its possible values.
+ `Education` – The worksheet for Education level dimension.
+ `Satisfaction` – The worksheet for Satisfaction level dimension.
+ `Job Involvement` – The worksheet for Job Involvement level dimension.
+ `WorkLIfeBalance` – The worksheet for WorkLifeBalance level dimension.
+ `PerformanceRating` – The worksheet for Performance Rating level dimension. 
+ `WorkLifeBalance` – The worksheet for WorkLifeBalance level dimension.
+ `Employee Data 2018 – 2019` – the worksheet that contains the fact/individual information of each employee.
+ `Attrition Rates` - The attrition rate information given by HR between 2016 to 2020.

💻 **Data Cleaning and Preparation**
1.	Removed duplicates and null values
2.	Reformat some fields necessary for analysis
3.	Created calculated columns `AgeGroup` and `Year` and new 
measures for metrics ` TotalEmployees`,` InactiveEmployees `, `ActiveEmployees`,`%Attrition` rating and Attrition Rate using DAX in Power BI.
4.	Created new relationship and hierarchies.

📈 **Dashboard Insights**
The Power BI dashboard provides the following insights

**1. Overall Metrics**
+ Total Employees:1470
+ Current Employees: 1233
+ Total Attrition: 237
+ Attrition Rate: 16%
+ Youngest Employee : 18
+ Oldest Employee : 60

**Findings based on Employee Demographics**
+ Research & Department employ the highest personnel (828), followed by Sales (354) then by Human Resource (51)
+ Attrition rate was highest during 2018 reporting year: 48%
+ More employees are within the >=30 to < 40 age bracket (622), the least number of employees belongs to >= 50 years (173)
+ Almost half of the employee is currently married (47.58%). Single comprises of 31.97% then divorce at 22.24%
+ As employee grows old and Job level, the average monthly income increases also regardless what department he is.

 **Dashboard Preview:**
![Overview](https://github.com/user-attachments/assets/c88afcf7-f8e5-4f60-82a7-d066e2d59c92)

![Demographics](https://github.com/user-attachments/assets/ff79c055-6093-4c6e-b9f5-8ab0a2b0a0e3)


**Attrition by Department and Job Role**  
+ Attrition rate is high on the Sales and Human Resource Department.

**Attrition by Tenure** 
+ Based on the line graph, attrition rate is high on the first year in the company, then rose during the employees’ 23rd year. This might be due to employee nearing retirement age. 

**Attrition by Travel Frequency**  
+ Employee tends to stay in the company when they just stay in the office rather than doing field work or doing business travel.

**Attrition by Years at Current Role** 
+ Based on the Bar chart, attrition rate is high on the first-year job role in the company, then stabilize a bit then rose again during 15th year in the same job role.


**Dashboard Preview:**
![Performance](https://github.com/user-attachments/assets/97009842-a239-4362-b560-02234b751886)

![Recommendation](https://github.com/user-attachments/assets/c462b607-1f9e-4b12-b401-760eccd334b5)

🛠️ **Tools Used**
+ Power BI: For data extraction,initial exploration,cleaning,visualization and dashboard creation.

📈**Key Learnings**
+ Gained experience in using Power BI for interactive data visualization.
+ Learned to identify key drivers of employee attrition.



**Recommendations**
1.	Enhance Onboarding and Early Engagement -Implement structured onboarding and mentorship programs for new employees to address attrition spikes in the first year and cultivate a positive work experience from the outset.

2.	Strengthen Retention in Sales and HR - Conduct surveys and exit interviews to pinpoint reasons behind high turnover rates. Address challenges such as workload, leadership development, and career progression opportunities.

3.	Support Career Progression and Retirement Planning - Provide opportunities for role rotation or expanded responsibilities for mid-to-late career employees to prevent stagnation. Introduce retirement planning resources and phased transition programs to tackle attrition nearing the 23rd year.

4.	Reduce Business Travel Where Possible - Reassess roles with frequent travel requirements and explore flexible work arrangements or hybrid setups for employees in these positions.

5.	Promote Age-Inclusive Strategies - Develop support systems tailored to both younger and older employees. Foster collaboration and knowledge-sharing initiatives between generations to enhance engagement across all age groups.


**Conclusion**
The analysis of employee demographics and attrition data provides valuable insight into workforce trends and identifies areas requiring focused strategies. With a total of 1,470 employees, the company currently retains 1,233 staff members, indicating a 16% attrition rate. Research & Development and Sales departments have the largest number of employees, while Human Resources has the smallest team.

Attrition rates reveal significant peaks during the first year of employment and around the 23rd year, highlighting critical stages of disengagement: initial adaptation and pre-retirement. Sales and Human Resources departments experience notably higher attrition, which may point to issues such as job satisfaction, workload challenges, or leadership gaps.

Moreover, the correlation between employee age, job level, tenure, and income growth is evident. However, younger employees—especially those in travel-intensive roles or field positions—are more likely to leave the organization earlier, potentially due to challenges in work-life balance or insufficient onboarding.



