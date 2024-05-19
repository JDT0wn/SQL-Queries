# 

<h1>SQL-Queries</h1>


<h2>Description</h2>
In this lab I show how I created a SQL Query to filter the login attempts table for failed login attempts that occured after hours.   

1. In the 1st query I used the [*] to return all data from the table so that i could make a decision on the easiest way to sort my information. 

2. Afterwards I decide to sort the information by login date so that I have a clearer picture of the activity on a certain timeframe.

3. Next I order the info by login date, and login time so that my information is in chronological order, and i can view the failed login attempts, which user attempted the login and the time of the attempted login.

4. I want to go even further and check the failed login attempts by certain dates, from here the OR operater is used to distinguish 2 different dates 



<h2>Languages and Utilities Used</h2>

- <b>SQL</b>
- <b>MariaDb Enviornment</b> 



<h2>Program walk-through:</h2>

<p align="center">
Select all available tables using [*]: <br/>
<a href="https://imgur.com/YTcJCG9"><img src="https://i.imgur.com/YTcJCG9.png" title="source: imgur.com" /></a><br />
<br />
Filter by login date:  <br/>
<a href="https://imgur.com/rAzngss"><img src="https://i.imgur.com/rAzngss.png" title="source: imgur.com" /></a>
<br />
<br />
Filter query by login date, time: <br/>
<a href="https://imgur.com/bw8SPvw"><img src="https://i.imgur.com/bw8SPvw.png" title="source: imgur.com" /></a>
<br />
<br />
Filter query by login date, time: <br/>
<a href="https://imgur.com/gqFrQJO"><img src="https://i.imgur.com/gqFrQJO.png" title="source: imgur.com" /></a>
<br />


  


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
