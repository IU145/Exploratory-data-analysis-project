# Exploratory-data-analysis-project
Analysed transaction and customer data to identify metrics driving total sales to gain insights into sales performance.

Two datastes are used in this project :

1. Transaction datatset - a year worth's of transaction data of chips which contains the following columns : a) Date b) Store number c) Loyalty card number d) Product number e) Product name f) Product quantity g) Total sales h) Transaction id
2. Purchase dataset - customer dataset for a region which contains the following columns : a) Loyalty card number b) Lifestage (young singles/couple, midage single/couples, old singles/couples, old families, new families, young families, retirees) c) Premium customer (budget, premium, mainstream)

I start with the transction data, cleaning and examining the data, checking for any missing and null value or any incorrect formats and outliers. After cleaning the data, i move on to find out the different brands and pack sizes that are being offered. I try to use a line chart to explore the sales performance in the last year, which shows that most sales happened around christmas.

I then move on to examine the purchase datset, and merge it with the transaction dataset by using the loyalty card number which was unique to each customer.

To find out what affects total sales, i first had a look at which customer segment contibutes the most towards sales. According to the analysis, budget older families and mainstream young singles/ couples are contributing the most to sales. Total sales could be affected by number of customers, so i took a look at number of customrs by customers segment. The analysis showed that mainstream young singles/couples have the most number of customers which is why they contribute towards a higher sales value. Wherease, for budget older families, the number of customers are low.

Since number of customers is not a prime reason for high sales for budget older families, I investigate the avergae chips purchased per customer as it could also drive total sales. The bar chart showed that older families across all customer segments do indeed purchase higher number of avergae chips. The same goes for young families.

Lastly, I take a look at avergae price spent per customer by different customer segemnts, which showed that mainstream midage and young singles and couples are paying more per packet of chips compared to their budget and premium counterparts.
