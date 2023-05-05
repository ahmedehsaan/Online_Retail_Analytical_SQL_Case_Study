# Online_Retail_Analytical_SQL_Case_Study
Background:
Customers has purchasing transaction that we shall be monitoring to get intuition behind each customer behavior to target the customers in the most efficient and proactive way, to increase sales/revenue , improve customer retention and decrease churn.
You will be given a dataset, and you will be required to answer using SQL Analytical functions you have learnt in the course.

Q1- Using OnlineRetail dataset
• write at least 5 analytical SQL queries that tells a story about the data
• write small description about the business meaning behind each query


Q2- After exploring the data now you are required to implement a Monetary model for customers behavior for product purchasing and segment each customer based on the below groups
Champions - Loyal Customers - Potential Loyalists – Recent Customers – Promising - Customers Needing Attention - At Risk - Cant Lose Them – Hibernating – Lost
The customers will be grouped based on 3 main values

• Recency => how recent the last transaction is (Hint: choose a reference date, which is the most recent purchase in the dataset )

• Frequency => how many times the customer has bought from our store

• Monetary => how much each customer has paid for our products

As there are many groups for each of the R, F, and M features, there are also many potential permutations, this number is too much to manage in terms of marketing strategies.
For this, we would decrease the permutations by getting the average scores of the frequency and monetary (as both of them are indicative to purchase volume anyway)
![image](https://user-images.githubusercontent.com/95180897/236383883-f9fe215d-01e7-45aa-8242-c67f469d8295.png)

Label each customer based on the below values
![image](https://user-images.githubusercontent.com/95180897/236383984-5774bfd0-3367-4f87-b4ca-82ef3fcfeb9c.png)
![image](https://user-images.githubusercontent.com/95180897/236384011-b0a5440b-1a4f-4f91-abe9-6e6ce5c3d5bd.png)
![image](https://user-images.githubusercontent.com/95180897/236384042-5d0a7adb-7dfc-41c8-ae17-e38732fb9cfe.png)
