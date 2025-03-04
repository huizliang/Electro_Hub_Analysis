# Electro Hub Analysis

<div align="center"> <img src="https://github.com/user-attachments/assets/a95d2548-e441-4df0-b588-39cc441667ec"/> </div>

# Background of Electro Hub

Established in 2018, Electro Hub is an e-commerce company that sells popular electronics products and that has since expanded to a global customer base. Similar to many e-commerce companies, Electro Hub  sells products through their online site as well as through their mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad. The purpose of this analysis is to examine the company's sales data from 2019 to 2022 in order to capture trends and revealations that may be used to grow Electro Hub's success.

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

<div align="center"> <img src="https://github.com/user-attachments/assets/d077f5e9-11ed-4711-a3e3-caca2eb31173"/> </div>

From 2019 to 2022, Electro Hub achieved a total of $28 million in sales across 108,000 orders, demonstrating a 28% increase in both revenue and order volume over the course of four years. A significant time period for sales was 2020, in which the COVID-19 global pandemic caused consumers to shift from in-person to online shopping, resulting in $6 million in sales for that year alone. However, in 2021-2022, key performance metrics trended downwards, with sales decreasing by 46%, average order value by 10%, and order count by 40%. To ensure long-term growth, Electro Hub must focus on strategies to retain the value captured during its peak sales period.

The ERD of the datasets can be found [here](https://github.com/huizliang/Elist_Analysis/blob/main/Elist_ERD.png).

# Deep-Dive Insights

## Sales Trends
<div align="center"> <img src="https://github.com/user-attachments/assets/2ba5988f-2b38-48b7-827d-a72e7214e3a4"/> </div>


<div align="center"> <img src="https://github.com/user-attachments/assets/d957ddc1-6d0a-4303-8425-31c4e8029fe7"/> </div>

- **Growth rates:** The year 2020 experienced the highest growth rate (163%), with average order value being 31% more expensive than those in 2019 and order count more than doubling from 2019. Interestinly however, while  sales total declined the following year in 2021 by 10%, the number of orders still increased by 6%, indicating a shift in purchase behavior- that is while customers were shopping more frequently, they were also spending less or buying less expensive items per order.
- **Monthly summary:** The months with the highest growth rates were March 2020, November 2019, December 2020, and December 2022. This pattern highlights the impact of the shift to online shopping during the pandemic and seasonal demand spikes, emphasizing the need for strategic planning around key shopping periods.

## Product Trends
<div align="center"> <img src="https://github.com/user-attachments/assets/bec17fa8-f4c3-4d24-9a56-b350215d47c1"/> </div>

- **Finding:** At the end of the four-year period, the top-grossing product was the 27-inch 4K Gaming Monitor, accounting for 35% of total sales ($9.8M). Following closely, Apple AirPods contributed 28% of sales ($7.7M), and MacBook Air laptops contributed 22% ($6.2M).
- **Recommendation:** Since there seems to be a huge demand for gaming monitors, the company should leverage its current success by dedicating resources to market this product category. Or perhaps, special offers can be offered to customers who purchase this product as a way to encourage them to add additional products. Second, given that Apple products generated 51% of total sales, strategies should also be developed to increase sales of products in this brand as it could provide a valuable opportunity to significantly boost company revenue. For example, data points to a hidden potential for Apple iPhone as they are the most expensive product in the Apple line but are generatin the least amount of sales within the brand. Thus, developing strategies to specifically increase iPhone sales would help increase company revenue as well.

## Loyalty Program
<div align="center"> <img src="https://github.com/user-attachments/assets/834f4d28-36e3-45d6-8d30-f9d38839517a"/> </div>

- **Finding:** Between 2019 and 2020, non-loyalty customers outperformed loyalty customers across all key metrics, including sales, average order value (AOV), and order count. However, in the subsequent years of 2021-2022, loyalty customers began to surpass non-loyalty customers in these areas. Sales for loyalty customers were $480K higher, average order values were $30 higher, and order count exceeded non-loyalty orders by 649, all of which indicate a favorable outcome for the loyalty program.
- **Recommendation:** Considering the fact that in recent years, loyalty customers are not only making more purchases but also more expensive purchases than non-loyalty customers, we would recommend continuing with the loyalty program. 

## Refund rates

<div align="center"> <img src="https://github.com/user-attachments/assets/cfdc34bf-1aab-4cd8-8371-96ea78fcc986"/> </div>

- **Findings:** The product with the highest refund rate was Thinkpad Laptops which has an average order value of $1,100. Given its high cost, reasons for returns should be examined in order to implement strategies to reduce loss. 
- **Apple Products:** The refund rates for Apple products were as follows: AirPods (5%), iPhone (8%), and MacBook Air (11%). 
- **Recommendation:** Similar to Thinkpad Laptops, reasons for returns should be looked into all products but especially for tbe MacBook Air as it also has a high average order value ($1,588). If reasons for returns can be mitigated, then revenue loss will be minimized and customer satisfaction will be increased overall. Lastly, it was also noted that refund rates were highest in 2020 at 10% and lowest in 2022 at 0%. However, this may be due to data incompleteness. A follow-up with the payments team will be needed to confirm refund rate for 2022.


## Marketing Channels


<div align="center"> <img src="https://github.com/user-attachments/assets/38097a8e-8eb2-44a5-9d0c-41890f9e115c"/> </div>
 
- **Recommendation:** Based on the analysis of current sales trends, it is evident that the majority of sales are driven by direct traffic. To optimize marketing strategies and allocate resources more effectively, it would be beneficial to gather insights into how customers are discovering the company’s website. This data could enable more targeted marketing efforts, potentially boosting overall revenue.

-  Additionally, email marketing is experiencing growth and presents an opportunity for further development. Identifying strategies to enhance this channel could lead to more significant returns.

- On the other hand, both social media and affiliate marketing have shown stagnant performance. To improve outcomes, it would be prudent to concentrate efforts on enhancing the effectiveness of these channels, ensuring they contribute more substantially to revenue generation.
