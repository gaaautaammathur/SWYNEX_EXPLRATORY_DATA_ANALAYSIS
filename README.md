Task 2: Exploratory data analysis

Statistics (252 orders): total order value ₹34.1 lakh; revenue after cancelled and returned orders ₹18.8 lakh; average order ₹12,768 against a median of about ₹3,000; average delivery time 5.4 days.


Key insights
Revenue depends on a few products. Electronics is 73.8% of revenue, and the iPhone 13 alone is 48.9%.
Almost half of the order value is lost. 23.0% of orders are cancelled and 18.7% returned, which is 44.9% of all order value.
Cancellation rates differ by payment method. Credit Card is highest (31.4%) and Net Banking lowest (14.6%), but the groups are small.
Revenue is lumpy and has anomalies. 35 outlier orders make up 72.5% of order value, and July 2026 revenue is about 3.3 times the monthly average because of one large iPhone order.
Two cities generate half of the revenue. Hyderabad and Bengaluru together are 48.9%.
Price drives order value, not discounts. Order amount follows unit price (correlation 0.90); discounts show almost no link to quantity (-0.05).
Ratings are split. 37.8% of ratings are 1 or 2 stars and 40.0% are 4 or 5.
Charts

Monthly revenue Revenue by category Top products Order amount outliers

Limitations
Only 252 orders and 45 ratings, so small differences (payment method, weekday, rating by category) can be chance.
Revenue excludes cancelled and returned orders and counts pending orders as expected sales.
A few missing dates were estimated from the median delivery time during cleaning.
Tools

Python, pandas, matplotlib, Jupyter Notebook.

Author

Gautam
