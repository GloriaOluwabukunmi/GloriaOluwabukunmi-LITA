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
The Dataset used for this project comprises of the information of the present and past employees in the company and it was computed by the HR Department. It analyses  the attrition of all the employees in each department inorder to uncover the attrition rate and other causes of attrition among the employees in the company 
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
- Age group by attrition count shows that 17% of male from the R&D department left the company, their average age group was 37 and based on the job satisfactory analysis just 1 person was dissatisfie with the job and othrrs could have left because of their marital issue because 16 wqs divorced and 22 were married.

- Based on the job role satisfactory analysis Laboratory Technician has the highest number of people that were Very Dissatisfied with the Job either because of the pay or their marital status.

- Life sciences has the highest Attrition by Educational field, showing 15% of the Attrition rate out of the 16% of the overall attrition rate
