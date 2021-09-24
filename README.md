# A/B Test Result Analysis

Analysing A/B test results, using Python

## Summary

In this this project, I analysed the results of an A/B test run by a fictional e-commerce website. The company had developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. My goal was to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

This project had a series of predefined steps to follow, with the analysis for each step needing to be coded. Techniques called upon included statistical tests and regression.

The data cannot be shared, so the only file available here is Analyze_ab_test_results_notebook.html, a static HTML version of the Jupyter Notebook file. The data is included for reference.

## Conclusions

The z-score of -1.311 meant that the observed difference was 1.311 standard deviations below the (assumed) true difference of zero.

The p-value of 0.9051 meant that there was a 90.51% probability of observing a difference greater (in value) than our observed difference when drawing a random sample of this size from the population, assuming the true difference is zero.

This meant there was not sufficient evidence to reject the null hypothesis that the new pages are no better than the old pages, because the p-value obtained is greater than the chosen Type I error rate of 5%.

Based on this analysis, the company should not implement the new page.

## Credits

This project was provided by [Udacity](https://www.udacity.com) as part of their [Data Analyst nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002).
