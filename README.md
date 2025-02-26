# Lending Club Analysis

Company is the largest online loan marketplace, offering personal, business, and medical loans through a fast online platform.
The company faces financial risks due to credit loss, which occurs when borrowers default on their loans.
Charged-off customers are the primary contributors to these losses.


## Table of Contents
* [General Info](#general-information)
* [Key findings](#key-findings)
* [Recommendations](#recommendations)
* [Technologies Used](#technologies-used)
* [Contacts](#contacts)


## General Information
This project aims to identify high-risk applicants using exploratory data analysis (EDA) to help reduce credit losses.By understanding key factors behind loan defaults, Company can improve risk assessment and refine its loan approval strategy.Researching risk analytics will provide further insights into significant variables affecting defaults

The key challenge for Company is **minimizing credit losses** while maximizing profitability. The company must balance two critical aspects:  
unnecessary rejections.  
1. **Identifying high-risk applicants** to prevent financial losses due to defaults.  
2. **Approving creditworthy applicants** to generate revenue through interest payments while avoiding 

By understanding the **factors influencing loan defaults**, Company can refine its **risk assessment strategies** and make more informed lending decisions.  

The project utilizes the **loan dataset from year 2007 to 2011 year** ([loan.csv]). This dataset contains various borrower details, including loan amounts, interest rates, credit scores, and repayment status. Through **exploratory data analysis (EDA)**, the dataset will be examined to identify patterns and risk factors associated with loan defaults.  

*. Dataset includes:
- Borrower demographics
- Loan characteristics
- Credit profiles
- Payment histories
- Verification statuses
- Geographic distribution
- Income and employment data

## Key findings
1. **Borrower Profile**
- 14% overall default rate across portfolio
- Employment length >10 years indicates higher stability
- Income alone is not a strong default predictor
- Geographic concentration in CA, NY, TX, FL with varying risk levels
2. **Loan Characteristics**
- Grade B and C loans show unexpectedly high defaults
- Debt consolidation represents highest default volume
- Interest rate, grade, and term have strongest correlation with defaults
- $20,000 payment threshold identified as critical default risk indicator
3. **Risk Indicators**
- Income-to-loan ratio strongly predicts default risk (20% at low ratios)
- Payment patterns in first 6 months crucial for default prediction
- Verification status has minimal impact on reducing defaults
- Most defaults occur early without extended late fee periods
4. **Payment Behavior**
- Strong correlation between different payment metrics
- Early payment patterns better predict defaults than credit profiles
- Revolving utilization shows minimal correlation with defaults
- Late fees and recoveries operate as independent risk factors

## Recommendations
1. **Risk Detection Enhancement**
- Implement real-time payment monitoring
- Focus intervention in first 6 months
- Set automated triggers for irregular payment patterns
2. **Lending Criteria Reform**
- Enforce strict income-to-loan ratio thresholds
- Strengthen debt consolidation screening
- Develop region-specific risk models
3. **Risk Assessment Optimization**
- Prioritize payment history for assessment
- Reform Grade B/C evaluation criteria
- Implement $20,000 payment threshold monitoring
4. **Implementation Strategy**
- Focus on early payment pattern monitoring
- Enhance income-to-loan ratio controls
- Develop targeted intervention programs

## Technologies Used
- Pandas version: 2.2.2
- Python version: 3.11.11 
- Matplotlib Version: 3.10.0
- Seaborn Version: 0.13.2

## Contact
Created by [@amitkmrjha](https://github.com/amitkmrjha) & [@tuyettu1712](https://github.com/tuyettu1712) - feel free to contact any one of us!

## Dataset
https://drive.google.com/drive/folders/1KxROT45QQPCEaNrqlkvHXyZUIKGCvM6Q 

