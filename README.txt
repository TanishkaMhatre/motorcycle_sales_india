MOTORCYCLE SALES ANALYSIS — MYSQL PRACTICE DATASET
Indian fictional business dataset created for SQL learning.

Tables:
products(product_id, product_line, product_name, unit_price)
warehouses(warehouse_id, warehouse_name, state)
payment_methods(payment_id, payment_method, fee_rate)
sales(sale_id, sale_date, product_id, warehouse_id, payment_id, sales_channel, quantity, discount_rate)

Revenue logic:
gross_revenue = quantity * unit_price
discount_amount = gross_revenue * discount_rate
payment_fee = (gross_revenue - discount_amount) * fee_rate
net_revenue = gross_revenue - discount_amount - payment_fee

The dataset is fictional and designed for practice. It is inspired by the structure of the DataCamp Motorcycle Parts Sales project, while using an India-focused scenario and MySQL-compatible schema.
