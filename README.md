```SQL


// products less than 8000
SELECT * FROM product WHERE price <= 8000;

// number of distinct states you have users
SELECT COUNT(DISTINCT state) FROM Customers;

// Number of products for a specific user
SELECT count(order_id) FROM order WHERE customer_id = '1';

// update the price of a specific product
UPDATE product SET price  = '3' WHERE product_id = '6';

// select the customer with the highest order
SELECT customer_id from order WHERE amount IN(SELECT max(amount) from order);




s



