# Lending Club Case Study
> This project analyzes loan data from Lending Club to identify key factors influencing loan defaults using Exploratory Data Analysis (EDA). The goal is to minimize financial risk by predicting borrower behavior.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Project Background: The study is focused on risk analytics in financial services, specifically examining loan default behaviors at Lending Club.
- Business Problem: The goal is to identify high-risk borrowers to reduce potential financial losses from defaults.
- Dataset: The project uses past loan applicant data, including borrower profiles, loan terms, and repayment statuses.

## Conclusions
### What We Did:
- We used various data points—like loan grades, borrower behavior, and loan purposes—to figure out what makes someone more likely to default on their loan. We built a Credit Risk Score that combines these factors and tells us how risky each loan is.

### Key Findings:
- Loan Grades Matter: Loans with lower grades (D, E, F, G) had a much higher chance of defaulting compared to higher grades (A, B, C).
- High Utilization Rates Are Risky: Borrowers using a lot of their available credit were more likely to default.
- Loan Purpose is Key: Loans for things like Small Business and Renewable Energy showed higher default rates, so they’re riskier.
- Past Behavior Predicts Future Risk: Borrowers with past delinquencies were more likely to default again, which makes sense—past behavior is a strong indicator of future actions.
- Location Matters: Some states like Nevada and Florida showed higher default rates, meaning geographical location plays a role in risk.

### Credit risk score
- We combined all these factors into a Credit Risk Score, fine-tuning the weights of each factor to reflect their impact on default risk.
- The score effectively separated risky loans from safer ones, helping us identify which loans need stricter approval criteria or higher interest rates

### Recommendations:
- Use the Score in Decision-Making: The Credit Risk Score can help the company decide which loans to approve, adjust loan terms, or set interest rates based on risk levels.
- Focus on High-Risk Areas: Be extra cautious with loans for risky purposes or in high-default states.
- Keep Updating the Score: Regularly check and adjust the Credit Risk Score to keep it accurate as market conditions change.


## Technologies Used
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook



## Contact
Created by @sachinbehl - feel free to contact me!
