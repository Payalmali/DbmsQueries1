# DbmsQueries1
Q1-Check status of your orders.
ans- To check status of orders--
# select status from orders;
-------------------------------
Q2-Find total amount of your orders.
ans- To find the total amount of orders--
# SELECT SUM(total) AS total FROM orders;
---------------------------------
Q3- Update your city.
ans- To update city--
# UPDATE Address SET city = 'Gwalior' WHERE state = 'Maharashtra';
---------------------------------
Q4- Change product Description.
ans- To change description of product--
# UPDATE products SET p_desc = 'New version' WHERE p_id = 'p1';
---------------------------------
Q5- Display returnable products.
ans- To display returnable products--
# select p_name from products where p_returnable = 'yes';
------------------------------------------------------------
Q6- Generate er diagram ?
Ans. ER Diagram is attached with the repo
