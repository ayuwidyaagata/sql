# sql
# Revising the Select Query
Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.The CITY table is described as follows: 

<img width="290" alt="image" src="https://user-images.githubusercontent.com/60659161/186940469-7ddc4f19-bd33-4737-b9e5-dac5cce2172c.png">

```
SELECT * FROM CITY WHERE POPULATION > 100000 AND COUNTRYCODE = 'USA'; 
```
