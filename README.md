![power of data](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2013.53.07.png)

# Data Analysis Portfolio
-A collection of my data analysis projects. Each project includes a README with context, information, and visualizations:

## Table of Contents
- Nike vs Adidas Shoe Pricing and Rating Analysis
  - Project Insights
  - Data Source
  - Repository Structure
  - Conclusions and Recommendations
  - Future Directions
- Bank Loan Default Client Risk Factor Analysis
  - Project Insights
  - Repository Structure
- Shinkansen Travel Experience and Satisfaction Analysis
  - Project Insights
  - Demographic Impact
  - Key Findings
- US Adidas Geo-Spatial Sales and Trends Analysis
  - Project Insights
  - Regional Profit
  - Product Category Insights

## [Nike vs Adidas Shoe Pricing and Rating Analysis](https://github.com/moiez326/Nike_vs_Adidas/tree/main)
![shoes](https://www.vestilanatura.it/wp-content/uploads/2022/06/nike-vs-adidas-competizione-e-rivalita.jpg)

The "Adidas Sales Analysis" project offers a comprehensive examination of Adidas' sales data in the United States. This analysis aims to decode patterns in sales, understand profitability dynamics, and grasp customer preferences.

### Project Insights:  
  ![chart 1](https://github.com/moiez326/Nike_vs_Adidas/blob/main/media/Screenshot%202023-11-28%20at%2013.20.35.png)
  
- **Numerical Variable Comparison**: Analysis reveals that while Nike shoes generally cost more and have a slightly higher rating, Adidas offers more substantial discounts.

  ![chart 2](https://github.com/moiez326/Nike_vs_Adidas/blob/main/media/Screenshot%202023-11-28%20at%2013.23.57.png)
  
- **Price-Rating Correlation**: Regression analysis shows a weak correlation between price and rating for both brands. Adidas exhibits marginally higher average ratings in the \$50 to \$100 price range. Nike, on the other hand, shows greater variability in customer ratings at higher price points.
#### Data Source
The analysis utilizes data from [Kash on Kaggle](https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike), featuring transactional sales data for various Adidas products across different US regions.

#### Repository Structure
- [Raw Data](https://github.com/moiez326/Nike_vs_Adidas/blob/main/data/shoes_raw_data.csv): The initial dataset.
- [Cleaned Data](https://github.com/moiez326/Nike_vs_Adidas/blob/main/data/shoes_cleaned_data.csv): The dataset post-cleaning and preprocessing.

#### Conclusions and Recommendations
The study has identified pivotal product categories driving sales and profitability and highlighted regional differences in sales performance. Recommendations are provided for pricing strategies and inventory management to enhance Adidas' market position.
#### Future Directions
Future work includes:
- Integrating external data like market trends and customer demographics for a more in-depth analysis.
- Employing machine learning models for predictive sales forecasting and trend analysis.

## [Bank loan default client risk factor analysis](https://github.com/moiez326/loandefault)
![Defaulting loan Analysis](https://media.istockphoto.com/id/1372053987/vector/default-bank-loans-isometric-3d.jpg?s=612x612&w=0&k=20&c=Rqy-n5FhihLGtOf6DtdKjyRI-8l2sRXPYjG69ie79cM=)

The "Global Bank Loan Default Analysis" delves into the complexities of loan defaults, a key aspect of financial risk management. This project investigates various client and loan characteristics to identify the factors that significantly influence loan defaults at Global Bank.

![Chart 2](https://github.com/moiez326/loandefault/blob/main/media/Screenshot%202023-11-28%20at%2013.37.35.png)
### Credit-related variables such as derogatory reports showed a more drastic difference in frequency of bad and good loan status.

Key insights from the analysis include:
- Loan amounts are not significant indicators of the likelihood of default.
- Credit-related factors such as derogatory reports and debt-to-income ratios are more closely associated with loan defaults.
- The purpose of a loan, particularly in the case of debt consolidation, is a critical factor with a higher default rate.

I suggest a refocus in risk assessment models towards the borrower's credit history and the loan's purpose. By refining loan approval criteria, Global Bank can enhance its lending strategies and risk management approach.

## [Shinkansen Travel Experience and Satisfaction Analysis](https://github.com/moiez326/shinkansen)
![N700 series Shinkansen](https://www.japanhouselondon.uk/assets/New-Discover-page/_resampled/FillWyI3MjgiLCI0MDgiXQ/Shinkansen-Landing-page-banner.jpg)

The "Shinkansen Passenger Satisfaction Analysis" project explores the crucial aspects influencing passenger satisfaction on Japan's renowned bullet train. This analysis is centered on understanding the diverse elements contributing to the overall travel experience.

![Age-group and gender satisfaction](https://github.com/moiez326/shinkansen/blob/main/media/Screenshot%202023-12-06%20at%2011.58.55.png)

- Demographic Impact: Gender and age significantly impact satisfaction levels. Elderly and younger demographics show differing levels of satisfaction, highlighting a potential need for targeted service improvements.
Key findings from the study include:
- Service quality and onboard amenities have a more substantial influence on satisfaction than travel distance and delays.
- Demographic factors like age and gender significantly impact satisfaction levels, with varying satisfaction observed in elderly and younger passenger groups.
- The quality of onboard services, such as comfort, catering, and entertainment, emerges as key drivers of passenger satisfaction.

These insights are vital for the travel industry, particularly for services like the Shinkansen. Enhancing service quality and customizing the travel experience to cater to diverse passenger needs can lead to significant improvements in satisfaction rates. Tailoring services to different demographic groups could be

 a strategic approach to boosting overall passenger satisfaction.

## [US Adidas Sales Analysis](https://github.com/moiez326/US-Adidas-sales)
![Adidas logo](https://1000logos.net/wp-content/uploads/2019/06/Adidas-Logo-1991.jpg)

The "US Adidas Sales Analysis" delves into Adidas's sales data across various U.S. regions, focusing on understanding consumer preferences and uncovering growth opportunities in the crucial U.S. market.

### Objective
This comprehensive analysis aims to:
- Conduct **Exploratory Data Analysis (EDA)** to identify patterns and anomalies in Adidas's U.S. sales data.
- Perform **Geo-Spatial Analysis** to visualize and interpret sales data across different geographic segments.

### Key Questions
- How do sales figures and patterns vary across U.S. regions, states, and cities?
- What insights can be gleaned from a geo-spatial analysis of the sales data?

#### Repository Structure
- [adidas_EDA.ipynb]: Jupyter notebook containing in-depth EDA and visualizations.
- adidas_csv_master.csv: Raw sales data.
- final_adidas.csv: Cleaned and processed sales data.
- stores.csv: Subset data for Adidas retail stores.
- orders.csv: Subset data for order information.

### Insights and Recommendations
![average profit](https://github.com/moiez326/US-Adidas-sales/blob/main/media/Screenshot%202023-12-06%20at%2012.04.13.png)

- Women's Street Footwear and Men's Street Footwear are the highest profit categories, particularly in the West region, which leads in operating profits across most product types.
- Men's Apparel has the lowest average operating profit, suggesting it is the least profitable category, especially in the Midwest and Southeast regions.
- The Southeast region shows growth potential, with overall lower profits indicating an opportunity for targeted marketing and sales initiatives.

### Conclusion
This analysis sheds light on key strengths and growth opportunities in Adidas's U.S. sales. Strategic decisions and marketing efforts informed by these insights can significantly boost regional sales and align with consumer preferences and product category performance.
### Future Directions
- **Deep Dive into Consumer Preferences**: Further research into specific consumer preferences to inform targeted marketing and product development.
- **Predictive Modeling**: Utilization of predictive models to anticipate sales trends and explore emerging market opportunities.



