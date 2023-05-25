# Retail-Price-Optimisation
Maximising the profits of a Cafe, by modelling the products price elasticity, leveraging linear regression. Statistical Inference

## Data
We are provided with three datasets. A daily transactional datasets recording daily transactions at the cafe for the 4 products sold, the burger, the burger + lemonade, the burger + coke, the burger + coke + coffee. A product description datasets that give more information about the products. And a day info dataset, which gives specific information about any given day (weekend or weekday, holiday or not, schoolbreak or not, temperature, etc...) 

## Methods
- The EDA work helps us analysing, at the level of the cafe, which are the most important products. In case of tradoffs to be done, we should privilege our most selling and profitable products 
- When seeing that not all products contribute equally to the variance of the cafe's profits, some are more important than others, we try to see which factors, price but also others, can have an impact on quantity sold and therefore profits 
- We validate which features are useful and necessary to effectively model product quantity sold, through linear regression, F tests and T tests. We also make sure the conclusions of the linear regressions are valid by performing residuals analysis
- We then model quantity based on price as the price will be our main lever to maximise profits. For every product. For the main product here, we derive 4 equations, whether we are in the weekend/weekday, and whether we are in colder or warmer times, as the quantity sold also seemed to change in those conditions (without seeing a change in price)
- Then we make sure that cannabilisation will not occur, optimising for one product should not lead to decreasing the sales of another, by plotting quantity solds correlation between products
- Thanks to our products price elasticity equations, we then create a function to calculate the optimal price and the additional estimated profits leveaging the optimal price
- We conclude on the overall profits gained from this pricing optimisation decision making

## Results
We find that optimising for prices for every product may lead in some cases to 2x profit increase 

## Limitations 
A better way to be sure of our conclusion, would be to experiment on the prices, either on the same cafe in different yet similar days. Or on two similar cafes 

## Conclusion
This analysis provides the tools needed for a pricing manager to quantify the expected increase in profits, when using a theoretical optimal price


