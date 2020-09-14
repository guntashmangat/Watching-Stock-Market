# Watching-Stock-Market

CREATE TABLE stocks (
	symbol TEXT,
	name TEXT,
	date_time DATETIME,
	price REAL);
	
INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:08 10:00:00', 379.25);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:08 14:00:00', 357.34);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:08 18:00:00', 346.93);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:09 10:00:00', 352.29);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:09 14:00:00', 356.09);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:09 18:00:00', 354.25);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:10 10:00:00', 370.05);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:10 14:00:00', 383.52);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:10 18:00:00', 383.38);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:11 10:00:00', 385.65);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:11 14:00:00', 381.20);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:11 18:00:00', 363.10);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:12 10:00:00', 373.19);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:12 14:00:00', 3373.71);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:12 18:00:00', 374.42);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:13 10:00:00', 373.00);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:13 14:00:00', 373.31);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:13 18:00:00', 373.74);

DELETE FROM stocks
WHERE price = 352.29;

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:09 10:00:00', 352.29);

INSERT INTO stocks
VALUES ('TSLA', 'Tesla Inc', '2020:09:13 18:00:00', 373.74);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:08 10:00:00', 62.38);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:08 13:00:00', 62.30);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:08 16:00:00', 63.34);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:09 10:00:00', 63.06);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:09 13:00:00', 63.66);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:09 16:00:00', 63.62);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:10 10:00:00', 63.86);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:10 13:00:00', 64.15);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:10 16:00:00', 63.84);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:11 10:00:00', 63.57);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:11 13:00:00', 63.56);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:11 16:00:00', 64.39);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:12 10:00:00', 64.25);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:12 13:00:00', 64.31);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:12 16:00:00', 64.50);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:13 10:00:00', 64.35);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:13 13:00:00', 64.48);

INSERT INTO stocks
VALUES ('BMW', 'Bayerische Motoren Werke AG', '2020:09:13 16:00:00', 64.48);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:08 10:00:00', 6.73);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:08 14:00:00', 6.78);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:08 18:00:00', 7.05);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:09 10:00:00', 6.93);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:09 14:00:00', 6.99);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:09 18:00:00', 6.93);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:10 10:00:00', 6.81);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:10 14:00:00', 6.89);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:10 18:00:00', 6.88);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:11 10:00:00', 6.84);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:11 14:00:00', 6.81);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:11 18:00:00', 6.78);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:12 10:00:00', 6.90);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:12 14:00:00', 6.89);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:12 18:00:00', 6.90);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:13 10:00:00', 6.89);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:13 14:00:00', 6.91);

INSERT INTO stocks
VALUES ('F', 'Ford Motor Company', '2020:09:13 18:00:00', 6.92);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:08 15:00:00', 189.83);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:08 17:30:00', 189.02);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:08 20:00:00', 186.74);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:09 15:00:00', 189.77);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:09 17:30:00', 189.94);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:09 20:00:00', 190.56);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:10 15:00:00', 190.01);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:10 17:30:00', 189.00);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:10 20:00:00', 187.96);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:11 15:00:00', 190.11);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:11 17:30:00', 191.52);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:11 20:00:00', 191.75);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:12 15:00:00', 191.81);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:12 17:30:00', 191.72);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:12 20:00:00', 191.94);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:13 15:00:00', 191.79);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:13 17:30:00', 191.66);

INSERT INTO stocks
VALUES ('RACE', 'Ferrari NV', '2020:09:13 20:00:00', 191.00);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:08 10:00:00', 148.13);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:08 13:00:00', 148.15);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:08 16:00:00', 152.23);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:09 10:00:00', 149.27);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:09 13:00:00', 150.25);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:09 16:00:00', 150.59);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:10 10:00:00', 151.92);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:10 13:00:00', 151.85);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:10 16:00:00', 151.00);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:11 10:00:00', 149.87);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:11 13:00:00', 149.30);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:11 16:00:00', 150.33);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:12 10:00:00', 150.25);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:12 13:00:00', 150.03);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:12 16:00:00', 150.54);

DELETE FROM stocks
WHERE price = 150.03 AND symbol = 'VOW3';

DELETE FROM stocks
WHERE price = 150.54 AND symbol = 'VOW3';

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:12 13:00:00', 150.32);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:12 16:00:00', 150.31);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:13 10:00:00', 150.33);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:13 13:00:00', 150.03);

INSERT INTO stocks
VALUES ('VOW3', 'Volkswagen Group', '2020:09:13 16:00:00', 150.54);

SELECT DISTINCT name FROM stocks;

SELECT * FROM stocks
WHERE name = 'Tesla Inc'
ORDER BY date_time;

SELECT AVG(price) FROM stocks
WHERE symbol = 'RACE';

SELECT name, ROUND(AVG(price), 2) AS 'average price' FROM stocks
GROUP BY name /* calculates average price for each company over whole time period */
ORDER BY price DESC; 

SELECT symbol, ROUND((MAX(price)-MIN(price)), 2) AS 'difference' FROM stocks
GROUP BY symbol;

SELECT name, MAX(price), MIN(price) FROM stocks
GROUP BY name;

SELECT name, date_time, price FROM stocks
WHERE price = 3373.71;

INSERT INTO stocks 
VALUES ('TSLA', 'Tesla Inc', '2020:09:12 14:00:00', 373.71);

DELETE FROM stocks
WHERE price = 3373.71;

SELECT name, ROUND(AVG(price), 2) AS 'average price' FROM stocks
WHERE symbol = 'TSLA' AND date_time = '2020:09:08 10:00:00';

SELECT name, SUBSTR(date_time, 1, 10) AS 'date', ROUND(AVG(price), 2) AS 'average price' FROM stocks
WHERE SUBSTR(date_time, 1, 10) = '2020:09:08'
GROUP BY name;

SELECT REPLACE(date_time, '2020:09:08', '2020-09-08') FROM stocks;

UPDATE stocks
SET date_time = REPLACE(SUBSTR(date_time, 1, 10), ':', '-');

SELECT name, 
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-08' THEN price END), 2) as 'avg price 2020-09-08',
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-09' THEN price END), 2) as 'avg price 2020-09-09',
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-10' THEN price END), 2) as 'avg price 2020-09-10',
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-11' THEN price END), 2) as 'avg price 2020-09-11',
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-12' THEN price END), 2) as 'avg price 2020-09-12',
	ROUND(AVG(CASE WHEN DATE(date_time) = '2020-09-13' THEN price END), 2) as 'avg price 2020-09-13'
FROM stocks
GROUP BY name;
