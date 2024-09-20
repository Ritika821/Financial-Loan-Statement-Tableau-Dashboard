# Financial-Loan-Statement-Tableau-Dashboard


## Introduction :

This is about the Financial Loan Statement of a Bank of United Sates. This contains Borrower's Id, Address State of the Borrower's, Application Type, Borrower's employment length, Borrower's Employment title, Creditworthiness Grade, Subgrade, Borrower's home ownership, Issue Date, Loan Status, Purpose, Term of Loan, Id verification status, Borrower's Annual Income, Debt to Income Ratio, Installment, Interest Rate, Loan Amount and Total Payment. This project include skills like Dashboard, Tableau, MTD, PMTD, MoM, KPI, Data Visualisation Techniques, Calculated Fields, Buttons, Progress Chart, Lollipop Chart, Bar Chart, Map Chart, Data Cleaning, and Filters It gives KPIs like Total Loan Applications, Total Funded Amount, Total Amount Received, Average Interest Rate and Average Debt to Income Ratio. This Dashboard consist of 3 page Overview, Detail and Summary. In this we have compared between Good Loan and Bad Loan issued by Borrowers, Total Loan Applications and Purpose, State, Month, Term, Employment Length and home ownership.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Financial%20Loan.jpg" width="700" height="300">
</a></p>

----------------------------------------------------------------------------------------------------------------------------------------------------------------


## This Project Includes :

- **Data Import :** Connected data from the Text File and Transform it by ensuring accurate Data Type.
- **Data Processing :** Ensured accuracy and consistency in the data with the help of Excel Advanced Features.
- **Performing Descriptive Analysis :** Created various Calculated Fields, generated KPI by selecting the significant columns from vast data
- **Data Visualization :** Constructed some meaningful insights from the processed data through Show me Field and alter the format of charts in Marks Pane.
- **Creation of Dashboard :** Assembled all the significant worksheets in the dashboard sheet with some additional features like Filters, Buttons, Images etc. from the Objects field.

----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Project KPI :

In this Project, I have generated measures like Total Loan Applications i.e. 38.6K, its Month till Date is 4.3K and Month over Month is 6.9%, Total Funded Amount i.e. $435.8M, its Month till Date is $54.0M and Month over Month is 13.0%, Total Amount Received i.e. $473.1M, its Month till Date is $58.1M and Month over Month is 15.8%, Average Interest Rate i.e. 12.05%, its Month till Date is 12.4% and Month over Month is 3.5% and finally Average Debt to Income Ratio i.e. 13.33%, its Month till Date is 13.7% and Month over Month is 2.7%. In this Month over Month is calculated by (Current MTD - Previous MTD)/Previous MTD.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/KPI.png">
</a></p>

------------------------------------------------------------------------------------------------------------------------------------------------------------


## Important Questions derived from the Project :

1. What is the percent of Good Loan issued by the borrowers out of total loan applied ?
2. What is the percent of Bad Loan issued by the borrowers out of total loan applied ?
3. Which type of Loan Status is maximum in number of loans than others ?
4. In which month there is maximum loan applied by the borrowers ?
5. Most of the borrowers belong to which state ?
6. Most of the borrowers borrow loan for how long ?
7. Most of the borrowers are how much experienced ?
8. Which is the most common purpose of borrowing loan ?
9. Most of the borrowers belongs to which type of home ownership rent, mortgage, own or others ?

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Based on the report Insights, here are the outcomes :

In this Report, I have used three dashboards and those are controlled by Buttons inside the Menu Box. These dashboards are Summary, Overview and Detail Dashboards.

1. This is a Progress Chart of the Total Good Loans Issued by the Borrowers. Here Good Loan refer to those loans that were paid on time with the interest rate therefore it attracts a lower interest rate. the total good loan application is higher than bad loan applications i.e. 86.2%. Its total funded amount and total amount received is also higher than Bad Loans.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Summary/Good%20Loan%20Issued.png" width="400" height="200">
</a></p>

2. This is a Progress Chart of the Total Bad Loans Issued by the Borrowers. Here Bad Loan refer to those loans that were not paid on time with the interest rate therefore it has higher interest rate. the total bad loan application is less than good loan applications i.e. 13.8%. Its total funded amount and total amount received is also lesser than Good Loans.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Summary/Bad%20Loand%20Issued.png" width="400" height="200">
</a></p>

3. This is a Table of Loan Status means Charged Off, Current or Fully Paid. In this I have comparison between these three Loan Status then I found that Fully Paid type Applications are more than other two applications. Therefore its Average Interest Rate and Average Debt to Income Ratio is less than others. Current Loan type is less than other therefore its Average Interest Rate and Average Debt to Income Ratio is high.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Summary/Loan%20Status.png" height="200">
</a></p>

4. This is an Area Chart, from which I got that from January there is slightly decline till February then afterward there is rapid growth in the total Application till last month. From 2.3K in January it became 4.3K till December.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20Months.png" width="400" height="200">
</a></p>

5. In this Map Chart, I got that California (CA) has maximum loan applications than other states followed by New York (NY) and Florida (FL) whereas Maine (ME) has the least loan applications followed by Nebraska (NE) and Iowa (IA).

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20States.png" width="400" height="200">
</a></p>

6. In the Donut Chart, I have presented two types of term of loan i.e. 36 months and 60 months and I came to know from this Chart is that people mostly borrow loan for 36 months, mean out of total applications, 28.2K applications are for 36 months and rest 10.3K applications are for 60 months.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20Term.png" width="200" height="200">
</a></p>

7. This is a Horizontal Bar Chart that represent the total employment experience of the borrowers which indicates that mostly borrowers belongs in 10+ years of experience followed by 1 and 2 years of experience whereas least belongs in 9 years of experience followed by 8 and 7 years of experience.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20Employment%20Length.png" width="400" height="200">
</a></p>

8. In this I have used Horizontal Lollipop Chart that displays the comparison between the purpose of loan on the basis of total loan applications in which I found that people mostly borrow loan for the purpose of Debt Consolidation followed by Credit Card whereas rarely they borrow for renewable energy, education and vacation.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20Purpose.png" width="400" height="200">
</a></p>

9. Under this Tree Map Chart that shows the comparison between the home ownership status of the borrower on the basis of total loan applications in which I got that most of the borrowers belongs to Rent house followed by Mortgage whereas least belongs to Own house and others.

<p align="center">
<a><img src="https://github.com/Ritika821/Financial-Loan-Statement-Tableau-Dashboard/blob/main/Graph/Overview/Total%20Application%20by%20Home%20ownership.png" width="200" height="200">
</a></p>

------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Conclusion :

This Dashboard is of Financial Loan Statement of US Bank under which I have analyzed total loan application with various types of borrowers on the basis of month, state, term, employment length, purpose, home ownership, good loan and bad loan. This will help us to get meaningful information about types of loan in US mostly borrowed, the common purpose in whole US for borrowing loan, common borrower, Grade of the borrowers in US etc. This finally conclude that maximum total application is issued in CA state of US, it is mostly issued in December month, major term is 36 months, maximum employment length who has borrowed is +10 years, major purpose is Debt Consolidation and major borrower's home ownership is rent and mortgage.

------------------------------------------------------------------------------------------------------------------------------------------------------------------


## Author :

- [@Ritika821](https://github.com/Ritika821)
- Ritika - Data Analyst

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
