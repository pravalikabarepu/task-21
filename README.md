## A/B Testing – Conversion Rate Analysis

## Project Overview

This project performs an A/B test to compare the conversion rates of a Control group and a Treatment group. The analysis measures the difference between the two variants, estimates uncertainty using a 95% confidence interval, and determines whether the observed difference is statistically significant.

## Objective

To understand practical A/B test interpretation by:

* Comparing conversion rates between two variants
* Measuring the effect size
* Estimating uncertainty using confidence intervals
* Testing statistical significance
* Providing a data-driven recommendation

## Tool Used

Python

## Dataset

A/B Testing Dataset

The dataset contains users divided into Control and Treatment groups along with their conversion outcomes.

## Hypothesis

Null Hypothesis (H0): There is no difference in conversion rates between the Control and Treatment groups.

Alternative Hypothesis (H1): There is a difference in conversion rates between the Control and Treatment groups.

Significance level: 5%

## Analysis Performed

1. Loaded and inspected the dataset
2. Checked missing values and group distribution
3. Calculated users and conversions for each group
4. Calculated conversion rates
5. Calculated absolute difference in conversion rates
6. Calculated relative lift
7. Performed a two-proportion Z-test
8. Calculated the 95% confidence interval
9. Evaluated statistical significance
10. Generated a final recommendation

## Results

Control conversion rate: 12.04%

Treatment conversion rate: 11.89%

Absolute difference: -0.15 percentage points

Relative lift: -1.23%

Z-score: -1.2369

P-value: 0.2161

95% Confidence Interval: -0.38 to 0.09 percentage points

The p-value is greater than 0.05, so the difference is **not statistically significant**.

## Recommendation

The Treatment variant should not replace the Control based on the current experiment.

Although the Treatment conversion rate is slightly lower than the Control, the observed difference is not statistically significant. Therefore, there is not enough evidence to conclude that the Treatment performs differently from the Control.

## Key Insights

* The Control group has a slightly higher conversion rate than the Treatment group.
* The Treatment shows a relative decrease of approximately 1.23%.
* The confidence interval includes zero, indicating that the true difference could be negligible or in either direction.
* The p-value of 0.2161 is above the 0.05 significance threshold.
* Statistical evidence does not support adopting the Treatment variant.

## Conclusion

The A/B test does not provide sufficient statistical evidence that the Treatment variant improves conversion. The Control variant should therefore be retained unless additional testing provides stronger evidence for the Treatment.
