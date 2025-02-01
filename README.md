# Elist_Analysis
Sales trends analysis for electronics e-commerce company

# Company Background
Founded in 2018, Elist is an e-commerce company that sells popular electronics products and has since expanded to a global customer base. Like most e-commerce companies, Elist sells products through their online site as well as through their mobile app. They use a variety of marketing channels to reach customers, including Email campaigns, SEO, and affiliate links. Over the last few years, their more popular products have been products from Apple, Samsung, and ThinkPad.

# Stakeholder Questions

1. What were the overall sales trends from 2019 to 2022?
2. What were the company's yearly and monthly growth rates?
3. How has the new loyalty program performed? Should we keep using it?
4. What was the company's refund rate and average order value (AOV)?

Notes:
Focus on sales revenue, AOV, and order counts
Look at trends over yearly and monthly periods
For refunds and AOV specifically compare across Apple products

# Overview

From 2019 - 2022, Elist generated a total of $28M in sales and 108K  in orders. In the span of 4 years, overall sales and order count also increased by 28%. A significant portion of the sales derived from 2020 where the onset of the pandemic drove consumers to pivot their purchasing habits from in-person to online-ordering, resulting in $6M in sales for the company. In 2021-2022 however, figures trended downwards for sales -(46%), average order value (-10%), and order count (-40%). Finding ways to maintain the value captured from 2020-2021 would be essential for Elist to sustain long-term growth.

<img src="https://github.com/user-attachments/assets/07354f5d-1287-4be4-95b4-95d0f66d26fd" width="800" height="200"/>

The ERD of the datasets can be found [here](https://github.com/huizliang/Elist_Analysis/blob/main/Elist_ERD.png).

# Deep-Dive Insights

## Sales Trends
- **Yearly summary:** From 2019 to 2022, the yearly average sales was $7M, the yearly average number of sales was 27K, and the yearly average order value (AOV) was $245.
- **Growth rates:** 2020 had by far the highest growth rate, with more than double the number of sales and sales revenue than 2019. By reason, the average order value in 2020 sales was also 31% more expensive than the average order value in 2019. Although the number of sales increased in 2021, total sales revenue went down with the average order value being 15% less than those in 2020.

## Product Trends*

<img src="https://github.com/user-attachments/assets/4e71df45-16d5-464a-9afb-e2ddd3a360cd" width="700" height="200"/>


- **Finding:** By the end of the 4 year period, the top grossing product was the 27-inch 4K Gaming Monitor which made up 35% of all sales. Following closely, Apple AirPods made up 28% of sales, and MacBook Air accounted for 22% of total sales, generating $9.8M, $7.7M, and $6.2M respectively.
- **Recommendation:** Interestingly, although the Apple iPhone had the lowest sales of all the Apple products, it had the highest AOV of all the Apple products. This points to hidden potential for iphones. Given the popularity of other Apple products sold by the company, focusing on strategies to increase iPhone sales could provide a valuable opportunity to significantly boost company revenue.

## Loyalty Program
![image](https://github.com/user-attachments/assets/19a9427b-14e1-4f13-a104-7586b2aa694c)
Note: 0 represents non-loyalty shoppers and 1 represents loyalty shoppers.

- **Finding:** During 2019 and 2020, loyalty program customers made fewer purchases than non-loyalty program customers, and their purchases were less expensive than non-loyalty customers. However, in more recent years (2021-2022), loyalty customers began to make more purchases than non-loyalty customers and spent about $30 more on average per order in 2022.
- **Recommendation:** Considering the fact that in recent years, loyalty customers are not only making more purchases but also more expensive purchases than non-loyalty customers, we would recommend continuing with the loyalty program. 

## Refund rates

<img src="https://github.com/user-attachments/assets/1fd03764-c500-400c-a84b-0b9a470c7cfa" width="500" height="100"/>

- **Apple Products:** The refund rate for apple products are as follows: Airpods (5%), ipHone (8%), and Macbook Air Laptop (11%). Given that the Macbook Air Laptop was the 3rd highest grossing product and has a high average order value of $1588, a recommendation would be to look into the reasons for returns in order to mitigate them.
- **Finding:** Refund reates were highest in 202 at 10% and lowest in 2022 at 0%. However, this may be due to data incompleteness. A follow-up with the payments team will be needed to confirm refund rate for 2022.

