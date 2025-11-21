# Customer Default Risk Segmentation and Analysis
This project focused on segmenting and analyzing customer financial data for a credit card provider to predict default behaviour of its users allowing the company to improve it's lending strategies and reduce financial risk

### Project Objective
To segment customers based on credit risk and financial behavior, identify predictors of default, and generate actionable insights that optimize credit policies, reduce financial losses, and enhance retention of valuable customers. By completing this project, stakeholders identify default risk users and prevent them before it happens through strategies and policies for targeted credit risk management

### Project Background
Banks and micro-lending institutions face increasing challenges in predicting customer credit risk, leading to higher default rates and reduced profitability. Traditional credit assessments often fail to incorporate behavioral indicators such as utilization trends and late payment frequency, causing organizations to underestimate emerging risks in customers

This project analyzes customer financial and behavioral data to segment clients based on their risk of default. By examining factors like credit utilization, payment history, and demographic details, it reveals which customer groups are most likely to default. The analysis helps identify early warning signs, such as frequent late payments, enabling targeted strategies to reduce defaults and protect financial loss. The interactive Power BI dashboard makes these insights easy for decision-makers to explore and act on, improving credit risk management and customer retention

### Business Needs
- Spot high-risk customers early to reduce default losses and protect the company’s revenue.
- Make smarter lending decisions by using real behavioral data such as payment patterns and how much credit customers use.
- Support customers before they default with targeted repayment plans and personalized assistance.
- Protect profits while keeping valuable customers, especially those who carry some risk but have high future value.
- Improve cash flow by using early-warning alerts and monitoring systems that reduce bad debt.
- Build stronger investor and partner confidence with transparent, data-driven risk management practices.
- Grow the business responsibly by managing risk effectively without losing good customers or market opportunities

### Stakeholders and their Analytical Needs
#### Credit & Risk Management Team:
Needs to identify high-risk customers and understand factors that lead to defaults.
Uses insights to design better credit policies, reduce default losses, and monitor risk trends.
#### Customer Service & Collections Team:
Needs to know which customers require reminders, assistance, or intervention.
Uses insights to improve debt recovery, personalize repayment support, and reduce escalations.
#### Executive Leadership / Management:
Needs a high-level view of customer risk exposure, default impact, and potential profitability.
Uses insights for strategic decisions, policy alignment, and long-term financial protection.
#### Finance Team:
Needs accurate forecasting of losses, cash flow impact, and cost of customer retention programs.
Uses insights to improve budgeting accuracy and support sustainable financial planning.
#### Marketing and Customer Retention Team:
Needs to identify valuable customers worth retaining even if they carry moderate risk.
Uses insights to design loyalty programs, personalized offers, and retention strategies.
#### Investors & Financial Partners:
Need visibility into risk management practices and financial performance stability.
Use insights to gauge company reliability, build trust, and inform investment decisions.
#### Regulatory and Compliance Team:
Need to ensure lending fairness, ethical handling of risky customers, and compliance with regulations.

### Key Questions to Answer
- Which customer segments are most likely to default?
- What behavior trend best predict customer default risk?
- How does credit utilization affect the likelihood of late payment and default?
- What customer profiles (age, employment status, income level) show higher risk patterns?
- Which moderate-risk customers are valuable enough to prioritize for retention?
- How early can we detect customers moving toward default (early warning indicators)?
- Which interventions (payment reminders, restructuring offers, credit limit adjustments) can reduce default risk most effectively?
- How do high-risk customers impact revenue, CLV, and overall financial performance?
- Which risk mitigation strategies maintain profitability without losing valuable customers?
- How should the business allocate resources (collections effort, support, monitoring) based on customer risk tier?

### Analytical Steps, Activities, Methodology & Reasoning
#### Data Understanding and Requirement Definition
- Reviewed customer demographic, behavioral, and financial attributes.
- Identified key indicators affecting credit risk: credit score, utilization, payment history, income, CLV.
- Defined business goals (risk reduction + profitable retention) to guide modeling and segmentation.

Reasoning: Aligning analysis with business outcomes ensures the insights translate into strategic decisions rather than just descriptive statistics.

#### Data Cleaning & Preparation
- Handled missing values, normalized formats (dates, categories), corrected errors.
- Created binary and numerical features: Late Payment Count, Risk Flags, Default Indicator.
- Removed irrelevant or duplicate records.
  
Reasoning: High-accuracy risk modeling depends on clean, consistent, and unbiased data.

#### Feature Engineering & Metric Creation
- Built key indicators such as Credit Utilization Score, Risk Tier, Customer Lifetime Value (CLV).
- Derived early-warning features like Payment Frequency Trend, Late Payment Ratio, and Income-Risk Index.

Reasoning: Raw data alone cannot reveal risk patterns; engineered features reveal hidden behaviors that predict default.

#### Customer Segmentation and Risk Profiling
- Grouped customers into Low, Moderate, High risk tiers using utilization, payment behavior, and credit score.
- Cross-analyzed risk with demographics (age, employment) and revenue potential (CLV).

