# SQL
SQL portfolio
CREATE TABLE sanams_F1store (id INTEGER PRIMARY KEY, TSHIRT TEXT, inventory INTEGER, cost INTEGER, popularity INTEGER);
INSERT INTO sanams_F1store VALUES (1, "MCLAREN",3, 35, 4);
INSERT into sanams_F1store VALUES (2, "REDBULL",4, 35, 5);
INSERT into sanams_F1store VALUES (3, "MERCEDES",3, 40, 5);
INSERT INTO sanams_F1store VALUES (4, "ALPINE",3, 25,2);
INSERT INTO sanams_F1store VALUES (5, "ASTON MARTIN", 2, 25,1);
INSERT INTO sanams_F1store VALUES (6, "FERRARI", 5 , 40, 5);
INSERT INTO sanams_F1store VALUES (7, "ALFA ROMEO", 4, 30, 1);
INSERT INTO sanams_F1store VALUES (8, "HAAS F1", 4, 30, 1);
INSERT INTO sanams_F1store VALUES (9, "AlphaTauri", 5, 30, 1); 
INSERT INTO sanams_F1store VALUES (10, "WILLIAMS", 5, 30, 2);


SELECT SUM(inventory) from  sanams_F1store;
SELECT * FROM sanams_F1store;

--display the database ordered by price. 
SELECT * FROM sanams_F1store
ORDER BY popularity desc

