- 👋 Hi, I’m @irshadzaidi
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
irshadzaidi/irshadzaidi is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

INSERT INTO customers (customer_id, first_name, last_name, birth_date, address, city, state, points)  
VALUES ('786', ‘Lee’, ‘Richard’, ‘1998-10-10’, ‘3820-cavalry-ground', 'Bredford', 'BERKS', '200'),
       ('787', ‘Ale’, ‘Desmond’, ‘1992-01-18’, ‘8-canterbury', 'Burnham', 'Bucks', '100'),
       ('825', ‘vivian’, ‘Gold’, ‘1990-12-10’, ‘10-liester-road', 'Cippenham', 'BECONFIELD', '202'),
       ('989', ‘Bond’, ‘Jason’, ‘2000-11-19’, ‘2-Gloster-ave', 'Langely', 'Coln', '303'),
       ('222', ‘Akhi’, ‘Ben’, ‘1987-02-09’, ‘115-manchester-road', 'Manchester', 'ML', '200');
       
INSERT INTO orders (order_id, customer_id, order_date, status, shipper_date)  
VALUES (last_insert_id (), 301, ‘2020-10-10’, 5, ‘2020-11-12’),
       (last_insert_id (), 320, ‘2020-08-13’, 4, ‘2020-08-17’),
       (last_insert_id (), 310, ‘2020-07-21’, 3, ‘2020-07-25’),
       (last_insert_id (), 410, ‘2020-11-30’, 1, ‘2020-12-05’);
       
INSERT INTO order_items (order_id, product_id, quantity, unit_price)  
VALUES (last_insert_id (), 3, 28, 5.50),
       (last_insert_id (), 5, 50, 14.00),
       (last_insert_id (), 10, 100, 7.50),
       (last_insert_id (), 13, 05, 10.90);
       
INSERT INTO products (name, quantity_in_stock, unit_price)  
VALUES ('product1', 13, 1.99),
       ('product21', 50, 4.99),
       ('product33', 09, 11.90),
       ('product49', 30, 3.99),
       ('product55', 16, 2.49);
