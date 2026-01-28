# Banking-Analysis

# 📌 Project Overview

This project focuses on banking risk analytics by analyzing customer-level financial data to understand loan exposure, deposit strength, and risk concentration across different banking sectors. The solution combines Python-based exploratory data analysis (EDA) with interactive Power BI dashboards to support data-driven lending and liquidity decisions.

The analysis is segmented into four major banking sectors:

Retail Banking

Private Banking

Institutional Banking

Commercial Banking

# 🎯 Business Problem

Banks face significant risk when:

Loan exposure grows faster than deposits

Business lending becomes highly concentrated

Customer risk is not segmented effectively

Without clear visibility, this can lead to:

Higher default rates

Liquidity issues

Poor credit decisions

This project aims to provide actionable insights to help banks balance growth with risk.

# 🧠 Project Objectives

Analyze loan vs deposit behavior across banking sectors

Identify high-risk and high-value customer segments

Detect risk concentration in business and institutional lending

Build an interactive analytics dashboard for decision-makers

# 🗂️ Dataset Description

The dataset consists of multiple interrelated tables connected via primary and foreign keys, including:

Client Banking Details

Banking Relationship

Gender

Institutional Advisor

Time Period

Key Attributes

Loan amounts (Bank Loan, Business Lending, Credit Cards)

Deposit amounts (Savings, Checking, Foreign Currency)

Income levels

Customer engagement duration

Demographic details

# 🧪 Python Analysis (EDA)

Python was used to perform data validation and exploratory analysis before visualization.

Key EDA Tasks

Data cleaning and preprocessing

Distribution analysis of loans and deposits

Income band segmentation (Low / Medium / High)

Engagement duration analysis

Identification of outliers and skewed distributions

Tools Used

Pandas

NumPy

Jupyter Notebook

# 📊 Power BI Dashboard Design
Dashboard Structure

Home / Overview Page

High-level KPIs for loans, deposits, and customers

Sector-wise Summary Pages

Retail

Private Banking

Institutional

Commercial

Loan Analysis Pages

Loan distribution by income band, nationality, and sector

Business lending concentration

Deposit Analysis Pages

Savings vs checking account behavior

Deposit strength across customer segments

# 📈 Key KPIs

Total Loans: $4.38bn+

Total Deposits: $3.77bn+

Business Lending: $2.6bn+

Savings Accounts: $698M+

Checking Accounts: $963M+

# 🔍 Key Insights

Institutional and commercial sectors carry high concentration risk due to large business loans

Retail banking shows stable deposits and lower risk

Private banking delivers high value per client but requires close monitoring

Medium-income customers contribute significantly to both loans and deposits

Strong customer engagement correlates with higher deposit stability

# 💡 Recommendations

Diversify lending to reduce exposure concentration

Strengthen credit monitoring for institutional and commercial clients

Leverage deposit-rich segments for cross-selling opportunities

Integrate credit scores and repayment history for predictive risk modeling

# 🛠️ Tech Stack

Python: Pandas, NumPy, EDA

Visualization: Power BI

Analytics: DAX, Data Modeling

Domain: Banking & Financial Risk Analytics

#🚀 Future Enhancements

Predictive default risk modeling using machine learning

Time-series forecasting for loans and deposits

Automated early-warning risk alerts

Loan approval recommendation system
