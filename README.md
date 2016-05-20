```SQL


// Products with price less than 8000NGN
SELECT * FROM product WHERE price < 8000;

//Distinct states you have customer
SELECT DISTINCT state FROM customer;

// Number of products for a specific coustomer
SELECT count(order_id) FROM order WHERE customer_id = 1;

// update the price of a specific product
UPDATE product SET price  = 3 WHERE product_id = 6;

// all the customers in lagos state
SELECT * FROM customers WHERE customer_id IN (SELECT customer_id FROM customer WHERE state = 'Lagos';



