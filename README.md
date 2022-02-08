# Loan RISK Analysis 
> Suman Samarthi & Pruthvi HN consumer finance company
Here we take loan applicaiton's for all type of loans. 
Analysis the RISK driving factor and provide details about who can go as defaulters based on DRIVER variables or factors.

Provide Analysis Approach to implement suggestions like:
- Reducing loan amount
- Increase Interest rates
- Deny loan totally

The intent of the company is to :
1. Reduce/aviod the CREDIT LOSS to the COMPANY by tracing out the defaulters/charged-off applicants.
2. Reduce Finalcial Loss: Do not loose right candidate who are capable of return back the loan amount.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->


## General Information
- LC Suman&Pruthvi Project details about how a consumer finance company analyse the historic data .
  Comes up with a pattern on analysing driving factors for applicants becoming defaulters.
- Reducing credit loss and Finance loss to the company.
- Data set used is provided by LENDING CLUB.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Based on the above HISTOGRAM plot its evident that the number of "charged-off" applicants increases with "revol_util" % increment.
- The LOAN amount and the INTEREST rates given to NONE category applicants are less on an average, compared with other category applicants.
- When performing deep dive into the data to see NONE applicants . It observed that there are only THREE applicants part of that category.
Instead of considering this type , its better to ignore as an OUTLIER's category.
- Analysis gave information about how the purpose of loan is influencing the number of charged-off applicants.
- the probability of charged-off applicants is increasing along with the raise in DTI ratio.
- Observed that the LOAN amount is raising every year and charged-off and fully paid also raising equivalent. Charged off applicants are close to 1/4th of the fully paid applicants during 2011.Which is HIGH compared to other years.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy :(For scientific mathematics)
- pandas : (Univeriate biveriate analysis)
- matplotlib: (For visualization using plots and graphs part of analysis)
- seaborn: (For even detailed visualization part of analysis)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was UPGRAD CASE STUDY..
- References if any...
- This project was based on German Credit data [this tutorial](https://www.dropbox.com/scl/fo/yd4atqm3xmz8yid28ncgo/h?dl=0&rlkey=dur0x2cmtktygqssmuyeqrz9z).


## Contact
Created by [https://github.com/sumanes4u] 
           [https://github.com/pruthvipheonix/]
- feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->