# assessments
This repository will contain all assessments I would have to do as part of an interview process or something of the sort. So far I have had to do one assessment (Assessment_pd) involving the analysis of households to find correlation between some features such an income, education and access to water or electricity.The dataset contained information about households in a rural community. It included details such as household ID, number of family members, income(Ghc), education level of the head of the household, and access to basic amenities like electricity and clean water.The task was to clean the dataset, perform exploratory data analysis, and derive meaningful insights that can inform community development initiatives.

Part A: Data Cleaning
1. Cleaning the dataset by handling missing values, removing duplicates, standardizing formats, and ensuring data consistency.

Part B: Data Analysis
1. Conducting exploratory data analysis on the cleaned dataset to uncover patterns, trends, and relationships.
2. Applying relevant statistical techniques (e.g., correlation analysis, hypothesis testing) to gain insights into the socio-economic conditions of the households.
3. Identifying any significant factors that contribute to the households' access to basic amenities.

These are some of the key insights:
Correlation Analysis Interpretation:
Income and Number of Family Members: The correlation coefficient is highly positive. It indicates that higher family size is associated with higher income.
Income and Education Level: Positive correlation suggests that higher education levels are associated with higher income.

Hypothesis Testing Interpretation:
T-test for Income by Access to Electricity:
The p-value is less than 0.05, it indicates that there is a significant difference in the income of households with and without access to electricity. And the same with access to water
If the p-value is greater than 0.05, it suggests that there is no significant difference.

Chi-Square Test for Education Level and Access to Clean Water:
The p-value is less than 0.05, it indicates that there is a significant association between education level and access to clean water, as well as education level and access to electricity.
If the p-value is greater than 0.05, it suggests that there is no significant association.

Therefore the significant factors that contribute to a household's basic amenities are the income and the education level. And the income is affected by the number of individuals in the household.

Income Distribution:
The average household income is 2745.188888 Ghc, with a median of2700.000000Ghc.
The distribution of income across households almost represents a bell curve.

Education Levels:
Equal distribution of educational level.
Higher education levels are positively correlated with higher income.

Access to Amenities:
More households have access to electricity, while less households have access to clean water.
Households with access to electricity have significantly higher incomes compared to those without (T-test p-value < 0.05).

Statistical Analysis:
A significant association between education level and access to clean water (Chi-Square test p-value < 0.05) indicates that more educated households are more likely to have access to clean water.
By following these steps, you can clean your dataset, perform statistical analysis, and derive meaningful insights that can inform community development initiatives.
