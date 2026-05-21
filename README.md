# Digital Lending Portfolio Optimization  
### Consulting-Style Risk Analytics & Portfolio Strategy Project

## Overview
This project simulates a real-world digital lending institution operating in emerging markets and applies data-driven analytics to improve credit risk assessment, delinquency detection, portfolio profitability, and strategic growth decisions.
Using a synthetic lending portfolio of 15,000 customers, the analysis combines customer demographics, loan characteristics, repayment behavior, acquisition channels, and behavioral risk indicators to build actionable portfolio intelligence for senior leadership.
The project mirrors the type of work performed by strategy analysts, fintech risk teams, and consulting associates in financial services engagements.

# Business Problem
Digital lenders often achieve rapid growth through technology-driven customer acquisition and fast approvals. However, scaling portfolios without strong risk controls can lead to:
- Rising delinquencies
- Poor portfolio quality
- Negative customer lifetime value
- Weak unit economics
- Inefficient acquisition spending

The objective of this project is to design a data-driven framework that helps lenders:
- Identify high-risk borrower segments
- Detect early warning signs of default
- Optimize pricing and tenure strategies
- Improve risk-adjusted returns
- Support leadership with portfolio-level insights

# Project Objectives
This project addresses the following business questions:
1. Which customer segments exhibit different repayment and default behaviors?
2. Which acquisition channels generate the best risk-adjusted returns?
3. Which loan products and tenures balance growth and risk most effectively?
4. How can pricing and approval policies improve portfolio performance?
5. What metrics should leadership monitor proactively?

# Dataset Design
A fully synthetic lending ecosystem dataset was generated containing:
- 15,000 customers
- Customer demographics
- Income and employment profiles
- Credit quality indicators
- Loan products and ticket sizes
- Interest rates and risk grades
- Repayment behavior and delinquency flags
- Cashflow volatility indicators
- Acquisition channel information
- Customer Lifetime Value (CLV)

# Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

# Analytical Workflow
## 1. Synthetic Portfolio Generation
Created a realistic lending dataset simulating:
- Personal loans
- BNPL products
- SME working capital loans
Variables were designed to reflect real-world lending relationships between borrower quality, pricing, delinquency risk, and profitability.

## 2. Customer Risk Segmentation
Segmented borrowers using:
- Credit quality
- Income profile
- Cashflow volatility
- Loan characteristics
- Repayment behavior
The analysis identified materially different risk-return profiles across borrower groups.
### Key Finding
Certain segments with aggressive growth characteristics showed significantly higher default rates and negative portfolio contribution.

## 3. Acquisition Channel Analysis
Evaluated:
- Default rates by channel
- Customer Lifetime Value (CLV)
- Acquisition costs
- Unit economics
- Risk-adjusted returns
### Key Finding
Referral-based acquisition channels delivered materially stronger portfolio quality compared to high-volume digital acquisition.

## 4. Product & Tenure Optimization
Analyzed:
- Loan product profitability
- Ticket size risk
- Tenure-level performance
- Product-tenure combinations
### Key Finding
Longer-tenure SME working capital loans generated the highest delinquency pressure, while BNPL products performed better as low-ticket entry products.

## 5. Early Warning Signal System
Developed rule-based delinquency triggers using:
- Partial payment behavior
- Cashflow volatility
- Credit quality
- Loan size and tenure
### Example Trigger Logic
- Partial payment + high volatility → elevated default probability
- Poor credit score + missed payment → severe delinquency risk

## 6. Portfolio Policy Simulation
Simulated the impact of:
- Segment-specific pricing
- Tenure reduction
- Stricter underwriting
- Acquisition budget reallocation
### Simulated Outcomes
- Reduced portfolio defaults
- Improved portfolio quality
- Better risk-adjusted yield
- Lower exposure to high-risk borrowers
# Key Insights

| Metric | Result |
|---|---|
| Portfolio Default Rate | 20.2% |
| Customers Analyzed | 15,000 |
| Early Warning Trigger Rate | 22.3% |
| Best Performing Channel | Partner Referral |
| Highest Risk Product | SME Working Capital |
| Strongest Product Strategy | Longer-tenure Personal Loans |

# Strategic Recommendations

## Risk Segmentation Strategy
- Tighten underwriting for high-volatility borrowers
- Increase pricing selectively for subprime segments
- Expand approval limits for stable low-risk customers
  
## Acquisition Optimization
- Reduce dependency on high-risk digital acquisition
- Shift budget toward referral-based channels
  
## Product Strategy
- Position BNPL as a low-risk customer acquisition product
- Restrict longer-tenure exposure for risky SME segments
  
## Early Warning Monitoring
Implement proactive monitoring for:
- Partial payment behavior
- Volatile cashflow patterns
- High-risk credit combinations
  
# Business Impact
The proposed policy framework demonstrated:
- Reduction in portfolio defaults
- Improved portfolio risk-adjusted returns
- Better allocation of acquisition spend
- Stronger portfolio monitoring capability
- Enhanced decision-making for leadership

# Dashboard & Visualizations
The project includes:
- Portfolio risk dashboard
- Segment-level default analysis
- Acquisition channel performance visuals
- Product-tenure risk matrices
- Early warning indicator tracking

# Repository Structure

```bash
digital-lending-portfolio-optimization/
│
├── data/
├── notebooks/
├── outputs/
├── reports/
├── dashboards/
├── README.md
└── requirements.txt
```

# Author
#Ishu Verma
#Aspiring Business Analyst | Risk Analytics | Consulting & Data Strategy.
