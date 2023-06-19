# Statistical Independency Tests

When working with categorical variables, it is often useful to determine if the 2 variables come from the same distribution or not (thus, if they are dependent or independent).
Knowing if the 2 variables are independent may be useful for several reasons like the validity of the results, the elimination of the bias from your data and the consistency and reliability of the results.
There is much confusion about these statistical tests and what "one-tailed" and "two-tailed" mean or when each of these tests should be applied.
This notebook, will explore in detail these tests and the variants that can be found.

Of course, some theoretical knowledge must be known in advance in order to understand the content:
- Fisher's test: Exact statistical test which is mainly used when the contingency table has the shape (2,2) and the expected counts for at least one element are $\leq 5$.
- $\chi^2$ test: Statistical test which makes an approximation between the data obtained from the statistics and the $\chi^2$ distribution with the appropriate number of degrees of freedom.

When talking about statistical tests you may consider:
- one-tailed tests: A one-tailed test is such that only one side of the distribution function is considered. You are interested only in whether the values are either greater or lower than the expected counts.
- two-tailed tests: A two-tailed statistical test looks for dependency on both sides of the distribution function.

![one-tailed vs two-tailed](./one-tailed-vs-two-tailed-test.jpg)
