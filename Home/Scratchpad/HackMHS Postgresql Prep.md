`brew install postgresql@15`
`brew services start postgresql`
`psql postgres`
`initdb /usr/local/var/postgres`
`pg_ctl -D /usr/local/var/postgres -l logfile start`

`\du` - list users
`\list` - list dbs
`\dt` - list tables
`\d` - describe table
`\q` - quit

`createuser homeuser`
`createdb homedb`
`psql homedb`

```sql
CREATE TABLE products (product_id varchar(10) NOT NULL, product_name varchar(20) NOT NULL, expiration_date DATE NOT NULL, price numeric NOT NULL);

  

INSERT INTO products (product_id, product_name, price) VALUES ('A1234', 'Computer', 500.00);

TABLE products;

  

\d products

  

ALTER TABLE products ALTER COLUMN expiration_date DROP NOT NULL;

  

\d products

  

TABLE products;

  

INSERT INTO products (product_id, product_name, expiration_date, price) VALUES ('B456', 'Hamburger', '2023-05-23', 10.00);

  

SELECT * FROM products;

  

INSERT INTO products (product_id, product_name, expiration_date, price) VALUES ('C987', 'Salad', '2023-05-14', 10.00);

  

SELECT * FROM products WHERE expiration_date=CURRENT_DATE;

  

SELECT * FROM products WHERE PRICE<20.00;

  

DELETE FROM products WHERE product_name='Salad';
```

# uninstall
`brew services stop postgresql@15`
```bash
$ rm -rf /usr/local/var/postgres
$ rm /usr/local/var/log/postgres.log
$ rm -f ~/.psqlrc ~/.psql_history
```