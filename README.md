# A/B Test: Subscription Pricing with Discount Message

The goal of this A/B test is to determine whether offering a 50% discount message alongside the $4.99 subscription price (Group
B) has a statistically significant impact on the install-to-payment conversion rate compared to offering the standard $4.99 price
without a discount message (Group A).

## A/B Test Results: Impact of Discount Message on Conversion Rate

### Hypothesis
* **Null Hypothesis (H₀):** There is no statistically significant difference in the install-to-payment conversion rate between Group A (standard price) and Group B (discounted price message).
* **Alternative Hypothesis (H₁):** There is a statistically significant difference in the install-to-payment conversion rate between Group A and Group B. Specifically, we expect the conversion rate in Group B to be higher than Group A (one-tailed test).

### Metrics
* **Primary Metric:** Install-to-payment conversion rate

### Groups
* **Control Group:** Group A (standard $4.99 price)
* **Treatment Group:** Group B ($4.99 price with 50% discount message)

### Expected Outcome
We hypothesized that adding the 50% discount message would increase the install-to-payment conversion rate.

### A/B Test Analysis Results
Analysis was conducted using Jupyter Notebook, leveraging pandas for data manipulation, scipy.stats for statistical analysis, and matplotlib.pyplot for data visualization.

| Metric | Group A | Group B |
|---|---|---|
| Test Dates | July 3 - July 25, 2023 | July 3 - July 25, 2023 |
| Duration | 21 days | 21 days |
| Number of Users | 10,013 | 9,985 |
| Number of Conversions | 611 | 889 |
| Conversion Rate (%) | 6.10% | 8.90% |

### Statistical Significance Test Results

**Chi-squared Test:**

* **Chi-squared statistic:** 56.14
* **P-value:** 6.74 x 10⁻¹⁴

**Conclusion:**

Since the p-value (6.74 × 10⁻¹⁴) is significantly less than the commonly accepted significance level of 0.05, we can
confidently reject the null hypothesis of no difference between the groups. This means that the difference in
conversion rates between Group A and Group B is statistically significant.

### Visualization
[Insert links to visualizations here]
* Example visualization: A bar chart comparing the conversion rates of both groups.

### Decision
Based on the obtained results, which demonstrate a statistically significant increase in the conversion rate of 45.9%
(from 6.10% to 8.90%), it is recommended to implement the change introduced in Group B, that is, to offer the
subscription with the 50% discount message. This decision will likely have a positive impact on revenue.

### Further Analysis:
* Continue monitoring the conversion rate after implementing the change to ensure the stability of the results.
* Analyze other relevant metrics, such as the churn rate and average revenue per user, to fully understand the
impact of the change.
* Combining the observed increase in the conversion rate with statistical confirmation and continuous monitoring
allows for making an informed decision to optimize the subscription offer.
* A few minor improvements in wording for clarity and flow were made in the translation. The key information and
structure have been preserved.