Reasoning: Segmentation helps differentiate between high-risk customers to retain vs. those requiring stricter credit policies.

#### Insight Visualization and Interpretation
- Used Power BI to create dashboards (risk matrix, heatmaps, KPIs, trend charts).
- Highlighted patterns (age + risk, employment + CLV, utilization thresholds).

Reasoning: Visual analytics enables decision makers to quickly detect risk drivers and take targeted action.

#### Strategy Development and Recommendations
- Proposed actionable interventions (alerts, credit restructuring, tailored repayment, customer monitoring tiers).
- Linked insights to business metrics: reduced bad debt, improved retention of profitable customers.

Reasoning: Analysis is valuable only when it leads to decisions that improve financial outcomes

### Tools and Skills Used
- Power BI (interactive Dashboards, DAX, visuals, KPIs)
- Excel (Statistical Analytics)
- Data Transformation
- Credit Risk Analytics
- Segmentation Analytics

### Dashboard

#### Page one
<p align="center"><img src="https://github.com/BOAMAH-99/Customer_default_risk_analysis_and_segmentation/blob/78e371e820cce15eecb5f418630b7e6ca7ea3672/Dashboard/Customer%20Default%20Risk%20Analysis%20and%20Segmentation%20Dashboard%201.jpg" width="800"></p>

#### Page two
<p align="center"><img src="https://github.com/BOAMAH-99/Customer_default_risk_analysis_and_segmentation/blob/78e371e820cce15eecb5f418630b7e6ca7ea3672/Dashboard/Customer%20Default%20Risk%20Analysis%20and%20Segmentation%20Dashboard%202.jpg" width="800"></p>

### Key Findings:
- High credit utilization and low credit scores are strong predictors of default risk.
  
- Customers with "Fair" credit scores and credit utilization between 0.80–0.99 contribute disproportionately to total defaults.
  
- Late payment frequency serves as a reliable early-warning indicator of default, with customers in the "Fair" credit score segment showing the highest likelihood of repeated late payments.
  
- Moderate-risk customers represent the highest Customer Lifetime Value (CLV), indicating that targeted retention and credit risk management strategies could yield significant returns
  
- Employed customers has the biggest potential in terms of CLV(315M) but has the highest default rate with 35.02%
  
- Customers after the age of 60 years old provide the highest risk of default rate yet have a lower late payment habit.
  
### Strategic Recommendations:
- Prioritize intervention for customers with credit utilization above 0.70 and “Fair” credit scores. Create an automated monitoring system that flag these accounts weekly. Use targeted outreach (email, SMS, or phone) offering reduced interest rates for partial repayment, or a gradual credit limit reduction to manage risk without alienating customers.

- Leverage late payment frequency as an early-warning trigger for “Fair” and "Good" credit score customers. Set up an alert system that automatically sends payment reminders after the first missed payment and offers flexible payment dates or hardship support after the second.
  
- Protect moderate risk, high lifetime value customers with tailored retention initiatives. Design personalized credit counselling sessions, loyalty perks for on-time payments, or short-term credit restructuring offers to keep them engaged while reducing default risk.
  
- Reassess credit terms for employed customers with high CLV but also high default rates. Offer tiered repayment plans based on income level, and use data monitoring to detect sudden spending spikes for early intervention
  
- Address higher default rates in customers over 60 years with targeted support rather than restrictions. Conduct proactive income verification every 12 months, and offer emergency hardship plans for customers facing sudden financial changes.
  
- Use segmentation driven collections and risk management allocation. Assign high touch strategies (personal calls, dedicated account managers) to top-risk/high-value groups, while lower risk customers can be managed through automated monitoring and reminder systems. High CLV customers should be targetted and restrictions for low CLV should be tighten for those meeting Risky Tier.

- Regularly Review and Refine Segmentation Based on Dynamic Behavior
Monitor changes in utilization, payment behavior, and risk scores over time to detect customers moving into higher-risk categories early. This enables pre-emptive communication before default risk crystallizes.

By using clearer customer risk categories and real-time monitoring, the business can step in early before customers fall behind on payments. This should help reduce avoidable defaults and protect revenue that is currently lost to high-risk lending.

At the same time, the company will be able to focus on customers who still bring value but may need a small push, such as reminders or flexible repayment options. Instead of losing valuable customers, the organization can now protect profitable relationships, support them with smarter repayment options, and turn potential losses into long-term revenue. High-value clients get the right attention, risky clients are flagged early.

Overall, the dashboard gives teams the power to make fast, confident decisions backed by data. This boosts financial performance, strengthens trust with partners, and opens the door for sustainable, intelligent growth.

#### The customer default segmentation analysis clearly shows that grouping customers based on their financial behavior and risk factors brings measurable business benefits. By identifying which segments are most likely to default and which offer high lifetime value, allows a more targeted intervention that reduces losses and improve retention.
