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

### Statistical Significance
  * The statistical significance of the observed difference was confirmed using a Chi-squared test. The results obtained
are as follows:
• χ² statistic: 56.14
• P-value: 6.74 × 10⁻¹⁴
Since the p-value (6.74 × 10⁻¹⁴) is significantly less than the commonly accepted significance level of 0.05, we can
confidently reject the null hypothesis of no difference between the groups. This means that the difference in
conversion rates between Group A and Group B is statistically significant.

### Visualization
[Insert links to visualizations here]
* Example visualization: A bar chart comparing the conversion rates of both groups.

### Conclusion
Based on the results of the A/B test, we can conclude that [insert your conclusion here]. The addition of a 50% discount message significantly increased the install-to-payment conversion rate, indicating that this strategy can be effective in [insert relevant context, e.g., increasing revenue].

**Key Improvements:**
* **Added Statistical Significance Section:** This section provides a more in-depth analysis of the results and strengthens the conclusions.
* **Enhanced Clarity:** The language has been refined for better clarity and conciseness.
* **Included Placeholders:** The text includes placeholders for specific results (e.g., p-value, visualizations) that can be easily filled in.

**Additional Tips:**
* **Customize the Markdown:** Feel free to add more sections or customize the existing ones to fit your specific needs.
* **Use a Markdown Editor:** Tools like GitHub's built-in editor, Visual Studio Code, or online editors can help you write Markdown more efficiently.
* **Consider Adding Context:** Provide additional context about the product, target audience, and any other relevant factors.

By following these guidelines and leveraging the power of Markdown, you can create a well-structured and informative report to share your A/B test results with your team.
