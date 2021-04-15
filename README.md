# Comparing Baltimore vs Washington D.C. Household Income and College Graduation Rate

## Background
Baltimore and Washington D.C. are both considered two of the biggest cities in the east coast of the United States. Two cities share many similarities as they both have a population around 600,000 people and are only 30 miles apart from each other. However, Washington D.C. is generally more known to people as it is the capital of the country. Considering this fact, I wanted to compare the average household income of two cities and how the results affect the college graduation rates. 
## Business Question
_As Washington D.C. being the capital of United States and has much lower unemployment rate, would people living in Washington D.C. have higher average household income than those living in Baltimore? How does the difference in average household income affect college graduation rates in both cities?_
## Household Income
Extracting data from Opportunity Atlas, I was able to compare the average household income of Baltimore and Washington D.C. regardless of parents' income, race, and gender.

## Previous Excel Data

#### Baltimore
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/Baltimore%20Average%20Household%20Income%20Graph.png)
Using the data from Opportunity Atlas, I created a Pivot Table and a Bar Chart to analyze the average household income in Baltimore. The average household income in Baltimore is $29,900.
#### Washington D.C.
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/Washington%20D.C.%20Average%20Household%20Income%20Graph.png)
Using the data from Opportunity Atlas, I created a Pivot Table and a Bar Chart to analyze the average household income in Washinton D.C. The average household income in Washington D.C. is $35,500.
#### College Graduation Rate vs Household Income
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/College%20Graduation%20Rate%20Graph.png)

In addition to average household income data, I was able to get the data of college graduation rates for both Baltimore and Washington D.C. The data shows that the college graduation rate for Baltimore is 21.63% while the rate for Washington D.C. is 33.91%. The graph shows that Washington D.C. has both higher average household income and college graduation rates than Baltimore. 

By comparing Baltimore and Washington D.C., I could conclude that higher household income leads to higher college college graduation rates and vice versa. As a college student in Baltimore, it was interesting to conduct an analysis of average household income and college graduation rates of Baltimore and to compare the data with a nearby city.  

## Python Analysis

In Python, I used the same data sets from Opportunity Atlas. I was able to merge the data of household income and college graduation rates for both cities. By utilizing numpy statements, I was able to organize the names of the counties into two big categories: Baltimore, MD and Washington D.C. Using pivot analysis and creating a bar chart from plotly, I was able to compare the household income and college graduation rates of two cities.

### Household Income
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/bal_was_inc.png)

Baltimore Average Household Income : $49,535
Washington D.C. Average Household Income: $46,967

Washington D.C. has a higher average household income than that of Baltimore. 

### College Graduation Rates
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/bal_was_college_grad.png)

Baltimore College Graduation Rates: 0.43
Washington D.C. College Graduation Rates: 0.55

Washington D.C. has a higher college graduation rates than Baltimore. 

### Household Income vs College Graduation rates

From the analysis above, we might be able to associate household income and college graduation rates as Washington D.C. has both higher household income and college graduation rates than Baltimore. In order to prove this theory, I have looked at the relationship between household income and college graduation rates for both cities separately using line graph through plotly. 

#### Baltimore
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/bal_inc_college.png)

#### Washington D.C.
![alt text](https://github.com/justinjiholee/baltimore-washingtondc-household-data/blob/main/was_inc_college.png) 

These graphs show that while not all counties with higher household income leads to higher college graduation rates, there is some correlation between the two variables. In both Baltimore and Washington D.C., counties with higher household income tend to have higher college graduation rates as the line is increasing.

## Conclusion




