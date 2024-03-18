# Python_RFM_Analysis

## 1. Introduction:

* SuperStore Company is a global retail company. On Christmas and New Year, the Marketing Department wants to run marketing campaigns to thank customers who have supported the company over the past time as well as exploit customers who have the potential to become loyal customers.
* However, the Marketing Department has not yet been able to group each customer this year because the data set is too large to be processed manually like in previous years, so they asked the Data Analysis Department to assist in implementing a classification problem. Segment each customer to deploy each marketing program suitable for each customer group.
* The Marketing Director also suggested using the RFM model, but in the past, when the company was small, the team could calculate and classify it themselves using Excel. Currently, the amount of data is too large, so they want the Data Department to build a flow to deploy Segmentation evaluation through Python programming.

## 2. Import the dataset:

The dataset we used here was an Exel file that included 2 sheets. Sheet 1 was Ecommerce retail which had all the information we need about customers and sheet 2 was the Segmentation which contained the RFM score for each segment of customers.

Sheet 1

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/cb753eb5-9db5-4bc9-a093-bfa2b9c9df7b)

Sheet 2

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/b24f9e77-88f7-4fd3-abb2-80a68d73473b)

## 3. What is RFM model?

RFM, also known as RFM analysis, is a type of customer segmentation and behavioral targeting used to help businesses rank and segment customers based on the recency, frequency, and monetary value of a transaction. RFM marketing can help marketers and small business owners determine their target audience to use their budget most effectively.

This method gives customers scores based on 3 factors:

* Recency: Recency refers to how recent a customer's last purchase was. Customers who have made a recent purchase, typically within the last few weeks, still have the product and brand on their minds and are most likely to make a repeat purchase. You can measure recency however you deem necessary for your business. However, it's important to note that some companies might not have customers ordering every few days, weeks, or even months. For example, a car company might sell a single car to an individual within ten years.
* Frequency: Frequency is how often the customer makes purchases, which can help you identify repeat customers. For example, many clients make frequent repeat purchases within a set timeframe. Frequency is essential in determining the individuals most likely to continue shopping with your brand after their first initial purchase.
* Monetary value: Monetary value refers to how much a customer spends within a given period. It's always important to consider because it can tell you a few things about consumer behavior. For example, you might find that customers with the highest monetary value don't purchase items as frequently as others but typically buy the most expensive products when they do.
 
The values of each factor allow businesses to provide objective analysis and determine which audience to target for the most effective advertising and marketing campaigns. Most companies use a scale between 1 to 5, but you can use any values you think are necessary and helpful in evaluating clients.

## 4. Data Visualization:

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/caa45393-ecf2-4033-8c7a-972ef5d828da)

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/7bfbff57-482f-4e8d-be4d-16550e0813d5)

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/ffb6420d-1dd6-487b-a3a9-91371eccc389)

![image](https://github.com/ngocthien2409/Python_RFM_Analysis/assets/155359458/43f86844-4ac8-4160-83f8-9bfb81f91a18)

## 5. Insights & Recommendations:

* This company's Recency index is excellent; the most allocated index is below 50, not too high, indicating that customers return to purchase the company's goods.

* It is also encouraging to see that the Frequency index is most widely distributed at less than 100, indicating customers purchase things frequently.

* Given that the company's Monetary index is not excessively high, it might be required to encourage consumption to encourage customers to make larger or more expensive purchases in a single transaction.

* According to the Treemap graphic, the company is doing well because the Champions customer group has the largest share. All three client groups require the highest level of care, and all account for a high proportion — the Loyal customer group at 9.52%, the Potential Loyalist group at 11.73%, and the Champions customer group at 18.34%. The company needs to focus its maximum resources on taking care of these customer groups because these are the groups that bring the largest source of revenue for the company.

* The Champions group is the highest customer group, buys frequently and spends the most money so the company needs to provide special privileges for this group, giving them the right to be the first to use upcoming products. They help promote the company's brand to others very well.

* The Loyal group is a group of customers who buy frequently and spend large amounts of money. The company should also provide membership programs and suggest they buy higher-priced products to turn them into Champions.

* The Potential Loyalist group is a group of customers who buy regularly, but the amount of money they spend is not too large or they only spend a lot occasionally. The company should provide membership programs, customer loyalty programs, how to attract their attention to the company and suggest other products related to the products they have purchased to try to turn them into Loyal group.

* There is also a big problem that the two groups of customers that need the most attention to make them stay with the company are Hibernating and Lost customers which also account for a very high rate, Hibernating accounts for the same rate as Champions and Lost accounts for 9.95%. %. For these two groups, it is necessary to apply strong discount programs to attract their attention to the company.

* The 6 customer groups in the middle of the rankings account for an equal proportion and also need a lot of attention to pull these groups to higher customer rankings. Solutions can be sending emails or personalized messages to connect, offering promotions, limited-time purchases, and products related to the products they have purchased in the past...
