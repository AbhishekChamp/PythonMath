### Descriptive Statistics

-   Describing the characteristics of a dataset:
    -   Mean, median, mode
    -   Variance
    -   Kurtosis, skew
    -   Distribution shape
    -   Spectrum
-   **_Notes:_** No realtion to population; no generalization to other datasets or groups.

### Inferential Statistics

-   Using features of the dataset to make laims about a population.
    -   P-value
    -   T / F / chi-square value
    -   Confidence intervals
    -   Hypothesis testing
-   **_Notes:_** The entire purpose is to relate data features to populations or generalize to other groups!

### A, P, R : Definitions

**Accuracy:** The relationship between the measurement and actual truth **_(inversely related to bias)._**

**Precision:** The certainty of each measurement **_(inversely related to variance)._**

**Resolution:** The number of data points per unit measurement **_(time, space, individual, ...)._**

### Data Distributions - Why we need them

-   Most statistical procedures are based on assumptions about distributions.
-   Knowing these distributions is necessary for appropriately applying statistics.
-   Data distributions provide insights into nature.
-   Physical and biological systems are modeled using distributions.

### Central Tendency

The value you would expect the data points to merge towards

### Mean

-   Also known as arithmetic mean
-   Also known as average
-   It is suitable for roughly normal distributed data
-   The suitable data types are interval, ratio

### Mean for other data types

-   **Discrete data example -** Average US family has 1.9 children.
-   **Ordinal data example -** Average course rating of 4.3 stars (out of 1-5 stars)
-   **Nominal data example -** Average person likes 1.7 ice cream flavor (1 = chocolate, 2 = vanilla, 3 = strawberry)
-   **Conclusions:**
    -   The mean is best applied to interval and ratio data.
    -   The mean of discrete and ordinald data can be useful, but must be carefully interpreted.
    -   The mean is not appropriate for nominal data.

### Median

-   It is suitable for unimodal distributions.
-   The suitable data types are interval, ratio.

### Mode

-   Mode is known as most common value.
-   It is suitable for any distribution.
-   Suitable for any data (numerical data should be converted to discrete)

### Summary (Mean, Median, Mode)

**Mean :** Average value, sensitive to outliers. Most commonly used measure of central tendency.
**Median :** Middle value (50% below, 50% above).
**Mode :** Most common value.

### Variance

-   It is suitable for any distribution.
-   Suitable data types are numerical and ordinal (but requires mean)
-   In formula, why are the differences squared?
    -   We want the distance to the average; without squaring the variance would be 0.
-   In formula, why not take the absolute value ("mean absolute difference")?
    -   **Squaring:** emphasizes large values; is better for optimization (continuous and the differentiable); is closer to Euclidean distance; is the second "moment" of the distribution; better link to least-squares regression; and much more.
    -   **MAD:** Also good; robust to outliers; less commonly used.
-   In formula, why divide by n-1?
    -   Dividing by N-1 is for sample variance.
    -   Dividing by N is for population variance.
    -   Population mean is a theoretical quantity, whereas the sample mean is an empirical quantity.

**QQ Plot:** To determine whether your data distribution is normal(Gaussian or non-Gaussian).

### Statistical moments

| Moment Number | Stats Number | Interpretation       |
| ------------- | ------------ | -------------------- |
| First Moment  | Mean         | Average Value        |
| Second Moment | Variance     | Dispersion           |
| Third Moment  | Skewness     | Dispersion asymmetry |
| Fourth Moment | Kurtosis     | Tail "fatness"       |

### How many bins? (Histogram)

-   k = [(max(x) - min(x)) / h]
-   h - bin width
-   k - number of bins
-   we use the ceiled values

| Guidelines        | Formula                | Key Advantage                            |
| ----------------- | ---------------------- | ---------------------------------------- |
| Sturges           | k = [log2(n)] + 1      | Depends on data count                    |
| Freedman-Diaconis | h = 2IQR / cuberoot(n) | Depends on data count and on data spread |
| Arbitrary         | k = 40                 | Easy to use                              |

### Entropy

-   Suprising things convey more information.
-   This formula can be applied to Nominal, ordinal, discrete data.
-   If we have interval or ratio data, we can convert it to discrete by binning (via histogram creation)
-   Entropy depends on bin size and number
-   High entropy means that the dataset has a lot of variability.
-   Low entropy means that most of the values of the dataset repeat (and therefore are redundant)
-   Entropy is nonlinear and makes no assumptions about the distribution.
-   Variance depends on the validity of the mean and therefore is appropriate for roughly normal data.
