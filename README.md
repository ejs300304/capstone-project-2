# capstone-project-2

Tokopedia Promo Efficiency & Customer Retention Analysis

An end-to-end data science and business analytics project evaluating transaction-level data to optimize promotional budget allocation, eliminate non-value-adding discounts, and identify operational drivers (such as courier performance and shipping fees) affecting 90-day repeat order rates across Indonesian e-commerce user cohorts.

Executive Summary

Between 2023 and 2024, Tokopedia shifted from hyper-growth user acquisition toward sustainable unit economics and profitability under the GoTo Group corporate mandate. This study analyzes over 50,000 distinct users and multi-table transactional records to solve a core strategic dilemma: How can Tokopedia optimize promotional spending without compromising user retention?

Key Findings:

Promo Budget Leakage: Approximately 42.5% of total promotional spend was consumed by churned discount seekers or users who only ordered once during promo periods.

Zero Retention Lift: Users receiving first-order vouchers demonstrated an identical repeat rate (~78%–79%) compared to users who purchased with No Voucher (78.9%), indicating that early subsidies subsidize baseline demand rather than forming habits.

Logistics Service Quality Trumps Subsidies: First delivery experiences with courier ratings below 3.0 caused user churn to surge to 69.6%, whereas shipping cost tiers (Low: IDR 1k–5k vs. Medium: IDR 5k–15k) showed minimal variance in user churn (23.9% vs. 20.4%).

Acquisition Channel Efficiency: Organic and Referral acquisition channels delivered superior retention and ROI (Referral: 22.5x ROI, 86.1% repeat rate) compared to Paid Ads (5.4x ROI, absorbing 54% of promotional spend).

Repository Structure

```text
├── README.md # Project documentation & findings
├── capstone 2.ipynb # Data cleaning, EDA, and visualization code
├── [Capstone 2]Tokopedia Growth & Retention Strategy.pptx # Slide presentation
└── Capstone 2 dashboard.twbx # Tableau workbook
