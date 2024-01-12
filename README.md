![power of data](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2013.53.07.png)

# Introduction
- Welcome! I'm Moiez, a passionate data analyst with a background in Geography and Philosophy from York University. My journey began with Python, driven by a fascination for data's storytelling power and its impact on the world. I specialize in Python, R, Excel, Google Sheets, and Tableau, with a focus on data cleaning, statistical calculations, and visualization. Notable projects include a comprehensive analysis of Shinkansen travel data and a detailed study of bank loan defaults, both reflecting my interest in service-oriented industries like
- 
## Table of Contents
- [Nike vs Adidas shoe pricing and rating analysis](https://github.com/moiez326/Nike_vs_Adidas/blob/main/nike%20vs%20adidas.ipynb)
  - [Data Source](https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike)
  - [data_repo](https://github.com/moiez326/Nike_vs_Adidas/tree/main/data)
- [Bank Loan Default Client Risk Factor Analysis](https://github.com/moiez326/loandefault/blob/main/loan_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/loandefault/tree/main/data)
- [Shinkansen Travel Experience and Satisfaction Analysis](https://github.com/moiez326/Data_analysis_portfolio/blob/main/Shinkansen/shinki_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/shinkansen/tree/main/data)
- [US Adidas Regional trends analysis](https://github.com/moiez326/US-Adidas-sales/blob/main/adidas_EDA.ipynb)
  - [data_repo](https://github.com/moiez326/US-Adidas-sales/tree/main/data)

## [Nike vs Adidas Shoe Pricing and Rating Analysis](https://github.com/moiez326/Nike_vs_Adidas/tree/main)
![shoes](https://www.vestilanatura.it/wp-content/uploads/2022/06/nike-vs-adidas-competizione-e-rivalita.jpg)

#### Context 
- The "Adidas Sales Analysis" project offers a comprehensive examination of Adidas' sales data in the United States. This analysis aims to decode patterns in sales, understand profitability dynamics, and grasp customer preferences.

### Key insight 
![chart 1](https://github.com/moiez326/Nike_vs_Adidas/blob/main/media/Screenshot%202023-11-28%20at%2013.23.57.png)
  
- Regression analysis shows a weak correlation between price and rating for both brands.
- Adidas exhibits marginally higher average ratings in the \$50 to \$100 price range. Nike, on the other hand, shows greater variability in customer ratings at higher price points.
#### Data Source
The analysis utilizes data from [Kash on Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike), featuring transactional sales data for various Adidas products across different US regions.

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
![N700 series Shinkansen](https://www.japanhouselondon.uk/assets/New-Discover-page/_resampled/FillWyI3MjgiLCI0MDgiXQ/Shinkansen-Landing-page-banner.jpg)

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

### Key insight
![chart 4](https://github.com/moiez326/Data_analysis_portfolio/blob/main/US%20Adidas/Screenshot%202024-01-12%20at%2012.16.28.png)

- - Seasonal and Regional Dynamics: Sales across all regions demonstrate seasonal peaks, with the South reaching the highest in July, likely influenced by summer promotions or events. The West peaks similarly in mid-year, while the Northeast and Southeast show steadier sales with less variance. A common trend across regions is a noticeable dip in February, reflecting a post-holiday sales decline.
- Mid-Year Recovery: Sales generally pick up starting in March, with varying degrees of increase across regions.
- Year-End Behavior: The South dips after mid-year but picks up slightly in December, while the Northeast and Southeast show gradual increases towards year-end, and the West experiences a decline post-August.
- Volatility and Leadership: The South region not only leads in sales volume but also shows the most significant volatility. The Midwest follows a similar pattern with lower overall sales.

### Executive summary
- ### Strategic Insights for Adidas

- **Optimization Strategies**: Concentrating marketing on high-margin segments like Men's Street and Women's Footwear, especially in the high-performing West region, could enhance profitability. Meanwhile, targeted strategies are needed for other regions to boost sales.
- **Product and Pricing Focus**: The success in Women's Footwear suggests potential for growth through focused innovation, while varied margins across categories highlight opportunities for strategic discounting to increase volume sales.
- **Comprehensive Review**: A detailed understanding of regional and category-specific successes can inform overall cost management and strategic direction to improve Adidas's market position.
