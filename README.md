# MySql.Database



This SQL code sets up a relational database for an e-commerce system, with tables for customers, products, orders, and order items. The customers table stores basic customer information, including a unique identifier (customer_id), name, email, and the timestamp when the customer was created. The products table contains product details, such as product_id, name, description, price, and available stock. The orders table captures order transactions, linking each order to a specific customer via a foreign key (customer_id), along with the total order amount and date. The order_items table records the individual products in each order, connecting to the orders and products tables with foreign keys, and includes the quantity and unit price of each item. Sample data is inserted into each table to provide realistic test cases. Additionally, the code contains several SQL queries that demonstrate the ability to join tables, aggregate data, and perform calculations like total revenue, average order value, and order count per customer. This structure allows for efficient querying and reporting on key e-commerce metrics, while ensuring data integrity through primary and foreign key relationships.




Reflection Questions

How do primary and foreign keys help maintain data integrity?
Primary keys uniquely identify records in a table, while foreign keys establish relationships between tables. This ensures data consistency, preventing issues like orphaned records.

What insights can be gained by joining multiple tables?
By joining tables, you can extract complex data relationships, such as linking orders to customers and products, providing a comprehensive view of business operations.

How can aggregate functions summarize data?
Aggregate functions like SUM() and AVG() can summarize large datasets, helping to analyze revenue, order value, and more.

What types of analyses are enabled by date functions?
Date functions enable time-based analysis, such as filtering orders by date or calculating revenue over time.

How might you extend this database for additional e-commerce features?
I could add tables for product categories, customer reviews, inventory tracking, shipping information, or discounts.
