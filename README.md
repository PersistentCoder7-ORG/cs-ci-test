# centurySign()
Depending on the month and day you were born, you were born under one of 4 Century High School signs. Your job is to write a function that will determine what sign you were born under based on your birthday.


**requirements:**
----------
* Anyone born between August 15 and November 14 is born under the Jag Crew Sign
* Anyone born between November 15 and February 14 is born under the Canned Food Drive Sign
* Anyone born between Febuary 15 and May 14 is born under the Forecasting Sign
* Anyone born between May 15 and August 14 is born under the Jagfest Sign
* Any month that is less than 1 or greater than 12 will return a "Month Error"
  * [regardless of whether there is a day error or not]
* Any day that is less than 1 or greater than 31 will return a "Day Error"

**Inputs:**
----------
* **centurySign()** receives two values (integers): *month* & *day*
  * **month** = the month you were born (as an integer)
  * **day** = the day of that month you were born (as an integer)

**Output:**
------------
Output will be a string ('Jag Crew', 'Canned Food Drive', 'Forecasting', 'Jagfest')

**Examples:**
inputs => output/s
--------------------------------
* 11 18 => Food Drive
* 8 14 => Jagfest
* 8 15 => Jag Crew
* 5 14 => Forecasting
* 2 14 => Food Drive
* 2 15 => Forecasting
* 13 10 => Month Error
* -91 15 => Month Error
* 10 0 => Day Error
* 8 42 => Day Error
* 20 100 => Month Error
