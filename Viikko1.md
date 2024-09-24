# Viikko 1

### Tehtävä 1
SELECT * FROM taulu WHERE kentta = 'arvo'

![kuvakaappaus](viikko1.1.png)


# Viikko 2

### Tehtävä 1
SELECT id, name, description, icon, target, target_minvalue, target_maxvalue, target_text FROM goal;

![kuvakaappaus](Viikko2Teht1.png)

### Tehtävä 2
 SELECT name, type FROM airport WHERE iso_country = 'FI';

![kuvakaappaus](Viikko2Teht2.png)

### Tehtävä 3
SELECT name FROM airport WHERE iso_country = 'FI' ORDER BY name ASC;

![kuvakaappaus](Viikko2Teht3.png)


### Tehtävä 4
SELECT name, type FROM airport WHERE iso_country = 'FI' ORDER BY type, name;

![kuvakaappaus](Viikko2Teht)


### Tehtävä 5
SELECT name FROM country WHERE name LIKE 'f%';


![kuvakaappaus](Viikko2Teht5.png)


### Tehtävä 6
SELECT name FROM country WHERE name LIKE '%f%';


![kuvakaappaus](Viikko2Teht6.png)


### Tehtävä 7
SELECT location FROM game WHERE screen_name = 'Vesa';

![kuvakaappaus](Viikko2Teht7.png)

### Tehtävä 8
SELECT co2_consumed FROM game WHERE screen_name = 'Ilkka';

![kuvakaappaus](Viikko2Teht8.png)


### Tehtävä 9
SELECT co2_budget FROM game LIMIT 1;

![kuvakaappaus](Viikko2Teht9.png)



