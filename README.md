# The Effect of Caffeinated vs. Caffeine-Free Energy Drinks on Blood Glucose Change

## Overview

This project investigated whether a 250 mL caffeinated energy drink, compared with a 250 mL caffeine-free energy drink, affects short-term changes in blood glucose among simulated Arcadia adults aged 20–39.

## Research Question

Does consuming a 250 mL caffeinated energy drink, compared with a 250 mL caffeine-free energy drink, affect short-term blood glucose change?

## Experimental Design

- Completely randomized experiment
- 42 simulated participants
- 21 participants per treatment group
- Caffeinated vs. caffeine-free energy drink
- Blood glucose measured at baseline and 9–11 minutes after treatment

## Data Preparation

The raw dataset contained 46 records, including 42 primary participants and 4 reserve participants.

After applying the predefined criteria for primary participants and usable primary responses, 42 participants were included in the primary analysis.

- Caffeinated: 21
- Caffeine-free: 21
- Usable primary responses: 42
- Missing primary outcomes: 0

## Statistical Analysis

The primary treatment contrast was defined as:

**Caffeinated − Caffeine-free**

The treatment effect was estimated as the difference in mean glucose change between the two groups.

A two-sided Welch two-sample t-test was used with a significance level of 0.05.

## Results

| Statistic | Result |
|---|---:|
| Estimated treatment effect | −2.38 mg/dL |
| 95% Confidence Interval | −6.14 to 1.38 mg/dL |
| t-statistic | −1.281 |
| Degrees of freedom | 38.933 |
| p-value | 0.208 |

The caffeinated group had a mean glucose change of 31.43 mg/dL, compared with 33.81 mg/dL in the caffeine-free group.

The estimated treatment effect was −2.38 mg/dL, meaning that the caffeinated group had an average glucose change 2.38 mg/dL lower than the caffeine-free group.

## Conclusion

The analysis did not provide statistically significant evidence of a difference in short-term blood glucose change between the caffeinated and caffeine-free treatment groups.

This result should not be interpreted as proving that caffeine has no effect on blood glucose. The confidence interval includes zero and a range of possible treatment effects.

## Limitations

- The study used simulated Arcadia participants aged 20–39.
- Participants were not selected through a simple random sample of the broader Arcadia population.
- Only one 250 mL energy-drink treatment was studied.
- Blood glucose was measured only 9–11 minutes after treatment.
- No blinding was used.
- The results should not automatically be generalized to other populations, products, doses, or longer-term effects.

## Tools & Skills

**Tools**
- R
- Islanders Simulation Platform

**Statistical Methods**
- Experimental Design
- Welch Two-Sample t-Test
- Hypothesis Testing
- Confidence Intervals
- Statistical Inference
- Assumption Checking

**Data Skills**
- Data Import
- Data Cleaning
- Data Validation
- Data Analysis
- Data Visualization
