1.
```
select * from products;
select name,phone from shippers;
```
![image](https://github.com/user-attachments/assets/bc5a47be-dad0-49ae-b3cb-8c87740e7368)
![image](https://github.com/user-attachments/assets/069ca159-7789-41ef-8c3e-d8b956ef08bd)

2.
```
select avg(price) as avg_price, max(price) as max_price, min(price) as min_price from products;
```
![image](https://github.com/user-attachments/assets/352a9b03-33fd-4b29-b6ae-35c9333b1449)

3. 
```
select distinct category_id, price from products order by price desc limit 10;
```
![image](https://github.com/user-attachments/assets/4e370683-d0be-422b-82d3-987f10fda796)

4. 
```
select count(*) from products where price between 20 and 100;
```
![image](https://github.com/user-attachments/assets/7effa85b-8133-465e-aaf6-630e59b6870d)

5. `
```
select supplier_id, count(*) as product_count, avg(price) as avg_price from products group by supplier_id;
```
![image](https://github.com/user-attachments/assets/c93df2e9-a7f1-4e1d-a33c-7109bae640a8)

