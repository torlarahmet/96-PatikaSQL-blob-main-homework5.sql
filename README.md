# 96-PatikaSQL-blob-main-homework5.sql
--1.soru

SELECT * FROM film
WHERE title LIKE '%n'
ORDER BY length DESC
LIMIT 5;

--2.soru

SELECT * FROM film
WHERE title LIKE '%n'
ORDER BY length 
OFFSET 5
LIMIT 5;

--3.soru

SELECT * FROM customer
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4;
