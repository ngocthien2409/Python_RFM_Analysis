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
