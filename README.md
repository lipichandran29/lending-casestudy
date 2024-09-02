# Project Name: Lending Club Case Study

##  Table of Contents
* [General Information](*GeneralInformation)
* [Technologies Used](*TechnologiesUsed)
* [Conclusions](*Conclusions)
* [Acknowledgements](*Acknowledgements)

## General Information
  ### Project Information
    The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

  ### Project Background
    This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower      interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss   
    (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers 
    who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

  ### Project Statement
    Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

  ### Data Set
    The data set is a csv file with the loan data for the Lending Club.

## Technologies Used
    Python
    Pandas
    NumPy
    Seaborn
    MatplotLib
    Plotly

## Conclusions
  * Loans for small business, debt consolidation, and other purposes have the highest default rates, ranging from 15% to 27%.
  * Borrowers in the "High DTI" category have a significantly higher default rate (16.73%) compared to those in the "Low DTI" (12.61%) and "Moderate DTI" (15.13%) categories.
  * Customers from CA, NY, TX, and FL are the largest borrowers of loans, but these regions also have the highest volume of defaults.
  * A strong positive correlation exists between loan amount and the number of installments, suggesting that larger loans are typically repaid over longer periods.
  * Loans with interest rates exceeding 16% have a significantly higher risk of default compared to loans with lower interest rates.
  * Loans with a 60-month term have a significantly higher default rate (25.31%) compared to those with a 36-month term (11.09%). Prefer shorter tenure loan over longer
    tenure loan.
  * Individuals with a history of public derogatory records are more likely to file for bankruptcy. To mitigate risk, Lending Club should implement stricter criteria
    to ensure that borrowers do not have any public derogatory records

## Acknowledgments
  The UpGrad IITB Machine Learning and Artificial Intelligence course provided the inspiration for this case study
