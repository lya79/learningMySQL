# `JOIN`
`JOIN`常見的使用共有 6總用法. 作用在於能將**兩張或多張資料表**關聯起來, 基於資料表的欄位.
1. INNER JOIN
2. LEFT JOIN
3. RIGHT JOIN
4. FULL JOIN
5. CROSS JOIN
6. NATURAL JOIN

## INNER JOIN
查詢結果只會返回符合條件的資料.

customers資料表
| c_id | name | 
| ---|--- | 
| 1 | AAA | 
| 2 | BBB | 
| 3 | CCC | 

orders資料表
| order_no | c_id | 
| ---|--- | 
| 134 | 3 | 
| 546 | 3 | 
| 234 | 1 | 
| 211 | 2 | 
| 222 | 1 | 
| 112 | 9 | 

查詢的命令
```shell
SELECT customers.name, orders.order_no
FROM customers
INNER JOIN orders
ON customers.C_Id=orders.C_Id;
```

查詢結果
| name | order_no | 
| ---|--- | 
| CCC | 134 | 
| CCC | 546 | 
| AAA | 234 | 
| BBB | 211 | 
| AAA | 222 | 

## LEFT JOIN

## RIGHT JOIN

## FULL JOIN

## CROSS JOIN

## NATURAL JOIN

# 參考
- [JOIN 連接 (SQL JOIN)](https://www.fooish.com/sql/join.html)
- [Mysql 连接的使用](http://www.runoob.com/mysql/mysql-join.html)

