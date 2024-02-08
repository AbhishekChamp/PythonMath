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
