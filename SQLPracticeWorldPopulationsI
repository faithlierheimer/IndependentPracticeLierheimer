--World Populations SQL Mini-Project I--
--Code by Faith Lierheimer--
--Data provided by Codecademy Pro Data Science Path--
--Q1: How many distinct years are covered by the data set?--
SELECT DISTINCT year
FROM population_years;
--The dataset covers 11 distinct years of population data, 2000-2011--
--Q2: What is the largest population size for Gabon in this dataset?--
SELECT max(population), year
FROM population_years
WHERE country = "Gabon";
--Result shows max population for Gabon in 2010 at 1.54 million inhabitants.--
--Q3: What were the 10 lowest population countries in 2005?--
SELECT country, population
FROM population_years
WHERE year = 2005
ORDER BY population ASC
LIMIT 10;
--The 10 lowest population countries are largely islands, with Niue coming in with the lowest population.--
--Q4: What are all the distinct countries with a population over 100 million in 2010?--
SELECT DISTINCT country, population
FROM population_years
WHERE year = 2010
AND population > 100
ORDER BY population DESC;
--There are 11 distinct countries with a population over 100 million in 2010, with China in first.--
--Q5: How many countries in this data set have the word "Islands" in their name?--
SELECT DISTINCT country
FROM population_years
WHERE country LIKE "% Islands %";
--The Falkand Islands is the only country in the data set that has the word "Islands" in the name.--
--Q6: What is the difference in population between 2000 and 2010 in Indonesia?--
SELECT population
FROM population_years
WHERE year = 2000
AND country = "Indonesia";
SELECT population
FROM population_years
WHERE year = 2010
AND country = "Indonesia";
--The population increased by 28 million people from 2000 to 2010 in Indonesia.--




