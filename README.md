# Zomato Coupon Effectiveness Analysis

An end-to-end data analysis project evaluating the impact of coupons on order value, profitability, redemption and customer repeat behaviour.

## Tools Used

* Python
* Pandas and NumPy
* Matplotlib and Seaborn
* SciPy
* Jupyter Notebook

## Analysis Performed

* Data cleaning and validation
* Coupon versus non-coupon order comparison
* Monthly revenue and profit analysis
* Coupon-code profitability analysis
* Offer redemption and channel performance
* Restaurant, city and cuisine analysis
* Welch’s t-tests for order value and profitability
* 30-day customer repeat analysis

## Key Findings

* Analysed 2,249 delivered orders from 300 customers.
* Coupon orders had an average order value of ₹769.38, compared with ₹558.36 for non-coupon orders.
* Coupons were associated with a 37.79% increase in average order value.
* Average profit fell from ₹117.29 to ₹30.22 per order—a 74.23% reduction.
* The overall coupon-offer redemption rate was 7.50%.
* The customer repeat rate within 30 days of the first coupon order was 41.56%.
* REPEAT75 was the most profitable coupon, while WELCOME50 and FLASH40 generated negative average profit.

## Business Recommendations

* Target coupons toward new, inactive and high-potential customers instead of distributing them broadly.
* Apply minimum-order thresholds and maximum-discount limits.
* Evaluate campaigns using profit and repeat behaviour, not redemption alone.
* Redesign or discontinue coupons that consistently produce negative profit.
* Use controlled A/B tests before launching large campaigns.

## Project Files

* `zomato_eda.ipynb` — complete Python analysis
* `data/` — source datasets
* `outputs/` — processed analytical tables

## Limitation

The project uses synthetic observational data. The results show associations and should not be interpreted as proof that coupons caused the observed changes.
