# Switch statements

## 1. World Cup Winners
Here is data in [JSON format (JavaScript Object Notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)), giving the winners of the FIFA World Cup since 1934.

```json
 { "Brazil": [1958, 1962, 1970, 1994, 2002]
 , "Germany":	[1954, 1974, 1990, 2014]
 , "Italy": [1934, 1938, 1982, 2006]
 , "Argentina": [1978, 1986]
 , "France": [1998, 2018]
 , "Uruguay": [1930, 1950]
 , "Spain": [2010]
 , "England": [1966]
 }
 ```

Create a variable called `winner`.
Create a variable called year, and give it a value between 1934 and 2018.

Write a switch statement that will set the value of `winner` to the name of the country that won the Cup in any given year. If the World Cup was not held in the given year, set `winner` to "No competition was held in XXXX", where "XXXX" is the given year.

## 2. Days in each month

Create a variable called `month`, and give it a value such as "January" or "September"
Create a variable called `numberOfDays`

Create a switch statement that sets `numberOfDays` to the number of days in the month.

Example: if `month` is "July", the switch statement should set `numberOfDays` to 31.
