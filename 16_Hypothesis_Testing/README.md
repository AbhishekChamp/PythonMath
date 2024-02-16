### Stats Lingo

-   **Dependent Variable (outcome variable):** The variable you are trying to explain.
-   **Independent Variable (explanatory variable):** The variables that you hope will explain the dependent variable.
-   **Model:** A model is an equation that explains some features in a dataset.
-   Residuals should be small, but model should be simple.
-   Residuals should be small, but models should be relevant.
-   A model should be as simple as it can be, and as complicated as it must be.

### Hypothesis

-   A falsifiable claim that requires verification, typically from experimental or observational data, and that allows for predictions about future observations.
-   Hypotheses improve experiment design, critical thinking and data analyses.
-   Hypotheses transform loose ideas into concrete and specific claims.
-   Hypotheses are used to develop new and more accurate theories, and to dissolve bad theories.
-   Most progress in science, engineering and medicine is the result of hypothesis-testing.
-   The **null hypothesis** is the hypothesis that nothing interesting is happening in the data.
-   It is not possible to prove an hypothesis.
-   Hypotheses can be rejected or fail to be rejected (interpreted as being supported).

### p-value

-   They are probabilities.
-   They range from 0 to 1.
-   Values closer to zero indicate low probability of alternative hypothesis values, given null hypothesis H<sub>A</sub> | H<sub>O</sub>
-   Values closer to one indicate high probability of alternative hypothesis values, given null hypothesis H<sub>A</sub> | H<sub>O</sub>
-   A finding is called **statistically significant** if the test statistic is greater than a threshold.
-   Threshold is arbitrary; common values are p<.05 or p<0.01
-   There are several ways to compute a p-value, and they depend on the specific statistical test and assumptions made.
-   Importantly, the interpretation of a p-value is always the same, regardless of how the p-value was computed.

### Why are degrees of freedom important?

-   Degrees of freedom (df) determine the shape of H<sub>O</sub> distributions.
-   Higher df generally indicates more power to reject the null hypothesis (related to statistical power).
-   df is also a way of checking an ANOVA table for accuracy and understanding.

### Degreees of freedom:

-   The number of independent sample values.
-   The number of sample data points that can vary.
-   The number of data values that are unconstrained by the rest of the data values.
-   Generally: **_df = N - k_** (N data points, k parameters)

### Parametric Vs Non-Parametric Tests

| **Parametric test** | **Non-parametric test** |
| ------------------- | ----------------------- |
| 1-sample t-test     | Wilcoxon sign-rank test |
| 2-sample t-test     | Mann-Whitney U test     |
| Pearson correlation | Spearman correlation    |
| ANOVA               | Kruskal-Wallis test     |

| **Parametric statistics**                          | **Non-parametric statistics**                           |
| -------------------------------------------------- | ------------------------------------------------------- |
| Standard, widely used                              | Some are nonstandard                                    |
| Based on assumptions                               | No assumptions necessary                                |
| Assumptions should be tested, (though rarely done) | Can be slow/intensive                                   |
| Can be incorrect when assumptions are violated     | Some are sensible algorithms rather than proven methods |
| Computationally fast                               | Appropriate for non-numeric data                        |
| Analytically proven                                | Appropriate for small sample sizes                      |
|                                                    | Some methods give different results each time           |

**Conclusion:**

-   Use parametric methods when possible.
-   Use nonparametric methods when necessary.

| **p-value**                                                             | **classification accuracy**                                      |
| ----------------------------------------------------------------------- | ---------------------------------------------------------------- |
| Tests the probability of the sample statistic (or model) by chance      | Tests how closely the model output matches an observed outcome   |
| Can be computed separately for each parameter in the model              | Individual parameter contributions can be difficult to determine |
| Analytic solutions with established mathematical theory                 | Sensible empirical method. Results may differ for each run       |
| Can be obtained for nearly any kind of model with any kind of variables | Used only for certain kinds of models and variables              |
| Sensitive to extreme N's                                                | Robust to sample size                                            |
