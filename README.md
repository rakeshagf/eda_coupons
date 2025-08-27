# Data Analysis to predict Coupon Acceptance 

# Problem
The goal of this project is to exercise the learnings on visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 

# Data
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

- “Right away”
- “Later, before the coupon expires”
- “No, I do not want the coupon”

# Summary of findings

## Key Findings for Bar coupons
Based on the analysis of bar coupons, it appears that drivers who frequent bars more often have a significantly higher acceptance rate.
Additionally, factors such as being over 25, not having kids as passengers, driving to non urgent location, and having occupations outside of farming, fishing, or forestry seems associated with a higher likelihood of accepting bar coupons.

Therefore, a possible hypothesis is that bar coupon acceptance is strongly influenced by the driver's existing bar-going habits and demographics that align with a typical bar-going demographic (e.g., age, lack of child passengers).

## Key Findings for Coffee House coupons
The overall acceptance rate for "Coffee House" coupons is 50%. 
Drivers aged below 21 have the highest coffee house coupon acceptance rate.   
Coffee house visit frequency is a strong predictor of coupon acceptance, with higher frequency correlating with higher acceptance rates.   
Acceptance rates vary significantly by time, with higher acceptance in the morning (10 AM) and lower acceptance in the evening (6 PM and 10 PM).   
Acceptance rates are notably higher when the driver is with friends or a partner. 
### Insights and Next Steps related to Coffee House coupons
Targeting younger drivers (below 21) and those who frequent coffee houses could improve the redemption rate of "Coffee House" coupons.
Consider the time of day and companion type when distributing "Coffee House" coupons for optimal results.
