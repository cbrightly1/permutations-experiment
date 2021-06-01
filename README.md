# 2 Sample t-test Permutations Experiment
2 sample t-test Experiment with a small survey (n < 30). The client was frustrated with the limitations of the parametric 2 sample t-test and was open to other methods of obtaining statistical support. The permutation or randomization test was a perfect application for this data set, so I built the code to see if the results could be helpful. 

## Data Background
* The survey was given to students and their supervisors. The primary investigators were interested in if the survey responses on a likert scale were significantly different between the two groups.

## Permuation Test Outline
* Hypotheses: 
    * Null: The average survey response is the same between the two groups.
    * Alternative: The average survey response is not the same between the two groups.
* Obtain the t-statistic from the original data set.
* Between the two groups, permute or shuffle the responses without replacement.
* Calculate the t-statistics from the permuted responses.
* Repeat the permuation 1000 times.
* Calculate the proportion of t-statistics in the permutations that were greater than the original t-statistic. This proportion is the p-value for the test and can be treated as such (alpha = 0.05).

## Project Highlights
* In the end, none of the survey questions had a p-value that was equal to or below 0.05. Therefore, none of the questions had significantly different response between the student and the supervisor.
* Histograms were made for each question to show the distribution of the t-statistic from the permutations. 
* While the intiution is strong, it took a couple of attempts to understand the test interpretation and the correlation with the histograms.
