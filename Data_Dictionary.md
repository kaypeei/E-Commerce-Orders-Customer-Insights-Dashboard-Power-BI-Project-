# Orders Table

| Column | Type | Description |
| --- | --- | --- |
| order_id | INT | Unique order identifier |
| customer_id | INT | Links to Customers table |
| order_date | DATE | Date of purchase |
| amount | DECIMAL | Order value |  

<img width="818" height="966" alt="image" src="https://github.com/user-attachments/assets/0de68a68-31df-4cc5-a76e-374e4bcc1799" />


# Customers Table

| Column | Type | Description |
| --- | --- | --- |
| customer_id | INT | Unique customer |
| name | VARCHAR | Customer full name |
| region | VARCHAR | North, South, East, West |
| signup_date | DATE | Date customer joined |v  

<img width="1159" height="524" alt="image" src="https://github.com/user-attachments/assets/a4372ad9-81b9-42fe-b85c-33cd5371ece8" />
