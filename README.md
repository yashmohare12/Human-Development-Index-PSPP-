

**Drivers of Global Development: A Statistical Regression Analysis**

**Objective **
The objective of this analysis was to identify the primary drivers of the Human Development Index (HDI) across 25 diverse nations. Using Multiple Linear Regression, we modeled the relationship between HDI and four key indicators: Economic Wealth (GDP), Public Health (Life Expectancy), Infrastructure (Internet Penetration), and Education (School Enrollment).The final model explains 96% of the variance in HDI scores (R^2=.96). The analysis reveals that while all four factors are statistically significant, Life Expectancy and Internet Penetration are the strongest predictors of a nation's development, outweighing raw GDP per capita.

**Methodology & Data Tool Used:**

PSPP (Statistical Analysis Software) Sample Size: N = 25 Countries (ranging from Low to Very High HDI).

Variables Analyzed:

Dependent Variable (DV): Human Development Index (0-1 scale).

Independent Variables (IV):

GDP Per Capita: Wealth measure (USD).

Life Expectancy: Health measure (Years).

Internet Penetration: Digital infrastructure measure (%).

School Enrollment: Education measure (% Gross).

<img width="827" height="254" alt="image" src="https://github.com/user-attachments/assets/292bb1cc-55f5-4e21-abd1-ea7086aabb34" />
<img width="829" height="569" alt="image" src="https://github.com/user-attachments/assets/513bd30c-0ee9-4025-aad6-4deb4ec5c938" />
<img width="827" height="698" alt="image" src="https://github.com/user-attachments/assets/8df1b722-3fef-42a4-b8ae-4e68b6d6b37c" />


**Regression Coefficients** & Drivers The regression output confirms that all four variables are significant predictors of HDI (p<0.05)


<img width="825" height="509" alt="image" src="https://github.com/user-attachments/assets/5a9cd81e-721a-4ff4-bfd2-178b88c9afb5" />

**Analysis of Multicollinearity:** We examined the VIF (Variance Inflation Factor) values. All VIF scores are below 5 (Highest: Internet at 4.56), indicating that while the variables are correlated, multicollinearity is within acceptable limits and the model is valid.

**Key Findings & Managerial Insights1.** Health is Wealth (Beta .38): Contrary to the popular belief that "money buys development," our model proves that Life Expectancy is the single strongest driver of HDI. A healthy population is more productive and capable than a purely wealthy one. The Digital Factor (Beta .31): Internet Penetration emerged as the second most important factor. In the modern economy, access to information acts as a "force multiplier" for development 3. The Education Threshold (Beta .18): School Enrollment was significant, but it had the lowest impact. This suggests that while getting students into school is necessary, it is the outcomes of that education (often captured by Internet usage and GDP) that truly drive development scores.

****Conclusion ****
This project successfully validated a 4-factor model for predicting Human Development. The analysis suggests that developing nations looking to improve their standing should prioritize Healthcare and Digital Infrastructure investments, as these yield higher marginal returns on HDI than focusing solely on GDP growth.



