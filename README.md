# Gender Bias in Graduate Admissions

If you were a man applying to Berkeley's graduate school in 1973, you were almost twice as likely to be admitted as your female peers. On the surface, this seems to have been a flagrant case of gender discrimination. However, a closer inspection of the data reveals that women were more likely to apply to departments where the admission rate was lower overall, which was the true reason for any difference between the sexes.

The Berkeley problem is a classic example of Simpson's paradox – an important concept in statistics where an effect disappears or even reverses when you control for other factors. Knowledge of this concept can prove critical in areas such as education policy, human resources, or any other field where bias or discrimination is a concern.

![Berkeley](https://user-images.githubusercontent.com/23168063/216784296-9d50dbcb-8db6-4ba4-9a6a-138a847f1ac9.jpg)

It's 1973, and – as one of the top-ranked universities in the United States – Berkeley has attracted thousands of applicants to its graduate school. But how many made the cut?

I will start off by loading the UCBAdmissions dataset, which is included in base R. This shows the number of students – male and female – who were admitted or rejected from the six largest departments at Berkeley. Since the dataset takes the unwieldly form of a three-dimensional array, I will convert it to tidy format using the tidy function from the tidytext package. Then I will be ready to start doing some analysis.
