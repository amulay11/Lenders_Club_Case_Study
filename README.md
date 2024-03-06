# Lenders Club Case Study
> The project objective is to perform exploratory data analysis on a loan data set to understand how consumer attributes and loan attributes influence the tendency of default (charge off) of a loan


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background: Lenders club is a finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. The company has to make a decision with least risk involved such that it does not give loans to individuals who may default and at the same time does not reject the loans for individuals who have a good probability of paying off the loan
- Dataset: The data given contains information about past loan applicants and whether they ‘defaulted’ or not.
- Business problem to solve: Identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- python - version 3.11.5
- pandas - version 2.0.3
- seaborn - version 0.12.2
- matplotlib - version 3.7.2
- numpy - version 1.24.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Conclusions
- The loan amount for more than 50% of the applications lies between 5000 to 15000. 
- For 95% of applicants the annual income lies between 20k to 185k
- For more than 70% of the cases the debt to monthly income ratio lies between 5% to 22%
- Though charged off loans with term of 36 are higher in numbers, the loans with term 60 months have higher percentage of charge off
- The percentage of charged off loans increases with the count of derogatory public records and publicly recorded bankruptcies
- The percentage of charged off loans increases with loan grade from A to G and at the same time % of fully paid loans decreases
- More than 25% of loans taken for small business get charged off, next higest percentage is that of renewable energy at more than 18%
- More than 50% of the charged off loans are from the states of CA, FL, NY, TX, NJ and GA
- Loan accounts with higher interest rates range have higher percentage of charged off loans
- Loan accounts with higher loan amount range have higher percentage of charged off loans
- The percentage of charged off accounts is low in case where the loan amount is a smaller percentage of individuals annual income
- Loans for individuals with low annual income and interest rates between 10 to 20% have a higher concentration of charge offs
- Loans of amount up to 15000 and interest rate between 10 to 17.5% have higher concentration of charge offs
- 86% of overall loan charge offs are for the individuals with annual income less than 90000
- If we observe the charge off peaks in the pair plot historams, the peaks are at - lower range of loan amount, mid range of interest rates and towards higher DTI
- Low DTI but mid to high interest rate also shows a cluster of charged off loans
- Higher loan amount percentage vs annual income and mid to high interest rate also shows a cluster of charged off loans
- Thus overall the factors influencing the loan charge off are low annual income, high loan amounts, high interest rates, derogatory public records, loans for purposes such as small business and higher DTI


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



## Acknowledgements
- This project is based on case study provided as part of Upgrad course on AI & ML
- References used for study of credit risk analysis
    https://corporatefinanceinstitute.com/resources/commercial-lending/credit-risk-analysis/
    https://www.investopedia.com/terms/l/lossgivendefault.asp
    https://www.wallstreetmojo.com/probability-of-default/
    https://www.fico.com/en/products/fico-score

- Tutorials/Documentation used:
https://seaborn.pydata.org/generated/seaborn.barplot.html
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.legend.html
https://seaborn.pydata.org/generated/seaborn.boxplot.html
https://matplotlib.org/stable/gallery/pyplots/index.html
https://seaborn.pydata.org/generated/seaborn.countplot.html
https://towardsdatascience.com/10-must-know-seaborn-functions-for-multivariate-data-analysis-in-python-7ba94847b117


## Contact
Created by [@amulay11] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->