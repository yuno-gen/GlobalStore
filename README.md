# GlobalStore 🛒
This data set has two tables in it:

#1. Global Superstore Login Table

  This table is designed to track user login activities, providing insights into customer engagement, frequency of visits, and potentially identifying peak usage times. Key fields in this table might include:
  - UserID: A unique identifier for each user.
  - Username: The user's chosen name or identifier for logging in.
  - LogInDate: The date and time when the user logged into the platform.


#2. Purchase Log Table.

  This table records details about customer purchases, which is crucial for understanding sales trends, customer preferences, and inventory management. Important fields might include:

  - PurchaseID: A unique identifier for each purchase transaction.
  - UserID: A unique identifier for the user making the purchase. This field links back to the Global Superstore Login Table.
  - ProductID: A unique identifier for each product.
  - ProductName: The name of the product purchased.
  - Category: The category to which the product belongs (e.g., Electronics, Clothing, Furniture).
  - Quantity: The number of units of the product purchased.
  - Cost: The total cost of the purchase for that product.
  - PurchaseDate: The date and time when the purchase was made.
  - PaymentMethod: The method of payment used (e.g., credit card, PayPal, bank transfer).
  - ShippingAddress: The address to which the product was shipped.
  - DeliveryDate: The date the product was delivered to the customer.


> [!NOTE]
> - The ipynb file has the EDA of the GlobalStore dataset which shows if the dataset has null values or not(no null values in the dataset) with correlations between all the parameters of the dataset being highest for Sales and profit.
> - There is also the market basket analysis of the GlobalStore dataset showing the sub-categories that are frequently purchased together.
> - The analysis of Login_data shows the most loyal customers and also the days on which GlobalStore had the highest traffic.

Following is the storytelling of the GlobalStore dataset using Tableau:

This shows the sales over the years of GlobalStore from 2011-2014:
![image](https://github.com/yuno-gen/GlobalStore/assets/81225964/ca4b7bd5-590e-4859-a265-e58a28b84947)


This bar chart shows the sales of each segment per region of the GlobalStore:
![image](https://github.com/yuno-gen/GlobalStore/assets/81225964/6289b7db-ca3d-4515-a63c-7c0ef1835be3)

This visualization shows the performance of each sub-category in terms of sales of the store as of whole:
![image](https://github.com/yuno-gen/GlobalStore/assets/81225964/585ca081-c97e-4357-9654-2bd0d9418df9)

This horizontal bar chart shows the comparison of shipping cost to the profit as per countries the GlobalStore is active in:
![image](https://github.com/yuno-gen/GlobalStore/assets/81225964/e14bf8ff-3325-41cf-a9ee-e686e30bf496)

