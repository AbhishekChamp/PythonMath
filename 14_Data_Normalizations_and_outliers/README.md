### Garbage In, Garbage Out (GIGO)

-   Awful data leads to awful results.
-   Unfortunately, awesome data does not guarantee awesome results.
-   When possible, start with clean data.
-   Be meticulous, critical, patient and unbiased when cleaning data.

### Z-Score Standardization

-   **Key insight:** A value on its own is difficult to interpret; a value relative to its distribution is easy to interpret.
-   **Mean-center:** Subtract the average from each individual value.
-   **Variane-normalize:** Divide by the standard deviation.
-   The units are standard deviations away from the mean of the distribution.
-   Z-transform shifts and stretches, but doesn't change shape.
-   **Z-transform assumption:** Mean and standard deviation are valid descriptions of the distribution's central tendency and dispersion.
-   That is, the distribution is **_roughly_** Gaussian.

### Min-Max Scaling

-   Scale to a range of 0 to 1.
-   We can also scale to range of **_a_** to **_b_**.
-   It is a way of rescaling the data to any arbitrary range (typically [0, 1])

### Outliers

-   Also called as anomaly, extreme (deviant) data, non-representative data, noise.
-   Outliers come from noisy data, noisy or faulty equipment, human error, non-cooperative research participant, natural variation.
-   Outliers are bad because they become **hugh** when squared.
-   Outliers can have **more impact** with small N.
-   Not all outliers are equal. They are worse near the **edges** of the data distribution compared to the **middle**.

### How to deal with outliers

-   Strategy 1:
    -   Identify outliers and remove them from the data prior to any analyses.
    -   **Assumption:** Outliers are noise or otherwise invalid.
-   Strategy 2:
    -   Leave outliers in and use robust methods that attenuate the negative impact of the outliers on the results.
    -   **Assumption:** Outliers are unusual but valid data.

### The z-score

-   Z-scores are interpreted as standard deviation units away from the center of the distribution.
-   Z-scores are valid if the distributions are roughly Gaussian.

### Z-score for outliers

-   Convert data to z-score.
-   A datapoint is an outlier if it exceeds some standard deviation threshold (often 3, but this is arbitrary).
-   Remove outliers and repeat until no more outliers.

### Z-score method for multivariate data

-   Compute the data mean.
-   Compute the distance from each data point to the mean.
-   Convert distances to z-score.
-   Remove outliers based on threshold, as shown previously.
