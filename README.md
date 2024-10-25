# Hypothesis Testing for Website Theme Evaluation

## Overview
Hypothesis testing is a statistical method that helps draw conclusions about a population based on sample data. It starts with a **Null Hypothesis (H0)**, which represents no effect or difference, and an **Alternative Hypothesis (H1 or Ha)**, which reflects the effect we aim to detect.

## Hypothesis Testing Process
1. **Collect Data**: Gather the necessary data for testing.
2. **Define Hypotheses**: Establish H0 and H1.
3. **Set Significance Level (α)**: Determine the threshold for rejecting H0 (commonly 0.05).
4. **Choose Statistical Test**: Select an appropriate test (e.g., t-test, chi-square).
5. **Execute the Test**: Apply the chosen statistical test to the data.
6. **Interpret Results**: Analyze the p-value to draw conclusions.

## Dataset Summary
The dataset consists of **1,000 records** across **10 columns**, with no missing values. Key metrics include:
- **Click Through Rate (CTR)**: Avg. 0.26 (range: 0.01 - 0.50).
- **Conversion Rate**: Avg. 0.25 (range: 0.01 - 0.50).
- **Bounce Rate**: Avg. 0.51 (range: 0.20 - 0.80).
- **Scroll Depth**: Avg. 50.32% (range: 20.01% - 80%).
- **Age**: Avg. 41.5 years (range: 18 - 65).
- **Session Duration**: Avg. 925 seconds (range: 38 - 1800 seconds).

These metrics provide insights into user engagement, crucial for evaluating website theme performance.

## Comparative Analysis
The analysis compares two website themes based on:
- **CTR**: Dark Theme: 0.2645 | Light Theme: 0.2471
- **Conversion Rate**: Light Theme: 0.2555 | Dark Theme: 0.2513
- **Bounce Rate**: Dark Theme: 0.5121 | Light Theme: 0.4990
- **Scroll Depth**: Light Theme: 50.74% | Dark Theme: 49.93%
- **Session Duration**: Light Theme: 930.83 seconds | Dark Theme: 919.48 seconds

### Key Insights
- The Dark Theme has a higher CTR, while the Light Theme performs better in conversion and engagement metrics.

## Hypothesis Testing Results
Using a significance level of 0.05:
1. **Conversion Rate**: p-value = 0.635 (no significant difference).
2. **CTR**: p-value = 0.048 (statistically significant difference, favoring the Dark Theme).
3. **Bounce Rate**: p-value = 0.230 (no significant difference).
4. **Scroll Depth**: p-value = 0.450 (no significant difference).

### Conclusion
While the Dark Theme attracts more clicks, the overall user engagement, conversion rates, bounce rates, and scroll depths are not significantly affected by the choice of theme. This analysis aids in making informed design decisions based on user behavior metrics.
