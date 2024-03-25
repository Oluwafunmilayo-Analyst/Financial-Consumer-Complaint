# Financial Consumer Complaint Analysis

## Introduction:
Consumer complaints on financial products, services for Bank of America from 2017 to 2023, including the dates the complaint was submitted to the CFPB and then sent to the company, the product and issue mentioned in the complaint, and the company's response.This data was Analyzed using Power BI to derive insight to answer crucial questions and for  informed decision making.

### Data Source

Consumer complaint: The primary source of data set used for this analysis is the "Consumer_Complaint.csv" file, containing the detailed information provided by the Data Professionals.

### Tools 
- Power BI ( Data Cleaning and Visualization)

  - [Download here](https://powerbi.microsoft.com/en-us/desktop/)
 
#### Problem Statement
1. Do consumer complaints show any seasonal patterns?
2. Which products present the most complaints? What are its most common issues?
3. How complaints are typically resolved?
4. Can you learn anything from the complaints with untimely responses?
   

### Data Cleaning and preparation

#### Power Query
The dataset was uploaded in power BI for cleaning and transformed in power query before loading to Power BI for Visualization and analysis. The dataset contains 999+ rows;12 columns before cleaning and  rows;12 columns after cleaning .The data was found to be clean enough to perform the expected analysis.

![new project](https://github.com/Oluwafunmilayo-Analyst/Financial-Consumer-Complaint/assets/164716134/a580e8cf-8e5b-470b-a5e4-3f3231f7d3f6)

After thorough inspections on the data, i noticed the data was clean enough and ready for analysis. The only slight change i made to the data was to insert another column that contanied the year and this was extracted from the date submitted column for easly and comprehensive analysis.

![power query](https://github.com/Oluwafunmilayo-Analyst/Financial-Consumer-Complaint/assets/164716134/267e11a1-abdd-412d-a8a7-98bf70f51853)

#### Dashboard/ Visualization
The dashboard below gives a visual representation to the solution of the problem statement. 

![financial2](https://github.com/Oluwafunmilayo-Analyst/Financial-Consumer-Complaint/assets/164716134/816b0e07-1851-4d0b-9429-7979a630e206)

#### Analysis

1. The customer complaint year on year vary per products and some products rarely had complaints from the customers.In 2017 for example, almost all the products offered by the company had a customer complaint but you will notice that has the year went on the complaint on the products reduced drastically with the exception of checking or saving account product which was slightly increasing and decreasing year on year.
2.  The product that had the most complaint was Checking or saving account with over 20K complaint. The customers were finding it difficult to use this product effectively.
3. Complaint were solved and grouped in different catagories. Closing a complaint with explanation means the company provides an explanation to the consumer that substantively meets the consumer's desired resolution or explains why no further action will be taken. When a complaint is closed, it means that the issue has been resolved or the complaining party has withdrawn their complaint. A complaint closed with monetary relief means the offending company sent a. “measureable” dollar amount to the consumer. Monetary relief includes things like. refunding a penalty fee. Closed with non-monetary relief is the step taken by the company in response to the complaint which did not result in monetary relief, but may have addressed some or all of the consumer's complaint involving non-monetary requests. From the analysis these category of complaint we 20% each of all the data provided.
4. The complaint with timely response was over 50k and the complaint without timely response were very low. This timely response would have resulted in the decrease in the complaint of the customer year on year.

#### Recommendation
The compliation of customer's complaint by Bank would help build a database to better understand the customer's experience with the product provided and the response(solution) gathered can be complied into a repository that is easily accessible by the customers and this would help prospective customers easily navigate through their complaint and it will in turn help the bank attend to new complaint effectively especially when a new product is made by the Bank

#### Reference
1. Maven Analyst
2. Google.com
