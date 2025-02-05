# Elist_Analysis
Sales trends analysis for electronics e-commerce company

# Company Background
Founded in 2018, Elist is an e-commerce company that sells popular electronics products and has since expanded to a global customer base. Like most e-commerce companies, Elist sells products through their online site as well as through their mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad.

### Stakeholder Questions

1. What were the overall sales trends from 2019 to 2022?
2. What were the company's yearly and monthly growth rates?
3. How has the new loyalty program performed? Should we keep using it?
4. What was the company's refund rate and average order value (AOV)?

Notes:
- Focus on sales revenue, AOV, and order counts
- Look at trends over yearly and monthly periods
- For refunds and AOV specifically compare across Apple products

# Overview
<img src="https://github.com/user-attachments/assets/8442df55-6164-4313-a358-bdd2cfea50c7" width="700" height="280"/>

From 2019 to 2022, Elist achieved total sales of $28 million across 108,000 orders, representing a 28% increase in both revenue and order volume over four years. A significant surge occurred in 2020, as the shift in consumer purchasing behavior driven by the pandemic resulted in $6 million in sales that year alone. However, in 2021-2022, key performance metrics declined, with sales decreasing by 46%, average order value by 10%, and order count by 40%. To ensure long-term growth, Elist must focus on strategies to retain the value captured during its peak sales period.

The ERD of the datasets can be found [here](https://github.com/huizliang/Elist_Analysis/blob/main/Elist_ERD.png).

# Deep-Dive Insights

## Sales Trends
<img src="https://github.com/user-attachments/assets/b9e58113-4c86-4b5d-a131-c505315466d7" width="900" height="200"/>


- **Yearly summary:** The highest annual average sales were recorded in 2020 ($847K) and 2021 ($761K), while the lowest averages occurred in 2019 ($322K) and 2022 ($413K), reflecting the impact of the pandemic on consumer purchasing behavior.
- **Growth rates:** The year 2020 experienced the highest growth rate, with sales volume and revenue more than doubling compared to 2019. Consequently, the average order value in 2020 was 31% higher than in the previous year. However, in 2021, while overall sales growth declined by 10%, the number of orders saw a 6% increase, indicating a shift in purchasing patterns.
- **Monthly summary:** The months with the highest growth rates were March 2020, November 2019, December 2020, and December 2022. This pattern highlights the impact of the shift to online shopping during the pandemic and seasonal demand spikes, emphasizing the need for strategic planning around key shopping periods.

## Product Trends

<img src="https://github.com/user-attachments/assets/4e71df45-16d5-464a-9afb-e2ddd3a360cd" width="500" height="160"/>


- **Finding:** At the end of the four-year period, the top-grossing product was the 27-inch 4K Gaming Monitor, accounting for 35% of total sales or $9.8M. Closely following, Apple AirPods contributed 28% of sales ($7.7M), while the MacBook Air represented 22% ($6.2M).
- **Recommendation:** Given the popularity of Apple products, focusing on strategies to increase sales of Apple products could provide a valuable opportunity to significantly boost company revenue. Moreover, although Apple iPhone experienced the lowest sales of all the Apple products, it had the highest AOV of all the Apple products. This points to hidden potential for iphones. Thus, developing strategies to increase iPhone sales could also potentially increase company revenue.

## Loyalty Program
![image](https://github.com/user-attachments/assets/19a9427b-14e1-4f13-a104-7586b2aa694c)
Note: 0 represents non-loyalty shoppers and 1 represents loyalty shoppers.

- **Finding:** During 2019 and 2020, loyalty program customers made fewer purchases than non-loyalty program customers, and their purchases were less expensive than non-loyalty customers. However, in more recent years (2021-2022), loyalty customers began to make more purchases than non-loyalty customers and spent about $30 more on average per order in 2022.
- **Recommendation:** Considering the fact that in recent years, loyalty customers are not only making more purchases but also more expensive purchases than non-loyalty customers, we would recommend continuing with the loyalty program. 

## Refund rates

<img src="https://github.com/user-attachments/assets/1fd03764-c500-400c-a84b-0b9a470c7cfa" width="500" height="110"/>

- **Apple Products:** 
The refund rates for Apple products were as follows: AirPods (5%), iPhone (8%), and MacBook Air (11%). Given that the MacBook Air was the third highest-grossing product with a high average order value of $1,588, it is recommended to analyze the reasons for returns and implement strategies to reduce them, thereby minimizing revenue loss and improving customer satisfaction.
- **Finding:** Refund rates were highest in 2020 at 10% and lowest in 2022 at 0%. However, this may be due to data incompleteness. A follow-up with the payments team will be needed to confirm refund rate for 2022.

