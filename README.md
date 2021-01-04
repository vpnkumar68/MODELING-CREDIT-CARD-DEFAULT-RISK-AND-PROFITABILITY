# MODELING-CREDIT-CARD-DEFAULT-RISK-AND-PROFITABILITY

* Designed and implemented a predictive model to determine which future applicants should be approved for a credit card and which rejected. 
* Develop a binary classification process for “approve” or “reject” designed to maximize total bank profits. (In other wors, maximize average profits per applicant, including in the total number of applicants those that are rejected).
* Not all defaulters are unprofitable and not all non-defaulters are profitable. Therefore, the new relevant profitability metrics assumptions the bank uses are:
* The proportion of applicants that are unprofitable (25%), average losses per unprofitable customer (-$4,900), average profits per profitable customer ($4,000), and average profits per applicant when using no model ($1,775). 
* A “perfect” model that excluded all unprofitable and included all profitable customers would have an estimated profitability per applicant of ($4,000)*.75 = $3,000.
* I have six standardized data inputs available for each customer : Years at employer, Years at address, Income, Credit card debt and Auto debt.
* ``` SCORE = 0.19*Years at employer -0.08*Income -0.19*Credit card debt-0.07*Auto debt ```
* Reported ROC-AUC score of 84% on training data & 83% on test data and accuracy of 81% on training data & 79.5% on test data.
