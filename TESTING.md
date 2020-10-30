 was looking for a way to generate random data to use as input for my one sample t-test in R Markdown. In this example, I want to compare the results of psychology students to the results of the population, in the form :

oneSampleTTest (x=grades, mu=67.5)

The problem is that I do not want to use a data frame that is imported in R. I want to generate random data that I would use as input for both "grades" and the "mu". Further, the code should be in R Markdown format, i.e.,

```{r test output, echo = FALSE, comment = NA}
print(tt)
