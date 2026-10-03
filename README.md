# What I would recommend
### 1. I am recommending to target MID, 51-200 size, healthcare companies in US market basing on data proofs:
1. Best cohorts' LTV is higher on average 123$
2. Pro plan has on average 1.72% more customers and basic plan has 2.31 less customers in the best cohorts
3. Shares are higher for MID segment 14%, for 51-200 size 29%, for healthcare 21% and for US 11% on average compering best cohorts to poor cohorts

#### What risks we may face. We may face data risk as:
1. Difference in cohorts segments are quite small few percentage points;
2. Data may be not statistically significant cause we have small amount of data.

#### Next steps are:
1. Prepare survey to make sure we will be targeting correct one
2. Start preparing new marketing strategy targeting MID Healthcare companies (51-200 employees) in the US market
3. Start to develop converting incentives for basic plan conversion to pro plan
4. Monitor retention rate monthly to validate if targeting changes improve cohort performance

### 2. I recommend increase price for basic plan from 29$ to 39$ cause:
1. Customer Life Time Value is 142$ for basic plan, 339$ for pro plan -- 139% more then basic plan'.  
2. Basic plan have 40$ price difrerence comparing to pro plan - Pro plan is more expensive about 170%;
3. Avg. life time for basic plan is longer about 18 days. (0.6 = p_basic -- p_pro).

#### What risks we may face. We may face revenue decrease from this basic plan cause:
- Churn may go up
- CL and CLV may go down
- ARPU may go down

#### Next steps are:
- Increase prices to 39$
- Observe ARPU, CL, CLV and Churn for this cohort. 

# Where I got the data from:
- https://www.kaggle.com/datasets/mounikabusi/saas-customer-churn-dataset

# What I did:
### Artifacts
- Jupyter notebook code
- cohort_analysis_povot_table.xlsx

### Step by step
- Imported pandas and files .csv;
- Replaced things to make data consistent as removeing spaces, unexpected characters and words. Example P_PRO, P_Pro to p_pro or " " to "";
- Assign data types to data frames;
- Filtering data frames to analysis;
- Count churn rate for all cohorts from prepared data frames;
- Count churn rate, retention and share for all subscription plans Basic, Pro and Enterprise;
- Filter data for all plans to receive only churned customer then count Customer Life Time;
- Save data to file then use pivot tables to get churn for all cohorts;
- Choose best performing cohorts and compared to the rest;
- Countr segments shares for cohorts;
- Compering segments in cohorts;
- Count Average Revenue Per User and Life Time Value for cohorts
- Comparing distribution of plans and checking avg. difference between best performing cohorts and rest;
- Checking ARPU, Churn, TVL and Avg Life Time Value difference (Avg. from TOP5 - Avg. from BOTTOM 5) for all cohorts;
- Check procentag difference between best performing cohorts and bottom rest. 
