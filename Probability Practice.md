# Probability Practice

## Part A

Given 65% said Yes and 35% said No with a fraction of random clickers being 0.3 and random clickers clicking either one with equal probability, we can use the rule of total probability.

The rule of total probability for this scenario can be written: 

P(Yes) = P(Yes|Random Clicker) * P(Random Clicker) + P(Yes|Truthful Clicker) * P(Truthful Clicker)

We can rewrite this formula to find out what fraction of people who are truthful clickers answered yes:

P(Yes|Truthful Clicker) = (P(Yes) - P(Y|Random Clicker) * P(Random Clicker)) / P(Truthful Clicker)

We know from the problem statement the following parts of the total probability formula:

P(Yes) = 0.65

P(Random Clicker) = 0.3

P(Truthful Clicker) = 1 - P(Random Clicker) = 0.7

P(Yes|Random Clicker) = 0.5

We can now plut in the values into the total rule of probability formula:

P(Yes|Truthful Clicker) = (0.65 - 0.5 * 0.3) / 0.7 = 0.714

Therefore, the fraction of people who are truthful clickers that answered yes is **0.714**.


## Part B

Given that someone tests positive, the probability that they have the disease can be calculated using Bayes Rule.

For this scenario, Bayes Rule can be written:

P(Disease|Positive) = (P(Disease) * P(Positive|Disease)) / P(Positive)

From the problem statement, we can extract each of the probabilities needed to solve the problem:

P(Disease) = 0.000025

P(Positive|Disease) = the sensitivity = 0.993

To find the probability of a positive test, we can use the total rule of probability:

P(Positive) = P(Positive|Disease) * P(Disease) + P(Positive|no Disease) * P(no Disease)

P(Positive|no Disease) = 1 - specificity = 1 - 0.9999 = 0.0001

P(No Disease) = 1 - P(Disease) = 1 - 0.000025 = 0.993

P(Positive) = 0.993 * 0.000025 + 0.0001 * 0.993 = 0.0001248225

Now that we have all the probabilities, we can solve for P(Disease|Positive):

P(Disease|Positive) = (0.000025 * 0.993) / 0.0001248225 = 0.1988

Therefore, if someone tests positive, the probability that they have the disease is **0.1988**.