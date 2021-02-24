## A/B Test 

### Scenario: Decision between 2 different versions of email (A and B) - Maximizing click-through rate

**Metric of choice: click-through-rate**

Conducted an experiment with a sample size of 1000. The 2 websites were shown and the click-through rate was measured.
The contingency table is shown below:

![image](contingency_table.png)

The data was analyzed using a Bayesian as well as a Frequentist approach.
- Bayesian result: email B outperforms email A 93% of the time.
- Frequentist chi-square test: the difference between the variants are not statistically significant
- Frequantist proportion Z-test: same result as chi-square test. As only 2 variants were tested, I could use a proportion Z-test, however, if there are more than 2 variants to be tested, proportion Z-test is not a feasable approach.
