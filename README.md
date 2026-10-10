# What I recommend

### 1. Target MID (51–200 employees) healthcare companies in the US market based on data proofs:
1. Best cohorts' LTV is higher by $123 on average.
2. The Pro plan has 1.72% more customers on average, and the Basic plan has 2.31% fewer customers in the best cohorts.
3. Segment shares in the best cohorts compared to poor cohorts are higher on average for:
   - MID segment (+14%)
   - Company size 51–200 (+29%)
   - Healthcare industry (+21%)
   - US market (+11%)

#### Risks:
1. Differences in cohort segments are relatively small (only a few percentage points).
2. Data may not be statistically significant due to the small sample size.

#### Next steps:
1. Prepare a survey to ensure the correct target audience is selected.
2. Start preparing a new marketing strategy targeting MID Healthcare companies (51–200 employees) in the US market.
3. Develop incentives to drive conversions from the Basic plan to the Pro plan.
4. Monitor the retention rate monthly to validate whether targeting changes improve cohort performance.

---

### 2. Increase the price for the Basic plan from $29 to $39 based on:
1. Customer Lifetime Value (CLV) is $142 for the Basic plan vs. $339 for the Pro plan (139% higher than Basic).
2. The Pro plan currently costs $40 more than the Basic plan (138% more expensive).
3. Average customer lifetime for the Basic plan is longer by approximately 18 days ($p_{basic} - p_{pro} \approx 0.6$ months).

#### Risks (potential revenue decrease from the Basic plan):
- Churn rate may increase.
- Customer Lifetime (CL) and Customer Lifetime Value (CLV) may decrease.
- Average Revenue Per User (ARPU) may decrease.

#### Next steps:
- Increase the Basic plan price to $39.
- Monitor ARPU, CL, CLV, and Churn for the new cohorts.

---

# Data source
- Kaggle Dataset: [SaaS Customer Churn Dataset](https://www.kaggle.com/datasets/mounikabusi/saas-customer-churn-dataset)

# Deliverables & Artifacts
- Python analysis code: `Python data analysis - LTV, ARPU, Churn.ipynb`
- Excel cohort pivot tables: `cohort_analysis_pivot_table.xlsx`

### Step by step
* Import pandas and CSV files;
* Replace things to make data consistent, such as removing spaces, unexpected characters, and words (e.g., standardizing `P_PRO` and `P_Pro` to `p_pro`, or `" "` to `""`);
* Assign data types to data frames;
* Filter data frames for analysis;
* Count churn rate for all cohorts from prepared data frames;
* Count churn rate, retention, and share for all subscription plans: Basic, Pro, and Enterprise;
* Filter data for all plans to receive only churned customers, then count customer lifetime;
* Save data to file, then use pivot tables to get churn for all cohorts;
* Choose best-performing cohorts and compare them to the rest;
* Count segments' shares for cohorts;
* Compare segments in cohorts;
* Count Average Revenue Per User and Lifetime Value for cohorts;
* Compare distribution of plans and check the average difference between best-performing cohorts and the rest;
* Check ARPU, Churn, LTV, and Average Lifetime Value differences (Avg. from TOP 5 - Avg. from BOTTOM 5) for all cohorts;
* Check percentage difference between best-performing cohorts and the bottom/rest.
