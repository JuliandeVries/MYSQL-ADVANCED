# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT raceId AS race, circuitId AS circuit FROM races WHERE year > 2017
2. Copy paste je gemaakte SQL query hieronder
   SELECT name, surname, points FROM races, drivers, driver_standing WHERE year = 2017 AND points = 10
   SELECT 
3. Copy paste je gemaakte SQL query hieronder
   SELECT forename, surname FROM drivers, pitstops WHERE duration < 25
   SELECT
4. Copy paste je gemaakte SQL query hieronder
   SELECT name, name FROM constructors, races WHERE year = 2010 AND constructorref = 'mclaren'
   SELECT
5. Copy paste je gemaakte SQL query hieronder
   SELECT name, country, name FROM circuits, races WHERE year = 2010 AND surname LIKE 'f%'
   SELECT