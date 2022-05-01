# SQL
CREATE TABLE clothing_store (id INTEGER PRIMARY KEY, clothes TEXT, price INTEGER, size TEXT, color TEXT);

INSERT INTO clothing_store VALUES (1,"T-shirt", 5, "L", "black");
INSERT INTO clothing_store VALUES (2, "Button-up", 10, "XL", "red");
INSERT INTO clothing_store VALUES (3, "shorts", 15, "L", "blue");
INSERT INTO clothing_store VALUES (4, "jeans", 20, "XL", "blue");
INSERT INTO clothing_store VALUES (5, "sweatpants", 20, "XL", "green");
INSERT INTO clothing_store VALUES (6,"jackets",30, "XL", "red");
INSERT INTO clothing_store VALUES (7,"jackets",30, "XL", "red");
INSERT INTO clothing_store VALUES (8,"long sleeve",20, "L", "yellow");
INSERT INTO clothing_store VALUES (9,"cut-off",10, "M", "grey");
INSERT INTO clothing_store VALUES (10,"underwear",5, "L", "pink");
INSERT INTO clothing_store VALUES (11,"graphic",15, "S", "purple");
INSERT INTO clothing_store VALUES (12,"socks",6, "L", "white");
INSERT INTO clothing_store VALUES (13,"undershirt",8, "L", "white");
INSERT INTO clothing_store VALUES (14,"sweaters",23, "XXL", "navy");
INSERT INTO clothing_store VALUES (15,"swimwear",35, "M", "black");

SELECT * FROM clothing_store;
SELECT * FROM clothing_store ORDER BY price;
SELECT SUM(price) FROM clothing_store;
