select * from customers;
select customers.first_name, customers.last_name, company_orders.date, company_orders.order_number
from customers inner join company_orders
on customers.id = company_orders.customer_id
