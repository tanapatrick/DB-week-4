/* Question 1 */

SELECT 
    paymentDate, SUM(amount) AS amount
FROM
    payments
GROUP BY paymentDate
ORDER BY paymentDate DESC
LIMIT 5;


/* Question 2 */

SELECT 
    customerName,country, avg(creditLimit) as credit
FROM
    customers
GROUP BY 
    customerName, country;


/* Question 3 */

SELECT 
    productCode, quantityOrdered, SUM(priceEach)
FROM
    orderdetails
GROUP BY productCode , quantityOrdered;


/* Question 4 */

SELECT 
    checkNumber, MAX(amount)
FROM
    payments
GROUP BY checkNumber;
