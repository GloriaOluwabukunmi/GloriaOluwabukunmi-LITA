## PROJECT TITLE: ANALYSIS OF HR DATA

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCE](#data-source)

[SOME OF THE DATA COLLECTED](#some-of-the-data-collected)

[PROJECT OBJECTIVE](#project-objective)

[DATA ANALYSIS](#data-analysis)

[TOOLS USED IN THE POWERBI VISUALIZATION AND ANALYSIS](#tools-used-in-the-powerbi-visualization-and-analysis)

[DATA VISUALIZATION](#data-visualization)

[INFERENCE](#inference)

### PROJECT OVERVIEW
This employee attrition data analysis project provides a solid foundation for the company to understand the scope of its retention challenges and identify potential areas for improvement. The insights gleaned from this analysis can guide the development of more effective human resource management strategies to retain top talent and minimize the costs associated with employee turnover.
### DATA SOURCE
Data was provided by the HR Department
### SOME OF THE DATA COLLECTED
- Attrition
- Department
- Age Group
- Marital status
- Educaion Field 
- Gender
- Job Role
- Employee Id
### PROJECT OBJECTIVE
The aim of this project is to analyze the attrition rate among the employees in various departments, give possible reasons on the cause of attrition in the company and propose possible solution that can help to reduce or stop the causes of attrition in the company.
### KEY METRICS
- Attrition Rate: Sun or total number of Atrition Count X Sum or total number of Employee and this was calculated using the conditional column
- Average Age: Average age for the total number of Empployee was gotten with the DAX (Data Analysis Expression) FUNCTION called MEASURES.
  ### DATA ANALYSIS
- Importing and Transforming the Excel file provided by the company into Powerbi. This is the firat and a very important steps when analysing data with powerbi. The transform stge was where the data will be cleaned properly inorder to give accurate result while visualizing and analysing.The consistency of the column was checked i.e the column quality, column profile and column distribution.
  ![WhatsApp Image 2024-10-29 at 22 31 22_461af610](https://github.com/user-attachments/assets/14467268-c0c3-431d-be74-e6cc9ca8b749)

- Sum of Attrition was analysed using the conditional column ( YES = employees that have left, NO = emoloyees that are still in the company)
  ![WhatsApp Image 2024-10-29 at 22 31 19_406731fb](https://github.com/user-attachments/assets/0e9a4b28-7f61-4506-bcdd-ffdce30e0789)

-Percentage of attrition rate was calculated usin MEASURES.
ATTRITION RATE= SUM OF ATTRITION COUNT / SUM OF EMPLOYEE COUNT which gave me 16%
- Average age of total number of employee waas analysed with MEASURES using the AVERAGE FUNCTION
- Department by Attrition was analysed with the doughnut visual chart
- Number of current employee by their age group was analysed with the conditional column
  ### TOOLS USED IN THE POWERBI VISUALIZATION AND ANALYSIS
- Conditional colum
- Measures
- Visual charts
- Filters
- Slicers

  ### DATA VISUALIZATION
 ![POWERBI](https://github.com/user-attachments/assets/38361ed9-ce8f-47ab-badb-149d0c86f70c)

 ![WhatsApp Image 2024-10-29 at 22 34 42_632bd3a6](https://github.com/user-attachments/assets/52d77704-10f5-4047-a39d-f6ed51db600c)

 ### INFERENCE
- Attrition Rate Analysis:
The primary goal of this project is to analyze the attrition rate among employees across different departments in the company.
The analysis calculates the overall attrition rate, which stands at 16% according to the information provided.
Determining the attrition rate is a crucial first step in understanding the scope of the employee churn problem the company is facing.


- Demographic Factors:
The dataset includes employee information such as age, marital status, education field, gender, and job role.
Analyzing these demographic factors can help identify patterns and potential reasons contributing to employee attrition.
For example, the analysis of employees by age group can reveal if certain age brackets are more prone to leaving the company.


- Departmental Insights:
Examining the attrition by department provides visibility into which areas of the business are experiencing the highest turnover.
This information can help the company target its retention efforts and resources towards the departments with the most significant attrition challenges.


- Data Preparation and Visualization:
The project highlights the importance of proper data import, transformation, and cleaning in Powerbi before conducting the analysis.
The use of conditional columns, measures, and various visual charts (e.g., doughnut charts) demonstrates the analytical capabilities of Powerbi in uncovering insights from the employee data.


- Proposed Solutions:
While the project overview does not explicitly mention any proposed solutions, the analysis of attrition rates and contributing factors can inform the development of targeted strategies to reduce employee turnover.
Potential solutions could include reviewing compensation and benefits, improving career development opportunities, enhancing work-life balance, or addressing department-specific pain points.



