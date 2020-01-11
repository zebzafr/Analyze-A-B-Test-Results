# Analyze-A/B-Test-Results

#### Project Overview
For this project, I worked to understand the results of an A/B test run by an e-commerce website. The company had developed a new web page to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The goal is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

#### Part I - Probability
Statistics were computed to find out the probabilities of conversion for both new and old page. These were used to analyze if one page or the other led to more conversions.

#### Part II - A/B Test
Next, hypothesis testing was conducted assuming that the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%.

The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

#### Part III - Regression
Logistic regression was chose based on the target variable 'converted' to confirm results of the previous steps. Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

Also, impact of the country where a user lives on conversion rate for different pages was analyzed using the statistical output using logistic regression.

#### Conclusions
1. A/B Testing and Regression Modeling suggest that navigating either page old or new will not lead to conversions.
2. There is no impact of the location of the user on the conversion rate.
