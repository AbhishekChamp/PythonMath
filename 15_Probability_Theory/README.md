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
