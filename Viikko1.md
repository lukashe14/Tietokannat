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

![kuvakaappaus](Viikko2Teht4.png)


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


# Viikko 2
## WHERE-osan liitosehto harjoituset

### Tehtävä 1
SELECT iso_country AS "country name", name AS "airport name" FROM airport WHERE iso_country = 'IS';


![kuvakaappaus](Viikko2Teht2.1.png)


### Tehtävä 2
SELECT name AS "airport name" FROM airport WHERE iso_country = 'FR' AND type = "large_airport";


![kuvakaappaus](Viikko2Teht2.2.png)


### Tehtävä 3
SELECT country.name AS "country_name", airport.name AS "airport_name" FROM airport, country
    -> WHERE country.continent like 'AN' AND airport.iso_country like country.iso_country;


![kuvakaappaus](Viikko2Teht2.3.png)



### Tehtävä 4



![kuvakaappaus](Viikko2Teht2.4.png)


### Tehtävä 5


![kuvakaappaus](Viikko2Teht2.5.png)


### Tehtävä 6


![kuvakaappaus](Viikko2Teht2.6.png)


### Tehtävä 7



![kuvakaappaus](Viikko2Teht2.7.png)


### Tehtävä 8



![kuvakaappaus](Viikko2Teht2.8.png)


### Tehtävä 9


![kuvakaappaus](Viikko2Teht2.9.png)


### Tehtävä 10
select country.name
     from country, goal, goal_reached, airport, game
    where game.screen_name = "Ilkka" AND goal.name = 'CLOUDS' AND game.id = goal_reached.game_id and goal_reached.goal_id = goal.id and game.location = airport.ident AND airport.iso_country = country.iso_country

![kuvakaappaus](Viikko2Teht2.10.png)



# Viikko 3


### Tehtävä 1














