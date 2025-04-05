/*Using the data in W3School SQL Tutorial, write SQL queries to answer the following.
1.	Find the number of items in each order?
2.	Determine the value of each Customer Order?
3.	Find out the number of boxes in each Customer Order?
*/
/*
Answer Sketch.
The [OrderDetails Table] contains the ‘ProductIDs’ in the respective Orders. The [OrderDetails Table] does not have the prices. 
The prices are in the [Products Table], as well as the Unit detail of the product. The ProductID is the primary key in the [Products Table], and the foreign key in the [OrderDetails Table]. 

I will try using JOIN, SUBQUERY and/or CTE to get an accurate answer.

Step 1
Determine the quantity of each product in each order. A sum of these products with tell the number of items in each order. 

Step 2
By using an inner join to build a relationship between the [OrderDetails Table] and the [Products Table] using the ProductID, I can calculate the total price value of the product (Price* Quantity) in an order. 

Step 3
The Units give the details of all the products. The orders with boxes, could be determined using SUBSTRING
*/
