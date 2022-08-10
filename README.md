# Lending Club
Lending Club is a case study on performing extrapolatory data analysis

## Table of Contents
* [Objective](#objective)
* [Study Details](#study-details)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Objective
- The main objective of this study is to determine top 5 attributes of loan applicants, which can identify if they default or not based on preliminary data analysis.

## Study Details
- The investors are interested in understanding the factors responsible for lending a loan
- Historical data set of defaulted loans and fully paid loans is provided.
- The goal is to perform the following activities using the historical data
  - **Data Understanding**: Understand various attributes of data and their types.
  - **Data Cleaning**: Perform tasks such as handling missing values, handling outliers, etc
  - **Data Analysis**: Perform various analysis for 
  - **Recommendations**: Provide the details of 5 good indicators found in above analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Strong Indicators :
  - **Grade**
    - Borrowers with grade 'A' are highly unlikely to default. 
    - Targeting these borrowers will reduce the risk.
    - Borrowers with grade 'C' and above are more likely to default.

  - **Revolving utilization ratio**
    - Target borrowers with lower revolving ratio for reducing risk of default

  - **is_inq_last_6mths
    - Look for borrowers who have not done any inquiries in last six months for reducing the risk of default

  - **Debt to income group**
    - Borrowers having Low debt to income group (dti <= 10) are less likely to get default.
    - On other hand, borrowers having High debt to income group (dti > 20) are more likely to default.

  - **Annual income group**
    - More defaulters from the low annual income group

- Weak Indicators:
  - Home ownership
  - Verification status
  - Loan purpose
  - Revolving Balance
  - Borrower's address state
  - Does Borrower has any public records
  - Does Borrower has any deliquents in last 2 years
- Further two or more indicators can be combined together and check if the resulted one is a good indicator or not.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy 
- pandas 
- matplotlib
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is my first one on extrapolatory data analysis. I'd like to thank my group member, **Pramod Khandare**, and the mentor, **Siddesh Gunjal**.

## Contact
Created by [@gpacju] - feel free to contact me!

