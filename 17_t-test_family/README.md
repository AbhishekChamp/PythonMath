### One-sample t-test: assumptions

-   Data are numeric **_(not categorical)_**, ideally interval or ratio **_(discrete is probably OK)_**
-   Data are independent from each other.
-   Data are randomly drawn from the population to which generalization should be made.
-   Mean and standard deviation are valid descriptors of central tendency and dispersion **_(i.e., data are approximately normally distributed)._**

### T-Test Types

-   **Paired or unpaired:** Whether the two groups of data are drawn from the same or different individuals.
-   **Paired:** The same individuals self-report their stress levels before vs. after social distancing.
-   **Unpaired:** Change in social distancing-related stress in India Vs America.
-   **Equal or unequal variance:** Whether the two groups have (roughly) equal variance.
-   **Equal Variance:** Group "A" and "B" are caucasian 20-year old students from the same university; group "A" studies engineering and group "B" studies computer science.
-   **Unequal Variance:** Group "A" is caussian 20-year old students at the same engineering university. Group "B" is a random sample of 20-year olds from across the country.
-   **Equal or unequal sample sizes:** Whether the groups have the same number of values (applies only to unpaired groups).
-   **Equal:** Both groups have N=30.
-   **Unequal:** Group "A" is 13 Parkinson's patients, group "B" is 20 matched controls.

### Wilcoxon signed-rank test

-   Nonparametric alternative to the one or two samples t-test.
-   Mainly used when the data do not confirm to the normality assumption.
-   Tests for differences in medians instead of differences in means (median is insensitive to outliers)

### Mann-Whitney U test

-   Nonparametric alternative to the independent two-samples t-test.
-   Mainly used when the data do not confirm to the normality assumption.
-   Tests for differences in medians instead of differences in means (median is insensitive to outliers).
-   The two groups do not need to have the same sample size.
