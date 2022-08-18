# Prosper Loans Analysis
## by Idris Lawal


## Dataset

The dataset consists of information regarding 113937 loans including status, APR, Debt-to-Income ratio and other attributes associated with a loan and borrower from the peer-to-peer online credit marketplace, Prosper Funding LLC, between 2005 (when the company was founded) and 2014.


## Summary of Findings
In the exploration, i found that Annual Percentage Rate (APR) has quite an effect on a loan status i.e it fairly determines if a loan will be completed, defaulted or charged off. From my analysis;

* Completed loans have an average APR of 0.2 and 50% of the APR values are below 0.19.

* Defaulted loans have an average APR of 0.23 and 50% of the APR values are below 0.24.

* Charged off loans had an average APR of 0.25 and 50% of the APR values are below 0.26. </br>

This indicates that loans on low APR have a higher chance of being completed. Other parameters such as Debt-to-Income (DTI) ratio, Income range and Monthly Income also contribute to this effect.

DTI is a measure of how healthy a person finances is. From my analysis majority of the completed loans have borrowers with low DTI ratio which indicates that such person(s) spends less of the income on prior loans, which increase the chances of completing the currents ones. I suspected that high monthly income earners with low DTI ratio would have a high percentage of completed loans and this was found to be true during the analysis, however, the pattern was also present in defaulted and charged off loans. It also observed that borrowers on high income range tend to complete more of their loans compared to those on low income range. Although this might be due to the fact that there are more borrowers in the higher income range but the risk of a loan being defaulted or charged off are low if the borrower is on the high income range.</br>

Futher exploration into other variables of interest revealed that the higher the monthly loan payment, the higher the chances that the loan would be charged off or defaulted. Outstanding principal has a fair effect on the loan status as borrowers with high outstanding principal tends to default on their loans which might end up being charged off. Prosper score show interesting relationship with loan status as most of the completed loans have high prosper score. I also found that majority of the loans listed are for "Debt Consolidattion" i.e most loans are taken out to service/pay off previous loans.


## Key Insights for Presentation

In the presentation, i focused on the influence of Debt-to-Income (DTI) ratio, Annual Percentage rate (APR), Outstanding principal, Income Range and Prosper score. I start off with introducing the loan status variable, then i check the distribution of each numrical variable using a histogram plot and the frequency of the categorical variables with countplots.
</br>

Afterwards, I presented the relationship between the numerical variables and the target variable using a boxenplot and pointplots, then i visualize the relationship between the categorical variables and the target variable using a (adaptive) countplot to depict how each variable stated affect loan status. I wrap up the presentation with a multivariate plot of Income Range and Outstanding Payment by Loan status using a (adaptive) barplot.
