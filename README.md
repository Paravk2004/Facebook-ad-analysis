# Facebook Ad Campaign Analysis  

## Project Overview  
This project analyzes a Facebook ad campaign dataset to uncover insights that can help improve ad performance. The analysis involves **Exploratory Data Analysis (EDA)** to understand key advertising metrics and identify trends that impact conversions.  

## Objectives  
1. **Improve the Total Conversion Rate (TCR)** of ad campaigns by identifying factors influencing user conversions.  
2. **Perform data cleaning and preprocessing** to ensure accurate and consistent analysis.  
3. **Analyze user engagement metrics** like Click-Through Rate (CTR), Cost Per Click (CPC), and their relationship with conversion rates.  
4. **Segment users based on age, gender, and interests** to identify high-converting demographics.  
5. **Optimize ad spend allocation** by analyzing performance trends and determining the most cost-effective strategies.  
6. **Provide data-driven recommendations** to enhance targeting and improve overall ad conversion efficiency.  

## Tools & Technologies  
- **Python** (Pandas, NumPy)  
- **Data Visualization** (Matplotlib, Seaborn)  
- **Jupyter Notebook**  
- **GitHub** for version control  

## Dataset Details  
The dataset used for this analysis was sourced from **Kaggle** and contains **1,143 records** related to Facebook ad campaigns. The dataset includes key features such as:  

### Ad & Campaign Identifiers  
- **ad_id**, **xyz_campaign_id**, **fb_campaign_id** :- Unique IDs for ads and campaigns.  

### User Demographics  
- **age**, **gender** :- User attributes impacting ad engagement.  

### Ad Performance Metrics  
- **Impressions** :- Number of times an ad was displayed.  
- **Clicks** :- Number of times users clicked on the ad.  
- **Spent** :- Total advertising budget spent on the ad.  
- **Total_Conversion** :- The number of users who completed a desired action.  
- **Approved_Conversion** :- Verified successful conversions.  

### Data Quality Insights  
- No missing values were found in the dataset.  
- High **duplicate values** in some columns (e.g., `campaign_id` had **99.74% duplicates**).  
- `Clicks` and `Conversions` showed significant variability, with **high uniqueness** in values.  
- `Interest` has **40 unique values**, making it an important variable for segmentation.  

## Key Findings  
1. **Males aged 30-34** had the **highest Total Conversion Rate (18.52%)**, making them the most responsive audience.  
2. **Females aged 30-34** followed with **12.14%**, showing strong engagement but slightly higher Cost Per Conversion.  
3. **Males aged 45-49 had the highest Cost Per Conversion (`$25.68`)**, making them less cost-effective.  
4. **The highest ad spend was on Females aged 45-49 (`$13,433.21`)**, but their **conversion rate was the lowest (4.22%)**, indicating inefficient budget allocation.  
5. **CTR decreases as impressions increase**, suggesting that while higher impressions bring more clicks and conversions, they also reduce engagement per impression.  

## Recommendations to Optimize Campaign Performance  
1. **Increase Budget for Campaign 916**  
   - Highest conversion efficiency and lowest cost per conversion make it the best-performing campaign.  
2. **Optimize or Reduce Budget for Campaign 1178**  
   - Poor conversion rates and high cost per conversion (`$20.85`) indicate inefficiency.  
   - Improvement in **ad targeting** is needed.  
3. **Refine Targeting for Campaign 936**  
   - Lower conversion rates compared to Campaign 916.  
   - **Optimize ad creatives & audience selection** to improve performance.  
4. **Prioritize Budget Allocation for High-Converting Groups**  
   - **Increase ad spend on Males aged 30-34** since they have the **best ROI**.  
   - **Reduce budget for Females aged 45-49**, as their **Cost Per Conversion is too high** and conversions are low.  
5. **Improve Targeting for Moderate-Performing Age Groups**  
   - **Refine targeting for 35-39 and 40-44 age groups**, as they have **moderate CTR but lower conversions**.  
   - **Test new ad creatives, landing pages, and personalized offers** to improve conversion rates.  
6. **Optimize Ad Creatives and Messaging**  
   - **Interest 104 has high CTR but low conversions**, suggesting **ad messaging or landing page issues**.  
7. **Reallocate Budget Towards Cost-Efficient Interests**  
   - **Increase spending on Interests 36 & 31**, as they have **strong conversion rates and low Cost Per Conversion**.  
   - **Reduce ad spend on Interest 7**, which has **high Cost Per Conversion (`$11.00`)** and is inefficient.  
8. **Improve Cost Efficiency & Bidding Strategies**  
   - **Adjust bids for high CPC groups (35-39) to lower costs**.  
   - **Use retargeting campaigns** to improve CTR and conversions without increasing CPC.  

## Final Strategy for Campaign Optimization  
1. **Focus on high-converting demographics** (**Males 30-34**) while **reducing spend on low-performing groups** (*Females 45-49*).  
2. **Improve ad creatives & CTAs** to boost engagement for underperforming segments.  
3. **Test & iterate ad strategies** based on data-driven insights rather than just CTR.  
4. **Refine audience segmentation & personalize targeting** for better conversions.  
5. **Monitor Cost Per Conversion & ROI regularly** to optimize future campaign performance.  

### **Final Takeaway**  
- Simply **increasing impressions is not enough** – successful campaigns require **strategic audience targeting, budget allocation, and continuous optimization** for **maximum conversions and ROI**.  

## How to Use  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/Paravk2004/facebook-ad-analysis.git
