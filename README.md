# Project Name: Lending Club
Lending Club Case Study: Given a loan data frame and asked to comeup with some patterns using EDA concepts.
Finally conclude some observations which can help to approve or reject loan application


# Table of Contents
1. Data Analsis
2. Data cleaning
3. Derive new columns
4. Convert object/folad datatype to integer datatype for plotting
5. Execute Univariate on important variables
6. Execute Bivariate on combination of variables
7. Run Multivariate analysis
8. Conclude some observations



## General Information
Goal is to identify certain patterns, which helps to execute final decision on the loan application to be accepted or rejected
Identify pattern who falls under ‘Fully Paid’ category, but low to moderate chances that he/she may fall in charged off category in future
Identify pattern who falls under “Charged Off’ category, still can accept their loan applications.


## Conclusions
### "Charged Off" category:
  1. Higher is the interst rate, more chances of applicants falling in "charged off" category
  2. Higher is the interest rate when having low grades may fall in "charged off" categroy
  3. Seeking loans for small business, other, house categories may fall in "charged Of" category
  4. Up to some extent, with less income <30k and are having revol_credit score more than 30% may fall in "Charged Off" category
  5. pub_rec having 1 and 2 and having court cases have high chances to fall in "Cahrged Off" category
  6. Less is the income and having high interest rate have high chances to fall in "Charged Off" category
  7. High chances of “Charged off” ration when having more bankrupt cases
### "Fully Paid" Category: 
  1. High risk to provide loans when having pub_rec as 1 and 2 and having court cases
  2. High risk when revol_credit score greater than 30% and getting less income
  3. High risk when interest rate is high for low-income people
  4. Low risk when getting less income and having least grades

## Technologies Used
- Jupytor Notebook
- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
### References
-   https://www.youtube.com/watch?v=GGL6U0k8WYA
-   https://www.youtube.com/watch?v=4DnWYK88-E4
-   https://www.youtube.com/watch?v=Bjz00ygERxY
-   https://medium.com/@ozan/interactive-plots-with-plotly-and-cufflinks-on-pandas-dataframes-af6f86f62d94
-   https://pythonguides.com/what-is-matplotlib-inline/
-   https://towardsdatascience.com/financial-data-analysis-2f86b1341e6e
-   https://towardsdatascience.com/pandas-tips-and-tricks-33bcc8a40bb9
-   https://www.geeksforgeeks.org/how-to-reset-index-after-groupby-pandas/
-   https://www.w3resource.com/pandas/dataframe/dataframe-unstack.php
-   https://towardsdatascience.com/financial-data-analysis-80ba39149126

## Contact
Created by @ibmfagroup - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
