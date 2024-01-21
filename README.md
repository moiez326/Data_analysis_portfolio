![power of data](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2013.53.07.png)

# Introduction
Welcome! I'm Moiez, a data analyst fascinated by the power and impact data. I use tools like Python, Open AI API, Google Sheets, and some machine-learning, and Tableau to uncover insights in service-centric and consumer-focused industries.
I'm interested in sectors such as train/air travel, hotels, sportswear brands, and online retail. My porfolio is characterized by a focus on:

Travel and Transport: I focus on analyzing travel trends and passenger preferences in train and air travel to improve their experience and streamline operations.
Apparel and Sportswear: I study market trends, consumer behavior, and competitive strategies in the sportswear and fashion industry.
E-Commerce: My work involves understanding online shopping behavior, enhancing digital marketing, and increasing customer engagement.

## Table of Contents
- [Nike vs Adidas shoe pricing and rating analysis](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Nike%20vs.%20Adidas%20shoes/nike_adidas.ipynb)
  - [Data Source](https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike)
- [Bank Loan Default Client Risk Factor Analysis](https://github.com/moiez326/loandefault/blob/main/loan_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/loandefault/tree/main/data)
- [Shinkansen Travel Experience and Satisfaction Analysis](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Shinkansen/shinki_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/shinkansen/tree/main/data)
- [US Adidas Regional trends analysis](https://github.com/moiez326/US-Adidas-sales/blob/main/adidas_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/US-Adidas-sales/tree/main/data)
  - [SQL analysis](https://github.com/moiez326/Data_analysis_portfolio/blob/main/US%20Adidas/US%20Adidas%20SQL.ipynb)

## [Nike vs Adidas Shoe Pricing and Rating Analysis](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Nike%20vs.%20Adidas%20shoes/nike_adidas.ipynb)
![shoes](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Nike%20vs.%20Adidas%20shoes/Screenshot%202024-01-21%20at%2016.47.51.png)

#### Context 
- Compare Adidas and Nike based on price, rating, and discount % to identify trends within the sportswear industry.

### Key insight 
![chart 1](https://github.com/moiez326/Nike_vs_Adidas/blob/main/media/Screenshot%202023-11-28%20at%2013.23.57.png)
  
- Regression analysis shows a weak correlation between price and rating for both brands.
- Adidas exhibits marginally higher average ratings in the \$50 to \$100 price range. Nike, on the other hand, shows greater variability in customer ratings at higher price points.

#### Executive summary
- Nike generally offers more expensive and higher-rated shoes, maintaining their market dominance, while Adidas provides more generous discounts, offering better value-for-price options. However, raises a question: Does Nike's market leadership primarily derive from its global brand presence, shaped by marketing and high-profile athlete endorsements? I believe these approaches contribute to a perceived image of superior quality and value, distinguishing Nike from competitors like Adidas, Reebok, Under Armour etc. 

## [Bank loan default client risk factor analysis](https://github.com/moiez326/loandefault)
![Defaulting loan Analysis](https://media.istockphoto.com/id/1372053987/vector/default-bank-loans-isometric-3d.jpg?s=612x612&w=0&k=20&c=Rqy-n5FhihLGtOf6DtdKjyRI-8l2sRXPYjG69ie79cM=)

#### Context
- The "Global Bank Loan Default Analysis" delves into the complexities of loan defaults, a key aspect of financial risk management. This project investigates various client and loan characteristics to identify the factors that significantly influence loan defaults at Global Bank.

### Key insight  
![Chart 2](https://github.com/moiez326/loandefault/blob/main/media/Screenshot%202023-11-28%20at%2013.37.35.png)

- that loan amount is not a strong predictor of the debt-to-income ratio.
- defaulted loans tend to have a higher debt-to-income ratio, pointing to other contributory factors to loan default.

#### Executive summary 
- The EDA reveals that there is a significant correlation between loan defaults and factors such as the reasons for loans and credit history and that defaulting loans are smaller than good loans.
- By making more categories within the categorical variables, Job and Reasons for loan, Global Bank can have a better picture of who their clients are and why they take out loans to better segment their risk.

## [Shinkansen Travel Experience and Satisfaction Analysis](https://github.com/moiez326/shinkansen)
![N700 series Shinkansen](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Shinkansen/Screenshot%202024-01-12%20at%2014.17.59.png)

#### Context 
- The "Shinkansen Passenger Satisfaction Analysis" project explores the crucial aspects influencing passenger satisfaction on Japan's renowned bullet train. This analysis is centred on understanding the diverse elements contributing to the overall travel experience.

#### Key insight 
![chart 3](https://github.com/moiez326/shinkansen/blob/main/media/Screenshot%202023-12-06%20at%2011.58.55.png)

- Gender and age significantly impact satisfaction levels. Elderly and younger demographics show differing levels of satisfaction, highlighting a potential need for targeted service improvements.

### Executive summary
-  The study focused on age distribution, satisfaction across age groups, gender influence, and the relationship between travel distance and delay times. 
Key findings include:
- Mid-20s and early 40s are the largest passenger demographic groupp with females in general having higher satisfaction, and middle-aged and young adult men having the highest dissatisfaction but this is also due to them being the largest demographic
- delay times are significantly correlated with passenger satisfaction

## [US Adidas regional trends Analysis](https://github.com/moiez326/US-Adidas-sales)
![Adidas logo](https://1000logos.net/wp-content/uploads/2019/06/Adidas-Logo-1991.jpg)

#### Context 
- The "US Adidas Sales Analysis" delves into Adidas's sales data across various U.S. regions, focusing on understanding consumer preferences and uncovering commerce patterns vary across U.S. regions, states, and cities?
#### SQL analysis 
[LINK](https://github.com/moiez326/Data_analysis_portfolio/blob/main/US%20Adidas/US%20Adidas%20SQL.ipynb)
### Key insight
![chart 4](https://github.com/moiez326/Data_analysis_portfolio/blob/main/US%20Adidas/Screenshot%202024-01-12%20at%2012.16.28.png)

### Summary of Adidas Sales Trends
- Peak Season Sales: The South dominates in sales with a significant July peak and post-holiday recovery in December, while the West also sees a mid-year surge. The Northeast and Southeast have more consistent sales with minor fluctuations.
- Sales Patterns: All regions experience a February slump, rebound in March, and diverge towards year-end with the South and Northeast picking up, and the West declining.
- Sales Consistency: The South shows high volatility in sales, leading the regions, whereas the Midwest maintains a similar but less pronounced pattern.
### Executive summary
- Optimization Strategies: Concentrating marketing on high-margin segments like Men's Street and Women's Footwear, especially in the high-performing West region, could enhance profitability. Meanwhile, targeted strategies are needed for other regions to boost sales.
- Product and Pricing Focus: The success in Women's Footwear suggests potential for growth through focused innovation, while varied margins across categories highlight opportunities for strategic discounting to increase volume sales.
- Comprehensive Review: A detailed understanding of regional and category-specific successes can inform overall cost management and strategic direction to improve Adidas's market position.
