- π Hi, Iβm @irshadzaidi
- π Iβm interested in ...
- π± Iβm currently learning ...
- ποΈ Iβm looking to collaborate on ...
- π« How to reach me ...

<!---
irshadzaidi/irshadzaidi is a β¨ special β¨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

INSERT INTO customers (customer_id, first_name, last_name, birth_date, address, city, state, points)  
VALUES ('786', βLeeβ, βRichardβ, β1998-10-10β, β3820-cavalry-ground', 'Bredford', 'BERKS', '200'),
       ('787', βAleβ, βDesmondβ, β1992-01-18β, β8-canterbury', 'Burnham', 'Bucks', '100'),
       ('825', βvivianβ, βGoldβ, β1990-12-10β, β10-liester-road', 'Cippenham', 'BECONFIELD', '202'),
       ('989', βBondβ, βJasonβ, β2000-11-19β, β2-Gloster-ave', 'Langely', 'Coln', '303'),
       ('222', βAkhiβ, βBenβ, β1987-02-09β, β115-manchester-road', 'Manchester', 'ML', '200');
       
INSERT INTO orders (order_id, customer_id, order_date, status, shipper_date)  
VALUES (last_insert_id (), 301, β2020-10-10β, 5, β2020-11-12β),
       (last_insert_id (), 320, β2020-08-13β, 4, β2020-08-17β),
       (last_insert_id (), 310, β2020-07-21β, 3, β2020-07-25β),
       (last_insert_id (), 410, β2020-11-30β, 1, β2020-12-05β);
       
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
