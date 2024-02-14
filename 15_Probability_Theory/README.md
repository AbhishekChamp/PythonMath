### Definition of probability

-   Probability is a numerical description of how likely an event is to occur or how likely it is that a proposition is true.
-   Probability is a number between 0 and 1, where, roughly speaking, 0 indicates impossibility and 1 indicates certainty.
-   The sum of all probabilities in a set must sum to 1.
-   We need probability when there is uncertainty about the outcome of an event.

### Data types for probability

-   Discrete
-   Ordinal
-   Nominal
-   Interval or Ratio -> convert them to discrete

### Data validity for probability

-   Data must have mutually exclusive labels or bins.
-   Because total probabilities must sum to 1 (100%).

The **probability** of event **_i_** is the **count of events** **_i_** divided by the **total number of all events.**

### Odds

-   Often discussed in the context of betting or disease.
-   r = m / n
-   For example, "The odds are 6:1 against."

### Odds as a probability ratio

-   "Odds" is a ratio of the probability of an event not occuring, to the probability of it occuring.
-   r = ( 1 - p ) / p
-   p = 1 / ( 1 + r )
-   p = 1 / ( 1 + ( m / n ))
-   **Example:** What are the odds of drawing a king in a deck of cards?

### Probability mass vs density

-   **Probability:** The chance that an event will occur.
-   **Probability mass:** A function that describes probabilities for a set of exclusive **_discrete_** events.
-   **Probability density:** A function that describes probabilities for a set of exclusive **_continuous_** events.

### Cumulative Distribution Function (cpf)

-   A cpf is the cumulative sum (or integral) of the probability distribution (or density).
-   The y-axis value at each x-value is the sum of all probabilities to the legt of that x-value.
-   A cdf starts at 0 and increases monotonically to 1. The sum of the cdf is more than 1.
-   **Example:** What is the probability of getting at least 1 std higher on the SATs than average?

### Monte Carlo Methods

-   To solve really hard problems by randomly sampling the solution instead of doing the **_real work._**
-   Often used in physics, statistics, deep learning, even in pure math.
-   **Monte Carlo sampling** is the same thing as randomly sampling from a population to estimate an unknown population parameter.

### Sources Of Sampling Variability

-   **Sampling variability:** Different samples from the same population can have different values of the same measurement.
-   **Implications:** A single measurement may be an unreliable estimate of a population parameter.
-   **Natural variation:** Often seen in biology **_(e.g., height, weight)_** and physics **_(e.g., earthquake magnitude, number of stars per galaxy)_**
-   **Measurement noise:** The senors are imperfect **_(e.g., electrical line noise, measuring micrograms with a gram-precision scale)_**
-   **Complex systems:** Measuring some factors while ignoring others **_(e.g., measuring height while ignoring age)._**
-   **Stochasticity (randomness):** The universe is a wild and unpredictable place **_(e.g., photons hitting a camera lens)._**

### What to do about sampling variability?

-   **Take many samples!** Averaging together many samples will approximate the true population mean.
-   **Run statustical analyses!** Compute measures of confidence of sample-based parameter estimates.

### Expected value Vs Average value

-   Average is an empirical sample estimate based on finite data.
-   Expectation value is the expected average in the population, or from a very very large number of samples **_(approaching infinity)._**
-   Expected value and average value are the same **_when drawing LARGE and representative random samples from a population._**

### Conditional Probability

-   The probability of event **A** changes based on what you know about event **B**.
-   **A** and **B** are independent when knowing **_P(A)_** provides no information about **_P(B)_**. In such cases, **_P(A intersect B) = P(A)P(B)_**
-   **P (A | B) = P (A intersect B) / P(B)**

### Law of Large Numbers

-   As the number of experiment repetitions increases, the average of the sample means better approximates the population mean.
-   Any one sample (or any one experiment) is sensitive to sampling variability, noise, and other sources of non-systematic variation.
-   This means that one sample or one experiment is unlikely to provide a good estimate of the true population mean.
-   But sampling many times can provide an accurate measure of the true population mean.

### Central Limit Theorem

-   The distribution of sample means approaches a Gaussian distribution, regardless of the shape of the population distribution.
-   Random samples from independent variables will tend towards a normal **(Gaussian)** distribution, even if the variables are non-normally distributed.
-   The above depends on sample count, data scale or normalization and other factors.
-   Many statistical analyses rely on the assumption of normality (roughly Gaussian distribution).
-   Gaussian distributions are easy to paramterize (mean, variance, skew, kurtosis) and compute confidence intervales around.
-   Independent components analysis (ICA) is based on the assumption that signals are non-Gaussian distributed while random mixtures of signals are Gaussian.
